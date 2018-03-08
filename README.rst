Service Documentations
=======================

In this repository we collect all [Swagger](https://swagger.io/) service documentations of the [ExCELL Developer Portal](https://www.excell-mobility.de/developer/). It contains JSON files for the following services:

  * CsEventManager
  * GeocodingService
  * HeatmapService
  * MonitoringService
  * RoutingService
  * SchedulingService
  * SensorDataColletor
  * TrackingService
  * TrafficStateService

The following link provides an example about how the services should be called via the Integration Layer::

  https://dlr-integration.minglabs.com/swagger/API-Example.html

The Swagger documentation for the Integration Layer can be found here::

  https://dlr-integration.minglabs.com/swagger/index.html

The Swagger documentations of single services can be accessed by adding `?url=<Service_Name>` to the URL (case sensitive!)::

  https://dlr-integration.minglabs.com/swagger/index.html?url=GeocodingService.json


TODO::

  * Change hosts and base path to match access via Integration Layer
  * Add api token auth to every swagger file
