# Text Mining Simpsons

Analisi dei testi dei dialoghi, in lingua inglese, di circa 600 episodi della celebre serie animata “The Simpsons”.
Il dataset non è stato incluso nella repository perché troppo pesante, ma è reperibile su kaggle (https://www.kaggle.com/datasets/prashant111/the-simpsons-dataset).

I principali obiettivi della ricerca sono:
- applicare una procedura *tidy* per la strutturazione e la pulizia dei testi
- evidenziare le parole più frequenti dei personaggi principali e capire eventuali termini caraterizzanti tramite indici specifici
- analizzare il sentiment di alcuni personaggi caratteristici sfruttando tecniche di sentiment analysis
- individuare degli eventuali topic specifici per determinati luoghi utilizzando la *Latent Dirichelet Allocation*
- proporre due modelli di machine learning in grado di predire, con un certo grado di accuratezza, quale sia il personaggio che recita una certa battuta, in base alle parole che vengono utilizzate nella battuta stessa.

L'intera analisi è stata svolta utilizzando *R* e i pacchetti presenti nel *tidyverse*. TM_Simpsons.Rmd contiene l'intera analisi e questo file genera TM_Simpsons.pdf.
