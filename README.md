# Reference Data Model Implementation

The repository hosts a series of resources used for the [Reference Data Model Implementation](http://rds-dev.swissartresearch.net), a Swiss Art Research Infrastructure project carried out by [ETHZ](https://ethz.ch/en.html) and [UZH](http://uzh.ch/en.html).  

## Entities  

The entities described in the data use version 6.2 of the [CIDOC-CRM ontology](http://www.cidoc-crm.org) and the path expressions for the attributes follow the rules expressed in the [Reference Data Model](https://docs.swissartresearch.net/instruction/).  Links and corresponding documentation can be found in the table below.

| Entity Type        	| Reference Data Model final version                       	|
|--------------------	|----------------------------------------------------------	|
| Places             	| [https://docs.swissartresearch.net/et/place/](https://docs.swissartresearch.net/et/place/)              	|
| Persons            	| [https://docs.swissartresearch.net/et/person/](https://docs.swissartresearch.net/et/person/)             	|
| Groups             	| [https://docs.swissartresearch.net/et/group/ ](https://docs.swissartresearch.net/et/group/)             	|
| Events             	|[ https://docs.swissartresearch.net/et/bibliographic_item/](https://docs.swissartresearch.net/et/bibliographic_item/) 	|
| Built Works        	| [https://docs.swissartresearch.net/et/built_work/](https://docs.swissartresearch.net/et/built_work/)         	|
| Artworks           	| [https://docs.swissartresearch.net/et/artwork/](https://docs.swissartresearch.net/et/artwork/)            	|
| Bibliographic Item 	| [https://docs.swissartresearch.net/et/bibliographic_item/](https://docs.swissartresearch.net/et/bibliographic_item/) 	|
| Digital Object     	| [https://docs.swissartresearch.net/et/do/](https://docs.swissartresearch.net/et/do/)                 	|
| Archival Item      	|                                                          	|
| Oeuvres            	|                                                          	|
| Projects           	|                                                          	|


   
    
## Vocabularies and patterns

A series of vocabularies and patterns have been used across the resource. The table below offer an overview of which terminological resource is used for each of the expressed value


| ﻿Model          	| Element                        	| Example                          	| Authority                                                                                 	|
|----------------	|--------------------------------	|----------------------------------	|-------------------------------------------------------------------------------------------	|
| Shared         	| Name Language                  	|                                  	| glottolog                                                                                 	|
| Shared         	| Name Language                  	|                                  	| language tag on the label                                                                 	|
| Shared         	| Alternative Name Type          	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300404653>                                 	|
| Shared         	| Identifier Type                	|                                  	|                                                                                           	|
| Shared         	| Part of the name               	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300404653>                                 	|
| Shared         	| Citation                       	|                                  	| crm:P2_has_type <http://vocab.getty.edu/aat/300311705>                                    	|
| Shared         	| Short Biography                	|                                  	| crm:P2_has_type <http://vocab.getty.edu/aat/300055908>                                    	|
| Shared         	| Short Biography                	|                                  	| crm:P2_has_type "Short Biography"                                                         	|
| Shared         	| Long Biography                 	|                                  	| crm:P2_has_type <http://vocab.getty.edu/aat/300055908>                                    	|
| Shared         	| Long Biography                 	|                                  	| crm:P2_has_type "Long Biography"                                                          	|
| Shared         	| Description                    	|                                  	| crm:P2_has_type <http://vocab.getty.edu/aat/300411780>                                    	|
| Shared         	| Short Description              	|                                  	| crm:P2_has_type <http://vocab.getty.edu/aat/300411780>                                    	|
| Shared         	| Short Description              	|                                  	| crm:P2_has_type "Short Description"                                                       	|
| Shared         	| Long Description               	|                                  	| crm:P2_has_type <http://vocab.getty.edu/aat/300411780>                                    	|
| Shared         	| Long Description               	|                                  	| crm:P2_has_type <http://vocab.getty.edu/aat/300055908>                                    	|
| Shared         	| Long Description               	|                                  	| crm:P2_has_type "Long Description"                                                        	|
| Shared         	| Place                          	|                                  	| Geonames                                                                                  	|
| Shared         	| Actor/Creator Role             	| Architect                        	| Narrower concepts of <http://vocab.getty.edu/aat/300024979>                                 	|
| Shared         	| Description Type               	| "General description"            	|                                                                                           	|
| Shared         	| Material                       	|                                  	| Narrower concepts of <http://vocab.getty.edu/page/aat/300010358>                            	|
| Shared         	| Techniques                     	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300053003>                                 	|
| Shared         	| Conservation Event - Type      	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300053003>                                 	|
| Shared         	| Conservation Event - technique 	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300053003>                                 	|
| Shared         	| Uncertainty               	|                                  	| expressed with a type from the uncertainty vocabulary <https://github.com/swiss-art-research-net/vocab/tree/master/uncertainty>                                    	|
| Event          	| Objects Employed               	| "Letters" or Any type of objects 	| narrower concepts of <http://vocab.getty.edu/aat/300230425> ?                               	|
| Person         	| Honorific                      	|                                  	| Narrower concepts of <http://vocab.getty.edu/page/aat/300417193>                            	|
| Person         	| Gender                         	|                                  	| Narrower concepts of <http://vocab.getty.edu/page/aat/300055146>                            	|
| Person         	| Nationality                    	|                                  	| Type from  <https://github.com/swiss-art-research-net/vocab/tree/master/nationalities>                                	|
| Person         	| Cultural Affiliation           	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300111079>                                 	|
| Person         	| Languages                      	|                                  	| glottolog                                                                                 	|
| Person         	| Occupation/General Role        	| "Sculptor", "Playwright"         	| Type from  <https://github.com/swiss-art-research-net/vocab/tree/master/occupation>                                 	|
| Person         	| Relation Type                  	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300024979>                                 	|
| Person         	| Field of Activity              	| "Book History"                   	| Narrower concepts of <http://vocab.getty.edu/aat/300054134>                                 	|
| Person         	| Educational training           	|                                  	| For the Education E55 Type the URI <http://vocab.getty.edu/aat/300054360> should be used. 	|
| Group          	| Group Type                     	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300025948>                                 	|
| Group          	| Group/CorporateBody            	|                                  	| Corporate body: <http://vocab.getty.edu/aat/300386361>                                      	|
|                	|                                	|                                  	| Group: <http://vocab.getty.edu/aat/300025948>                                               	|
| Group          	| Legal Status                   	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300025948>                                 	|
| Group          	| Scope of Activity              	|                                  	| Narrower of <http://vocab.getty.edu/aat/300256408>                                          	|
| Artwork        	| Generic part types             	|                                  	| Narrower concepts of <http://vocab.getty.edu/aat/300241583>                                 	|
| Artwork        	| Subject                        	|                                  	|                                                                                           	|
| Artwork        	| Right Type                     	|                                  	|                                                                                           	|
| Built work     	| Designation Status Type        	|                                  	|                                                                                           	|
| Digital Object 	| Type                           	| image, drawing                   	|                                                                                           	|
| Digital Object 	| Locator Type                   	| API, SPARQL                      	|                                                                                           	|
| Digital Object 	| Stored on                      	| HD, CD,                          	|                                                                                           	|
| Place          	| Place type                     	|                                  	| narrower of <http://vocab.getty.edu/aat/300008407>                                          	|

## URI Patterns

The URI used for the description of the resource are derivation from the base uri:

	https://resource.swissartresearch.net/  

Where each entity types is described using the following URIs:

	https://resource.swissartresearch.net/person/
	https://resource.swissartresearch.net/group/
	https://resource.swissartresearch.net/place/
	https://resource.swissartresearch.net/event/
	https://resource.swissartresearch.net/archivalunit/
	https://resource.swissartresearch.net/artwork/
	https://resource.swissartresearch.net/builtwork/
	https://resource.swissartresearch.net/bibliographicitem/
	https://resource.swissartresearch.net/digitalobject/
	https://resource.swissartresearch.net/terminology/
