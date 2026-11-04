# Kveldsloggen

En liten app for å logge kvelden: 10 000 skritt, ingen mat etter kl. 18 og trening – med en emoji som belønning.

Appen er en PWA (progressiv web-app). Den legges ut på nettet gratis, og alle som har lenken kan installere den på hjemskjermen. Den virker også uten nett.

## Legg den ut på GitHub Pages (ca. 10 minutter)

1. Lag en gratis konto på github.com hvis du ikke har en.
2. Trykk **New repository**. Kall det for eksempel `kveldsloggen`, velg **Public**, og trykk **Create repository**.
3. Trykk **uploading an existing file**, og dra inn alle filene og mappen `icons` fra denne pakken (ikke selve zip-filen). Trykk **Commit changes**.
4. Gå til **Settings → Pages**. Under *Branch* velger du `main` og `/ (root)`, og trykker **Save**.
5. Etter et minutt eller to står adressen øverst på siden, for eksempel `https://brukernavn.github.io/kveldsloggen/`.

Del den adressen med de som skal bruke appen.

## Installer på mobilen

- **iPhone (Safari):** Åpne adressen → Del-knappen → **Legg til på Hjem-skjerm**.
- **Android (Chrome):** Åpne adressen → menyen ⋮ → **Installer app** (eller **Legg til på startsiden**).

## Godt å vite

- **Hver person har sin egen logg.** Dataene lagres bare på telefonen til den som bruker appen. Ingen andre ser dem, og ingenting sendes til noen server.
- **Ingen synk mellom enheter.** Bytter du telefon, bruk **Lagre sikkerhetskopi** nederst i appen, og **Hent sikkerhetskopi** på den nye.
- **Sletter du nettleserdata** for siden, forsvinner loggen. Ta en sikkerhetskopi av og til.
- **Oppdatere appen:** Last opp de endrede filene på nytt på GitHub, og øk versjonsnummeret øverst i `sw.js` (for eksempel `v1` → `v2`). Brukerne får den nye versjonen neste gang de åpner appen med nett.

## Filer

| Fil | Hva den gjør |
|---|---|
| `index.html` | Selve appen |
| `manifest.webmanifest` | Navn, ikon og farger når appen installeres |
| `sw.js` | Gjør at appen virker uten nett |
| `icons/` | App-ikoner i ulike størrelser |
