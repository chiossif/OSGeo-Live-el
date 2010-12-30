Συγγραφεας: Hamish Bowman
Έκδοση: osgeo-live4.0
 ’δεια: Creative Commons

.. _grass-quickstart:
 
.. image:: images/project_logos/logo-GRASS.png
  :scale: 100 %Κλίμακα:100%
  :alt: project logoalt:Λογότυπο του τμήματος
  :align: rightΣτοίχιση: Δεξιά
  :target: http://grass.osgeo.org


********************
GRASS GIS Εγχειρίδιο γρήγορης εκκίνησης
********************

Τρέχοντας το πρόγραμμα                                                                                                                                                                    =======

Για να τρέξετε το GRASS στο Live DVD, κάνετε κλικ στη συντόμευση του GRASS στην επιγάνεια εργασίας.
Από το  "Welcome to GRASS" (παράθυρο καλωσορίσματος) επιλέξτε ή το Spearfish ή το North
Carolina (nc_spm_08) αρχείο δεδομένων για την για την τοποθεσία, και "user1" για το αρχείο χάρτη mapset,
και κέντε κλικ στο [Start Grass].

.. image:: images/screenshots/800x600/grass-startup.png
  :scale: 40 %
  :alt: screenshot
  :align: rightΣτοίχιση: Δεξιά

Αυτό θα ξεκινήσει το GRASS με το νέο γραφικό περιβάλλον γραμμένο σε wxPython. Κατά την περίοδο του γραψίματος είχαμε αντιμετωπίσει σχεδόν όλα τα "προβλήματα" και ήμασταν κοντά στο να το πούμε (και GRASS 6.4.0) πλήρες. Το παλιό 
Tcl/Tk γραφικό περιβάλλον είναι ακόμα διαθέσιμο. Εάν επιθυμείτε να το χρησιμοποιήσετε, μπορείτε να ξεκινήσετε γράφοντας ``g.gui --ui`` στη γραμμή εντολών.

Εάν είστε σε ένα netbook με χαμηλή ανάλυση (800x600 ανάλυση)
η οθόνη εκκίνησης μπορεί να είναι λίγο scrunched και το κουμπί [Start GRASS]
κρυμμένο πίσω από το location and mapset lists. Εάν αυτό σας συμβαίνει, η λύση είναι να σύρετε την γωνία του παραθύρου για να το κάνετε λίγο μεγαλύτερο. Μπορεί να χρειάζεται να μετακινήσετε το παράθυρο προς το πάνω τμήμα της οθόνης για να κερδίσετε χώρο (κρατήστε πατημένο το πλήκτρο Alt και με δεξί κλικ σύρετε το παράθυρο για να το μετακινήσετε).

Παρουσιάζοντας χάρτες
~~~~~~~~~~~~~~~

.. image:: images/screenshots/800x600/grass-layerman.png
  :scale: 50 %
  :alt: screenshot
  :align: left

Όταν πια έχετε μπεί στο πρόγραμμα, προσθέστε ένα επίπεδο με χάρτη σε μορφή εικόνας, όπως είναι το "`elevation`" από το PERMANENT
mapset. Για να το κάνετε αυτό, πηγαίνετε στο παράθυρο the GIS Layer Manager και κάνετε κλικ στο κουμπί με το a "+"  σε αυτό στη γραμμή εργαλείων checkerboard. Τότε επιλέξτε το όνομα χάρτη που επιθυμείτε από την αναδιπλούμενη λίστα  "*map to be displayed*"  και κάντε κλικ στο [Ok].

Κατά τον ιδιο τρόπο προσθέτετε το "`roads`" διανυσματικό επίπεδο από το PERMANENT
mapset κάνοντας κλικ στο κουμπί της μπάρας εργαλείων με το a "+" και μια poly-line
που μοιάζει περισσότερο με ένα "V".

Από τη γραμμή εργαλείων του παραθύρου επισκόπησης χάρτη (Map Display window) κάντε κλικ στο κουμπί eyeball για να δημιουργηθεί η όψη.

Τώρα θα πρέπει να μπορείτε να δείτε τους χάρτες.

Εκτύπωση προφίλ υψομέτρου                                                                                                ~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: images/screenshots/800x600/grass-profile.png
  :scale: 50 %
  :alt: screenshot
  :align: rightΣτοίχιση: Δεξιά

Πίσω στο παράθυρο GIS Layer Manager κάντε κλικ στο  `elevation` raster
map name για να το επιλέξετε. Στο παράθυρο επισκόπησης χάρτη (Map Display window), στα δεξιά των κουμπιών μεγέθυνσης στη γραμμή εργαλείων Map Display, βρίσκεται ένα εικονίδιο με ένα γραμμικό γράφημα και μια σκακιέρα σε αυτό. Κάντε κλικ σε αυτό και επιλέξτε **Profile Surface Map**.
Εάν δεν καταγράφεται αυτόματα, τότε επιλέξτε ξανά ένα elevation map σάν επίπεδο χάρτη και πατήστε [Ok]. Το δεύτερο κουμπί προς τα μέσα από αριστερά, επιτρέπει τον καθορισμό της profile line. Κάντε κλικ σε αυτό τότε μαρκάρετε μερικά σημεία στοMap
Display canvas. Όταν ολοκηρωθεί και αυτό πηγαίνετε πίσω στο παράθυρο Profile και κάντε κλικ στο κουμπί eyeball για να δημιουργήσετε το αρχείο προς εκτύπωση. Κάντε κλικ στοκουμπί  I/O πάνω δεξιά για να κλείσετε το παράθυρο profile.

Δημουργήστε μια τυχαία επιφάνεια
~~~~~~~~~~~~~~~~~~~~~~~

Τώρα ας δημιουργήσουμε ένα χάρτη. Επιλέξτε :Μενού:`Raster --> Generate 
surfaces --> Fractal surface` από το μενού (κοντά στο κάτω μέρος);
δώστε στο νέο σας χάρτη ένα όνομα; προσαρμόστε τις επιλογές σας στο Options
tab (τα προεπιλεγμένα είναι μια χαρά); και κάντε κλικ στο [Run]. Τότε μπορείτε να κλείσετε  [Close] το παράθυρο διαλόγου *r.surf.fractal* module's dialog window.

.. image:: images/screenshots/800x600/grass-fractal.png
  :scale: 50 %
  :alt: screenshot
  :align: rightΣτοίχιση: Δεξιά

Προσαρμογή των χρωμάτων
~~~~~~~~~~~~~

Τώρα προσθέστε το νέο σας επιπεδο εικόνας στη λίστα επιπέδων οπως κάνατε προηγουμένως με τον χάρτη υψομέτρου. Ωστόσο, αυτή τη φορά θα είναι στο "user1"
mapset εργασίας. Μπορείτε αν θέλετε τώρα να ξεκλικάρετε το επίπεδο υψομέτρου από το σχετικό κουτί έτσι ώστε να μην αλληλοεπικαλύπτονται τα δύο μεταξύ τους. Κάντε κλικ στο eyeball για να δείτε το νέο σας χάρτη.
Τα χρώματα μπορεί να μην είναι όπως σας αρέσουν οπότε ας τα αλλάξουμε. Με το fractal DEM επιλεγμένο στη λίστα επιπέδων,στο`Raster` μενου, επιλέγετε :Μενού:`Manage colors --> Color Tables`.
Στην καρτέλα "Colors" κάντε κλικ στην αναδιπλούμενη λίστα για την επιλογή "Type of color
table" option, και πάρτε ένα από τη λίστα. "srtm" είναι μια καλή επιλογή. Όταν ολοκληρώσετε, κάντε κλικ στο κουμπί [Run] και κλείστε το παράθυρο διαλόγου  *r.colors* dialog window.

Επειδή έχετε τροποποιήσει τα μεταδεδομένα του χάρτη, θα πρέπει αυτή τη φορά να ξαναφτιάξετε από την αρχή νέα επισκόπηση του χάρτη. Οπότε, κάντε κλικ στο μικρό κουμπί της ανανέωσης, δίπλα στο κουμπί eyeball, προκειμένου να επανασχεδιαστούν τα επίπεδα και τότε θα μπορείτε να δείτε το χάρτη σας με τα νέα του χρώματα.
  
Create a shaded relief map
~~~~~~~~~~~~~~~~~~~~~~~~~~

.. image:: images/screenshots/800x600/grass-shadedrelief.png
  :scale: 50 %
  :alt: screenshot
  :align: rightΣτοίχιση: Δεξιά

Next we'll create a shaded relief map of the elevation layer we saw
earlier. Start by verifying that the computational region is set match
the raster map of interest, "`elevation`" in the PERMANENT mapset. To
do this, make sure it is loaded into the layer list of the main Layer
Manager window, right click on its name and select "Set computation region
from selected map(s)". In the `Raster` menu select :menuselection:`Terrain
analysis --> Shaded relief` (Terrain analysis is about half way
down), and the module control dialog will appear. With the elevation
map name selected as the input map click [Run]. Now add the new
elevation.shade @user1 map into your layer list and un-tick the other
raster layers, then click the eyeball to re-render. (If you get sick of
clicking the eyeball all the time you can tick the "Render" box in the
bottom right of the Map Display window to have that happen automatically)

Watersheds and streams
~~~~~~~~~~~~~~~~~~~~~~

Once again select the `elevation` @PERMANENT map and in the `Raster` menu
choose :menuselection:`Hydrologic modeling --> Watershed analysis`. This
will open the ``r.watershed`` module. Set the `elevation` layer as your
input map, in the 'Input Options' tab set the sub-basin *threshold* to
10000 cells, then in the 'Output Options' tab enter "elev.basins" for the
watershed basin option and "elev.streams" for the stream segments option
just below it. Then click [Run].

Back in the Layer Manager window add those two new raster maps to the
layer list and make sure that they are the only two which are ticked
for display in the box to the left of the layer name. Right click on
the elev.basins raster map layer name and select "Change opacity level".
Set it to about 50% then re-render the Map Display.

.. image:: images/screenshots/800x600/grass-watersheds.png
  :scale: 50 %
  :alt: screenshot
  :align: left

In the GIS Layer Manager window click on the third button in from the
right to add a grid layer. For size of grid put 0:03 for 0 degrees and
3 minutes (format is D:M:S), then in the "Optional" tab tick Draw
geographic grid and press [Run] and re-render.

To add a scalebar go to the Map Display window and press the "Add
map elements" button to the right of where you selected the Profile tool
earlier and select "Add scalebar and north arrow". Read the instructions
then click [Ok]. A scalebar will appear in the top left. Drag it down
to the bottom left. From the same toolbar menu select "Add legend" and
in the instructions window click the Set Options button to set the
raster map name to create the legend for. After picking one click [Ok]
and [Ok] again. Drag your new legend over to the right side of the map
canvas.

Now you may be thinking to yourself that these fonts are a bit bare.
That's easily fixed in the GIS Layer Manager menus open :menuselection:`Config  --> 
Preferences` and in the Display tab click the [Set font] button and
then [Apply] in the Preferences window. You will have to do a full
re-render to see the change so click on the re-render button next to the
eyeball. The fonts will now be much prettier.

Vector modules
~~~~~~~~~~~~~~
 
The above tasks have only covered a few raster modules. Don't let this
give you the idea that GRASS is just for raster maps -- the vector engine
and modules are every bit as full-featured as the raster ones. GRASS
maintains a fully topological vector system which allows all sorts of
very powerful analyses.

3D visualization
~~~~~~~~~~~~~~~~

.. image:: images/screenshots/1024x768/grass-nviz.png
  :scale: 30 %
  :alt: screenshot
  :align: rightΣτοίχιση: Δεξιά

Start the 3D visualization suite from the :menuselection:`File --> NVIZ`
menu item. Select an `elevation` map as the raster elevation.
Once the 3D display interface loads, maximize the window.
Next select :menuselection:`Visualize --> Raster Surfaces` from the top menu,
and set the fine resolution to "1", then move the positioning puck and height
slider around to get different views.

To drape satellite or aerial imagery over the top of the DEM, in the
**Raster Surfaces** controls click on the **Surface Attributes**
drop down menu and select "color". Select "New Map" to pick the overlay
image. In the Spearfish dataset "`spot.image`" in PERMANENT is a
good choice; in the North Carolina dataset "`lsat7_2002_50`"
in PERMANENT is a good choice. Finally, click "Accept" and then once
back at the main window click on the "Draw" button in the top-left, just 
under the File menu.

Shutdown and the command line
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

When finished, exit the GRASS GUI with :menuselection:`File --> Exit`.
Before you close the GRASS terminal session as well, try a GRASS
module by typing "``g.manual --help``" which will give you a list
of module options. The GRASS command line is where the true power of
the GIS comes into its own. GRASS is designed to allow all commands
to be tied together in scripts for large bulk processing jobs. Popular
scripting languages are Bourne Shell and Python, and some neat tricks
for making scripting easier are included for both. With these tools
you can make a new GRASS module with only about 5 minutes of coding,
complete with powerful parser, GUI, and help page template.

"``g.manual -i``" will launch a web browser
with the module help pages. When done close the browser and type "exit"
at the GRASS terminal prompt to leave the GIS environment.

Further reading
===============
* Visit the GRASS website at `http://grass.osgeo.org <http://grass.osgeo.org>`_
* Visit the GRASS Wiki help site at `http://grass.osgeo.org/wiki <http://grass.osgeo.org/wiki>`_
* A more tutorials and overviews can be found `here <http://grass.osgeo.org/wiki/GRASS_Help#Getting_Started>`_.
* A `synopsis of the GRASS modules <http://grass.osgeo.org/gdp/grassmanuals/grass64_module_list.pdf>`_, including
  GUI menu position. (`HTML version <http://grass.osgeo.org/gdp/grassmanuals/grass64_module_list.html>`_)
* If the 400 GIS modules which come with GRASS aren't enough for you have a look at the many contributed
  add-ons at `http://grass.osgeo.org/wiki/AddOns <http://grass.osgeo.org/wiki/AddOns>`_
