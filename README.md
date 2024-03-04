---
title: Relazione progetto esame di Editoria Digitale
author: Gabriele Bagnasco 05724A
date: a.a. 2023/24
institute: Università degli Studi di Milano
course: Editoria Digitale
tags: rivista, ingegno
version: 0.1
kind: Document
bibliography: bibliografia.bib
csl: IEEE.csl
---

![Logo UNIMI](./logo/minerva.jpg){width=100px height=100px}

# Ingegno
Progetti pazzi per persone pazze

## Introduzione
Ingegno è una rivista tecnica distrubita secondo una scadenza mensile che ad ogni uscita propone un nuovo progetto da realizzare. Si tratta di progetti fuori dal comune, che toccano rami diversi delle materie scientifiche come meccanica, elettronica e informatica. La scrittura di ogni numero viene svolta in diverse fasi prestando particolare attenzione ai dettagli riguardanti la realizzazione del progetto, definiti in formato XML e ad un'impaginazione accattivante permessa grazie all'uso di software professionali come Adobe InDesign. L'uninione di queste due tecnologie ha permesso di creare un layout di base della rivista, che però rimane molto personalizzabile e adattabile rapidamente, a seconda del progetto trattato nel numero in questione. Si è raggiunta una qualità della rivista che permette una lettura molto scorrevole, facile e chiara nelle istruzioni per la realizzazione del progetto.

## Ideazione 

### Tema
Questo prodotto si pone l'obiettivo ispirare i lettori ad esplorare le frontiere della conoscenza scientifica attraverso la realizzazione di progetti accessibili e stimolanti. Gli appassionati di chimica, fisica, informatica, meccanica e più in generale tutte le materie scientifiche sono tanti; tuttavia, molto spesso, questi temi vengono trattati su supporti diversi. Questa rivista vuole essere un compendio dove ciascun lettore può trovare risposta su materie diverse. Ogni mese viene proposto un nuovo argomento. Per ognuno di essi vi è una prima panoramica generale, dopodichè al lettore viene proposto un nuovo progetto da realizzare riguardante l'argomento trattato; I temi discussi, infatti, sono più facilmente comprensibili se applicati in un contesto reale.

### Destinatari
La rivista è adatta a tutti in quanto ogni argomento viene trattato con molta semplicità; tuttavia, il progetto è stato ideato prendendo come riferimento alcuni destinatari in particolare. Si tratta di persone appassionate di materie in ambito STEM. Di seguito verranno mostrate 3 personas inventate, ma basate sulla realtà, le quali, probabilmente, sarebbero i soggetti più interessati al prodotto.

![personas](https://github.com/gabrielebagnasco/Editoria-digitale/assets/47850441/6843f596-7790-4e8e-9351-dd6daf219396)

Personas come quelle descritte in figura potrebbero usufruire di questo prodotto nel tempo libero, ma non solo. Persone come gli insegnanti, invece, potrebbero prendere degli spunti da alcuni numeri della rivista per creare un argomento di discussione coinvolgente per gli alunni.

### Requisiti di accettazione

Come è già stato spiegato in precedenza, gli argomenti presenti nella rivista, vengono spesso trattati separatamente dai competitor. Inoltre, le istruzioni per la realizzazione di esperimenti e progetti fuori dagli schemi non sono sempre facili da reperire. Questo prodotto, quindi, propone un'innovazione da un punto di vista della qualità dei contenuti andando ad unire appassionati di materie diverse. E' molto importante che il prodotto sia fruibile da un grande numero di dispositivi e che gli articoli della rivista possano essere compresi in modo chiaro.

### Canali di distribuzione
Ingegno è un progetto nato per il web con una particolare attenzione rivolta alla condivisione. Si è deciso di esportare ogni numero in formato PDF per via della sua grande portabilità. E' possibile visualizzare gli articoli su tantissimi dispositivi; anche offline, nel caso vengano scaricati in locale. Il formato PDF permette inoltre, di gestire molto facilmente immagini e forme varie, caratteristica di fondamentale importanza per un progetto come questo. Il prodotto viene sviluppato adottando uno stile piuttosto informale, permettendo di raggiungere una più ampia fetta di mercato.

## Processo di Produzione

### Acquisizione dei contenuti
Le fonti variano a seconda del progetto mensile che viene proposto. Principalmente provengono dal web. Alcune informazioni sono distruibuite come fonti libere, altre necessitano semplicemente della menzione dell'autore originale. Nella stesura dell'articolo, in partiolare per alcune parti specifiche (istruzioni per la costruzione del progetto) è richiesto un lavoro di redazione manuale. Vengono infatti, realizzate delle immagini raffiguranti i passaggi chiave per ottenere il risultato finale. Alcuni progetti sono riprodotti anche dall'autore dell'articolo come è avvenuto con il primo articolo.

### Gestione documentale
Attraverso l'analisi del mercato, viene scelto il progetto mensile da editare. Quindi si passa alla ricerca delle fonti e raccolta dei contenuti. Durante questa fase dobbiamo tenere conto degli aspetti legali riguardanti i diritti delle fonti. Gli articoli vengono scritti in formato XML per poi essere importati in Adobe InDesign ed infine esportati in formato PDF. Lo stile grafico viene gestito con Adobe InDesign. Per quanto riguarda le immagini relative ai passaggi chiave nelle istruzioni sono realizzate con LibreCAD. Adobe InDesign permette un'ottima gestione dei metadati e di conseguenza è stato scelto per la loro scrittura. La revisione del progetto passa attraverso fasi di rilettura ed analisi a più voci, ponendo particolare attenzione sulla frubilità e veridicità dei contenuti. La rivista viene promossa attraverso i canali social e sul web in generale da cui si ricevono anche eventuali feedback degli utenti, utili per l'analisi post produzione.

### Tecnologie adottate

* XML: E' stato deciso di utilizzare un minimo di 3 file XML. Il primo per strutturare la copertina della rivista, il secondo per l'articolo vero e proprio e il terzo per la pagina finale della rivista. Nel caso siano presenti più articoli in quel numero, verranno utilizzati più file XML, uno per ogni articolo oltre a quello per la copertina e la pagina finale.
* Adobe InDesign: E' un software di publishing che ha permesso di realizzare un layout di base della rivista, contenente elementi in comune per ogni numero. Grazie a questo programma è possibile importare file XML e impaginarli automaticamente secondo il layout creato. E' poi possibile apportare modifiche di tipo grafico molto velocemente.
* LibreCAD: E' un software di CAD gratuito e viene utilizzato per la realizzazioni delle immagini raffiguranti i passaggi chiave descritti nelle istruzioni.
* PDF: E' il formato scelto per la distribuzione del prodotto per i motivi spiegati precedentemente.

### Esecuzione del flusso
Sul profilo GitHub è possibile trovare tutti i materiali che permettono di riprodurre il flusso di produzione documentale.

https://github.com/gabrielebagnasco/Editoria-digitale/

## Valutazione dei risultati raggiunti

### Valutazione del flusso di produzione
La suddivisione del lavoro in più fasi e l'utilizzo di tecnologie coerenti ad esse permette un risparmio di tempo nel lungo termine.
 
### Confronto con lo stato dell'arte
Si potrebbe pensare di aggiungere una fase di scrittura dell'articolo in un formato più user-friendly per poi convertirlo in XML così da rendere più semplice la sua redazione.

### Limiti emersi
La scelta di procedere in più fasi ha richiesto tempi più lunghi per la stesura del primo numero della rivista. La scelta è stata però dettata dal guadagno a partire dal secondo numero. Un altro problema affrontato è stato il costo dei programmi di publishing. Programmi professionali come Adobe InDesign sono abbastanza costosi. Inizialmente si era deciso di utilizzare un'alternativa gratuita che però, non disponendo di alcune funzioni fondamentali per questo progetto, si è deciso di affidarsi al software già menzionato più volte.

## Conclusioni
Il progetto risponde all'esigenza di fruibilità diffusa riuscendo a raggiungere il target previsto. Dalle analisi effettuate risulta che la lettura di un articolo sia di facile comprensione.

## Bibliografia e sitografia
Elenco delle risorse fondamentali per la realizzazione del prodotto
[@Rulof_Fai.da.Te_]
