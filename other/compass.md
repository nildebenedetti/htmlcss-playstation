
# Analisi Struttura

header
    hellobar
    menu (burger fino a md compreso)
main
    section.games-carousel
        hero gamecard <!--(background image con overlay text, a tutta ampiezza nei breakpoint più estesi)-->
        grid altre card <!--  col-xs-6 col-sm-4 col-md-4 col-lg-2 -->
            card*6
    section.playstation-5
        section.ps5-hardware-accessories
            ps5-hardware-accessories-title
                titolo
                paragrafo
            grid hardware-accessories --> <!--col-xs-12 *1 elemento
                                             col-sm-12 *1 elemento
                                            col-md-12*1 elemento ma appare anche img-->
            .products-overview 
                card img-text*5 <!-- giocare con effetti bottom border in active e hover
                                    xs: solo immagini, il testo sparisce, con img-1 in col-12 e le altre in col-4
                                    sm: ugiuale a xs
                                    md: testo e button a sx + image a dx in col-12, a capo 5*card con img top + txt bottom (quindi il testo appare solo da md)
                                    lg: uguale a md-->
    section.sponsored-game
        hero gamecard <!-- UGUALE a quella di games-carousel-->
    section.new-releases <!-- questa ha un background black-->
        section-title
            title
            paragraph
        new-games-grid
            card*12 image+txt <!-- xs: col-xs-6
                                    sm: col-sm-4
                                    md: col-md-4
                                    lg: col-lg-2-->
    section.playstation4
        section-title
            title
            paragraph
        card-hardware <!-- col-xs-12 | col-sm-12 | col-md-12 | col-lg-4 -->
        card-vr
        card-accessories
    section.banner playstation-plus
        card con logo <!-- da md spunta immagine di dx - RICICLARE BUTTON CAMBIANDO COLORINI-->
    section.hub-discounts
         section-title
            title
            paragraph
        nav.sales-hub
            img*3 <!-- xs-col-12 ... col-md-4 -->
     section.banner playstation-now
        card con logo <!-- da md spunta immagine di dx - RICICLARE PS PLUS CAMBIANDO COLORINI-->
    section.social-media
        p.cta
        nav.hub-social-media
            img*4 <!--col-xs-6 |  col-sm-3-->
    footer
        divvone <!-- col-xs-12 | col-lg-6 -->
            logo <!-- col-12 -->
            country/region <!-- col-12 -->
        nav <!--col-sm-12 | sospetto sia come la ricetta di giallo booleano-->
            blocco link1 <!-- col-xs-12 | col-md-4 |col-lg-6 -->
            blocco link2
            blocco link3
        divvone <!-- col-xs-12 |-->
            Sony Interactive Entertainment logo
            copyright

# Variables
Quegli elementi che vogliamo scrivere una volta e poi addio

_riscriviamo le variabili di warning/primary con la palette del sito corrispondente ad arancio e blu dei bottoni_


# Utility Classes
Elementi che si ripetono da stilizzare una tantum e poi riutilizzare:
1. btn - Crea un button a cui applichiamo diversi schemi colore

# Elementi che si ripetono?
1. La hero dei giochi in evidenza
2. I banner di PS Plys e Now

# Modus Operandi

1. Per ciascuna sezione, rileggi analisi
2. scrivi struttura direttamente con breakpoints
3. confronta con screenshot
4. adjustments stile
5. aggiungi effettini hover/active se fondamnetali

_Quando finito tutto ti puoi dedicare agli orpelli._
