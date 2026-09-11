# BPC-SPEA – web předmětu

Statický web předmětu **Silnoproudá a přístrojová elektrotechnika** (ÚBMI FEKT VUT), určený pro GitHub Pages.

## Struktura

```
index.html                                  – celý web (HTML + CSS v jednom souboru, bez JS)
Vyhlaska_k_hodnoceni_BPC-SPEA_2026-27.pdf   – vyhláška předmětu
prednasky/                                  – prezentace přednášek (01–05)
cviceni/                                    – materiály ke cvičením
```

Odkazy v `index.html` jsou relativní, složky musí mít názvy `prednasky/` a `cviceni/` (bez diakritiky, malá písmena).

## Nasazení

1. Repozitář → Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
2. Po pushnutí je web během minuty na `https://<uživatel>.github.io/<repozitář>/`.

## Doplnění materiálů

- Nový soubor ke cvičení nahrát do `cviceni/` a v `index.html` v příslušném řádku nahradit
  `<span class="tbd">bude doplněno</span>` odkazem podle vzoru u cvičení 1 nebo 2.
- Aktualizovanou přednášku nahradit v `prednasky/` a u tématu odstranit `<span class="ver">verze 2025</span>`.
- Datum v patičce („Aktualizováno …“) upravit ručně.
