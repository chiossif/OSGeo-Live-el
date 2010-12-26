ΣυγγραφέΑς: Huawei Luo and Trevor Wekel
Έκδοση: osgeo-live4.0
Άδεια: Creative Commons

.. _mapguide-quickstart:Οδηγός γρήγορου ξεκινήματος mapguide

.. image:: images/project_logos/logo-MapGuideOS.png
  :scale: 100 %Κλίμακα:100%
  :alt: project logoalt:Λογότυπο του τμήματος
  :align: rightΣτοίχιση: Δεξιά 

Οδηγός γρήγορου ξεκινήματος mapguide
====================

Ο οδηγός αυτός περιγράφει πώς:

* Να ξεκινήσετε το MapGuide
* Να μορφοποιήσετε τα χωρικά δεδομένα χρησιμοποιώντας το Maestro 
* Επιπλέον σημειώσεις στο 64-bit Ubuntu  

Πώς να ξεκινήσετε το MapGuide
-------------------------------

1. Πηγαίνετε στο Desktop->Server και κάνετε κλικ Start MapGuide. Αυτό θα ξεκινήσει και το MapGuide server και το MapGuide Web server

.. image:: images/screenshots/1024x768/mapguide_desktopIcons.png
  :scale: 50 %
  :alt: mapguide desktop icons
  :align: center 

2. Ανοίγετε τον browser στη διεύθυνση http://localhost:8008/mapguide/phpviewersample/ajaxtiledviewersample.php για να δείτε τη δοκιμαστική εφαρμογή 

.. image:: images/screenshots/1024x768/mapguide_viewer.png
  :scale: 50 %
  :alt: mapguide desktop icons
  :align: center

MapGuide Maestro
----------------

1. Για να ξεκινήσετε το Maestro, πηγαίνετε στο Desktop->Server, κάνετε κλικ MapGuide Maestro, και αυτό ανοίγει το Maestro login GUI, όπως φαίνεται στο ακόλουθο screenshot. Κάντε Login στο http://localhost:8008/mapguide/mapagent/mapagent.fcgi με το username "Administrator" και password "admin" 

.. image:: images/screenshots/1024x768/mapguide_maestroLogin.png
  :scale: 50%
  :alt: screenshot
  :align: center
 
2. Κάνετε κλικ στο Ok για να πάτε στο Maestro main GUI, όπως φαίνεται στο ακόλουθο screenshot.

.. image:: images/screenshots/1024x768/mapguide_maestroMain.png
   :scale: 50%
   :alt: mapguide maestro main GUI
   :align: center

3. Επεκτείνετε την tree view στο αριστερό panel, πηγαίνετε στο Samples->Sheboygan->Layers,κάντε διπλό κλικ στο Buildings και ο layer editor για τα  Buildings θα ανοίξει στο δεξί panel, όπως φαίνεται στο ακόλουθο screenshot:

.. image:: images/screenshots/1024x768/mapguide_maestroLayerFeatures.png
   :scale: 50%
   :alt: mapguide maestro layer features
   :align: center

4. Κυλίστε κάτω το δεξί panelγια να φανεί το Layer Style. Στην στήλη Featurestyle, κάνετε κλικ στο ...κελί για να φέρετε  τον Style Editor, όπως φαίνεται στο ακόλουθο screenshot: 

.. image:: images/screenshots/1024x768/mapguide_maestroLayerStyle.png
   :scale: 50%
   :alt: mapguide maestro layer stype panel
   :align: center

.. image:: images/screenshots/1024x768/mapguide_maestroStyleEditor.png
   :scale: 50%
   :alt: mapguide maestro color chooser
   :align: center

5. Στην αναδιπλούμενη λίστα Foreground Color , επιλέξτε πράσινο Green και κάντε click στο Ok για να κλείσετε τον Style Editor. Στο Maestro Main GUI, κάντε κλικ στο Disk icon για να σώσετε. 

.. image:: images/screenshots/1024x768/mapguide_maestroSaveIcon.png
   :scale: 50%
   :alt: mapguide maestro Save icon 
   :align: center

6. Για να μπορέσετε να κάνετε μια επισκόπηση των αλλαγών, ανοίξτε τον browser στη διεύθυνση http://localhost:8008/mapguide/phpviewersample/ajaxtiledviewersample.php ή κάντε κλικ στο Preview icon στη γραμμή εργαλείων από το Maestro main GUI, το οποίο θα ανοίξει τον browser στην παραπάνω διεύθυνση. Στην browser map view, αν κάνετε μεγέθυνση στο building level, το χρώμα του κτιρίου είναι τώρα πράσινο. 

.. image:: images/screenshots/1024x768/mapguide_buildingColorBeforeChanging.png
   :scale: 50%
   :alt: Building color is grey 
   :align: center

.. image:: images/screenshots/1024x768/mapguide_buildingColorAfterChanging.png
   :scale: 50%
   :alt: Building color is green 
   :align: center

