:Author: OSGeo-Live
:Author: Tom Kralidis, Angelos Tzotsos
:Reviewer: 
:Version: osgeo-live5.0
:License: Creative Commons

.. _pycsw-quickstart:

.. image:: ../../images/project_logos/logo-pycsw.png
  :scale: 80 %
  :alt: project logo
  :align: right
  :target: http://pycsw.org/

********************************************************************************
Γρήγορη Εκκίνηση pycsw
********************************************************************************

Το pycsw είναι μια υλοποίηση εξυπηρετητή του προτύπου OGC CSW σε γλώσσα προγραμματισμού `Python`_.

To pycsw υλοποιεί την οδηγία 10 (πρωτόκολο επικοινωνίας HTTP του προτύπου Catalogue Services for the Web, CSW) της προδιαγραφής υλοποίησης Υπηρεσίας Καταλόγου του OpenGIS, στην έκδοση 2.0.2. Η υλοποίηση ξεκίνησε το 2010 (και ανακοινώθηκε πιο επίσημα το 2011).

Το pycsw επιτρέπει την δημοσίευση και αναζήτηση γεωχωρικών μεταδεδομένων. Υπάρχοντα αποθετήρια γεωχωρικών μεταδεδομένων μπορούν να δημοσιευθούν μέσω του προτύπου OGC:CSW 2.0.2.

Το pycsw είναι Λογισμικό Ανοιχτού Κώδικα, υπό την άδεια MIT, και υποστηρίζει όλες τις κύριες πλατφόρμες (Windows, Linux, Mac OS X).

Το pycsw είναι προεγκατεστημένο στο OSGeo Live. Αυτός ο οδηγός περιγράφει την διαδικασία εγκατάστασης και δοκιμής της υπηρεσίας μέσω της εγκατεστημένης εφαρμογής δοκιμών.

.. Εγκατάσταση
.. ============
.. 
.. To install pycsw, TODO (how do we install?)


Δοκιμαστική Εφαρμογή
==========================

Για να εκτελέσετε την δοκιμαστική εφαρμογή, επιλέξτε από το μενού WebServices το εικονίδιο pycsw ή εναλλακτικά ανοίξτε ένα παράθυρο Firefox και πληκτρολογήστε http://localhost/pycsw/tester/index.html στη μπάρα διευθύνσεων.

.. image:: ../../images/screenshots/1024x768/pycsw_tester.png
  :scale: 75 %

Το έγγραφο δυνατοτήτων της υπηρεσίας μπορούν να βρεθούν στο: http://localhost/pycsw/csw.py?service=CSW&version=2.0.2&request=GetCapabilities.

.. image:: ../../images/screenshots/1024x768/pycsw_getcapabilities_response.png
  :scale: 75 %

Για πλήρη ανάλυση των δυνατοτήτων του λογισμικού, για ρυθμίσεις και προσθήκη μεταδεδομένων, μπορείτε να συμβουλευθείτε την επίσημη σελίδα του λογισμικού: http://pycsw.org/documentation.html


.. _`Python`: http://www.python.org/
.. _`OpenGIS Catalogue Service Implementation Specification`: http://www.opengeospatial.org/standards/cat
.. _`2011`: http://www.kralidis.ca/blog/2011/02/04/help-wanted-baking-a-csw-server-in-python/
.. _`Open Source`: http://www.opensource.org/
.. _`documentation`: http://pycsw.org/documentation.html

