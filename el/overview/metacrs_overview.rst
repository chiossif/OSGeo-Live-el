:Author: OSGeo-Live
:Author: Mike Adair
:Version: osgeo-live5.0
:License: Creative Commons

.. _metacrs-overview:

.. image:: ../../images/project_logos/logo-GDAL.png
  :scale: 60 %
  :alt: project logo
  :align: right
  :target: http://gdal.org/

.. image:: ../../images/logos/OSGeo_incubation.png
  :scale: 100 %
  :alt: OSGeo Project
  :align: right
  :target: http://www.osgeo.org/incubator/process/principles.html

MetaCRS
=======

Coordinate Reference Systems Transformations
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. comment: Can we please get an image. Maybe a collage of different projections. Make sure the image has rights to be included in a CC document.

Η ομάδα την πακέτων MetaCRS παρέχει βιβλιοθήκες λογισμικού για την μετατροπή μεταξύ διαφόρων γεωγραφικών συστημάτων συντεταγμένων.
Ένα γεωγραφικό σύστημα συντεταγμένων επιτρέπει σε όλα τα σημεία στην γη να αναπαριστώνται ως συντεταγμένες (όπως το γεωγραφικό μήκος, το γεωγραφικό πλάτος και το υψόμετρο). Διάφορα συστήματα χρησιμοποιούνται επίσης στην αναπαράσταση της τρισδιάστατης γήινης επιφάνειας σε δύο διαστάσεις.

Οι βιβλιοθήκες MetaCRS περιλαμβάνονται/χρησιμοποιούνται επίσης και σε άλλα πακέτα λογισμικού ενώ πολλές είνα διαθέσιμες για εκτέλεση και από την γραμμή εντολών.

Στα πακέτα του MetaCRS περιλαμβάνονται:

.. comment: Find examples for where all libraries are used, or don't mention any.
.. comment: I assume camel case should be Proj4JS or Proj4js instead of Proj4Js? (I've changed below)

* PROJ.4 (C++) - χρησιμοποιείται από τα: MapServer, GRASS GIS, PostGIS, Mapnik και πολλά άλλα.
* Proj4js (JavaScript) - χρησιμοποιείται από το OpenLayers.
* CS-Map (C++) - χρησιμοποιείται από το MapGuide.
* GeoTIFF/libgeotiff (C++) - .
* Proj4J (Java) - used ???.
* `SpatialReference.org <http://spatialreference.org/>`_  - website to retrieve coordinate system definitions.

Core Features
-------------

* Παρέχει μετασχηματισμούς μεταξύ γεωγραφικών συστημάτων συντεταγμένων.
* Περιλαμβάνει μετατροπές μεταξύ των διαφόρων datums.
* Υποστηρίζει μεγάλο αριθμό κλάσεων μετατροπών/προβολών.


Implemented Standards
---------------------

Τα προγράμματα αυτά χρησιμοποιούν τυπικούς ορισμούς συστημάτων γεωγραφικών συντεταγμένων από το
`European Petroleum Survey Group (EPSG) <http://www.epsg.org/>`_ τα οποία έχουν καταγραφεί σε Well Known Text (WKT) format.

Details
-------

.. comment: For Proj4js, We should only have one website. I've removed the trac reference (users can find it from the main website).
.. comment: Need to work out the license for Proj4J


PROJ.4
------

  **Website:**  http://trac.osgeo.org/proj/
  
  **Licence:** `X/MIT style Open Source license <http://trac.osgeo.org/proj/wiki/WikiStart#License>`_
  
  **Software Version:** 4.7.0
  
  **Supported Platforms:** Windows, Linux, Mac
  
  **API Interfaces:** C, C++, Python, Java, Ruby
  
  **Support:** http://lists.maptools.org/mailman/listinfo/proj

Proj4js
-------

  **Website:**  http://trac.osgeo.org/proj4js/ and http://proj4js.org
  
  **Licence:** `LPGL <http://www.gnu.org/copyleft/lesser.html>`_
  
  **Software Version:** 1.0.1
  
  **Supported Platforms:** Windows, Linux, Mac
  
  **API Interfaces:** JavaScript
  
  **Support:** http://lists.osgeo.org/mailman/listinfo/MetaCRS

CS-Map
------

  **Website:**  http://proj4js.org
  
  **Licence:** `custom <http://svn.osgeo.org/metacrs/csmap/trunk/CsMapDev/license.txt>`_
  
  **Software Version:** 13.0
  
  **Supported Platforms:** Windows, Linux, Mac
  
  **API Interfaces:** C, C++

  **Support:** http://lists.osgeo.org/mailman/listinfo/MetaCRS

GeoTIFF/libgeotiff
------------------

  **Website:**  http://trac.osgeo.org/geotiff/
  
  **Licence:** `X/MIT style Open Source license <http://trac.osgeo.org/proj/wiki/WikiStart#License>`_
  
  **Software Version:** 1.3.0
  
  **Support:** http://lists.maptools.org/mailman/listinfo/geotiff
  
Proj4J
------

  **Website:**  http://trac.osgeo.org/proj4j/
  
  **Licence:** `Apache License, Version 2.0 <http://www.apache.org/licenses/LICENSE-2.0>`_
  
  **Software Version:** 
  
  **Supported Platforms:** Windows, Linux, Mac
  
  **API Interfaces:** Java
  
  **Support:** http://lists.osgeo.org/mailman/listinfo/proj4j
  

Quickstart
----------
    
* `Quickstart documentation <../quickstart/metacrs_quickstart.html>`_
