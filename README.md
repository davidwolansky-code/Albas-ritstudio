# Albas ritstudio

En ritapp för mobilen där teckningen låter medan man ritar.

**Prova:** öppna sidan på telefonen och rita med fingret.

## Så fungerar det

- **Färgen väljer instrument.** Åtta färger, åtta instrument: Piano, Xylofon, Klockspel, Flöjt, Harpa, Orgel, Bubbla och Bas.
- **Höjden väljer ton.** Ritar du högt upp blir tonen hög, ritar du lågt ner blir den låg. Tonerna ligger i en skala som alltid låter bra ihop, så det går inte att spela fel.
- **Former:** rita med linje, stjärnor, hjärtan, prickar eller blommor.
- **Stämplar:** tryck för att sätta en katt, hund, fjäril, fisk, regnbåge, blomma, enhörning eller stjärna. Man kan dra innan man släpper för att flytta den.
- **Ångra** tar bort det senaste. **Rensa** kräver två tryck, så att inget försvinner av misstag.
- **Spela upp** ritar om hela teckningen steg för steg, med samma ljud.
- Ljudet kan stängas av med knappen **Ljud**.

## Gjord för

Mobil, i stående läge. Den fungerar också på surfplatta och dator.

## Teknik

En enda HTML-fil. Ljudet skapas direkt i webbläsaren med Web Audio, inga ljudfiler används. Ingen data sparas eller skickas någonstans.

## Tips

På iPhone är ljudet av om ringsignalsknappen står på tyst läge.

## Publicera

Lägg `index.html` i ett eget repo, till exempel `albas-ritstudio`, och slå på GitHub Pages (Settings → Pages → Deploy from a branch → main / root).
