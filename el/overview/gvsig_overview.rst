:Author: Johannes Wilden
:Version: osgeo-live4.0
:License: Creative CommonsΣυγγραφέας: Johannes Wilden Έκδοση:Osgeo - live 4.0 Άδεια: Creative commons

.. _gvsig-overview:

.. image:: images/project_logos/logo-gvSIG.png
  :scale: 75 %
  :alt: project logoalt:Λογότυπο του τμήματος
  :align: rightΣτοίχιση: Δεξιά
  :target: http://www.gvsig.org/

.. image:: images/logos/OSGeo_incubation.png
  :scale: 100 %Κλίμακα:100%
  :alt: OSGeo Projectalt:Osgeo Έργο
  :align: rightΣτοίχιση: Δεξιά
  :target: http://www.osgeo.org/incubator/process/principles.html


gvSIG Desktop
==============

Desktop GIS
~~~~~~~~~~~

gvSIG_ is a Geographic Information System (GIS) desktop application
designed for capturing, storing, handling, analysing and deploying any kind of
referenced geographic information in order to solve complex management and
planning problems.Το πρόγραμμα gvSIG είναι ένα Γεωγραφικό Σύστημα Πληροφοριών σχεδιασμένο για κατάκτηση, αποθήκευση, ανάλυση και... κάθε είδους αναφερμένων γεωγραφικών πληροφοριών για λύση σύνθετων προβλημάτνω διαχείρισης και προγραμματισμού. gvSIG is known for its user-friendly interface and being
able to access all common vector and raster formats.Το gvSIG είναι γνωστό για τη φιλική στο χρήστη οθόνη εργασίας και για το ότι έχει τη δυνατότητα πρόσβασης σε όλους τους κοινους διανυσματικούς και μωσαϊκού τύπου, τύπους αρχείων. It features
a wide range of tools for working with geographic information (query,
layout creation, geoprocessing, networks, etc.), which turns gvSIG into the
ideal tool for users working in the land realm.Στα χαρακτηριστικά του περιλαμβάνεται ένα μεγάλο εύρος εργαλείων για εργασία με γεωγραφικές πληροφορίες (ερώτημα, γεωεπεξεργασία, δίκτυα κλπ), γεγονός που το καθιστά ιδανικό εργαλείο για χρήστες που δουλεύουν 

gvSIG is known for:

* integrating in the same view both local and remote data through OGC standards.
* being easily extendible, allowing continuous application 
  enhancement, as well as enabling the development of tailor-made solutions.
* being available in over 20 languages (Spanish, English, German, French, 
  Italian,...) .
* being available for Windws, Linux, and Mac OS X platforms:

.. image:: images/screenshots/1024x768/gvsig_desktop.png
  :scale: 50 %
  :alt: screenshot
  :align: rightΣτοίχιση: Δεξιά

Core Features
-------------

* Provides common GIS tools like data loading, map navigation, query 
  map information like alphanumeric information, distance measurement, thematic
  cartography, legend edition using common legend types, labelling,
  feature selection by many selection types, data tables with statistics,
  ordering, table relations, table linking, layout manager, geoprocessing tools,
  CAD, raster processing, etc.

* Interoperable: able to work with most known data formats:

  * raster : ecw,  ENVI hdr, ERDAS img, (Geo)TIFF, GRASS, ...
  * vector & CAD: shapefile, GML, KML, DGN, DXF, DWG
  * databases: PostGIS, MySQL, Oracle, ArcSDE
  * remote: ECWP, ArcIMS, OGC standards

* Discovery services client to localize data resources within an
  SDI (catalogue and gazeteer services)
  
  * Catalogues: Z3950, SRW, CSW (ISO/19115 and ebRIM)
  * Gazetteers: ADL, WFS, WFS-G
  
* More than 290 geoalgorithms via SEXTANTE_ and GRASS integration
  
* Integrated advanced CAD tools:

  * vector data: modify, create and delete elements
  * command console typical element in CAD software
  * tools like help, grid, command stack, complex element selections
  * tools for inserting elements like points, polygons, lines, ellipses, etc...
  * tools to modify its rotation, symmetry,...
  
* Integrated advanced raster tools:

  * georeferencing and reprojecting
  * export, clipping
  * look up tables, histogram
  * filters, vectorization
  * overviews and regions of interest management

* Scripting support
* Powerful reprojection engine via PROJ4


Implemented Standards
---------------------

Advanced client support of numerous Open Geospatial Consortium (OGC) standards

* Load WMS, WFS and WCS layers
* Export/import of SLD legends
* Export/import of Web Map Context (WMC)
* Search on catalogues with  CSW (ISO/19115 and ebRIM)
* Search on gazetteers using WFS-G recommendation

Details
-------

**Website:** http://www.gvsig.org/

**Licence:** GNU General Public License (GPL) version 2

**Software Version:** 1.10 (beta)

**Supported Platforms:** Windows, Linux, Mac

**Support:** http://www.gvsig.org/web/organization/services


.. _gvSIG: http://www.gvsig.org
.. _SEXTANTE: http://forge.osor.eu/projects/sextante/
