# Brf Solgårdarna Stigberget – förslag till ny webbplats

Hela webbplatsen ligger i `index.html` och behöver ingen byggprocess. Öppna filen i en webbläsare eller publicera mappen, till exempel med GitHub Pages. Bilder ligger i `bilder/` och typsnitt i `typsnitt/`: Newsreader och Figtree, båda under licensen SIL OFL. Typsnitten ligger lokalt, så sidan hämtar ingenting från Google Fonts.

## Sidor
Start · Felanmälan och kontakt · Boende (Regler och boende, Gästlägenheter, Andrahandsuthyrning, Ny i föreningen, Frågor och svar) · Tvättstuga · Dokument · Om föreningen

## Innehåll som fylls i via CONFIG
Längst ner i `index.html` finns `CONFIG`. Fält som är tomma döljs på sidan. Det finns inga synliga rutor om att något saknas.

| Fält | Vad som visas när det är ifyllt |
|---|---|
| `news` | Avsnittet "Aktuellt" på startsidan, med datum och rubrik |
| `boakt.phone`, `boakt.email`, `boakt.url` | Kontaktvägar för felanmälan |
| `urgentPhone` | Telefonnummer för akuta fel |
| `sbcUrl` | Länk till SBC:s portal |
| `rulesUrl` | Länk till trivselreglerna. Pekar just nu på nuvarande webbplats |
| `driveFolderId`, `documents` | Google Drive-mappen visas på sidan, plus en lista med utvalda dokument och deras filformat |
| `laundryAppName`, `laundryUrl`, `laundryIos`, `laundryAndroid` | Knappar för att boka tvättid |

Sidorna Ny i föreningen och Frågor och svar innehåller exempeltext (lorem ipsum) som ska ersättas.
