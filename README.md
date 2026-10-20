# Málagai Magyar Közösség — háromnyelvű statikus weboldal

## Státusz
Jogi bejegyzés és szervezeti név nem igazolt. A projekt munkanéven készült. A honlap szándékosan `noindex` és `robots.txt Disallow`, amíg nem ismert a végleges név, domain, jogi szereplő, tárhelyszolgáltató, adatvédelmi tájékoztató. A weboldal előnézetként futtatható.

## Indítás
A könyvtárból: `python3 -m http.server 8080`, böngészőben http://localhost:8080/hu/

## Élesítés előtti kapuk
1. Névellenőrzés, jóváhagyott hivatalos név és jogi státusz.
2. A tárhely/domain kiválasztása, tulajdon és adatkezelő azonosítása.
3. Érvényes, valós GDPR-tájékoztató; tárhelyszolgáltató szerződés és naplózás.
4. Hiteles kapcsolat, képviselet, NIF, nyilvántartási státusz pontos közzététele (vagy szándékosan jelölt hiánya).
5. SEO élesítés: noindex feloldás, robots engedély, abszolút canonical/hreflang, sitemap, tényszerű Organization JSON-LD.
6. A tartalom spanyol anyanyelvi és helyi jogi ellenőrzése.
7. Valós programadatok felvétele; addig esemény séma nem használható.

## Architektúra
7 útvonal x 3 nyelv + nyelvi kapcsolók. Tisztán statikus HTML és CSS. Nincs analytics, cookie, űrlap vagy külső asset. A hiányzó adatok nem helyettesítettek kitalált adatokkal.
