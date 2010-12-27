Συγγραφεας: OSGeo Live
Συγγραφεας: Astrid Emde
Συγγραφεας: Christoph Baudson
Συγγραφεας: Arnulf Christl
Έκδοση: osgeo-live4.0
 ’δεια: Creative Commons
Ευχαριστείες: mapbender-user list

.. _mapbender-quickstart:
 
.. image:: images/project_logos/logo-Mapbender.png
  :scale: 100 %Κλίμακα:100%
  :alt: project logoalt:Λογότυπο του τμήματος
  :align: rightΣτοίχιση: Δεξιά

********************
Εγχειρίδιο Γρήγορης Εκκίνησης Mapbender 
********************

Το Mapbender είναι ένα διαδικτυακό περιβάλλον για την κατασκευή γεωχωρικών ιστοσελίδων για την δημοσίευση, επισκόπηση, πλοήγηση, παρακολούθηση και ασφαλή πρόσβαση σε γεωχωρικά δεδομένα και Υπηρεσίες Χωρικών Πληροφοριών.
 

Οι διεπιφάνειες διαχείρισης ενισχύουν τους διαχειριστές που χρειάζεται οποίοι χρειάζενται να συντηρήσουν, κατηγοριοποιήσουν και παρακολουθήσουν υπηρεσίες χαρτών και δεδομένων και παρέχει πρόσβαση σε άτομα, ομαδες και άλλες υπηρεσίες 

Δεν χρειάζεστε τίποτα άλλο εκτός από έναν περιηγητή γι'αυτό το Εγχειρίδιο Γρήγορης Εκκίνησης

Αυτό το Εγχειρίδιο Γρήγορης Εκκίνησης περιγράφει:
  *Τη δημιουργία μιας εφαρμογής 
  * Το "φόρτωμα" μιας διαδικτυακής χαρτογραφικής υπηρεσίας (OGC WMS)
  * Τη δημιουργια χρηστών και ομάδων και ανάθεση εφαρμογών σε αυτούς 

Εκκίνηση του Mapbender
===============

.. TBD: Προσθήκη μενού γραφικών σε αυτό το Εγχειρίδιο Γρήγορης Εκκίνησης uDig 

#. Επιλέξτε από τα μενού τα εξής:`Mapbender` από το μενού έναρξης

#. Η εφαρμογή χρειάζεται λίγο χρόνο για να ξεκινήσει

Εάν έχετε δυσκολίες ποσπαθώντας να τρέξετε το Mapbender, παρακαλώ ελέγξτε εάν ο Apache διαδικτυακός εξυπηρετητής και η PostgreSQL βάση δεδομένων σας τρέχουν.

Σελίδα καλωσορίσματος
============

#. Πρίν ξεκινήσετε να εργάζεστε με το Mapbender θα πρέπει να συνδεθείτε (login) προκειμένου να αποκτήσετε πρόσβαση στις εφαρμογές.

#. <Η σελίδα καλωσορίσματος παρέχει συνδέσεις με τις πιο σημαντικές σελίδες οι οποίες σχετίζονται με το Mapbender. 

#. Μπορείτε να συνδεθείτε χρησιμοποιώντας ως user :guilabel:`root` και password :guilabel:`root` (Αυτά είναι τα προεπιλεγμένα user και password τα οποία παίρνει κάποιος μετά την εγκατάσταση τουMapbender. Παρακαλώ αλλάξτε το root password εφόσον επιθυμείτε να τρέξετε ένα παραγωγικό περιβαλλον. Παρακάλώ μην διαγράψετε το χρήστη user :guilabel:`root` καθώς ο χρήστης αυτός έχει πρόσβαση στις εφαρμογές προτύπων του Mapbender και χρησιμοποιείται στις αναβαθμίσεις.
  
  .. image:: images/screenshots/800x600/mapbender_welcome.png
     :scale: 80

Μετά από την επιτυχημάνη σύνδεση κατευθύνστε στο :guilabel:`application overview (επισκόπηση εφαρμογών)`.



Επισκόπηση εφαρμογών
====================
Μετά από την επιτυχημάνη σύνδεση κατευθύνστε στοAfter the login you are directed to the :guilabel:`application overview`(επισκόπηση εφαρμογών) με μια λίστα από εφαρμογές στις οποίες σας ειπτρέπεται η πρόσβαση.
Στο Mapbender  υπάρχουν οι εφαρμογές προτύπων, οι οποίες μπορούν να χρησιμοποιηθούν για το στήσιμο των προσωπικών εφαρμογών.

  .. image:: images/screenshots/800x600/mapbender_application_overview.png
     :scale: 80

Υπάρχουν
   *Εφαρμογές διαχειριστή
   * Εφορμογές χαρτογραφικές
   * container εφαρμογές

Οι εφαρμογές στο σύνολό τους παρατίθενται στο  :guilabel:`categories`. Αργότερα θα μπορείτε να καθορίζετε τις προσωπικές σας κατηγορίες και να προσθέτετε τις εφαρμογές σας στις κατηγορίες που θέλετε.


Administration applications
===========================

:guilabel:`Administration applications` allow you f. e. to load services, create user, to set up new applications. 

Each :guilabel:`administration application` provides different functionality. Later on your can set up your own :guilabel:`administration applications` with the functionality you would like to provide.

After installation user :guilabel:`root` has access to:
   * admin2_en - WMS, application, user/group handling
   * admin_en_services - focus on WFS and metadata handling and owsproxy    
   * admin1 - template with all administration elements 

  .. image:: images/screenshots/800x600/mapbender_admin2_en.png
     :scale: 80

.. tip:: You get back to the application overview with the |HOME| button.

  .. |HOME| image:: images/screenshots/800x600/mapbender_home.png
     :scale: 100Κλίμακα:100%

Map applications
================
Map applications contain OGC WMS, one ore more maps, buttons, a geodata explorer, a legend element, your logo and more. 

#. Choose a map application :guilabel:`by click` from the :guilabel:`application overview`

#. Get to know Mapbender and try the functionality the applications provide.
   
   * choose for example gui, gui_digitize
     
  .. image:: images/screenshots/800x600/mapbender_gui_digitize.png
     :scale: 80

.. tip:: If your browser supports tabs you can open the applications in tabs and easily switch between them.

WMS container applications
==========================
You can create a container application to store your WMS. WMS container are not for display. With containers you can create a sophisticated service repository.

  .. image:: images/screenshots/800x600/mapbender_container.png
     :scale: 60

Create an individual application
=================================

#. go to the administration application :menuselection:`admin2_en` 

#. choose :menuselection:`Application Management --> Create new application`

#. define a name and description for your application and hit the button **new** to create the application

#. go to the link :menuselection:`Application Management --> Edit application elements` and select the new application

#. in the selectbox at the top choose an application that you would like to take as a template and hit the button **add all elements**. This process will take all elements from the application you selected to your new application.

#. you can also take a single element from another application to your new application. Choose the single element by activating the radiobutton at the element and hit the **save** Button to save this element in your new application.

#. your application is set up. Now you need a WMS to be displayed in your application. This will be described in the next section.


.. tip:: You also can create a new application by copying an existing application. Go to :menuselection:`Application Management --> Rename/copy application`, choose the application you want to copy and define a name for the new application.

Loading Web Map Services
========================
You can load OGC Web Map Services (WMS) to your application.

#. Go to :guilabel:`admin2_en` and choose :menuselection:`WMS Management --> Load WMS`. Choose the application which shall contain the WMS. Link to the WMS getCapabilities URL in the text field and hit **Load**.

#. Here are some example WMS you can use to load to your appliction

   * Demis World Map http://www2.demis.nl/wms/wms.asp?wms=WorldMap&VERSION=1.1.1&REQUEST=GetCapabilities&SERVICE=WMS
   * Bird Studies Canada http://www.bsc-eoc.org/cgi-bin/bsc_ows.asp?VERSION=1.1.1&REQUEST=GetCapabilities&SERVICE=WMS
   * Germany demo http://wms.wheregroup.com/cgi-bin/mapserv?map=/data/umn/germany/germany.map&VERSION=1.1.1&REQUEST=GetCapabilities&SERVICE=WMS 
   * WhereGroup OSM WMS http://osm.wheregroup.com/cgi-bin/osm_basic.xml?REQUEST=GetCapabilities&SERVICE=WMS&VERSION=1.1.1
   
.. image:: images/screenshots/800x600/mapbender_wms_application_settings.png
  :scale: 80

User and group management
==========================
An access to Mapbender always requires authentication. This user has permissions to access one or a set of applications and the services (WMS, WFS) which are assigned to these applications.

There is no inherent difference between roles like :guilabel:`guest`, :guilabel:`operator` or :guilabel:`administrator`. The :guilabel:`role` of a user depends on the functionality and services the user has access through his applications.


**Create a user**

#. To create a user go to :guilabel:`admin2_en` and select :menuselection:`User Management --> Create and edit user`

#. Choose a name and a password for your user. 

.. image:: images/screenshots/800x600/mapbender_create_user.png
     :scale: 80 


**Create a group**

#. Create a group by :menuselection:`User Management --> Create and edit group`. Define a name and a description for your group.


**Assign applications to user/group**

#. Assign a user to a group by :menuselection:`User Management --> Add one user to several groups` or by the link :menuselection:`User Management --> Add several users to one group`

#. Assign an application to a user by :menuselection:`User Management --> Allow one user to access several applications`

#. Assign an application to a group by :menuselection:`User Management --> Allow one group to access several applications`

.. tip:: If you want to grant a user write access to an application you have to use :menuselection:`User Management --> Assign to edit an application to a user`.

#. Logout from Mapbender with the |LOGOUT| button.

#. Login as the new user

#. What happens when the user has access to one or more than one application?

  .. |LOGOUT| image:: images/screenshots/800x600/mapbender_logout.png
     :scale: 100Κλίμακα:100%

Things to try
=============

Here are some additional challenges for you to try:

#. Try to load some WMS in your application. Try to configure your WMS with :menuselection:`Configure WMS access --> WMS application settings`.

#. Try to create an individual application - change the background-color, move the buttons, change the size of the map (element mapframe1). :menuselection:`Application Management --> Edit application elements`.


What next?
==========

.. Writing tip
  Provide links to further tutorials and other documentation.

This is only the first step on the road to using Mapbender. There is a lot more functionality you can try.

* Mapbender Project home

  http://www.mapbender.org/

* You find tutorials at

  http://www.mapbender.org/Tutorials

* Try the tutorial in english language

  `Mapbender tutorial (english) <http://www.mapbender.org/Mapbender_Tutorial_en>`_

