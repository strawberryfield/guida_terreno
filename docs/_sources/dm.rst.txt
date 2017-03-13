.. _distant_mountains:

******************************
Modellare le montagne distanti
******************************

La procedura di creazione delle montagne distanti si effettua sempre con Demex
(se non avete la versione registrata va usato in modalità ``Demostration``)

.. image:: images/demex_demonstration.jpg

Accertiamoci che fra le route sia presente lo scenario di default USA2 (Marias Pass):
durante il processo di costruzione vengono prelevati alcuni files da questa route.

Apriamo il ``Route Geometry Extractor`` e creiamo una route chiamata *Temporanea*: non è necessario creare il 
quad-tree, bastano solo i parametri generali.

Apriamo Demex (se non avete la versione registrata va usato in modalità ``Demostration``),
Selezionare la propria ROUTE
Da ``File``   ``Refresh Route Tiles``
``DM Terrain`` ``Prepare Route`` ``OK``
Minimizzare Demex

Apriamo nuovamente il ``Route Geometry Extractor`` e quindi apriamo la nostra route

``File`` ``Load Quad Tree`` e ingrandire al massimo centrando la ROUTE
Cliccare il pulsante DM con freccia in basso
Con tasto sinistro fare un rettangolo grande che comprenda dentro la vs. ROUTE. 
Con tasto destro ``Add all Selection Tiles``
Sempre con tasto destro ``Toggle Populated State``
``File`` ``Save Quad Tree``
``Edit`` ``Generate Flagged Tiles``
``File`` ``Save Quad Tree``

Possiamo chiudere il ``Route Geometry Extractor``

Ingrandiamo Demex

``File`` ``Refresh Route Files``
``DM Terrain`` ``Select Temporary Route`` ``OK``
``DM Terrain`` ``Clone DM terrain from std. Terrain`` ``OK``

Minimizzare DEMEX

Apriamo il ``Route Editor``

Selezionare la Route Temporanea creando quindi il Terrain Buffer. Così facendo si creano i Tiles nell’omonima cartella della Route temporanea

Chiudiamo il ``Route Editor``

Ingrandiamo nuovamente Demex

``DM Terrain`` ``Copy DM Tiles back to ROUTE`` ``OK``

Chiudere definitivamente Demex

Controllare nelle cartelle LO-TILES e TD della vostra route ci siano I fles corretti.
Aprire la route in MSTS (si presume abbiate creato una mini activity e quindi un Path funzionante e vdere se le DM ci sono

