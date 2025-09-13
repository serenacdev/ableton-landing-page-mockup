# 🎹 Ableton Landing Page - Mockup

Questo progetto è una riproduzione **non ufficiale** della landing page di **Ableton**, realizzata esclusivamente a scopo didattico.



## 📑 Indice
- [🎯 Obiettivo](#-obiettivo)  
- [🎵 Perché proprio Ableton?](#-perché-proprio-ableton)  
- [📚 Risorse e Strumenti](#risorse-e-strumenti)  
- [🛠️ Tecnologie utilizzate](#-tecnologie-utilizzate)  
- [📂 Struttura e sviluppo del progetto](#-struttura-e-sviluppo-del-progetto)  
- [🛠️ Workflow con Git](#-workflow-con-git)  
- [⚠️ Criticità e sviluppi futuri](#-criticità-e-sviluppi-futuri)  
- [💻 Come aprire il progetto in locale](#-come-aprire-il-progetto-in-locale)  


## 🎯 Obiettivo
L'obiettivo di questo progetto è replicare una landing page reale per **esercitarmi nello sviluppo frontend**, migliorando le mie competenze in **HTML e CSS**. 

## 🎵 Perché proprio Ableton?
Ho studiato musica al conservatorio e conosco il mondo della produzione musicale e i suoi strumenti. Ho scelto la landing page di Ableton perché rappresenta un punto di riferimento per i musicisti e i producer, e volevo unire la mia passione per la musica con l’esercizio sul **frontend**.

## Risorse e Strumenti
Ho seguito le indicazioni fornite da **[Frontend Pratice](https://www.frontendpractice.com/projects/ableton)**, una piattaforma specializzata, progettata appositamente per aiutare sviluppatori frontend di tutti i livelli a migliorare le proprie competenze tramite la riproduzione di pagine web reali.


- Le 📷 immagini sono state reperite da **[Pexels](https://www.pexels.com/it-it/)** e salvate nella cartella `images`.  
- Le icone sono state implementate con **FontAwesome**.
- Il font **Jost** è stato reperito da **[Google Fonts](https://fonts.google.com/specimen/Jost)** ed importato nel progetto tramite `<link>` nell'`<head>` dell’HTML. 
- La 🎨 **palette di colori** fornita è la seguente:

            - Giallo: `#fbffa7`
            - Arancione: `#ff764d`
            - Azzurro: `#b1c5ff`
            - Viola: `#d5b3ff`
            - Verde: `#b6ffc0`
            - Blu: `#0000ff` 

## 🛠️ Tecnologie utilizzate
- **HTML5** per la struttura
- **CSS3** per lo stile
## 📂 Struttura e sviluppo del progetto

La struttura del progetto non era fornita da Frontend Practice, per cui, dopo i setup iniziali, ho suddiviso il lavoro in **sezioni**, alcune delle quali simili tra loro per struttura e facilmente replicabili. Sono state così affrontate dapprima nell’ordine di apparizione sulla pagina e successivamente a blocchi per le sezioni con caratteristiche simili. Di seguito le principali sezioni individuate: 


- **Navbar**  
  
- **Sezione foto con titolo**  
Sezione introduttiva che combina immagini e testo, realizzata utilizzando `position: relative` e `position: absolute`.

- **Sezioni con testo grande e piccolo**  
Realizzate anch’esse con `position: relative` e `position: absolute` per controllare la disposizione degli elementi.

- **Sezioni con foto su sfondo colorato**  
Realizzate in particolare utilizzando `position: relative` e `position: absolute` per il posizionamento preciso degli elementi.

- **Un’area per la preview video**  
  Collegata al video YouTube corrispondente presente nella landing page di Ableton. 

- **Una sezione suddivisa a metà**  
Con foto da un lato e testo dall'altro. 


- **Footer**  
   Strutturato con **Flexbox** principalmente su 3 colonne e due righe.

---

### 🛠️ Workflow con Git

- Ho lavorato da **terminal**, creando **branch separati** per ogni sezione.  
- Una volta soddisfatta del risultato, eseguivo il **merge sul branch master**, mantenendo il progetto ordinato e tracciabile.

---

### ⚠️ Criticità e sviluppi futuri

- Il posizionamento delle immagini con testo sovrapposto e delle immagini sopra i quadrati colorati è stato gestito con `position: relative` e `absolute`.
- **Responsive design** non ancora implementato, sarà oggetto di studio futuro.
- L’anteprima video presente sul sito di Ableton non è stata replicata: attualmente viene utilizzata quella standard di YouTube. La creazione di un’anteprima fedele alla landing page originale sarà oggetto di una rivisitazione futura.


## 💻 Come aprire il progetto in locale

Segui questi semplici passaggi per avviare il progetto direttamente sul tuo computer:

1. Clona il repository

git clone https://github.com/serenacdev/ableton-landing-page-mockup

cd ableton-landing-page-mockup

2. Apri il file index.html

Puoi semplicemente doppio clic sul file index.html per aprirlo nel tuo browser predefinito, oppure dal terminale con i seguenti comandi:
- start index.html   (per Windows)
- open index.html    (per macOS)
- xdg-open index.html (per Linux)
