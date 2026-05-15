# 🕐 Digiuno Intermittente — App PWA

Tracker personale per il digiuno intermittente con:
- ⏱ Timer in tempo reale con fase metabolica attiva
- 🔬 7 fasi metaboliche con descrizioni scientifiche
- 💧 Tracker acqua giornaliero con storico 7 giorni
- 📊 Grafico storico digiuni con ore e bicchieri
- 📖 Guida completa alle fasi (Anabolica, Catabolica, Brucia Grassi, Chetosi, Autofagia, GH, Rigenerazione)
- 📱 Installabile come app PWA su Android e iPhone
- 🌙 Dark mode automatica
- ✈️ Funziona offline

---

## 🚀 Come pubblicare su GitHub Pages (passo per passo)

### 1. Crea un account GitHub
Vai su [github.com](https://github.com) e registrati (è gratuito).

### 2. Crea un nuovo repository
1. Clicca sul **+** in alto a destra → **New repository**
2. Nome: `digiuno-app` (o come preferisci)
3. Seleziona **Public**
4. **Non** spuntare "Add README"
5. Clicca **Create repository**

### 3. Carica i file
Nella pagina del repository appena creato:
1. Clicca **uploading an existing file** (link nel testo centrale)
2. Trascina TUTTI i file di questa cartella:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - cartella `icons/` con `icon-192.png` e `icon-512.png`
3. Scrivi un messaggio di commit (es. "Prima versione")
4. Clicca **Commit changes**

### 4. Attiva GitHub Pages
1. Vai su **Settings** (in alto nel repository)
2. Nel menu a sinistra clicca **Pages**
3. Sotto "Branch" seleziona **main** e cartella **/ (root)**
4. Clicca **Save**
5. Aspetta 1-2 minuti

### 5. Trova il tuo link
Dopo pochi minuti apparirà il link del tipo:
```
https://TUONOME.github.io/digiuno-app/
```
Copialo e aprilo sul telefono!

---

## 📱 Installa sul telefono

### Android (Chrome)
1. Apri il link su **Chrome**
2. Tocca i **⋮ tre puntini** in alto a destra
3. Tocca **"Aggiungi a schermata Home"** o **"Installa app"**
4. Conferma → l'icona appare nella home!

### iPhone (Safari)
1. Apri il link su **Safari** (non Chrome!)
2. Tocca l'icona **Condividi** ↑ in basso
3. Scorri e tocca **"Aggiungi a schermata Home"**
4. Conferma → l'icona appare nella home!

---

## 💾 I dati sono salvati?
Sì. Tutti i dati (digiuni, acqua, impostazioni) vengono salvati localmente sul tuo telefono tramite `localStorage`. Non vengono inviati a nessun server. Se disinstalli l'app o cancelli i dati del browser, i dati vengono persi.

---

## ⚠️ Note mediche
Le fasi del digiuno descritte nell'app sono a scopo informativo. I digiuni oltre le 24-48 ore devono essere effettuati solo sotto supervisione medica. Non adatto a diabetici, donne in gravidanza, persone sottopeso o con disturbi alimentari.
