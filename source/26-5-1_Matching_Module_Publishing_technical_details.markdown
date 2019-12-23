# 26.5.1 Matching Module - Publishing Technical Details

> You can use the Matching Module to request raw data through the API for use elsewhere. The information on this page is intended for developers

### Matching Module Opportunity API

Lamplight can store details of {{volunteering opportunity}} records. These can be made available through a public API for display on other websites etc.

### Access

Access to the records is controlled using an API key. This is different to the main publishing API key used in other parts of {{Lamplight}}.
We assume that {{volunteering opportunity}} records are 'more public' than other aspects of the matching module, and that the key may not be kept secret. The API in the main Publishing Module is treated as secret.  For example, with the Matching Module you may choose to embed an iframe directly in your website so that you can display opportunities more easily. This will mean that the API key is public.

The API key is available via the main system admin section in Lamplight.

Requests should be made to `https://lamplight.online/api/volunteering/opportunity`.
You will need to add a `key` parameter, with the API key.


### Searching Opportunities

The main endpoint for searching volunteering opportunities is
`https://lamplight.online/api/volunteering/opportunity/search`.  The following search parameters are available:



| Parameter | Type | Description |
| :-------- | :--- | :---------- |
| near_postcode | string | The UK postcode to search near |
| distance      | int    | Number of km to look around the postcode. Required for `near_postcode` to work |
| topics        | int[]  | Array of topic IDs to filter by (using and OR search) |
| roles         | int[]  | Array of role Ds to filter by (using and OR search) |
| provider_id   | int    | The ID of the Lamplight provider profile |
| id            | int    | The ID of the volunteering opportunity |


#### Paging

`start` is the record to start from; `num` is the number of results to return.

`include_form` will include a search form in the response (not for json formatted requests).


#### Return Formats

Data can be returned as partial `html`, `json`, or `iframe` - html results in a full web page.
Pass the `format` parameter to set this.  The default is `html` if this is empty or invalid.

You can change the amount of data returned using the `return` parameter; set to `short` it will provide a limited response.

Passing the `callback` parameter to a json response will wrap the response with the callback you pass:

<code>
https://lamplight.online/api/volunteering/opportunity/search?key=aabbcc&format=json&callback=console.log
</code>

returns

<code>
console.log({"meta": {}, "data": {}});
</code>

(See below for the structure of the data actually returned).


### Return data

If format=html or format=iframe you'll get rendered html, which will look something like this:

<code>
&lt;div class="lamplight lamplight-volunteering lamplight-listing"&gt;
    &lt;div id="lamplight_opportunity_container"&gt;
        &lt;div
            data-lplt_id="109"
            class="lplt-calendar-item workarea1-border control-workarea1"&gt;
            &lt;div class="lplt-detail"&gt;
                &lt;div class="lplt-summary"&gt;
                &lt;h3&gt;&lt;a href="http://lamplight/api/volunteering/opportunity/one?id=109&key=ccb4b364daae60c9956ff27de36245a3&format=iframe"&gt;test 2 all day friday, org 9 custom post SO21&lt;/a&gt;&lt;/h3&gt;at Generous Funder
                &lt;/div&gt;
                &lt;p class="lplt-maindetail"&gt;
                SO21 2JY
                &lt;/p&gt;
            &lt;/div&gt;
        &lt;/div&gt;
        &lt;div
            data-lplt_id="110"
            class="lplt-calendar-item workarea1-border control-workarea1"&gt;
            &lt;div class="lplt-detail"&gt;
                &lt;div class="lplt-summary"&gt;
                &lt;h3&gt;&lt;a href="http://lamplight/api/volunteering/opportunity/one?id=110&key=ccb4b364daae60c9956ff27de36245a3&format=iframe"&gt;test 3 evenings, org 8&lt;/a&gt;&lt;/h3&gt;at Grange Community Centre
                &lt;/div&gt;
                &lt;p class="lplt-maindetail"&gt;
                33a Bills Lane, North Front, Bargate, Southampton, SO14 0AB
                &lt;/p&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/div&gt;
&lt;/div&gt;

</code>

The difference between html and iframe is that iframe will also return a &lt;head&gt; and wrap the above in a &lt;body&gt;.  If there's a form, it will also include some javascript to enhance the form.


format=json will give you something like this:

<code>
{
    "data":[
        {
            "id":109,
            "start_date":"2013-12-02 09:00:00",
            "end_date":"2013-12-02 09:00:16",
            "workarea":["Workarea 1"],
            "provider":"Generous Funder",
            "provider_id":9,
            "title":"test 2 ",
            "description":"",
            "requirements_description":"",
            "practical_considerations":"",
            "availability":[],
            "location":{
                "address_line_1":"",
                "address_line_2":"",
                "address_line_3":"",
                "address_line_4":"",
                "address_line_5":"",
                "postcode":"SO21 2JY",
                "latitude":"51.0242341267990000",
                "longitude":"-1.390880"
            },
            "topics":[],
            "skills":[],
            "roles":[],
            "ideal_for":[],
            "requirements":[]
        },
        {
            "id":110,
            "start_date":"2013-12-02 09:00:00",
            "end_date":"2013-12-02 09:00:23",
            "workarea":["Workarea 1"],
            "provider":"Grange Community Centre",
            "provider_id":8,
            "title":"test 3 evenings, org 8",
            "description":"",
            "requirements_description":"",
            "practical_considerations":"",
            "availability":[],
            "location":{
                "address_line_1":"33a Bills Lane",
                "address_line_2":"North Front",
                "address_line_3":"Bargate",
                "address_line_4":"Southampton",
                "address_line_5":"",
                "postcode":"SO21 0AB",
                "latitude":"50.9071275936508600",
                "longitude":"-1.398581"
            },
            "topics":[],
            "skills":[],
            "roles":[],
            "ideal_for":[],
            "requirements":[]
        }
    ],
    "meta":{
        "numRecords":2,
        "totalRecords":"2"
    }
}
</code>

### Viewing a Single Opportunity

The endpoint will provide data for a single opportunity, using the id given by the responses above.

`https://lamplight.online/api/volunteering/opportunity/one?id=123key=aabbcc&format=iframe`


### Examples

Find volunteering opportunities within 15kms of W2 6FT

`https://lamplight.online/api/volunteering/opportunity/search?key=aabbcc&format=json&near_postcode=W2%206FT&distance=15`

Find opportunities for people interested in media, to use as the `src` of an iframe.

`https://lamplight.online/api/volunteering/opportunity/search?key=aabbcc&format=iframe&topics[]=1`

Look for 5 opportunities from provider id 332, starting on the third page, returning short html listings

`https://lamplight.online/api/volunteering/opportunity/search?key=aabbcc&format=html&provider_id=332&start=10&num=5&return=short`


### API Feeds

The easiest way to use all of this is to create [API feeds in Lamplight](/help/index/p/26.5.1), via the system admin menu. This lets you specify this information in advance, and provides an html snippet that can be embedded in other websites.

You can create any number of feeds for different purposes.

Key features of an API Feed:
- specify postcode and search radius
- specify whether to include a search form
- set how many results to show per page
- specify CSS files to include in the `<head>` of the iframe

By default, the iframe will render fairly simple results. 'Next page' links will be shown, and clicking on an opportunity will show full details.

Lamplight will provide the html code to copy and paste into your own website.


A request for a feed looks something like this:

`https://lamplight.online/api/volunteering/opportunity/feed?feed_id=4433|46&key=aabbcc&format=iframe`



###### match module
