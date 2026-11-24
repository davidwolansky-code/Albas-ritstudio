# Albas ritstudio

En ritapp för mobilen där teckningen låter medan man ritar.

**Prova:** öppna sidan på telefonen och rita med fingret.

## Så fungerar det

- **Färgen väljer instrument.** Åtta färger, åtta instrument: Piano, Xylofon, Klockspel, Flöjt, Harpa, Orgel, Bubbla och Bas.
- **Höjden väljer ton.** Ritar du högt upp blir tonen hög, ritar du lågt ner blir den låg. Tonerna ligger i en skala som låter bra ihop.

## Penslar

- **Linje**, **Stjärnor**, **Hjärtan**, **Prickar**, **Blommor** och **Gnistor**.
- **Regnbågspenna:** färgerna växlar längs strecket och den spelar alla åtta instrument i tur och ordning.
- **Sudd:** suddar ut det man ritat och är tyst.
- **Stämplar:** katt, hund, fjäril, fisk, regnbåge, blomma, enhörning och stjärna. Man kan dra innan man släpper för att flytta.
- Tre storlekar.

## Mer (knappen "⋯ Mer")

- **Spegla ritningen:** Av, Spegel (vänster och höger) eller Kalejdoskop (sex delar runt mitten).
- **Snurra kalejdoskopet:** tryck på ↻-knappen uppe till höger på ritytan, eller välj Snurra här. Kalejdoskopet roterar runt mitten, och du kan välja fart (Långsamt, Mellan, Snabbt) och riktning (medsols eller motsols). Det går att rita medan det snurrar: nya streck stannar där fingret ritade och snurrar sedan med.
- **Bakgrund:** Papper, Natt, Himmel, Gräs eller Sol.
- **Skala:** Mjuk (femtonig, går aldrig fel), Glad (dur) eller Mystisk (moll).
- **Ljud på och av.**
- **Spara bild** som PNG, och **Dela** via telefonens delningsmeny.

## Annat

- **Ångra** och **Gör om**. **Rensa** kräver två tryck.
- **Spela upp** ritar om teckningen steg för steg, med samma ljud, spegling och bakgrund. Under uppspelningen står kalejdoskopet stilla.
- Kalejdoskopstreck ligger alltid överst när teckningen snurrar. Sudd tar bort även dem.
- Teckningen **sparas automatiskt** i webbläsaren och finns kvar nästa gång.
- Fungerar i stående och liggande läge.

## Teknik

En enda HTML-fil. Ljudet skapas direkt i webbläsaren med Web Audio, inga ljudfiler används. Teckningen sparas bara på den egna enheten och skickas aldrig någonstans.

## Tips

På iPhone är ljudet av om ringsignalsknappen står på tyst läge.

## Publicera

Lägg `index.html` i ett eget repo, till exempel `albas-ritstudio`, och slå på GitHub Pages (Settings → Pages → Deploy from a branch → main / root).
