:Συγγραφέας: OSGeo-Live
:Συγγραφέας: Pirmin Kalberer
:Έκδοση: osgeo-live4.5
:Άδεια: Creative Commons Attribution-ShareAlike 3.0 Unported  (CC BY-SA 3.0)

.. _qgis-quickstart:
 
.. image:: ../../images/project_logos/logo-QGIS.png
  :scale: 100 %
  :alt: project logo
  :align: right
  :target: http://www.qgis.org

************
Οδηγός Γρήγορης Εκκίνησης QGIS
************

To Quantum GIS (QGIS) είναι μια φιλική GIS Desktop εφαρμογή, που επιτρέπει την προβολή, διαχείρηση, επεξεργασία, ανάλυση δεδομένων και σύνθεση εκτυπώσιμων χαρτών.

Αυτός ο οδηγός περιγράφει πώς:

  * Θα ενημερωθεί ένα project του QIS
  * Θα δημιουργηθεί ένα QGIS project με ένα απλό θεματικό επίπεδο (layer) διανυσματικών δεδομένων (vector)


Επεξεργασία QGIS project
=================

#. Με το ποντίκι:menuselection:`Desktop --> Desktop GIS --> Quantum GIS`.

#. Επιλογή :menuselection:`File --> Open Project...` από τη γραμμή εργαλείων.

#. Επιλογή :file:`QGIS-NaturalEarth-Example.qgs` και στη συνέχεια :guilabel:`Open`.

   * Θα πρέπει να δείτε ένα παγκόσμιο χάρτη.

#. Επιβεβαιώστε **10m_populated_places_simple** στο δέντρο των Layers

   * Οι κατοικήσιμες περιοχές πλέον προβάλλονται στο QGIS:

     .. image:: ../../images/screenshots/1024x768/qgis.png
        :scale: 50 %

#. Διπλό αριστερό κλικ **10m_rivers_lake_centerlines** στο δέντρο των Layers.

#. Επιλέξτε ένα διαφορετικό τόνο του μπλε για χρώμα στο Outline Options.

#. Πατήστε :guilabel:`OK`.

   * Τα ποτάμια πλέον προβάλλονται με ένα νέο χρώμα.


Δημιουργία νέουQGIS project
=========================

#. Επιλέξτε :menuselection:`File --> New Project`.

#. Με το ποντίκι επιλέξτε :menuselection:`Layer --> Add Vector Layer...`.

#. Πλοηγηθείτε στα δεδομένα :file:`/home/user/data/natural_earth/10m_admin_0_countries.shp`.

#. Επιλέξτε:guilabel:`Open`.

   * Θα πρέπει να δείτε όλες τις χώρες του κόσμου.


Τι ακολουθεί?
==========

Για να μάθετε περισσότερα για το QGIS, ένα σημείο εκκίνησης είναι το `Documentation page`_ στην κεντρική σελίδα του QGIS.

Το OSGeo-Live περιέχει ένα `A Gentle Introduction to GIS`_  και το`QGIS User Guide`_.

.. _`Documentation page`: http://www.qgis.org/en/documentation.html
.. _`A Gentle Introduction to GIS`: ../../qgis/qgis-1.0.0_a-gentle-gis-introduction_en.pdf
.. _`QGIS User Guide`: file:///usr/local/share/qgis/qgis-1.6.0_user_guide_en.pdf





