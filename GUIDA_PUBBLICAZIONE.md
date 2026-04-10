# TMS Valves — Guida alla Pubblicazione

## Contenuto del pacchetto

```
tms-valves-app/
├── index.html          ← L'app completa
├── manifest.json       ← Manifest PWA (nome, icone, configurazione)
├── icon-192.png        ← Icona 192x192 per Android
├── icon-512.png        ← Icona 512x512 per Android/splash screen
├── apple-touch-icon.png ← Icona 180x180 per iPhone/iPad
└── favicon-96.png      ← Favicon per il browser
```

## Pubblicazione su GitHub Pages (GRATIS)

### Se hai già un repository GitHub:

1. Sostituisci il vecchio file HTML con **tutti i file** della cartella `tms-valves-app`
2. Il file principale DEVE chiamarsi `index.html`
3. Tutti i file devono stare nella **stessa cartella** (root del repo o cartella /docs)
4. Vai su Settings → Pages → conferma che la Source è corretta
5. Attendi 1-2 minuti e visita il tuo URL GitHub Pages

### Se crei un repository nuovo:

1. Vai su github.com → New Repository
2. Nome: `tms-valves` (o quello che preferisci)
3. Pubblico ✓
4. Carica tutti i file dalla cartella `tms-valves-app`
5. Vai su Settings → Pages → Source: "main" branch → Save
6. L'URL sarà: `https://tuousername.github.io/tms-valves/`

## Installazione su Android (GRATIS)

Una volta pubblicata su GitHub Pages:

1. Apri Chrome su Android
2. Vai all'URL della tua app
3. Chrome mostrerà automaticamente un banner **"Aggiungi TMS Valves alla schermata Home"**
4. Tocca "Installa"
5. L'app apparirà come un'icona nella schermata Home
6. Si apre a schermo intero, senza barra del browser — come un'app nativa

Se il banner non appare automaticamente:
- Tocca i 3 puntini in alto a destra in Chrome
- Seleziona "Installa app" o "Aggiungi alla schermata Home"

## Installazione su iPhone/iPad (GRATIS)

1. Apri **Safari** (non Chrome!) su iPhone/iPad
2. Vai all'URL della tua app
3. Tocca l'icona di condivisione (quadrato con freccia in su)
4. Scorri e tocca **"Aggiungi alla schermata Home"**
5. Conferma il nome "TMS Valves"
6. L'app apparirà come un'icona nella Home
7. Si apre a schermo intero come un'app nativa

**Nota iPhone**: Apple non supporta le notifiche push per le PWA su iOS.
L'app funziona perfettamente per tutto il resto.

## Pubblicazione su Google Play Store (GRATIS)

Se vuoi pubblicarla anche sul Play Store:

1. Vai su https://www.pwabuilder.com/
2. Inserisci l'URL della tua app GitHub Pages
3. PWABuilder analizza l'app e genera il pacchetto Android (TWA)
4. Scarica il pacchetto Android
5. Crea un account Google Play Console (25$ una tantum — unico costo)
6. Carica il pacchetto APK/AAB
7. Compila le informazioni dello store e pubblica

**Alternativa completamente gratuita**: usa solo GitHub Pages + installazione PWA da Chrome.

## Pubblicazione su Apple App Store

Apple richiede un account Developer Program a 99€/anno.
L'alternativa gratuita è l'installazione da Safari (vedi sopra).

## Verifica che tutto funzioni

Dopo la pubblicazione, verifica:

- [ ] L'app si apre correttamente dall'URL
- [ ] L'icona TMS appare nel tab del browser
- [ ] Su Android: appare il banner "Installa"
- [ ] Dopo l'installazione: l'app si apre a schermo intero
- [ ] Le notifiche sonore funzionano
- [ ] La sincronizzazione cloud funziona
- [ ] Le foto si caricano e comprimono
- [ ] Il PIN funziona per eliminazione e completamento
