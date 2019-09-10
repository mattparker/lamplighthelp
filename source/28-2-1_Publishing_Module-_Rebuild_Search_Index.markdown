# 28.2.1 Publishing Module: Rebuilding Search Indexes

> When you publish a particular profile or {{work}} record, {{Lamplight}} builds a searchable index from that record

The searchable index is used by the text searches in the Publishing Module. This is where you have a search field on your website using your {{Lamplight}} data, for example if you have a directory of organisations which is searchable by keyword or postcode area. 

![Searchable Fields Linked to {{Lamplight}} Data in a Website](28.2.1a.png)

The search index is updated whenever you edit a published profile or {{work}} record. 

However, if you go to system administration in {{Lamplight}} and change the fields that can be published, the index will need to be rebuilt. This will ensure that  data from the correct fields is included in the index and can be searched for on your website. This is particularly important if you are removing fields that have previously been published.

You'll need to tell {{Lamplight}} when you need to rebuild a search index.

To do this:
- Go to 'admin -> system administration' and find the 'Module Administration' section at the bottom. 
- In the 'Publishing Module' box, click on 'Rebuild publishing search index - profiles' or 'Rebuild publishing search index - {{work}}', depending on whether the changes you have made changes are to profile settings or {{work}} records.
- {{Lamplight}} will rebuild the index and give you a confirmation {{message}} when complete telling you how many records have been added and updated. 


###### publish module

