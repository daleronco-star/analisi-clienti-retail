\# 📊 Analisi Vendite Online e Segmentazione Clienti



\## Descrizione del progetto



Questo progetto analizza un dataset di vendite online con l'obiettivo di individuare i principali trend commerciali, comprendere il comportamento dei clienti e ottenere informazioni utili a supportare le decisioni aziendali.



L'analisi è stata sviluppata utilizzando \*\*Python\*\* per la pulizia e l'esplorazione dei dati e \*\*Power BI\*\* per la realizzazione di una dashboard interattiva.



\## 🛠️ Tecnologie utilizzate



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Jupyter Notebook

\- Microsoft Power BI

\- Git e GitHub



\## 📁 Struttura del progetto



```text

analisi-clienti/

│

├── Online Retail.xlsx

├── analisi\_clienti.ipynb

├── Dashboard\_Analisi\_Clienti.pbix

├── vendite\_pulite.csv

├── clienti\_rfm.csv

├── .gitignore

│

└── images/

&#x20;   ├── andamento\_mensile.png

&#x20;   ├── ricavi\_paese.png

&#x20;   ├── ricavi\_segmenti.png

&#x20;   ├── segmentazione\_clienti.png

&#x20;   └── top\_10\_prodotti.png

```



\## 🔍 Attività svolte



\### 1. Pulizia e preparazione dei dati



\- Analisi della struttura del dataset.

\- Individuazione e rimozione dei duplicati.

\- Analisi dei valori mancanti.

\- Identificazione delle transazioni cancellate e delle anomalie.

\- Creazione di un dataset contenente le vendite positive.

\- Calcolo del fatturato per transazione.



\### 2. Analisi esplorativa delle vendite



Sono stati analizzati:



\- Ricavi complessivi.

\- Numero di ordini.

\- Quantità vendute.

\- Prodotti acquistati.

\- Distribuzione geografica dei ricavi.

\- Prodotti con maggior fatturato.

\- Andamento mensile delle vendite.



\### 3. Segmentazione clienti RFM



È stata realizzata un'analisi RFM basata su tre indicatori:



\- \*\*Recency:\*\* tempo trascorso dall'ultimo acquisto.

\- \*\*Frequency:\*\* numero di ordini effettuati.

\- \*\*Monetary:\*\* valore economico degli acquisti.



I clienti sono stati suddivisi in quattro segmenti:



\- Migliori clienti

\- Clienti fedeli

\- Altri clienti

\- Clienti da recuperare



\### 4. Dashboard Power BI



È stata realizzata una dashboard per visualizzare i principali indicatori e risultati dell'analisi attraverso KPI e grafici interattivi.



\## 📈 Principali risultati



L'analisi Python ha evidenziato:



| Indicatore | Risultato |

|---|---:|

| Ricavi totali delle vendite positive | 10.642.110,80 € |

| Numero ordini | 19.960 |

| Prodotti distinti | 3.922 |

| Clienti identificati | 4.338 |

| Quantità vendute | 5.572.420 |

| Righe del dataset pulito | 524.878 |



\### Risultati della segmentazione RFM



I migliori clienti rappresentano circa il \*\*21,7% dei clienti identificati\*\* e generano circa il \*\*64,6% dei ricavi associati ai clienti identificati\*\*.



Il dato evidenzia l'importanza della fidelizzazione e delle strategie di retention.



\### Distribuzione geografica



Il Regno Unito rappresenta il principale mercato, con circa l'84,6% dei ricavi complessivi delle vendite positive.



\## 📊 Visualizzazioni



\### Ricavi per Paese

!\[Ricavi per Paese](images/ricavi\_paese.png)



\### Top 10 prodotti

!\[Top 10 prodotti](images/top\_10\_prodotti.png)



\### Andamento mensile

!\[Andamento mensile](images/andamento\_mensile.png)



\### Segmentazione clienti

!\[Segmentazione clienti](images/segmentazione\_clienti.png)



\### Ricavi per segmento

!\[Ricavi per segmento](images/ricavi\_segmenti.png)



\## 📂 Dataset



Dataset utilizzato: \*\*Online Retail\*\*, relativo alle transazioni di un negozio online britannico.



Fonte: \[UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)



L'analisi dei ricavi considera le vendite positive, escludendo le transazioni cancellate e le righe con quantità o prezzo non positivi. I resi non vengono quindi sottratti dal fatturato presentato.



\## 🎯 Obiettivi raggiunti



\- Sviluppo di un processo di pulizia e preparazione dei dati.

\- Analisi esplorativa con Python.

\- Applicazione della metodologia RFM.

\- Creazione di una dashboard interattiva con Power BI.

\- Estrazione di informazioni utili sul comportamento dei clienti e sulle performance commerciali.



\---



\*\*Progetto realizzato a scopo di portfolio Data Analyst.\*\*

