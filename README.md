# Laura_Bassi_Information_Gaps

## Introduzione
Il progetto si propone di analizzare la rappresentazione della figura di Laura Bassi all'interno del Knowledge Graph **Wikidata**, con l'obiettivo di individuare e analizzare eventuali gap semantici nella modellazione delle informazioni a lei associate. Attraverso l'utilizzo del linguaggio SPARQL e il confronto con fonti biografiche autorevoli, il lavoro mira a evidenziare come fenomeni di _systemic bias_ (pregiudizio sistemico) e _curation bias_ (bias di selezione) possano influenzare la completezza e la qualità della conoscenza rappresentata, proponendo possibili strategie di arricchimento semantico del grafo.

## Descrizione Dell'Argomento
Il progetto nasce dalla seguente domanda di ricerca: "_Come si riflette il divario di genere nei database che governano il web semantico?_".

In particolare, l'attenzione è stata rivolta al divario di genere nell'ambito accademico dell'Università di Bologna, prendendo come caso di studio la figura di Laura Bassi _Q541652_), fisica italiana del XVIII secolo, seconda donna a laurearsi in Europa e prima donna ad ottenere una cattedra universitaria ufficiale in una disciplina scientifica.

La scelta di Laura Bassi è maturata durante una fase esplorativa dedicata alle docenti dell'Università di Bologna presenti su Wikidata. L'analisi preliminare ha evidenziato come alcune delle informazioni più significative relative alla sua carriera e al suo ruolo pionieristico fossero assenti, incomplete oppure rappresentate in modo poco espressivo dal punto di vista semantico. Questa osservazione ha portato a restringere il campo di indagine alla sua entità, utilizzandola come caso di studio per valutare la qualità della modellazione della conoscenza.

L'obiettivo del progetto è quello di trasformare informazioni prevalentemente narrative, ricavate da fonti biografiche quali Wikipedia e altre fonti storiche, in **conoscenza strutturata**, interrogabile e riutilizzabile all'interno del knowledge graph. Attraverso un'indagine basata su query SPARQL è stata quindi valutata la completezza dell'entità di Laura Bassi, individuando specifici gap semantici relativi alla rappresentazione del suo ruolo istituzionale, dei riconoscimenti ricevuti, delle relazioni accademiche e della sua attività scientifica.

L'analisi costituisce il punto di partenza per proporre un arricchimento del knowledge graph, mostrando come una modellazione più accurata possa rendere maggiormente esplicite informazioni storicamente rilevanti e contribuire a ridurre le distorsioni informative dovute ai bias dei dati. In questo modo, il progetto evidenzia come gli strumenti del Web Semantico possano essere impiegati non solo per interrogare la conoscenza esistente, ma anche per migliorarne la qualità, la completezza e la capacità di rappresentare figure storiche di particolare rilevanza.

## Il Team
*   **Anna Bonazza** (Matricola 1165595)
*   **Gianmarco Rombaldoni** (Matricola 1180017)
*   **Ludovica Villa** (Matricola 1178483)
*   *Anno Accademico 2025/2026 – Università di Bologna*

## Metodologia
Il lavoro segue un flusso metodologico rigoroso suddiviso in quattro fasi principali:
1.  **Audit & Diagnostica:** Ispezione del nodo Wikidata tramite query **SPARQL** per identificare lacune informative rispetto alle fonti storiografiche;
2.  **Isolamento dei Gap:** Definizione di 4 aree tematiche in cui il dato strutturato risultava assente, incompleto o poco espressivo;
3.  **Arricchimento tramite LLM:** Utilizzo di modelli di linguaggio per estrarre conoscenza dalle fonti e generare triple RDF in formato Turtle;
4.  **Validazione e Pubblicazione:** Verifica umana della correttezza logica delle triple prodotte e pubblicazione dei risultati su un portale web ospitato su GitHub Pages.

## Struttura Della Repository
*   `index.html` : Home page del progetto con la presentazione del soggetto;
*   `project.html` : Pagina esplicativa del progetto;
*   `gap1.html` - `gap4.html` : Documentazione dettagliata di ogni lacuna e della relativa query di audit;
*   `prompting.html` : Analisi comparativa dei risultati ottenuti con i diversi LLM;
*   `tripla1.html` - `tripla4.html` : Triple RDF di arricchimento generate dagli LLM con valutazione e validazione;
*   `conclusioni.html` : Conclusioni del nostro progetto;
*   `triple.ttl` : Dataset finale contenente le nuove triple RDF validate;
*   `style.css` : Foglio di stile unificato per il sito web;
*   `RisultatiQueryHTML/` : Cartella contenente i risultati tecnici delle interrogazioni SPARQL;
*   `images/` : Cartella contenente le immagini presenti nel sito web;
*   `en/` : Cartella contenente il sito clonato in inglese.

*Progetto realizzato per l'esame di Metodologie e Tecniche di Simulazione (Laurea Magistrale in Governance E Politiche dell'Innovazione Digitale - Alma Mater Studiorum).*

