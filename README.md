# ANALISI PREDITTIVADEGLI INFORTUNI SPORTIVI


Questo repository contiene un progetto di **Machine Learning** dedicato alla salute degli atleti. Attraverso un compito di classificazione binaria supervisionata, il sistema mira a prevedere il rischio di infortuni muscolari nei calciatori, trasformando l'approccio della medicina sportiva da reattivo a proattivo.

## Obiettivo del Progetto
L'obiettivo principale è sviluppare un sistema di **Early Warning** basato su dati storici, biometrici e di carico di lavoro. Il modello permette allo staff tecnico di:
* **Identificare pattern invisibili**: Correlare decine di variabili per individuare segnali premonitori impercettibili all'occhio umano.
* **Supportare le decisioni cliniche**: Fornire evidenze oggettive per giustificare la turnazione degli atleti o la riduzione dei carichi di allenamento.
* **Standardizzare la diagnosi precoce**: Garantire un monitoraggio scientifico e privo di soggettività per ogni membro del team.

## Risultati e Metodologia
Il progetto si concentra sulla **Recall** come metrica prioritaria, fondamentale in ambito medico-sportivo per minimizzare i Falsi Negativi (atleti a rischio non identificati).

* **Modello Primario**: Logistic Regression (scelta per la sua elevata stabilità e trasparenza).
* **Feature Engineering**: Sviluppo di indicatori avanzati come il `Fatigue_Index`.
* **Interpretability**: Analisi dettagliata dei driver di rischio (Flessibilità, Tempi di reazione, Storia clinica).

## Struttura del Repository
* `src/code/`: Contiene il file `.ipynb` con l'intero workflow di analisi.
* `src/data/`: Dataset originale utilizzato per l'addestramento.
* `report/`: Documentazione tecnica completa in PDF (LaTeX).
* `presentation/`: Presentazione del progetto (PPTX/PDF).

## Strumenti Utilizzati
* **Linguaggio**: Python 3.x
* **Librerie**: Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib.
* **Design**: Figma (Prototipazione Dashboard medica).
