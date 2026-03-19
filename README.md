Tahle hra vzniká jako jednoduchý 2D akční projekt ve stylu bullet hell, kde je hlavní důraz na boss fighty (bossrush).

Cílem je vytvořit hru, ve které se hráč postupně dostává přes kratší úrovně s běžnými nepřáteli až k bossům, kteří představují hlavní výzvu. Každý boss má vlastní útoky, chování a ideálně i více fází.

Projekt je zaměřený hlavně na zvládnutí práce v Godotu, návrh herních mechanik a implementaci základních herních systémů.

 ## Použité technologie

  * Engine: Godot
  * Jazyk: C# (Mono verze Godotu)

 ## Herní mechaniky

  * Plynulý pohyb hráče do všech směrů
  * Střelba projektilů
  * Bullet hell prvky (větší množství nepřátelských střel)
  * Kolize (zásahy hráče i nepřátel)
  * Systém životů (HP)
  * Nepřátelé ve vlnách
  * Boss fighty s různými útoky a fázemi

## Struktura hry

  * Hra je rozdělená do několika kratších úrovní:

   ### Úroveň 1

    * Základní nepřátelé
    * Jednodušší vzory střel
    * První boss
    * Spíše jednoduché útoky (na rozjezd)

   ### Úroveň 2

    * Více nepřátel
    * Rychlejší a hustší střely
    * Druhý boss
    * Složitější kombinace útoků

   ### Úroveň 3

    * Náročnější vlny nepřátel
    * Výraznější bullet hell prvky
    * Finální boss
    * Vícefázový fight
    * Kombinace všech předchozích mechanik

  ### Nepřátelé a AI

  * Nepřátelé mají jednoduché chování:

    * pohyb směrem k hráči / po scéně
    * střelba v intervalech

  * Bossové:

    * mají fáze podle zbývajícího HP
    * mění útoky v průběhu souboje

### Ukládání

  * ukládání postupu hráče
  * odemčené úrovně
  * high score
  * (přes soubory v Godotu)

### Assety

  * Vlastní:

    * některé grafické prvky (pokud stihnu)
    * případně jednoduché placeholdery

  * Externí:

    * (bude doplněno podle použití)
    * grafika: [doplním]
    * zvuky: [doplním]

  * Všechny použité assety budou mít uvedený zdroj a licenci.

## Zdroje

  * Oficiální dokumentace Godot enginu
  * Různé online tutoriály (YouTube, weby – doplním konkrétní odkazy)
  * Generativní AI (např. ChatGPT) pro návrh struktury a konzultace

 ## Stav projektu

  * Projekt je ve vývoji — některé části jsou hotové, jiné zatím ve fázi návrhu.

 ## Možná rozšíření

  * power-upy
  * více typů střel
  * více bossů
  * lepší efekty (particles apod.)
