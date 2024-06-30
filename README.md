# imago-mmm-linking
Il repository contiene il Jupyter Notebook (Mappatura.ipynb) usato per individuare corrispondenze tra manoscritti presenti nelle Knowledge Base di IMAGO e di Mapping Manuscript Mingrations.
Insieme al Notebook vi sono:
  - i risultati in formato csv delle query SPARQL fatte per recuperare i dati confrontati dei manoscritti.
  - un file json (authorNames.json) creato manualmente che associa le label degli autori usate nelle due KB, importato nel Notebook come dizionario.

La cartella "file_generati" contiene i file generati dal codice nel Notebook, che comprendono:
  - "mappedPlaces.json" dizionario Python salvato come file json che associa i nomi in lingua originale delle città (usati in IMAGO) alle rispettive denominazioni in inglese e a eventuali variazioni nella lingua originale.
  - "mappedLibraries.json" dizionario Python salvato come file json in cui è memorizzato l'esito di ogni confronto tra due bibilioteche.
  - "results.json" la lista dei match individuati salvata come file json.
  - "match_certi.txt" e "match_incerti.txt": file di testo che riportano i match rilevati tra i manoscritti inisieme alle rispettive informazioni.
  - "knowledge.ttl" file Turtle contenente le triple RDF sui manoscritti di MMM matchati.
