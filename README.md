# Bevásárlólista

Ebben a feladatban egy bevásárlólistát készítünk.

![Alt text](image.png)

Új tételt a szöveges mezőbe kell beírni, majd a rögzítéshez meg kell nyomni az <kbd>Enter</kbd> billentyűt, vagy rá kell kattintani a Hozzáadás gombra.

Egy tételt a listában az X gombbal lehet törölni, a ceruza gombra kattintva pedig szerkeszteni.

Az új és a szerkesztett tételek a lista végére kerülnek.

A lista az oldal frissítékor vgay újra megnyitásakor sem törlődik. Az adatokat a böngészőben (LocalStorage) tároljuk.

## Feladatok a HTML fájlban

1. Klónozd ezt a repository-t a saját számítógépedre és a továbbiakban ebben dolgozz!

1. Töltsd fel a repository-t egy új repository-ba a saját GitHub fiókodba! A továbbiakban is töltsd fel ide a commitokat!

1. Az oldal lapfülön megjelenő címe legyen Bevásárlólista! Ez a cím jelenjen meg első szintű címsorként is az oldal tetején!

1. A szöveges beviteli mező és a gomb egy formon helyezkedjen el! A szöveges mező azonosítója legyen "uj-elem", és az oldal betöltődésekor automatikusan kerüljön rá a kurzor! A gomb submit típusú legyen!

1. A form után legyen egy üres szakasz (div) "lista" azonosítóval! Ebbe kerülnek majd a bevitt elemek.

1. KApcsold az oldalhoz a styles.css stílusfájlt és az app.js szkriptet!

1. Commitold a módosításokat!

## Feladatok a CSS fájlban

1. Az oldal körül legyen 1 rem nagyságú belső margó! Háttere cornsilk színű legyen! A betűtípust állítsd Verdana-ra vagy talpatlanra!

1. A form margói felül és alul 1rem, két oldalon pedig 0 méretűek legyenek!

1. A formon lévő szöveges mező betűmérete 1.1rem legyen!

1. A lista margói felül és alul 0.5rem, két oldalon pedig 0 méretűek legyenek! A betűmérete 1.1rem legyen!

1. Készíts egy osztályt a listaelemeknek "lista-elem" néven! Ebben állítsd be, hogy a margók felül és alul 0.5rem, két oldalon pedig 0 méretűek legyenek!

1. A "lista-elem" osztályú elemek belsejében lévő gombok betűmérete 1rem, jobb oldali margója 0.5rem legyen!

