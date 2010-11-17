:Author: Johannes Wilden
:Version: osgeo-live4.0
:License: Creative CommonsΣυγγραφέας: Johannes Wilden Έκδοση:Osgeo - live 4.0 Άδεια: Creative commons

.. _deegree-overview:deegree-γενική επισκόπηση

.. image:: images/project_logos/logo-deegree.pngΕικόνα: Εικόνες/Έργο_λογότυπο/Λογότυπο-degree.png
  :scale: 80 %Κλίμακα:80%
  :alt: project logoalt:Λογότυπο του τμήματος
  :align: rightΣτοίχιση: Δεξιά
  :target: http://deegree.orgΣτόχος:http://deegree.org

.. image:: images/logos/OSGeo_project.pngΕικόνα:Εικόνες/λογότυπα/Osgeo_project.png
  :scale: 100Κλίμακα:100%
  :alt: OSGeo Projectalt:Osgeo Έργο
  :align: rightΣτοίχιση: Δεξιά
  :target: http://www.osgeo.orgΣτόχος:http://www.osgeo.org 


deegree
=======deegree

Web Services
~~~~~~~~~~~~Υπηρεσίες Δικτύου

deegree is free, stable, powerful and easy to use.Το deegree είναι ελεύθερο, σταθερό, δυνατό και εύκολο στη χρήση. deegree is
the most comprehensive set of implementations of Open Geospatial
Consortium (OGC) standards in free and open source software, ranging
from a transactional Web Feature Service to three-dimensional data
display through a Web Terrain Service and many more!Το deegree είναι το πιο περιεκτικό σύνολο εφαρμογών, βασιζόμενων στις προδιαγραφές του OGC, στο ελεύθερο και ανοιχτό λογισμικό, το οποίο εκτείνεται από 

deegree is a solution for web- and desktop-based
Geographic Information Systems (GIS) and Spatial Data Infrastructures
(SDI).Το deegree είναι μια λύση σε Γεωγραφικά Συστήματα Δεδομένων και Υποδομές Χωρικών στοιχείων βασιζόμενων σε δικτυακές ή προσωπικές εφαρμογές. It is comprised of a comprehensive yet powerful Java Application
Programming Interface (API) and a powerful object-relational mapping for
simple and complex spatial schemas.Συνίσταται από περιεκτική και ισχυρή API και ισχυρή αντικειμενο-συσχετιστική απεικόνιση για απλά και σύνθετα χωρικά σχήματα deegree also provides a set of
standards-compliant webservices for web mapping, feature and catalogue
services as well as sensor and processing services.

deegree gets your SDI up and running, using your own data and fulfilling
your requirements.


.. image:: images/screenshots/1024x768/deegree_mainpage.gif
  :scale: 50%
  :alt: project logoalt:Λογότυπο του τμήματος
  :align: rightΣτοίχιση: Δεξιά

Some example features
---------------------

* Web Map Service

  * very flexible concerning layer contents
  * supports and uses style definitions (SLD 1.0)
  * thematic mapping capabilities through charts (pie, bar, line) as point symbolizers
  * datasources: all common OGC web services (WMS, WFS, WCS), PostgreSQL/PostGIS, Oracle Spatial, any arbitrary SQL statements can be used to create the WMS layer content
  * very stable, even for large scales
  * supports HTTP GET, HTTP POST and feature info requests
  * certified to be OGC compliant

* Web Feature Service

  * supports simple and complex features
  * on the fly coordinate transformation for more than 3000 coordinate reference systems
  * supports flexible output formats
  * easily enhanced to support INSPIRE directive

* Web Coverage Service

  * supports HTTP GET and HTTP POST requests
  * datasources: images (tif, png, jpeg, gif, bmp); GeoTIFF; ECW files; Oracle GeoRaster
  * high-speed access to large coverages

* Catalogue Service-Web

  * datasources: PostgreSQL-Database; Oracle-Database
  * supported requests: GetCapabilities; DescribeRecord; GetRecordById; GetRecords; Transaction - Insert, Update, Delete; Harvesting

* Web Map Print Service

  * supports different print formats (HTML, PDF, PNG)
  * long time running jobs
  * supports asynchronous requests to enable large-scale plots
  * requests are stored within a database and will be available even if WMPS is stopped by an administrator or the machine fails

* Web Perspective View Service

   * datasources: remote/local-WMS, remote/local-WFS, local-WCS, Postgres/PostGIS, Oracle Spatial
   * elevation models can be vector data or raster data
   * requests: Get3DFeatureInfo, GetView


Implemented Standards
---------------------

* OGC Web Map Service (WMS) 1.1.0*, 1.1.1, 1.3.0*
* OGC Web Feature Service (WFS) 1.0.0, 1.1.0 (2.0 in progress)
* OGC Web Coverage Service (WCS) 1.0.0* (1.1.0 in progress)
* OGC Catalogue Service-Web (CSW) 2.0.0, 2.0.1, 2.0.2; including OGC ISOAP 1.0 and INSPIRE profile
* OGC Web Perspective View Service (WPVS) Draft 6
* OGC Web Coordinate Transformation Service (WCTS) 0.4.0
* OGC Web Processing Service (WPS) 0.4.0, 1.0.0
* OGC Sensor Observation Service (SOS) 1.0.0

Details
-------

**Website:** http://deegree.org

**Licence:** LGPL

**Software Version:** 2.3

**Supported Platforms:** Windows, Linux

**API Interfaces:** Java

**Support:** http://wiki.deegree.org/deegreeWiki/GettingSupport


Quickstart
----------

* `Quickstart documentation <../quickstart/deegree_quickstart.html>`_


