:Author: OSGeo-Live
:Author: Javier Sanchez, GeoNaTec
:Reviewer: Cameron Shorter, LISAsoft
:Version: osgeo-live6.5
:License: Creative Commons Attribution 3.0 Unported (CC BY 3.0)

.. Review Comment
 For the Project Logo, it should just contain the icon. Currently it also
 includes text and lots of white space above and below the text.
 Can the logo please be edited to only include the icon.
  
.. image:: ../../images/project_logos/logo-tilemill.png
  :scale: 75 %
  :alt: TileMill
  :align: right
  :target: http://www.tilemill.com

TileMill
================================================================================


Design studio for Web Maps
Σχεδιαστικό εργαστήρι για Διαδικτυακούς Χάρτες 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. Review Comment. For consistency with other Project Overviews, there should
  only be one image. As such, please remove the image below (or replace other
  image with this one). js: OK!, but finally I've selected the app interface one, better that the map examples, as I consider it to be more representative of the application.

Το TileMill είναι ένα σχεδιαστικό εργαστήρι για δημιουργία όμορφων, στηριζόμενων στο διαδίκτυο, διαδραστικών χαρτών από μια μεγάλη ποικιλία από υπάρχουσες πηγές γεωχωρικών δεδομένων.

.. Review Comment
  Is the following sentence accurate?
  What are MBTiles? I expect we should include a few words explaining what it is. js: OK! (added explanation about it.)

Οι διαδικτυακοί χάρτες που δημιουργούνται μπορούν να χρησιμοποιήσουν hover tooltips, ενεργά με κλίκ pop ups, διαδραστικά γραφικά και εικόνες, SVG σημάδια, πλούσιες υφές και πολλαπλά επίπεδα. Οι τροποποιημένοι χάρτες μπορούν να εξαχθούν σε διάφορα πρότυπα όπως: .png, .pdf, .svg και MBTiles. Τα MBTiles είναι μια ανοιχτή λεπτομέρεια που εφοδιάζει με έναν τρόπο για αποθήκευση χιλιάδων τετραγώνων σε μία μοναδική SQLite βάση δεδομένων, κάνοντας εφικτή την αποθήκευση και μεταφορά των διαδικτυακών χαρτών σε ένα μόνο αρχείο. Και αφού η SQLite είναι διαθέσιμη σε πολλές πλατφόρμες, τα MBTiles είναι ένα ιδανικό πρότυπο για διάβασμα των πλακιδίων απευθείας στο διαδίκτυο ή για εμφάνιση σε κινητές συσκευές. 

.. Review Comment
  Can Tilemill publish to WMS, WFS? If so, mention it here. js: It doesn't indeed, It is explained bellow that it does not support OGC standards...

Τα δεδομένα μπορεί να προέρχονται από διανυσματικά δεδομένα (CSV, shapefile, KML, GeoJSON), ψηφιδωτά δεδομένα (GeoTiff), όπως επίσης και μεγάλες πηγές δεδομένων όπως OpenStreetMap, Postgres and SQLite. 

.. Review Comment
  Can Tilemill connect to OGC services such as WMS, WFS? If so, mention it here. js: It can't, as far as I Know.

Το Tilemill χρησιμοποιεί το :doc:`Mapnik <mapnik_overview>` χάρτη που παρέχεται από την βιβλιοθήκη (όπως χρησιμοποιείται από το OpenStreeMap) και χρησιμοποιεί το CartoCSS ως γλώσσα μορφοποίησης των φύλλων.

Το TileMill τυπικά χρησιμοποιείται σε σύνδεση με το GIS (όπως το QuantumGIS) για προετοιμασία δεδομένων και με ένα γραφικό συντάκτη (όπως το GIMP) για δημιουργία εικονιδίων, προτύπων και υφής.

.. image:: ../../images/screenshots/1024x768/tilemill_interface.png
  :scale: 90 %
  :alt: TilleMill user interface
  :align: right

Βασικά Χαρακτηριστικά
--------------------------------------------------------------------------------

.. Review Comment
  Can you connect to other map formats, such as Google, Bing, WMS, WFS, ???
  If so mention it. js: It can't, as far as I Know.
* Φόρτωση δεδομένων από μεγάλη ποικιλία πηγών

  * ESRI Shapefile
  * KML
  * GeoJSON
  * GeoTiff
  * CSV spreadsheet
  * OpenStreetMap

* Σύνδεση με τις Γεωχωρικές βάσεις δεδομένων

  * PostgreSQL + PostGIS
  * SQLite

* Διαχείριση τροποποιημένων επιπέδων

* Μορφοποίηση Δεδομένων

  * Μορφοποίηση με χρήση υπαρχόντων ή τροποποιημένων χρωμάτων
  * Υπο όρους μορφοποίηση

* Πρόσθεση tooltips και legends

* Έκδοση

  * Αρχεία εικόνων: .png, .pdf, .svg, MBTiles.
  * Έκδοση ως διαδικτυακή σελίδα 
  * Ένθετος χάρτης σε διαδικτυακή σελίδα ή Σύστημα Διαχείρισης Περιεχομένου (WordPress, Drupal)

* JavaScript API

Υλοποιημένα Πρότυπα
--------------------------------------------------------------------------------

* Το TileMill δεν υποστηρίζει τα πρότυπα OGC, όπως το WMS ή WFS. Αντίθετα υποστηρίζει τα διαδεσομένα πρακτικά των z/x/y πλακιδίων των σχεδίων που χρησιμοποιούνται από την Google και το OSM και είναι βασισμένα στις MBTiles και UTFGrid λεπτομέρειες

Περισσότερες λεπτομέρειες
--------------------------------------------------------------------------------

**Κεντρική ιστοσελίδα:** http://tilemill.com

**Άδεια:** BSD

**Έκδοση Λογισμικού:** 0.10.1

**Υποστηριζόμενες πλατφόρμες:** Windows, Linux, Mac

**Προγραμματιστικές διεπαφές:** JavaScript

**Υποστήριξη:** http://www.tilemill.com


Οδηγός Γρήγορης Εκκίνησης
--------------------------------------------------------------------------------
    
* :doc:`Quickstart documentation <../quickstart/tilemill_quickstart>`
