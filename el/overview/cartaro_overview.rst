:Author: Friedjoff Trautwein, http://www.geops.de
:Author: Patric Hafner, http://www.geops.de
:Reviewer: Cameron Shorter, http://lisasoft.com
:Version: osgeo-live6.5draft
:License: Creative Commons Attribution 3.0 Unported (CC BY 3.0)

.. image:: ../../images/project_logos/logo-cartaro.png
  :scale: 100%
  :alt: project logo
  :align: right
  :target: http://cartaro.org

Cartaro
================================================================================

Γεωχωρικό CMS
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Το Cartaro εφοδιάζει με λειτουργίες γεωχωρικές και υπηρεσίες διαδικτύου μέσα στο Drupal Content Management System (CMS). Με λίγα μόνο κλίκ μέσα στο Cartaro, μπορείτε να στήσετε και να τρέξετε τα OGC πρότυπα βασισμένα σε υπηρεσίες διαδικτύου, όπως επίσης και να δημιουργήσετε χάρτες στις σελίδες του διαδικτύου. Το Cartaro χτίζεται πάνω σε γερά Ανοιχτού Κώδικα στοιχεία: την βάση δεδομένων :doc:`PostGIS <../overview/postgis_overview>`, :doc:`GeoServer <../overview/geoserver_overview>` και το GeoWebCache υπηρεσιών διαδικτύου, :doc:`OpenLayers <../overview/openlayers_overview>` χάρτες σε εξυπηρετητή, όλα διαχειρίζονται μέσα από το πανίσχυρο `Drupal <http://drupal.org>`_ CMS.     

Το Cartaro είναι σχεδιασμένο για CMS ιστοσελίδες που χρειάζονται να διαχειριστούν γεωχωρικά δεδομένα, και για οργανισμούς που θέλουν μια ελαφριά- με βάρος με Χωρικά Δεδομένα Υποδομή (Spatial Data Infrastructure (SDI)) με ελάχιστη διαμόρφωση και προγραμματισμό.  

.. image:: ../../images/screenshots/1024x768/cartaro_frontpage.png
  :scale: 50%
  :alt: Cartaro Frontpage
  :align: right

Σημαντικά Χαρακτηριστικά
--------------------------------------------------------------------------------

Οι περισσότερες SDI λειτουργίες γίνονται έξω από το κουτί μέσω της στενής ενσωμάτωσης του Drupal με την PostGIS και του Geoserver. Τα βασικά χαρακτηριστικά του Cartaro είναι:

* Αποθήκευση των χωρικών δεδομένων με πραγματικούς τύπους γεωμετρικών δεδομένων 
* Δημιουργία τύπων δεδομένων μέσα από το γραφικό περιβάλλον του Drupal
* Ενσωμάτωση τροποποίησης των γεωχωρικών δεδομένων σε πραγματικό χρόνο
* Έκδοση των δεδομένων με ενσωματωμένους χάρτες
* Διαμόρφωση των διαρρυθμίσεων και των συμπεριφορών των χαρτών
* Συμβολισμός της μορφοποίησης
* Έκδοση των δεδομένων μέσω των OGC προτύπων-συμφωνιών για υπηρεσιες διαδικτύων (OWS) όπως το WMS και το WFS 
* Υψηλές επιδόσεις των παραγόμενων χαρτών μέσω του GeoWebCache
* Διαφανής προνόμια διαχείρισης και ασφάλειας για όλα τα γεωχωρικά δεδομένα
* Ικανοποιητική έκδοση της ροής εργασίας και μέτρια επαναληπτικότητα
* Βασική συλλογή μεταδεδομένων μέσω πρόσβασης στο γραφικό περιβάλλον του GeoServer
* Πλήρης επέκταση μέσω εκατοντάδων εργαλείων του Drupal ή ατομικό προγραμματισμό

Πρότυπα εφαρμογής
--------------------------------------------------------------------------------

  * :doc:`../standards/wms_overview`
  * :doc:`../standards/wfs_overview`
  * :doc:`../standards/wcs_overview`
  * :doc:`../standards/fe_overview`
  * :doc:`../standards/sld_overview` 
  * :doc:`../standards/gml_overview`

Λεπτομέρειες
--------------------------------------------------------------------------------

**Website:** http://cartaro.org/

**Licence:** GNU General Public License (GPL) version 2

**Software Version:** 1.0-beta4

**Supported Platforms:** Windows, Linux, Mac

**API Interfaces:** JavaScript, PHP

**Support:** http://www.geops.de

Οδηγός Γρήγορης Εκκίνησης
--------------------------------------------------------------------------------
    
* :doc:`Quickstart documentation <../quickstart/cartaro_quickstart>`
