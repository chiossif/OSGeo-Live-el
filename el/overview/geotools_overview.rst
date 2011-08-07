:Author: OSGeo-Live
:Version: osgeo-live4.5
:License: Creative Commons

.. _geotools-overview:

.. image:: ../../images/project_logos/logo-GeoTools.png
  :scale: 60 %
  :alt: project logo
  :align: right
  :target: http://gdal.org/

.. image:: ../../images/logos/OSGeo_project.png
  :scale: 100 %
  :alt: OSGeo Project
  :align: right
  :target: http://www.osgeo.org/incubator/process/principles.html

GeoTools
========

Η GeoTools είναι μια ανοιχτή (LGPL) βιβλιοθήκη σε Java η οποία παρέχει τυπικές μεθόδους για την διαχείρηση γεωχωρικών δεδομένων και δομών βασισμένες σε προδιαγραφές του Open Geospatial Consortium (OGC).

.. image:: ../../images/screenshots/800x600/geotools-overview.png
  :scale: 60 %
  :alt: GeoTools is a modular library supported by plugins for additional formats
  :align: right

Η Geotools χρησιμοποιείται από έναν αριθμό προγραμμάτων στα οποία περιλαμβάνονβ\ται δικτυακές υπηρεσίες (web services), εργαλεία από την γραμμή εντολών και εφαρμογές με γραφική διεπαφή (desktop applications). Οι εφαρμογές OSGeo-Live στις οποίες περιλαμβάνεται η GeoTools: 
:doc:`52nSOS_overview`, :doc:`52nWPS_overview`, :doc:`atlasstyler_overview`, :doc:`geomajas_overview`, :doc:`geopublisher_overview`, :doc:`geoserver_overview`, and :doc:`udig_overview`.

Core Features
-------------

* Ορισμός των διεπαφών για τις χωρικές δομές (spatial concepts) και τις δομές δεδομένων.
  
  * Ολοκληρωμένη υποστήριξη γεωμετρίας μέσω της Java Topology Suite (JTS)
  * Χωρικά και φίλτρα χαρακτηριστικώνμε βάση την προδιαγραφή OGC Filter Encoding
  
* Καθαρό API με υποστήριξη: πρόσβασης, διαχείρησης και κλειδώματος μεταξύ των νημάτων (threads)
  
  * Πρόσβαση σε δεδομένα GIS με μεγάλη ποικιλία formats και γεω-χωρικών βάσεων δεδομέναν
  * Υποστήριξη συστημάτων συντεταγμένων και μετατροπών μεταξύ τους
  * Συνεργάζεται με πληθώρα χαρτογραφικών προβολών
  * Φιλτάρει/αναλύει τόσο γεωχωρικά όσο και απλά δεδομένα

* A stateless, low memory renderer, εξαιρετικά χρήσιμο σε περιβάλον server.
  
  * συνθέτει και εμφανίζει χάρτες με σύνθετες επιλογές αναπαράστασης (styling)

* Powerful *schema asisted* parsing technology using XML Schema to bind to GML content
  
  * The parsing / encoding technology is provided with bindings for many OGC standards including GML, Filter, KML, SLD, and SE.
  
* GeoTools Plugins: ανοιχτό σύστημα προσθέτων (plug-in) το οποίο επιτρέπει την εκμάθηση των επιπλέον format των βιβλιοθηκών
  
  * Πρόσθετα για το πακέτο ImageIO-EXT τα οποία επιτρέπουν στην GeoTools να διαβάζει επιπλέον formats μέσω GDAL
 
* GeoTools Επεκτάσεις

  * Παρέχουν επιπλέον δυνατότητες μέσω των χωρικών λειτουργιών της κεντρικής (core) βιβλιοθήκης.
  
  .. image:: ../../images/screenshots/800x600/geotools-extension.png
     :alt: Extensions built using the GeoTools library

  * Επεκτάσεις οι οποίες παρέχουν γραφικές και διαδικτυακές λειτουργίες (πχ αλγόριθμος ελάχιστης διαδρομής), αξιολόγηση δεδομένων, έναν web map server client, bindings for xml parsing and encoding and color brewer.

* GeoTools Unsupported
  
  * Η GeoTools είναι μέρος μιας ευρύτερης κοινότητας η οποία καλλιεργεί και αναδυκνύει νέα ταλέντα ενώ προάγει τον πειραματισμό.
  
  * Κάποια σημαντικά σημεία είναι η υποστήριξη swing (η οποία χρησιμοποιείται στα εγχειρίδια της geotools), swt, τοπική και δικτυακή υποστήριξη εφαρμογών, πρόσθετα σύμβολα, πολλά formats δεδομένων, παραγωγή κανάβων (grids) και υλοποιήσεις της γεωμετρίας ISO (ISO Geometry).

Supported Formats
-----------------  

* raster formats και δεδομένα:
  
  arcsde, arcgrid, geotiff, grassraster, gtopo30, image (JPEG, TIFF, GIF, PNG), imageio-ext-gdal, imagemoasaic, imagepyramid, JP2K, matlab.
  
* Υποστήριξη σε βάσεις δεδομένων "jdbc-ng" :
  
  db2, h2, mysql, oracle, postgis, spatialite, sqlserver.

* Διανυσματικά (vector) formats και δεδομένα:
  
  app-schema, arcsde, csv, dxf, edigeo, excel, geojson, org, property, shapefile, wfs.

* XML Bindings:

  Δομές δεδομένων Java και bindings τα οποία παρέχουν τα ακόλουθα:
  xsd-core (xml simple types), fes, filter, gml2, gml3, kml, ows, sld, wcs, wfs, wms, wps, vpf.
  
  Επιπρόσθετα εργαλεία Geometry, Filter και Style για την διαχείρηση/κωδικοποίηση εφαρμογών σε DOM και SAX.
  
Implemented Standards
---------------------

Υποστήριξη σε προδιαγραφές της Open Geospatial Consortium (OGC):

* OGC Style Layer Descriptor / Symbology Encoding
* OGC General Feature Model περιλαμβανομένης της λειτουργίας Simple Feature
* OGC Grid Coverage για την αναπαράσταση δεδομένων raster
* OGC Filter και Common Constraint Language (CQL)
* Clients για Web Feature Service (WFS), Web Map Service (WMS) και πειραματική υποστήριξη σε Web Process Service (WPS)
* ISO 19107 Geometry

Details
-------
 
**Website:** http://geotools.org/

**Licence:** LGPL

**Software Version:** 2.7.1

**Supported Platforms:** Cross Platform Java

**API Interfaces:** Java

**Support:** `Communication and Support <http://docs.geotools.org/latest/userguide/welcome/support.html>`_

Quickstart
----------

* `Quickstart documentation <http://docs.geotools.org/latest/userguide/tutorial/quickstart/index.html>`_
