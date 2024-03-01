---
title: Relazione progetto esame di Editoria Digitale
author: Gabriele Bagnasco 05724A
date: a.a. 2023/24
institute: Università degli Studi di Milano
course: Editoria Digitale
tags: tag1, tag2, tag3
version: 0.1
kind: Document
bibliography: bibliografia.bib
csl: IEEE.csl
---

![Logo UNIMI](./logo/minerva.jpg){width=100px height=100px}

# Ingegno
Progetti pazzi per persone pazze

## Introduzione
Ingegno è una rivista tecnica distrubita secondo una scadenza mensile che ad ogni uscita propone un nuovo progetto da realizzare. Si tratta di progetti fuori dal comune, che toccano rami diversi delle materie scientifiche come meccanica, elettronica e informatica. La scrittura di ogni numero viene svolta in diverse fasi prestando particolare attenzione ai dettagli riguardanti la realizzazione del progetto, definiti in formato XML e ad un'impaginazione accattivante permessa grazie all'uso di software professionali come Adobe InDesign. L'uninione di queste due tecnologie ha permesso di creare un layout di base della rivista, che però rimane molto personalizzabile e adattabile, rapidamente, a seconda del progetto trattato nel numero in questione. Si è raggiunta una qualità della rivista che permette una lettura molto scorrevole, facile e chiara nelle istruzioni per la realizzazione del progetto.

Breve descrizione del progetto toccando i punti più importanti affrontati nel documento.
*Obiettivi*, *tecnologie*, aspetti salienti del *flusso di gestione documentale*, *risultati* raggiunti.  

## Ideazione 

### Tema
Questo prodotto si pone l'obiettivo ispirare i lettori a esplorare le frontiere della conoscenza scientifica attraverso progetti fai-da-te accessibili e stimolanti. Gli appassionati di chimica, fisica, informatica, meccanica e più in generale tutte le materie scientifiche sono tanti; tuttavia, molto spesso, questi temi vengono trattati separatamente gli uni dagli altri. Questa rivista cerca di unire e trattare argomenti diversi in quanto andrebbero considerati come componenti di un'unica grande famiglia. 

Identificazione dei temi che il prodotto editoriale dovrà presentare. Evidenziare gli argomenti correlati e la tendenza dell'attenzione su questi temi. 

> LM2 slide 28

### Destinatari
La rivista è adatta a tutti in quanto ogni argomento viene trattato con molta semplicità, tuttavia, il progetto è stato ideato prendendo come riferimento alcuni destinatari in particolare. Si tratta di persone appassionate di materie in ambito scientifico come elettronica, meccanica, chimica, informatica, ecc. Di seguito verranno mostrate 3 personas inventate, ma basate sulla realtà, le quali, probabilmente, sarebbero i soggetti più interessati al prodotto.

![personas](https://github.com/gabrielebagnasco/Editoria-digitale/assets/47850441/6843f596-7790-4e8e-9351-dd6daf219396)

Personas come quelle descritte in figura potrebbero usufruire di questo prodotto nel tempo libero ma non solo, persone come gli insegnanti, ad esempio, potrebbero prendere degli spunti da alcuni numeri della rivista per creare un argomento di discussione coinvolgente per gli alunni.

Descrivere i destinatari del prodotto editoriale descrivendo le personas alle quali si rivolge il prodotto. Descrivete alcuni scenari d'uso nei quali inserire le personas scelte come destinatari.

> LM2 slide 29-32

### Requisiti di accettazione
Indicate i requisiti di accettazione che dovranno essere soddisfatti per raggiungere i destinatari. Quali modelli di fruizione consideriamo più efficaci per i nostri destinatari? Quali standard consideriamo come riferimento? Quali aspetti di innovazione possiamo proporre? Nella qualità dei contenuti o nel processo di fruizione?

> LM4

### Canali di distribuzione
Presentare i canali di distribuzione che si intendono raggiugnere e i formati dati richiesti da ogni canale. Esempi di canali sono: (i) Web, (ii) Social, (iii) Market place, (iv) Intranet. Esempi di formati. (i) Word, (ii) ePub, (iii) CBZ, (iv) PDF, (v) WebBook. 
Proporre alcuni accenni relativi all'identità visuale e alle regole tipografiche o di stile che si intendono seguire. Nel settore esisto classi di documento standard? Dati gli obiettivi è importante trasmettere un senso di adesione a modelli già conosciuti o un senso di innovazione? Lo stile sarà orientato verso un'espressione formale o informale?

## Processo di Produzione

### Acquisizione dei contenuti
Descrivere le fonti che saranno utilizzate nella costruzione del prodotto editoriale. Nella scelta delle fonti valutare il costo di acquisizione: (i) disponibili come fonti libere, (ii) generabili automaticamente, (iii) richiedono un lavoro di redazione manuale.

### Gestione documentale

Descrivere il *flusso di gestione documentale* definito per il progetto. Ad esempio, (i) la raccolta o produzione dei contenuti, (ii) la valutazione dei diritti, (iii) la trasformazione dei formati, (iv) la strutturazione dei contenuti, (v) l'applicazione dello stile grafico, (vi) la generazione dei metadati, (vii) la distribuzione dei contenuti. Nella descrizione del flusso considerare le  fasi di revisione, controllo e approvazione che possono richiedere le diverse fasi.

> LM2 slide 14-26

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
```mermaid
flowchart LR
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
```

### Tecnologie adottate

Descrivere le tecnologie addottate nelle diverse fasi e discuterne il contributo in termini di raggiungimento degli obiettivi descritti negli scenari d'uso.

|                |Scenario 1                          |Scenario 2                       |
|----------------|-------------------------------|-----------------------------|
|Markdown |`'Isn't this fun?'`            |'Isn't this fun?'            |
|XSLT       |`"Isn't this fun?"`            |"Isn't this fun?"            |
|ePud         |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|

### Esecuzione del flusso
Allegare, possibilmente attraverso il riferimento ad un repository documentale, i materiali, gli script, le configurazioni, che permettono di riprodurre il flusso di produzione documentale. I contenuti non devono necessariamente essere completi, può essere sufficiente fornire un prototipo per ogni tipologia di contenuto previsto e per ogni formato di destinazione previsto.  

## Valutazione dei risultati raggiunti


### Valutazione del flusso di produzione

Per valutare il contributo proposto valutare le diverse fasi del flusso in termini di (i) riduzione dei tempi di gestione documentale, (ii) riduzione degli errori, (iii) miglioramento della qualità dei documenti, (iv) miglioramento del livello di accettazione della tecnologia, (v) raggiungimento di nuovi canali di distribuzione, (vi) soddisfacimento di nuovi scenari d'uso.
 
### Confronto con lo stato dell'arte

Può anche essere utile confrontare una versione ASIS del flusso di gestione, senza la tecnologia o le innovazioni proposte, e una TOBE che include la tecnologia e le innovazioni proposte dallo studente.

### Limiti emersi

È importante sottolineare i limiti emersi. Come l'impossibilità di accesso ad alcune tecnologie o fasi del flusso di gestione documentale, limiti nella automazione di alcune passi di trasformazione dei formati o di integrazione delle sorgenti

## Conclusioni

Discutere i risultati ottenuti, verificando se gli obiettivi definiti dai casi d'uso siano pienamente o parzialmente raggiunti. Evidenziare gli aspetti nei quali si sono raggiunti i risultati più soddisfacenti e le limitazioni emerse.

## Bibliografia e sitografia

Elencare i riferimenti bibliografici e risorse online che hanno maggiormente contribuito alla realizzazione del progetto. Ad esempio [@sechi2010,@pantieri2021,@ceravolo2023]
