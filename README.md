# 📊 Analisi Vendite Online e Segmentazione Clienti

## Descrizione del progetto

Questo progetto analizza le transazioni di un negozio online con l'obiettivo di individuare i principali trend commerciali, comprendere il comportamento dei clienti e ricavare informazioni utili a supportare le decisioni aziendali.

Il progetto è stato sviluppato utilizzando **Python** per la pulizia, la preparazione e l'analisi dei dati e **Microsoft Power BI** per la realizzazione di una dashboard interattiva.

## 🛠️ Tecnologie utilizzate

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Microsoft Power BI
- Git e GitHub

## 📁 Struttura del progetto

```text
analisi-clienti-retail/
│
├── data/
│   ├── Online Retail.xlsx
│   ├── vendite_pulite.csv
│   └── clienti_rfm.csv
│
├── images/
│   ├── andamento_mensile.png
│   ├── ricavi_paese.png
│   ├── ricavi_segmenti.png
│   ├── segmentazione_clienti.png
│   ├── top_10_prodotti.png
│   └── dashboard_powerbi.png
│
├── notebook/
│   └── analisi_clienti.ipynb
│
├── Dashboard_Analisi_Clienti.pbix
├── README.md
└── .gitignore
```

## 🔍 Attività svolte

### 1. Pulizia e preparazione dei dati

- Analisi della struttura del dataset.
- Individuazione e rimozione dei duplicati.
- Analisi dei valori mancanti.
- Identificazione delle transazioni cancellate e delle anomalie.
- Preparazione di un dataset contenente le vendite positive.
- Calcolo del fatturato per transazione.

### 2. Analisi esplorativa delle vendite

Sono stati analizzati:

- Ricavi complessivi.
- Numero di ordini.
- Quantità vendute.
- Numero di prodotti distinti.
- Distribuzione geografica dei ricavi.
- Prodotti con maggior fatturato.
- Andamento mensile delle vendite.

### 3. Segmentazione clienti RFM

È stata realizzata un'analisi RFM basata su tre indicatori:

- **Recency:** tempo trascorso dall'ultimo acquisto.
- **Frequency:** numero di ordini effettuati.
- **Monetary:** valore economico degli acquisti.

I clienti sono stati suddivisi in quattro segmenti:

- Migliori clienti
- Clienti fedeli
- Altri clienti
- Clienti da recuperare

### 4. Dashboard Power BI

È stata realizzata una dashboard interattiva che comprende:

- Ricavi totali.
- Numero ordini.
- Prodotti venduti.
- Clienti identificati.
- Quantità totale venduta.
- Ricavi per Paese.
- Andamento mensile dei ricavi.
- Top 10 prodotti per ricavi.
- Segmentazione clienti RFM.
- Ricavi per segmento cliente.

## 📈 Principali risultati

I risultati seguenti fanno riferimento all'analisi svolta con Python sul dataset delle vendite positive.

| Indicatore | Risultato |
|---|---:|
| Ricavi totali | 10.642.110,80 € |
| Numero ordini | 19.960 |
| Prodotti distinti | 3.922 |
| Clienti identificati | 4.338 |
| Quantità vendute | 5.572.420 |
| Righe del dataset pulito | 524.878 |

### Segmentazione clienti

I migliori clienti rappresentano circa il **21,7% dei clienti identificati** e generano circa il **64,6% dei ricavi associati ai clienti identificati**.

Questo risultato evidenzia l'importanza delle strategie di fidelizzazione e retention.

### Distribuzione geografica

Il Regno Unito rappresenta il principale mercato, generando circa l'**84,6% dei ricavi complessivi** delle vendite positive.

## 📊 Visualizzazioni

### Ricavi per Paese

![Ricavi per Paese](./images/ricavi_paese.png)

### Top 10 prodotti per ricavi

![Top 10 prodotti](./images/top_10_prodotti.png)

### Andamento mensile dei ricavi

![Andamento mensile](./images/andamento_mensile.png)

### Segmentazione clienti RFM

![Segmentazione clienti](./images/segmentazione_clienti.png)

### Ricavi per segmento cliente

![Ricavi per segmento](./images/ricavi_segmenti.png)

### Dashboard Power BI

![Dashboard Power BI](./images/dashboard_powerbi.png)

## 📂 Dataset

Il progetto utilizza il dataset **Online Retail**, disponibile presso l'UCI Machine Learning Repository.

Fonte: [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)

Il dataset contiene transazioni commerciali di un negozio online britannico.

Per l'analisi principale sono state considerate le vendite positive, escludendo le transazioni cancellate e le righe con quantità o prezzo unitario non positivi.

**Nota metodologica:** i ricavi riportati rappresentano il valore delle vendite positive e non il fatturato netto dopo la sottrazione dei resi.

## 🎯 Obiettivi raggiunti

- Pulizia e preparazione di dati reali.
- Analisi esplorativa con Python.
- Calcolo dei principali KPI commerciali.
- Applicazione della metodologia RFM.
- Segmentazione della clientela.
- Creazione di visualizzazioni con Matplotlib.
- Realizzazione di una dashboard interattiva con Power BI.
- Comunicazione dei risultati attraverso un progetto completo di Data Analytics.

---

**Progetto realizzato a scopo di portfolio Data Analyst.**
