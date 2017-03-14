.. _standard_terrain:

********************
Modellare il terreno
********************

Con il procedimento del capitolo precedente abbiamo creato la cosidetta 
*distesa siberiana* ovvero un terreno uniformemente piatto per tutta l'estensione
della nostra route.

In questo capitolo ci occuperemo di modellare i rilievi utilizzando 
dati di elevazione disponibili in appositi database, le codidette DEM.

.. _dem_import:

Caricare le DEM
===============

Apriamo Demex, se non abbiamo la versione registrata utilizziamolo in modalità ``Unregistered``

.. image:: images/demex_unregistered.jpg

Nel menù ``File`` selezioniamo ``Open`` e selezioniamo il file con le DEM.

Se abbiamo necessità di utilizzare più files DEM per coprire l'area della nostra route
dobbiamo tornare nel menù ``File`` e selezionare ``Merge DEM`` per aggiungere tutti gli altri file.

Nella finestra di Demex apparirà una mappa, che sembra una radiografia, con la rappresentazione del terreno 
(più la mappa è chiara maggiore è l'altitudine del terreno).

.. image:: images/demex1.jpg

Ora dobbiamo importare la nostra route. 
Quindi nel menù ``File`` selezioniamo la voce ``Select Route`` e dall'elenco la nostra route.

.. image:: images/dm3.jpg

Vedremo comparire la griglia dei tile della nostra route sovrapposta al DEM.

.. image:: images/demex2.jpg


.. _generate_standard_terrain:

Generare le montagne
====================

Ora apriamo il menù ``Standard terrain`` e selezioniamo la voce ``Create Route Terrain``.

Si avvierà il processo di importazione dei dati DEM all'interno dei tile della nostra route.
Al termine apparirà una finestra di ``report`` sull'avvenuta estrazione dei DEM nei tile della route;
confermiamo ``OK`` e chiudiamo Demex.

Riaprendo il ``Route Editor`` possiamo vedere il terreno della route modellato.

.. image:: images/scrgrb0-450.jpg
