.. _distant_mountains:

******************************
Modellare le montagne distanti
******************************

La procedura di creazione delle montagne distanti si effettua sempre con Demex
(se non avete la versione registrata va usato in modalità ``Demostration``)

Le DM vanno sempre create nella cartella delle ROUTES di default (quantomeno deve essere presente USA2)

1. Mediante RGE create, nella stessa cartella, una ROUTE chiamata TEMPORANEA
2. Aprire DEMEX (versione completa e registrata)
Selezionare la propria ROUTE
Da File -----   Refresh Route Tiles
DM Terrain ---- Prepare Route ---- OK
Minimizzare DEMEX
3. Avviare RGE
Aprire propria Route
File -- Load Quad Tree e ingrandire al massimo centrando la ROUTE
Cliccare il pulsante DM con freccia in basso
Con tasto sinistro fare un rettangolo grande che comprenda dentro la vs. ROUTE. 
Con tasto destro Add all Selection Tiles
Sempre con tasto destro Toggle Populated State
File -- Save Quad Tree
Edit -- Generate Flagged Tiles
File -- Save Quad Tree
Chiudere RGE
4. Riingrandire DEMEX
File - Refresh Route Files
DM Terrain --- Select Temporary Route -- OK
DM Terrain --- Clone DM terrain from std. Terrain --OK
Minimizzare DEMEX
5. Aprire Route Editor
Selezionare la Route Temporanea creando quindi il Terrain Buffer. Così facendo si creano i Tiles nell’omonima cartella della Route temporanea
Chiudere il RE
6. Ringrandire DEMEX
DM Terrain -- Copy DM Tiles back to ROUTE -- OK
Chiudere definitivamente DEMEX
Controllare nelle cartelle LO-TILES e TD della vostra route ci siano I fles corretti.
Aprire la route in MSTS (si presume abbiate creato una mini activity e quindi un Path funzionante e vdere se le DM ci sono

