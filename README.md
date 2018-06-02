# MidSemI_Middleware
MidSemI is a mediator-based integration system that integrate information and searches for entities about persons, organizations, and products in internal enterprise CRM relational database and link it with semi-structured Facebook social network data and structured DBpedia linked data.

From an abstract point of view, our architecture consists of the following layers:

   •	Presentation Layer – comprises a user interface and navigation logic which provide simple access to integrated information.

   •	Schema and Metadata Layer – includes vocabularies and ontologies which provide a formal, machine-readable description of accumulated knowledge graphs and metadata information about sources and databases to ease data discovery. 

   •	Instance Layer – holds a set of internal speciﬁc databases and relevant domain web datasets instances related to the enterprise.

We implement the proposed approach in two complementary tools, a middleware configuration application and an automated, user-friendly keyword search web interface that retrieves its input from internal enterprise data combined with results from various SPARQL endpoints and Web APIs. 
