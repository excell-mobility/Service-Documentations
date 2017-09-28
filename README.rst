Service Dokumentationen
=======================

Beinhaltet momentan die Swagger Dokumentationen für::

  * CsEventManager
  * GeocodingService
  * HeatmapService
  * MonitoringService
  * RoutingService
  * SchedulingService
  * SensorDataColletor
  * TrackingService
  * TrafficStateService

Ein Beispiel wie momentan diese Services über die Integration Layer angesprochen werden können befindet sich hier::

  https://dlr-integration.minglabs.com/swagger/API-Example.html

Die Swagger Dokumentation für die Integration Layer befindet sich hier::

  https://dlr-integration.minglabs.com/swagger/index.html

Die Swagger Dokumentationen für die Services befinden sich unter (case sensitive!)::

  https://dlr-integration.minglabs.com/swagger/index.html?url=<Service_Name>


Also zum Beispiel::

  https://dlr-integration.minglabs.com/swagger/index.html?url=GeocodingService.json

für die Geocoding Dokumentation.


TODO::

  * Change hosts and base path to match access via Integration Layer
  * Add api token auth to every swagger file
