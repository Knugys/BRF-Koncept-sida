# Brf Solgårdarna Stigberget – konceptsida

Förslag på ny hemsida för Brf Solgårdarna Stigberget. Allt ligger i `index.html` (ingen byggprocess) – öppna filen i en webbläsare eller publicera med t.ex. GitHub Pages.

## Sidor
Hem · Om föreningen · Medlemsinfo (trivselregler, andrahandsuthyrning, gästlägenhet) · Boka tvättid · Dokument (Google Drive) · Nyinflyttad · Frågor & svar · Kontakt

## Att göra innan sidan visas skarpt
1. **Bilder** – lägg bilderna från nuvarande sida i `bilder/` (se `bilder/README.md`).
2. **Google Drive** – dela föreningens mapp som "Alla med länken kan visa" och fyll i `driveFolderId` i `CONFIG` längst ner i `index.html`. Mappen visas då inbäddad på sidan *Dokument*.
3. **Tvättbokning** – fyll i `laundryUrl`, `laundryIos` och `laundryAndroid` i `CONFIG`. Sätt `laundryEmbed: true` om bokningssystemet tillåter att visas inbäddat.
4. **Text** – rutor med streckad kant markerar text som ska kopieras från nuvarande sida (trivselregler, aktuellt, kontaktuppgifter till SBC/Boakt).
5. **Nyinflyttad & FAQ** – innehåller exempeltext (lorem ipsum). FAQ-frågorna redigeras i listan `FAQ` i `index.html`.
