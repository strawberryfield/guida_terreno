.. _dm_unregistered:

*******************************
Completare le montagne distanti
*******************************

Se avete creato le montagne distanti con Demex in modalità ``Demostration``
queste sono state generate solo parzialmente. Con un trucco perfettamente legale
spiegato da `Trensimpedia <http://www.trensim.com/trensimpedia/index.php?title=MSTS:Modelado_de_terreno_con_Demex>`_
si possono avere delle montagne "complete".

Generare il quad-tree nella route temporanea
============================================

Apriamo con il ``Route Geometry Extractor`` la route temporanea e
nel menù ``File`` clicchiamo su ``New Quad Tree``

Dobbiamo adesso creare un quad-tree identico a quello delle distant mountains,
con i quadrettoni grandi.

Modellare il terreno con Demex
==============================

Aprimao Demex in modalità ``Unregistered`` carichiamo le DEM come visto in precedenza e 
selezioniamo la route temporanea.

Trasferire i tiles
==================

A Questo punto non ci resta che copiare tutti i files contenuti nella cartella ``TILES``
della route temporanea nella cartella ``LO_TILES`` della route effettiva sovrascrivendo quelli esistenti.
Ora abbiamo delle Distant Mountains complete.
