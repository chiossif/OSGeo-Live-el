:Author: Eike Hinderk Jürrens (e.h.juerrens@52north.org)
:Version: osgeo-live4.0
:License: Creative Commons

.. _52nSOS-quickstart:
 
.. image:: ../../images/project_logos/logo_52North_160.png
  :scale: 100 %
  :alt: 52°North - exploring horizons - logo
  :align: right
  :target: http://52north.org/sos
  
***********************
Εγχειρίδιο Γρήγορης Εκκίνησης 52°North SOS
***********************

Αρχίζοντας
===============

Το 52°North SOS είναι μια υπηρεσία δικτύου, η οποία σας επιτρέπει να παρέχετε και να συλλέγετε χωρικά δεδομένα από αισθητήρες (συμπεριλαμβανομένων των μεταδεδομένων και των μετρήσεων/παρατηρήσεων).


1) Πηγαίνετε στο :menuselection:`Geospatial --> Web Services --> Start 52North SOS` για να αρχίσετε το 52°North SOS ή χρησιμοποιήστε το από το `direct link <http://localhost:8080/52nSOSv3.1.1/>`_.
  (Εάν η υπηρεσία δεν είναι διαθέσιμη, δοκιμάστε να ξεκινήσετε την μηχανή Tomcat servlet ακολουθώντας τα βήματα στο κάτω μέρος της σελίδας.) 


2) Ο περιηγητής Firefox θα ανοίξει το 52°North SOS test client (δείτε Εικόνα 1):

.. image:: ../../images/screenshots/1024x768/52n_sos_test_client.png
  :scale: 100 %
  :alt: screenshot of 52°North SOS test client
  :align: center
  
**Εικόνα 1**: 52°North SOS test client - welcome page  
  
3) Προκειμένου να ξεκινήσετε με το SOS, επιλέξτε το **GetCapabilities_allSections.xml** [1] αίτημα από την πτυσσόμενη λίστα δίπλα στο "Request Examples".


4) Πατήστε το **Send button** [2] και το αίτημά σας θα μεταδοθεί στο 52°North SOS. Ως αποτέλεσμα, ένα XML αρχείο επιστρέφει (δείτε Εικόα 2), το οποίο εμφανίζει τις δυνατότητες του SOS (διαθέσιμα δεδομένα,...).

.. image:: ../../images/screenshots/1024x768/52n_sos_response.png
  :scale: 70 %
  :alt: screenshot of 52°North SOS output - GetCapabilities response encoded in XML
  :align: center
  
**Εικόνα 2**: 52°North SOS - GetCapabilities response (XML encoded)
  
5) Προκειμένου να χτίσετε τα δικά σας αιτήματα, θα χρειαστείτε τα `capabilities of the 52°North SOS <http://localhost:8080/52nSOSv3.1.1/sos?REQUEST=GetCapabilities&SERVICE=SOS&ACCEPTVERSIONS=1.0.0>`_. Χρησιμοποιώντας αυτή την είσοδο, μπορείτε να επεξεργαστείτε τα παρεχόμενα αιτήματα από έναν test client. Απλά επιλέξτε τα από το πτυσσόμενο μενού.


Πρόσθετες πληροφορίες
======================

* Προκειμένου να μάθετε περισσότερα σχετικά με το 52°North SOS ή το 52°North, τα υποθετικά σημεία αρχής είναι:

* το 52°North `SOS overview <../overview/52nSOS_overview.html>`_,
* η 52°North Sensor λίστα ηλεκτρικού ταχυδρομίου: swe@52north.org, 
* ελέγξτε το 52°North `Sensor Web community forum <http://sensorweb.forum.52north.org/>`_, 
* 52°North `SOS website <http://52north.org/communities/sensorweb/sos/>`_, ή 
* την διαδικτυακή διεύθυνση `52°North Sensor Web Community <http://52north.org/communities/sensorweb/>`_.

* Όταν το SOS δεν είναι διαθέσιμο, παρακαλείσθε να ελέγξετε εάν η μηχανή tomcat servlet τρέχει χρησιμοποιώντας την ακόλουθη εντολή:

::

  user@osgeolive:~$ sudo /etc/init.d/tomcat6 status
  * Tomcat servlet engine is running with pid 1234          <-- Tomcat is running
  [...]
  * Tomcat servlet engine is not running.                   <-- Tomcat not runing, so please start:
  user@osgeolive:~$ sudo /etc/init.d/tomcat6 start
  * Starting Tomcat servlet engine tomcat6           [ OK ] <-- Tomcat is running, now
  
**Listing 1:** Tomcat Status and Start (password for sudo: user)

* The development of this version of the 52°North SOS was supported by the European FP7 research project `EO2HEAVEN <http://www.eo2heaven.org/>`_ 
  (co-funded by the European Commission under the under grant agreement n°244100):

.. image:: ../../images/project_logos/logo_52North_other_200px.png
  :scale: 100 %
  :alt: EO2HEAVEN - Earth Observation and ENVironmental Modeling for the Mitigation of HEAlth Risks
  :align: center
  :target: http://www.eo2heaven.org/
