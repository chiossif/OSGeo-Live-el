Συγγραφεας:Author: Johannes Wilden
:Έκδοση Version: osgeo-live4.0
: ’δειαLicense: Creative Commons
:Ευχαριστείες Thanks: geotools-user list

.. _deegree-quickstart:

******************
deegree Quickstart 
******************

deegree is a Java framework which can be used for setting up web based spatial
data infrastructures.Το πρόγραμμα DEEGREE είναι μια εφαρμογή JAVA που μπορεί να χρησιμοποιηθεί για  

This Quick Start describes how to:Οι συγκεκριμένες οδηγίες "Γρήγορου ξεκινήματος" περιγράφουν πώς:

  * use the iGeoportal ClientΧρησημοποιείται η εφαρμογή του iGeoportal Client
  * send some example requests to our ServicesΣτέλνουμε κάποια παραδείγματα αιτημάτων στις Υπηρεσίες μας

Start deegreeΞεκίνημα προγράμματος DEEGREE
=============

#. Επιλέξτε "Ξεκίνημα προγράμματος deegree" από το σχετικό κατάλογο έναρξηςChoose deegree start from the start menu
#. The application will take a few moments to start upΗ εφαρμογή χρειάζεται λίγο χρόνο για να ξεκινήσει

Welcome ViewΕικόνα καλωσορίσματος
============

#. When you start up deegree for the first time the Welcome view takes up the entire display.Όταν ξεκινάει το πρόγραμμα deegree για πρώτη φορά, η εικόνα καλωσορίσματος καταλαμβάνει ολόκληρη την οθόνη This screenΗ οθόνη αυτή
   has links to tutorials, documentation and the project website.έχει συνδέσεις με βοηθήματα, έγγραφα και την ιστοσελίδα του έργου.

You can return to the Welcome view at any time by clicking on "`Start page`" in
the menu on the left side.Μπορεί κανείς να επιστρέψει οποιαδήποτε στιγμή στην "<Οθόνη καλωσορίσματος" κάνοντας απλά κλικ στο "Σελίδα έναρξης" στον κατάλογο στην αριστερή πλευρά.

Services
========Υπηρεσίες

By clicking on "`Services`" in the menu bar on the left side of the welcome
view, a new view will be opened.Κάνοντας κλικ στο "Υπηρεσίες" στην μπάρα στην αριστερή πλευρά της σελίδας καλωσορίσματος, ένα νέο παράθυρο ανοίγει In the menu bar on the left, you can choose
between "`WMS example requests & clients`", "`WFS example requests & client`"
and "`WCS example requests & client`".Στην μπάρα αριστερά μπορεί κανείς να επιλέξει μεταξύ "WMS παραδειγματα αιτημάτων&πελατών" και  "WFS παραδειγματα αιτημάτων&πελάτη" και  "WCS παραδειγματα αιτημάτων&πελάτη".

Client(iGeoPortal) 
==================Πελάτης (iGeoPortal) 


Starting with the deegree welcome view, choose "`Client (iGeoPortal)`" from the
menu bar.Έχοντας ξεκινήσει με την εικόνα καλωσορίσματος του deegree, επιλέγουμε "`Client (iGeoPortal)`" από τη σχετική μπάρα καταλόγου The next window shows an overview of deegree iGeoPortal.Το επόμενο παράθυρο απεικονίζει μια γενική άποψη του deegree iGeoPortal Click on
"Utah" in the "`deegree iGeoPortal WebMapContexts`" menu on the left side.Στη συνέχεια κάνουμε κλικ στο "Utah" από τον κατάλογο  "`deegree iGeoPortal WebMapContexts`"που βρίσκεται στην αριστερή πλευρά. Now
iGeoPortal with the "Utah" WebMapContexts will be loaded.Τώρα το iGeoPortal με το "Utah" WebMapContexts θα φορτωθεί On the right side of
the map window, there is a LayerListView, where different layers can be switched
on and off.Στη δεξιά πλευρά του παραθύρου του χάρτη υπάρχει η επιλογή του LayerListView με την οποία παρέχεται η δυνατότητα στο χρήστη να επιλέγει εάν θέλει κάποια συγκεκριμένα στοιχεία  να είναι ενεργά ή μη. To see activated layers, you have to refresh the map window with the
"`refresh`" button above the map.Για να μπορέσει κάποιος να δεί τα ενεργοποιημένα στοιχεία, πρέπει να χρησιμοποιήσει το κουμπί της "ανανέωσης" που υπάρχει πάνω από το χάρτη. It is the leftmost one.Είναι το αριστερότερο όλων. A menu bar containing
tools for navigating in the map can be found above the map window.Η μπάρα με το μενου που περιλαμβάνει τα εργαλεία για την πλοήγηση στο χάρτη βρίσκεται πάνω από το παράθυρο του χάρτη. Click on the
magnifier with the "+" Button and click into the map window, to zoom in.Κάνοντας κλικ στον μεγεθυντή που αφορά στο κουμπί "+" και στη συνέχεια κλικ στο χάρτη μπορούμε να κάνουμε μεγέθυνση. You can
either use the "hand" Button, to move the map extent.Επίσης, με τη χρήση του "χεριού" μπορεί κανείς να προσαρμόσει το μέγεθος του χάρτη στο μέγεθος της οθόνης.


Web Map Service
===============Υπηρεσία Web Map

Starting on the "`Services`" page mentioned above, you can access the deegree Web
Map Service example requests and clients.Ξεκινώντας τη σελίδα "Υπηρεσίες" στην οποία έγινε αναφορά προηγουμένως, μπορεί κανείς να έχει πρόσβαση στην Υπηρεσία deegree Web Mapexample requests και clients. Επιλέγοντας το "`Basic WMS requests`" μπορεί κανείς να δεί εν συντομία τα βασικά requests  του deegree WMS και τα responses. Choose the "`Basic WMS requests`" to
have a look at the basic requests of the deegree WMS and its responses. 
Clicking on "Generic Client" on the left side starts the deegree Generic OGC
WebService Client to send POST requests to the WMS.Κάνοντας κλικ στο "Generic Client" στην αριστερή μεριά, το deegree Generic OGC
WebService Client ξεκινά να στέλνει POST requests στο  WMS.  Choose WMS from the Service
drop down menu and push the "Send" Button on the right side.Επιλέγοντας WMS από το αναδιπλούμενο μενού του "Service" και πατώντας το κουμπί "Send" στην δεξιά πλευρά, 
 η ανταπόκριση μπορεί να είναι μια εικόνα που να δειχνει τα The Response might
be a picture showing the citelayers below the xml field.

Web Feature Service
====================Υπηρεσία Web Feature

Starting on the "`Services`" page mentioned above, you can access the deegree
Web Feature Service example requests and clients.Ξεκινώντας τη σελίδα "Υπηρεσίες" στην οποία έγινε αναφορά προηγουμένως, μπορεί κανείς να έχει πρόσβαση στην Υπηρεσία dWeb Feature Service example requests and clients. Choose the "`Basic WFS
requests`" to have a look at the basic requests of the deegree WFS and its
responses.Επιλέγοντας το "`Basic WFS requests`" μπορεί κανείς να δεί εν συντομία τα βασικά requests  του deegree WFS και τα responses.  Clicking on "`Generic Client`" on the left side starts the deegree
Generic OGC WebService Client to send POST requests to the WFS.Κάνοντας κλικ στο "Generic Client" στην αριστερή μεριά, το deegree Generic OGC
WebService Client ξεκινά να στέλνει POST requests στο  WFS. Chose utah from
the examples drop down menu and Springs_code5.xml from the Request drop down
menu.Στη συνέχεια μπορεί κανείς να επιλέξει utah από το αναδιπλούμενο μενού του "examples" και το αρχείο Springs_code5.xml από το αναδιπλούμενο μενού του "Request". Then push the "Send" button on the right side and ahve a look at the
response below.Στη συνέχεια μπορεί κανείς να πατήει το κουμπί "Send" στη δεξιά πλευρά και να δεί την ανταπόκριση κάτω. 

Web Coverage Service
====================Υπηρεσία WebCoverage 

Starting on the "`Services`" page mentioned above, you can access the deegree Web
Feature Service example requests and clients.Ξεκινώντας τη σελίδα "Υπηρεσίες" στην οποία έγινε αναφορά προηγουμένως, μπορεί κανείς να έχει πρόσβαση στην Υπηρεσία dWeb Feature Service example requests and clients. Choose the "Basic WFS requests" to
have a look at the basic requests of the deegree WFS and its responses.Επιλέγοντας το "`Basic WFS requests`" μπορεί κανείς να δεί εν συντομία τα βασικά requests  του deegree WFS και τα responses. 

What Next?Τί αναμένεται στη συνέχεια?
==========

This was just a small overview about deegree services and clients.Αυτή ήταν μια σύντομη ανασκόπηση του προγράμματος  deegree services and clients Have a look
into the degree wiki, the deegree online demo and the deegree.org home, to learn
more about further services and functionalities of the deegree framework.Από τα degree wiki,deegree online demo και το deegree.org home μπορεί κανείς ναμάθει περισσότερα σχετικά με περαιτέρω υπηρεσίες και λειτουργικότητες του πλαισίου λειτουργίας του  deegree.

* deegree wiki

  Available on: http://wiki.deegree.org

* deegree online demo

  Available on: http://demo.deegree.org

* deegree home

  Available on http://deegree.org/
