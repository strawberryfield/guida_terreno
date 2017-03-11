# terrain_guide
## Guida alla creazione del terreno per MSTS e OR

Guida per creare il terreno utilizzando *Route Geometry Extractor* e *Demex* 
per la creazione dei rilievi utilizzando dati DEM

La guida è distribuita in formato sorgente *ReStructuredText*, 
ma nella directory `docs` è presente il sito html compilato
e nella cartella `docs\bin` le versioni in PDF ed EPUB.


## Compilazione dei sorgenti

Per chi volesse compilare da se i sorgenti riporto alcune note desunte dalla guida realizzata da Peter Gulyas
per la documentazione del progetto *OpenRails* consultabile qui: https://gist.github.com/pzgulyas/b5068c7c2cc801dc36e7

### Installare *Sphinx* e *MikTex*

Installare *Python* e *Sphinx*, come descritto qui: http://www.sphinx-doc.org/en/stable/install.html

Installare *sphinx-autobuild*, aprire il prompt comadi e scrivere:

    pip install sphinx-autobuild

Installare *MikTex* come descritto qui: http://miktex.org/howto/install-miktex

### Compilare la guida

Nella directory principale del progetto aprire il prompt comandi e scrivere

    make html
	
verrà generato il sito web nella cartella `_build\html` (avviare `index.html`)

Con il comando

    make latexpdf
	
verrà generato il file PDF nella cartella `_build\latex`

Con il comando 

    make epub
	
verrà generato un ebook in formato epub nella cartella `_build\epub`

Infine il comando

    make clean
	
pulirà completamente la cartella `_build` 
(utile in caso di modifiche per evitare che restino vecchi files inutili)

