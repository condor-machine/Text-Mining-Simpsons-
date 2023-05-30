# Text Mining Simpsons (ITA)

Analisi dei testi dei dialoghi, in lingua inglese, di circa 600 episodi della celebre serie animata “The Simpsons”.
Il dataset non è stato incluso nella repository perché troppo pesante, ma è reperibile su kaggle (https://www.kaggle.com/datasets/prashant111/the-simpsons-dataset).

I principali obiettivi della ricerca sono:
- applicare una procedura *tidy* per la strutturazione e la pulizia dei testi
- evidenziare le parole più frequenti dei personaggi principali e capire eventuali termini caraterizzanti tramite indici specifici
- analizzare il sentiment di alcuni personaggi caratteristici sfruttando tecniche di **sentiment analysis**
- individuare degli eventuali topic specifici per determinati luoghi utilizzando la *Latent Dirichelet Allocation*
- proporre due modelli di **machine learning** in grado di predire, con un certo grado di accuratezza, quale sia il personaggio che recita una certa battuta, in base alle parole che vengono utilizzate nella battuta stessa.

L'intera analisi è stata svolta utilizzando *R* e i pacchetti presenti nel *tidyverse*. TM_Simpsons.Rmd contiene l'intera analisi e questo file genera TM_Simpsons.pdf.

-------------------------------------------------------------------------------------------------------------------------------------------------------


# Text Mining Simpsons (EN)

Analysis of dialogue texts, in English, from about 600 episodes of the famous animated series "The Simpsons."
The dataset was not included in the repository because it was too heavy, but it can be found on kaggle (https://www.kaggle.com/datasets/prashant111/the-simpsons-dataset).

The main objectives of the research are:
- apply a *tidy* procedure for structuring and cleaning the texts
- highlight the most frequent words of the main characters and understand any caracterizing terms through specific indexes
- analyze the sentiment of some characteristic characters by exploiting **sentiment analysis** techniques
- identify possible specific topics for certain places using *Latent Dirichelet Allocation*
- propose two **machine learning** models capable of predicting, with a certain degree of accuracy, which character is playing a certain line, based on the words that are used in the line itself.

The entire analysis was carried out using *R* and the packages in the *tidyverse*. TM_Simpsons.Rmd contains the entire analysis and this file generates TM_Simpsons.pdf.
