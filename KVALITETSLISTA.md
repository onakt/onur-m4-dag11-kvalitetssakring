# Kvalitetslista (dag 11)

Gå igenom listan uppifrån och ned. Kryssa av när du kontrollerat.

## HTML
- [X] Validerar i validator.w3.org utan fel
- [X] `lang="sv"` på `<html>`
- [X] Exakt en `<h1>` per sida
- [X] Rubrikhierarkin hoppar inte (h1, h2, h3)
- [X] Semantiska element används (header, nav, main, section, article, footer)
- [X] Inga dubblerade `id`
- [X] Alla länkar går någonstans (testa dem)

## Tillgänglighet
- [ ] Alla bilder har alt-text som beskriver bilden
- [ ] Alla formulärfält har en kopplad `label`
- [ ] Alla knappar är `<button>` (inte `<div>`)
- [ ] All text klarar kontrast 4,5:1
- [ ] Du kan använda hela sidan med bara tangentbordet
- [ ] Fokus syns alltid

## CSS
- [ ] `box-sizing: border-box` är satt
- [ ] Färger och avstånd kommer från variabler
- [ ] Inga oanvända eller felstavade klasser
- [ ] Filerna är uppdelade och logiskt namngivna

## Responsivitet
- [ ] Ingen horisontell scroll på 360 px
- [ ] Fungerar på 360, 768 och 1280 px
- [ ] Bilder och formulärfält anpassar sig

## Git och publicering
- [ ] Commit per ändring, med begripliga meddelanden
- [ ] Allt är pushat
- [ ] Live-sidan visar senaste versionen
