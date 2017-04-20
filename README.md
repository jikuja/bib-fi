# Suomenkielinen lähdeluettolo bibtexillä
Käytetty malli on lähes identtinen Turun yliopiston Tulevaisuuden teknologioiden laitoksen mallipohjien mukana olevan `unstf.bst`-tiedoston kanssa.

Muutokset:
1) Custom-bib -ohjelman käyttämä Docstrip Batch Job(dbj) -tiedosto on määritelty luomaan identtinen .bst-tiedosto suoraavin muutoksin:
   1) Viiteluettelossa listataan kaikki tekijät. Eli `nmlm`-asetus ja siihen  liittyvät luvut on poistettu
   2) URL-tietue näytetään bibliografiassa omana blokkina: `url-nt` => `url-blk`
   3) Useita pieniä muutoksia uudemman custom-bib -version mukana: tuki doi- ja eprint-kentille, latex-komennot. Kts custom-bib-paketin changelogi.
2) Tyyliin on manuaalisesti lisätty `urldate`-kentän käsittely


# TODO
* Dokumentoi miten uusi bst-tiedosto luodaan
* Listaa mielenkiintoisimmat asetukset
* Dokumentoi miten @preamblea voidaan käyttää muuttamaan bibliografiaa
* Samat muutokset custom-bib -pakettiin.
