# IT: Analisi di un portafoglio defense in epoca di guerra - Modello di Markowitz

## Descrizione
Questo progetto intende sfruttare la teoria del portafoglio per studiare la redditività e i livelli di rischio di un portafoglio _defense_ durante un periodo di forti tensioni geopolitiche.
Tale modello, costruito attraverso un codice _Python_, restituisce come output un grafico che mostri la frontiera efficiente del portafoglio nel periodo di osservazione dell’andamento dei titoli e sarà utilizzato per svolgere tre principali analisi:
1. La prima ha come obiettivo individuare i portafogli più efficienti sulla frontiera efficiente, ovvero con rendimento più elevato o rischio più contenuto, discutendo la performance generale del portafoglio.
2. La seconda analisi confronta il portafoglio _defense_ con un portafoglio più ampio e diversificato per settori, ovvero con titoli di settori diversi tra di loro in maniera da ridurre il rischio specifico .
3. Infine, lo stesso portafoglio _defense_ sarà osservato in due periodi diversi: il periodo anteguerra russo-ucraina e durante il conflitto fino ad oggi, per testare fino a che punto le regole generali del portafoglio siano valide anche per l’ambito della difesa internazionale.

Per concludere, il portafoglio viene confrontato con due benchmark di riferimento MSCI index e Aereo&Defense index, al fine di valutarne la performance complessiva rispetto agli indici dei mercati azionari e del settore _defense_.

## Obiettivo
Simulare un portafoglio composto unicamente da titoli azionari _defense_, ambito ampiamente volatile e per questo molto rischioso, ma anche molto redditizio, in un contesto di forti tensioni politiche come quello odierno, per poi porlo a confronto con un portafoglio azionario più deversificato, composto da titoli di settori meno volatili.

**Note**: 
* I crediti per la struttura iniziale del codice Python sono da attribuire alla docente e ricercatrice [Tiziana Ciano]() il cui codice originale è stato modificato ai fini dello studio.
* Il presente lavoro è ancora in fase di sviluppo, ma, attraverso l'analisi di rendimento, rischio, diversificazione e correlazione, pone le basi per un approfondimento futuro su analisi predittive.  
* Le decisioni di investimento o di altra natura non devono essere assunte esclusivamente sulla base delle informazioni di tale ricerca. 

## Contenuto del repo
- [Report (Word)](https://github.com/krssclaire/portfolio-theory-defense-shares-study/tree/main/wip-report)
- [Notebook Python](https://github.com/krssclaire/portfolio-theory-defense-shares-study/blob/main/notebook/teoria-portafoglio.ipynb) per visualizzazioni e implementazione della modello di Markowitz
- [Notebook Python](https://github.com/krssclaire/portfolio-theory-defense-shares-study/blob/main/notebook/backtest.ipynb) per il backtest (confronto coni benchmark)
- [Grafici generati](https://github.com/krssclaire/portfolio-theory-defense-shares-study/tree/main/img/graphs) tramite librerie Python

## Come riprodurre l'analisi
* Clona il repo
* Per l'analisi del portafoglio:  
   * Apri lo script `portfolio-theory-defense-shares-study.ipynb` 
   * Sostituisci i ticker con i titoli da esaminare secondo i codici stabiliti da [YahooFinance](https://finance.yahoo.com/markets/stocks/trending/)
   * Esegui il notebook per ottenere grafici e risultati
* Per l'analisi di confronto con i benchmark
   * Apri lo script `backtest.ipynb` 
   * Sostituisci i ticker con i titoli da esaminare secondo i codici stabiliti da [YahooFinance](https://finance.yahoo.com/markets/stocks/trending/)
   * Sostituisci il nome degli indici e i ticker degli inidici secondo i codici stabiliti da [YahooFinance](https://finance.yahoo.com/markets/stocks/trending/)
   * Esegui il notebook per ottenere grafici di confronto e i risultati

---

# ENG: Defense portfolio analysis - Markowitz Model

## Overview


## Objective
 

**Disclaimer**: 

## Repository content


## How to reproduce the analysis
