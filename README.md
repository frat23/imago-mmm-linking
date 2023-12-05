# imago-mmm-linking
Il repository contiene il Jupyter Notebook (Mappatura.ipynb) usato per individuare corrispondenze tra manoscritti latini dei Knowledge Base di IMAGO e di Mapping Manuscript Mingrations.
Insieme al Notebook vi sono:
  - i risultati in formato csv delle query SPARQL fatte preliminarmente.
  - un file json (authorNames.json) creato manualmente che associa le label degli autori usate nei due KB, importato nel Notebook come dizionario.

La sotto-cartella "file_generati" contiene i file generati dal codice nel Notebook, che comprendono:
  - "mappedPlaces.json" dizionario Python salvato come file json che associa le denominazioni delle città usate in IMAGO alle rispettive denominazioni in inglese e nelle lingue ufficiali       del paese di appartenenza.
  - "mappedLibraries.json" dizionario Python salvato come file json che mappa le label usate nei due KB per le biblioteche.
  - "results.json" la lista dei match individuati salvata come file json.
  - "match_certi.txt" e "match_incerti.txt": file di testo che riportano le informazioni dei manoscritti matchati.
  - "knowledge.ttl" file Turtle contenente le triple RDF sui manoscritti di MMM matchati.
