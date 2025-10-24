# IT: Analisi di un portafoglio defense in epoca di guerra - Modello di Markowitz

## Descrizione
Questo progetto applica la teoria del portafoglio di _Markowitz_ per analizzare la redditività e i livelli di rischio di un portafoglio _defense_ durante un periodo di forti tensioni geopolitiche.  
Il modello, implementato in _Python_, genera un grafico che rappresenta la frontiera efficiente del portafoglio nel periodo di osservazione e consente di svolgere tre principali analisi:
1. Identificazione dei portafogli più efficienti sulla frontiera efficiente, ovvero quelli con rendimento più elevato o rischio più contenuto, con relativa discussione delle performance complessive.
2. Confronto tra il portafoglio _defense_ e un portafoglio diversificato per settori, al fine di ridurre il rischio specifico e valutare l’efficacia della diversificazione.
3. Analisi comparata del portafoglio _defense_ in due periodi distinti – anteguerra russo-ucraina e durante il conflitto – per verificare la validità delle regole generali della teoria del portafoglio anche in contesti di instabilità geopolitica.

Infine, il portafoglio viene confrontato con due benchmark di riferimento:
* *MSCI World Index*, per rappresentare il mercato azionario globale;
* *iShares Aerospace & Defense Index*, per rappresentare il settore di riferimento.

## Obiettivo
Simulare un portafoglio composto esclusivamente da titoli azionari del settore difesa, caratterizzato da elevata volatilità ma potenziale redditività, in un contesto geopolitico complesso.  
Il portafoglio viene poi confrontato con uno più diversificato, composto da titoli di settori meno volatili, al fine di valutare l’impatto della diversificazione e del rischio sistemico sulle performance complessive.

**Note**: 
* I crediti per la struttura iniziale del codice Python sono attribuiti alla docente e ricercatrice [Tiziana Ciano](https://www.univda.it/docenti/ciano-tiziana/), il cui codice è stato adattato ai fini di questa ricerca.
* Il progetto è ancora in fase di sviluppo, ma costituisce la base per futuri approfondimenti su analisi predittive e modelli di machine learning finanziario.
* Le informazioni contenute in questa ricerca non devono essere utilizzate per decisioni di investimento.

## Contenuto del repository
- [Report (formato Word)](https://github.com/krssclaire/portfolio-theory-defense-shares-study/tree/main/wip-report)
- [Notebook Python](https://github.com/krssclaire/portfolio-theory-defense-shares-study/blob/main/notebook/teoria-portafoglio.ipynb) per la visualizzazione e l'implementazione della modello di Markowitz
- [Notebook Python](https://github.com/krssclaire/portfolio-theory-defense-shares-study/blob/main/notebook/backtest.ipynb) per il backtest (confronto con i benchmark)
- [Grafici generati](https://github.com/krssclaire/portfolio-theory-defense-shares-study/tree/main/img/graphs) tramite librerie Python

## Come riprodurre l'analisi
1. Analisi del portafoglio
   * Clona il repository
   * Apri lo script `portfolio-theory-defense-shares-study.ipynb` 
   * Sostituisci i ticker con i titoli da analizzare ([codici YahooFinance](https://finance.yahoo.com/markets/stocks/trending/))
   * Esegui il notebook per ottenere grafici e risultati
2. Analisi di confronto con i benchmark
   * Apri lo script `backtest.ipynb` 
   * Sostituisci i ticker con i titoli da esaminare e aggiorna i nomi degli indici
   * Esegui il notebook per ottenere grafici comparativi e le metriche di performance


# ENG: Defense Portfolio Analysis in Wartime - Markowitz Model

## Description
This project applies Markowitz’s Portfolio Theory to analyze the profitability and risk levels of a defense-focused portfolio during a period of high geopolitical tension.  
The model, implemented in Python, produces a visualization of the efficient frontier for the selected observation period, and supports three main analytical objectives: 
1. Identify the most efficient portfolios on the efficient frontier—those with higher returns or lower risk—and discuss their overall performance.
2. Compare the defense portfolio with a more diversified, multi-sector portfolio to assess how diversification mitigates specific risk.
3. Analyze the same defense portfolio across two timeframes—before and during the Russia–Ukraine war—to test whether the general principles of portfolio theory hold in the defense sector under conditions of geopolitical instability.

Finally, the portfolio is compared with two benchmark indexes:
   * MSCI World Index, representing the global equity market;
   * iShares Aerospace & Defense Index, representing the defense sector.

This comparison helps evaluate the defense portfolio’s performance relative to both the global market and its own sector benchmark.

## Objective
To simulate a portfolio composed exclusively of defense-sector equities, a segment known for its high volatility but also high potential returns, especially in times of political tension.  
The analysis then compares this portfolio with a more diversified equity portfolio consisting of stocks from less volatile industries, in order to evaluate the impact of diversification and systemic risk on overall performance. 

**Disclaimers**: 
* Credit for the initial Python code structure goes to Dr. [Tiziana Ciano](https://www.univda.it/docenti/ciano-tiziana/), whose original work was adapted for this study.
* The project is still under development, but it lays the groundwork for future research on predictive modeling and machine learning applications in finance.
* The information and results presented here should not be used as investment advice or financial recommendations.

## Repository content
- [Report (Word format)](https://github.com/krssclaire/portfolio-theory-defense-shares-study/tree/main/wip-report)
- [Python Notebook](https://github.com/krssclaire/portfolio-theory-defense-shares-study/blob/main/notebook/teoria-portafoglio.ipynb) for visualization and implementation of the Markowitz model
- [Python Notebook](https://github.com/krssclaire/portfolio-theory-defense-shares-study/blob/main/notebook/backtest.ipynb) for backtesting (benchmark comparison)
- [Charts and plots](https://github.com/krssclaire/portfolio-theory-defense-shares-study/tree/main/img/graphs) generated using Python data visualization libraries

## How to reproduce the analysis
1. Portfolio Analysis
   * Clone this repository
   * Open the notebook `portfolio-theory-defense-shares-study.ipynb` 
   * Replace the tickers with those you want to analyze (using [Yahoo Finance codes](https://finance.yahoo.com/markets/stocks/trending/))
   * Run the notebook to generate charts and results
2. Benchmark Comparison
   * Open the notebook `backtest.ipynb`
   * Replace the tickers and benchmark names with your desired indices ([Yahoo Finance codes](https://finance.yahoo.com/markets/stocks/trending/))
   * Run the notebook to generate comparative charts and performance metrics