.. _standard_terrain:

********************
Modellare il terreno
********************

.. _dem_import:

Caricare le DEM
===============

Apriamo Demex, se non abbiamo la versione registrata utilizziamolo in modalità ``Unregistered``

Nella successiva finestra che appare, cliccare sul men? "File" e dal men? a tendina che si apre selezionare la voce "Open"; questo far? aprire la finestra "Select DEM data" dove noi andremo a digitare il percorso relativo al nostro DEM ( di solito ---> C:mapdataDEMs ).
Adesso selezioniamo il nostro file *.DEM ( Lazio - Umbria.DEM )e clicchiamo sul pulsante "Apri" ( oppure direttamente doppio click sul nome del nostro file ) e all'interno di DEMEX apparir? una mappa riferita al nostro DEM.
Ora che abbiamo selezionato il nostro DEM, lo dobbiamo importare nella nostra route all'interno dell'R.E.
Quindi, sempre da DEMEX, riaprire il men? "File" e dal men? a tendina che si apre selezionare la voce "Select Route".
Questa operazione aprir? la finestra "Select MSTS Route", dove noi andremo a selezionare la nostra route ( Route Fantasy ) che abbiamo precedentemente creato con il R.G.E. ( Route Geometry Extractor ).
Una volta selezionata la nostra route, clicchiamo su "OK" e vedremo comparire la griglia dei tile della nostra route, precedentemente creata con l'R.G.E. ( sottoforma di quadrati rossi con una croce all'interno ), sovrapposta al DEM all'interno di DEMEX.


.. _quad_tree:

Generare le montagne
====================

Ora apriamo il men? "Standard terrain" e selezioniamo la voce "Create Route Terrain".
A questo punto DEMEX avvier? il procedimento dell'importazione dei dati DEM all'interno dei tile della nostra route.
Quando DEMEX ha finito, appare una finestra di "report" sull'avvenuta estrazione dei DEM nei tile della route.
Cliccare su "OK" e chiudere DEMEX.

Adesso andiamo a riaprire l'R.E. ( Route Editor ), selezioniamo la nostra route e clicchiamo su "OK".
Questo procedimento avvier? il "Generating terrain buffer..."
Una volta che l'editor ha finito di generare il terreno della route avremo il terreno gi? modellato.

