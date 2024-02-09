---
label: Geo-data Services
order: 40
---
# Geo-data Services

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed lobortis nisl finibus, laoreet ligula sit amet, pulvinar tellus. Nullam ut mi finibus, suscipit nisi vel, consectetur ante. Aliquam ac aliquam felis. Pellentesque feugiat neque vel arcu mattis mattis. Etiam pulvinar lacus sed quam egestas, eget tempor dui molestie. Donec ac vehicula magna, id accumsan nibh. Phasellus risus metus, **lacinia sit amet nisi sed, ultricies lacinia arcu**. Vivamus laoreet massa in diam sodales, non hendrerit nulla iaculis. Nunc ut elementum neque, et eleifend odio.

<br>

### Overview of existing standards
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed lobortis nisl finibus, laoreet ligula sit amet, pulvinar tellus. Nullam ut mi finibus, suscipit nisi vel, consectetur ante. Aliquam ac aliquam felis. Pellentesque feugiat neque vel arcu mattis mattis. Etiam pulvinar lacus sed quam egestas, eget tempor dui molestie. Donec ac vehicula magna, id accumsan nibh. Phasellus risus metus, **lacinia sit amet nisi sed, ultricies lacinia arcu**. Vivamus laoreet massa in diam sodales,

<br>

### WMS (Web Map Service) ![](/static/img/two_star.png) 

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed lobortis nisl finibus, laoreet ligula sit amet, pulvinar tellus. Nullam ut mi finibus, suscipit nisi vel, consectetur ante. Aliquam ac aliquam felis. Pellentesque feugiat neque vel arcu mattis mattis. Etiam pulvinar lacus sed quam egestas, eget tempor dui molestie. Donec ac vehicula magna, id accumsan nibh. Phasellus risus metus, **lacinia sit amet nisi sed, ultricies lacinia arcu**. Vivamus laoreet massa in diam sodales, ([OpenGeoSpatial](https://www.ogc.org/standards/wms)).
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed lobortis nisl finibus, laoreet ligula sit amet, pulvinar tellus. Nullam ut mi finibus, suscipit nisi vel

<br>

### WFS (Web Feature Service)  ![](/static/img/two_star.png)  

WFS allow any usage that might work with web services to get geographic features from one or more distributed spatial
information system or a map itself. Similar to WMS (mapping output as an image), WFS deal with create, update, delete
and query functions of feature instances from regarding database. WFS serve eight general operations:
_Capabilities, DescribeFeatureType, DescribeFilterModel, Feature, FeatureWithLock, Property, LockFeature_ and _Transaction_.
Rules and applications of WFS are provided by **EN ISO 19142:2010**.

<br>

### WCAS (Web Catalogue Service) ![](/static/img/two_star.png)
#### Also known as: CSW, Catalogue Services for the Web

CSW service provides options to publish and searching capabilities of metadata about geospatial data, services, and related
information objects. Request types that CSW services offers include: _GetCapabilities, DescribeByRecord, GetRecords, GetRecordById,
GetDomain, Harvest_ and _Transaction_. Requests can encode the parameters in three different ways: GET with URL parameters,
POST with form-encoded payload and POST with XML payload.

<br>

### WCS (Web Coverage Service)  ![](/static/img/two_star.png)

WCS returns the original data with its descriptions along with actual semantics. This service allows access into coverage data for client-side rendering. WCS also offers clients to get information of a certain portions based on constraints and certain criteria, similar to WFS and WMS service.

<br>

### WMTS (Web Map Tile Service)  ![](/static/img/two_star.png)

WMTS makes detailed rendering of a raster data or a large volume of vector data in tiles which supports Key-Value-Pair 
(KV, process oriented) encoding interfaces, REST (Representational state transfer) encoding and SOAP encoding. 

<br>

### TJS (Table Joining Service)  ![](/static/img/two_star.png)

The TJS standard joins attribute data with its associated geospatial framework. Attribute data can be stored in one 
network and mapped with geographic data into another network which contains geometries for the attribute data.
TJS provides simple web-based services for searching, accessing and using attribute data from different sources which
can generate database, perform analysis and populate maps.

<br>

### WMC (Web Map Context)  ![](/static/img/two_star.png)

The OGC XML file standard WMC describes meta-information of a WMS (e.g. the URL, different layers within the service,
bounding box rectangle, coordinate system) in XML file, stores and loads XML schema which belongs to it.

<br>

### WPS (Web Processing Service)  ![](/static/img/two_star.png)

WPS service defines how to implement a geoprocessing service, geographic calculations or models as a service.
It offers simple web-based standardized method of finding, accessing and using of geoprocessing services,
at the same time also direct requests and responses of those services. WPS uses HTTP GET, HTTP POST,
SOAP and XML as a mechanism for describing the data and for interoperability.
