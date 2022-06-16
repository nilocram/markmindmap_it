---
maxWidth: 600
---

# myMarkmap
## Uno strumento libero<br> e gratuito

### <span class="ml-2">[Sorgenti](https://github.com/eyssette/myMarkmap/) su Github</span>
### _Autore: [Cédric Eyssette](https://eyssette.github.io/)
### Creato a partire dal<br> software [markmap](https://markmap.js.org/)

## Per creare delle<br> mappe mentali



- Clicca su 🖊️ (in alto a sinistra)<br>per **modificare** la tua mappa  mentale. <br>si utilizza la sintassi **Markdown**<br>per creare dei rami
  - `# Titolo` <br>per il livello 1
  - `## Sottotitolo`<br> per il livello 2
  - `### Livello 3`,<br> `#### Livello 4`<br>… eccetera
  - Oppure, si crea un elenco puntato<br>`- Livello 3`<br>　`  - Livello 4`<br>`- Livello 3`<br>(si aggiungono 2 spazi davanti <br>per  passare ad un altro livello)
- Clicca su 👓 per **nascondere** la<br> finestra di modifica e **vedere** <br>solo la mappa mentale
- Clicca su 💾 per **salvare** <br>la mappa in formato **svg**
- Clicca su 🔗 per copiare un **link**<br> di **condivisione** della mappa mentale nella clipboard
- Clicca sui **cerchi** all’intersezione \\ dei diversi rami per \\ **visualizzarli o nasconderli**

## Usi più \\ avanzati<!--fold-->

### Tag per \\ **controllare la visualizzazione** \\ della mappa

#### **Markdown** 

- Si possono utilizzare altri \\ **tag markdown**
  - `**testo**` : per mettere in **grassetto**
  - `_testo_` : per mettere in _corsivo_
- `[link](URL)` : per inserire un [link](https://eyssette.github.io/)
`![](URL)` : per inserire un’immagine
        - `![h-25](URL)`: per specificare l’altezza  \\dell'immagine (da h-25, h-50 … a h-200)
- ``` `code` ``` : Per inserire del `codice` 

#### **HTML**

- `<br>` per forzare l’a capo \\ oppure la scorciatoia: `\\` 
- `<span style="...">testo</span>` \\ per cambiare lo stile di un elemento
  
#### **Altri \\ tag**

- `<!--fold-->` alla fine della riga perché \\ i rami figli siano nascosti di default: \\bisogna cliccare sul cerchio per visualizzare il resto<!-- fold-->
    - Questo ramo è nascosto di default!
    - Anche questo ramo!
- `:code_emoji:` : per inserire un codice per un emoji [:link:](https://raw.githubusercontent.com/omnidan/node-emoji/master/lib/emoji.json)
- `{{partie masquée}}` per nascondere una parte \\ di un testo:  ecco per esempio un {{passaggio}} nascosto\\ (cliccaci sopra per visualizzarlo/nasconderlo di nuovo)

#### **Intestazione** \\ (YAML)

- Per specificare la larghezza \\ massima di un ramo
        - `---` \\ `maxWidth: 300` \\ `---`

### Possibilità di utilizzare un \\ **file esterno**

- È  possibile mettere il proprio testo \\ **su una forgia** e visualizzarlo \\ con myMarkmap
        - \\ `https://mymarkmap.vercel.app/#URL`
        - In caso di problemi: \\ `https://mymarkmap.vercel.app/#https://api.allorigins.win/raw?url=URL`
