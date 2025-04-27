# EsercitazioneFinale_Python
## ANALISI DATI sul Report dell'epidemia del virus COVID-19

Per il presente progetto, è stato richiesto dal committente di presentare un report sulla situazione mondiale della pandemia da Covid-19, nello specifico sui casi in diverse aree del mondo; a tal fine, è stato richiesto di utilizzare il dataset, curato da Our World in Data, all'indirizzo https://github.com/owid/covid-19-data/tree/master/public/data.
Il database è stato caricato da CSV ed analizzato con Python in un Notebook di JupyterLab.

Come primo approccio è stato quello di effettuate un'EDA del dataset per comprendere i dati caricati, la metodologia usata per il caricamento dei dati, trasformazione del formato dei dati dei campi ove necessario e una prima pulizia.
Le analisi preliminari, nello specifico, con l'analisi sulla correlazione dei dati -solo dei campi necessari per lo studio- si osserverà la loro relazione, oltre a dare una spiegazine per cui si filtreranno successivamente i dati per le seguenti analisi.


È stata richiesta un'analisi mirata dei seguenti punti:
1. Si chiede di trovare, per ogni continente:
  a. il numero di casi fin dall'inizio della pandemia;
  b. la percentuale rispetto al totale mondiale del numero di casi.
2. Selezionare i dati relativi all'Italia nel 2022 e mostrare con dei grafici:
  a. l'evoluzione del casi totali dall'inizio alla fine dell'anno;
  b. il numero di nuovi casi rispetto alla data.
3. Riguardo le nazioni di Italia, Germania e Francia:
  a. mostrare in un boxplot la differenza tra queste nazioni riguardo il numero di pazienti in terapia intensiva da maggio 2022 (incluso) ad aprile 2023 (incluso).
4. Riguardo le nazioni di Italia, Germania, Francia e Spagna in tutto il 2021:
  a. mostrare, in maniera grafica oppure numerica, la somma dei pazienti ospitalizzati per ognuna.

Per le richieste è stato selezionato un nuovo database filtrato dei dati necessari per le rispetive analisi, oltre alla dimostrazione numerica e grafica, e dei commenti per ogni analisi eseguita.
