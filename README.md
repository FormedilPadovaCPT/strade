# Stradario di Padova – PWA

Web app progressiva (PWA) per la ricerca del quartiere di una strada di Padova.

**🔗 Demo:** `https://<tuo-utente>.github.io/<nome-repo>/`

## Caratteristiche

- 📍 **2.122 strade** – Registro Toponomastico ufficiale (Ufficio Toponomastica, 28 marzo 2024)
- ⚡ **Ricerca istantanea** con autocomplete mentre si digita
- 🎨 **Colori per quartiere** – 6 quartieri di Padova distinti visivamente
- 📱 **PWA installabile** – funziona come app nativa su Android, iOS e desktop
- 📵 **Offline-first** – tutti i dati incorporati, nessuna dipendenza da server
- 🌙 **Dark mode** – si adatta al tema di sistema

## Struttura file

```
/
├── index.html          ← App principale (dati incorporati)
├── manifest.json       ← Manifest PWA
├── sw.js               ← Service Worker (cache offline)
├── favicon.ico
└── icons/
    ├── icon-72x72.png
    ├── icon-96x96.png
    ├── icon-128x128.png
    ├── icon-144x144.png
    ├── icon-152x152.png
    ├── icon-192x192.png
    ├── icon-384x384.png
    ├── icon-512x512.png
    └── apple-touch-icon.png
```

## Pubblicazione su GitHub Pages

1. Crea un repository su GitHub (es. `stradario-padova`)
2. Carica tutti i file **mantenendo la struttura delle cartelle**
3. Vai in **Settings → Pages → Source → Deploy from branch**
4. Seleziona `main` / `root` e salva
5. Dopo qualche minuto l'app sarà disponibile all'URL indicato

> ⚠️ Il Service Worker richiede HTTPS – GitHub Pages lo fornisce automaticamente.

## Fonte dati

Registro delle Strade di Padova  
Settore Cultura e Turismo – Ufficio Toponomastica  
Edizione aggiornata al **28 marzo 2024**
