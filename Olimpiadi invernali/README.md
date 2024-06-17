# Storia dei Giochi Olimpici Invernali

Questo è un libro illustrato scritto in R Markdown e **bookdown** (https://github.com/rstudio/bookdown). 

![Copertina del libro](images/cover.jpg)

## Descrizione

"Storia dei Giochi Olimpici Invernali" è un libro illustrato che racconta la storia dei Giochi Olimpici Invernali dal 1924 al 2026. Scritto da Adriana Angaran per il progetto del corso di Editoria Digitale nell'anno 2024.
Il libro offre una panoramica delle varie edizioni dei Giochi olimpici invernali, con foto e curiosità.
Pensato per una consultazione breve, per chi vuole avere qualche informazione in più riguardo all'evento.

## Caratteristiche

- **Contenuti:** Introduzione sulla nascita delle Olimpiadi invernali, un capitolo per ogni edizione con logo dell'edizione, immagini, dati, curiosità, eventuali mascotte. Indicazione delle fonti e sitografia.
- **Illustrazioni:** Foto di atleti e luoghi, immagini di loghi e mascotte.
- **Sitografia:** Indicazione dei siti da cui sono stati tratti i contenuti e le foto.
- **Formattazione:** Sviluppato utilizzando `bookdown`, con formattazione HTML moderna e facile da navigare.

## Dipendenze:

- **R version**: >= 4.4.0
- **Pacchetti R**:
  - `rmarkdown` >= 2.27
  - `bookdown` >= 0.39
- `pandoc` >= 3.2
- **Motore LaTeX**: MiKTeX-pdfTeX 4.18 (MiKTeX 24.1)

## Visualizzare il Libro

Il libro è visualizzabile in tre modi:

1. installando RStudio Desktop sul computer e aprendo il progetto `Olimpiadi invernali.Rproj`
2. aprendo la cartella "_book" che contiene tutti i file per la visualizzazione in html, aprire il file "index.html"
3. nella cartella "_book" è disponibile il file "Storia-dei-giochi-olimpici-invernali.epub" in formato epub che si può aprire con un visualizzatore di file epub online (es. [fviewer](https://www.fviewer.com/it/view-epub)) oppure con un software di gestione ebook (es. [Calibre](https://calibre-ebook.com/))

## Repository

Questo progetto è ospitato su GitHub. Il link della repository è [qui](https://github.com/AdrianaAngaran/Storia-Giochi-Olimpici-Invernali.git).

## Come Clonare e Costruire il Libro

Se desideri clonare la repository e costruire il libro localmente, segui questi passaggi:

1. Clona la repository:
    ```bash
    git clone https://github.com/AdrianaAngaran/Storia-Giochi-Olimpici-Invernali.git
    cd storia-giochi-olimpici-invernali
    ```

2. Se non l'hai già fatto installare R ([download](https://www.r-project.org/)) e RStudio ([download](https://posit.co/download/rstudio-desktop/)) 

3. Apri il file `Olimpiadi invernali.Rproj` in RStudio per caricare il progetto.

4. Assicurati di avere `bookdown` installato. Puoi installarlo in R con:
    ```R
    install.packages("bookdown")
    ```

5. Costruisci il libro:
    ```R
    bookdown::render_book()
    ```
6. Anteprima del libro su RStudio Desktop:
    ```R
    bookdown::serve_book()
    ```


## Licenza

Questo progetto è distribuito sotto la licenza MIT. Per ulteriori dettagli, consulta il file [LICENSE](LICENSE).


Altre risorse:

Il sito di riferimento del pacchetto **bookdown**: https://pkgs.rstudio.com/bookdown
