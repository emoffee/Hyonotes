# GeoSpatial Server for Analysis

* Create a new EC2 server and install GeoServer distribution
* Install a geospatial dataset into the server by using GeoServer's web UI
* Install & configure a RDS PostgreSQL database service
* Install a PostgreSQL & PostGIS client on the server instance
* Transfer geospatial data to the RDS database instance
* Create an AutoScale group based on a configured image from the EC2 server
* Create an ELB above all the GeoSpatial Servers template