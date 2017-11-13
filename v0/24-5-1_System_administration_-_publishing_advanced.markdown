# 24.5.1    System administration - publishing advanced

> When you publish a particular profile or {{work}} record, {{Lamplight}} builds a searchable index from that record. 

The searchable index is used by the free-text searches in the publishing module, and is updated whenever you edit a published profile or {{work}} record. However, if you change the fields that can be published in the system administration section, {{Lamplight}} needs to rebuild these indexes so that the data from the correct fields are included in the index. This is particularly important if you are removing fields that have previously been published.

Depending on the number of records involved, it can take a little while for {{Lamplight}} to rebuild these indexes. And because {{Lamplight}} won't know when you've finished making all the changes you want to, you'll need to tell {{Lamplight}} to rebuild these search indexes.

To do so, go to Admin -> System administration and click on "rebuild publishing search index - {{people}} and Orgs" or "rebuilding publishing search index - {{work}}", depending on the changes you've just made and so the indexes that need updating.

When you click either of these, {{Lamplight}} will rebuild the indexes and give you a confirmation {{message}} when complete, telling you how many have been updated. 

###### publish module

