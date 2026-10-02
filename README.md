# Walmart Sales: esplorazione delle vendite settimanali

Analisi esplorativa delle vendite settimanali di 45 punti vendita Walmart. Il progetto esamina differenze tra negozi, andamento nel tempo e relazione delle vendite con alcune variabili economiche e meteorologiche.

## Domande di analisi

- Come si distribuiscono le vendite settimanali tra i punti vendita?
- Le vendite mostrano variazioni nel tempo o differenze tra settimane festive e non festive?
- Come si associano alle vendite temperatura, prezzo del carburante, CPI e tasso di disoccupazione?

## Dati

Il file `walmart_sales.csv` contiene 6.435 righe, con 143 osservazioni per ciascuno dei 45 negozi, dal 5 febbraio 2010 al 26 ottobre 2012. Le colonne includono vendite settimanali, data, indicatore di festività, temperatura, prezzo del carburante, CPI e tasso di disoccupazione.

## Metodi e strumenti

- Controllo della struttura dei dati, statistiche descrittive e valori mancanti
- Aggregazioni e confronti per negozio
- Correlazioni tra vendite e variabili disponibili
- Confronto descrittivo tra settimane festive e non festive
- Grafici dell’andamento temporale e della distribuzione delle vendite
- Python, pandas, NumPy, Matplotlib e Jupyter Notebook

## File del progetto

- `walmart_sales.ipynb`: notebook con codice, grafici e commenti
- `walmart_sales.csv`: dati utilizzati

## Come riprodurre l’analisi

1. Clona o scarica il repository.
2. Installa Python e i pacchetti `pandas`, `numpy` e `matplotlib`.
3. Avvia Jupyter nella cartella del progetto e apri `walmart_sales.ipynb`.
4. Esegui le celle dall’inizio alla fine, mantenendo il CSV nella stessa cartella del notebook.

L’analisi è esplorativa: le correlazioni e i confronti osservati non dimostrano causalità e non bastano, da soli, a giustificare decisioni commerciali.
