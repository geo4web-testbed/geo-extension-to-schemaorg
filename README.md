# geo-extension-to-schemaorg
In this repository we develop an extension to schema.org to facilitate the discovery of geospatial data.

*Background*

The testbed Spatial Data on the web aims to develop methods and tooling to integrate spatial data into the web of documents. In order to achieve this spatial data is annotated with the schema.org vocabulary. While working with schema.org we noticed that most of the Things that are described with schema.org are modeled without a dedicated spatial focus in mind. For example the properties that describe "location" are spread over the schema, and the Things that can actually have a location are limited. 

This proposed extension is developed with the idea to start from scratch. Meaning: it does not propose modifications to the existing schema.org but rather seeks an alternative way to model geo information into schema.org keeping in mind the schema.org modeling objectives. We refrain from modeling specific constructs that can be used to execute a spatial analysis since 1) there are vocabularies that better support this and 2) search engines currently do not seem to be equipped with spatial indexes.  
 