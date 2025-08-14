# Sito Accademico Personale

Un sito web accademico personale elegante e professionale costruito con **Astro**, ispirato al design della London Business School.

## 🚀 Caratteristiche

- **Design moderno e professionale** ispirato alla London Business School
- **Completamente responsive** - funziona perfettamente su desktop, tablet e smartphone
- **Veloce e ottimizzato** - generato staticamente con Astro
- **Font eleganti** - Lora per i titoli e Source Sans 3 per il corpo del testo
- **Palette colori istituzionale** - blu LBS (#001E62) e grigi eleganti

## 📁 Struttura del Progetto

```
/
├── public/
│   └── assets/
│       ├── lbs-logo.svg       # Logo placeholder
│       ├── profile-image.jpg  # Immagine profilo placeholder
│       └── cv.pdf             # CV placeholder
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── Header.astro       # Navigazione principale
│   │   └── Footer.astro       # Footer del sito
│   ├── layouts/
│   │   └── MainLayout.astro   # Layout principale
│   ├── pages/
│   │   ├── index.astro        # Pagina About
│   │   ├── research.astro     # Pagina Research
│   │   ├── teaching.astro     # Pagina Teaching
│   │   └── cv.astro           # Pagina CV
│   └── styles/
│       └── global.css         # Stili globali
└── package.json
```

## 🎨 Design e Stile

### Palette Colori
- **Sfondo:** `#FFFFFF` (Bianco)
- **Testo Principale:** `#212529` (Grigio Scuro)
- **Blu Istituzionale:** `#001E62` (per link, titoli e accenti)
- **Grigio Chiaro:** `#EBE8E5` (per bordi e linee divisorie)
- **Grigio Tenue:** `#6C757D` (per testo secondario)

### Tipografia
- **Titoli:** Lora (serif) - font elegante per h1, h2, h3
- **Corpo:** Source Sans 3 (sans-serif) - font moderno per paragrafi e link

## 🚀 Quick Start

### Installazione

```bash
# Installa le dipendenze
npm install
```

### Sviluppo

```bash
# Avvia il server di sviluppo
npm run dev
```

Il sito sarà disponibile su `http://localhost:4321/`

### Build

```bash
# Genera il sito statico
npm run build
```

### Preview

```bash
# Anteprima del sito generato
npm run preview
```

## 📝 Personalizzazione

### 1. Informazioni Personali
Modifica i seguenti file per personalizzare le informazioni:

- **Header.astro:** Cambia "Nome Cognome" con il tuo nome
- **Footer.astro:** Aggiorna copyright e link social
- **index.astro:** Personalizza la biografia nella pagina About

### 2. Assets
Sostituisci i file placeholder nella cartella `public/assets/`:

- **lbs-logo.svg:** Il tuo logo istituzionale
- **profile-image.jpg:** La tua foto professionale (400x400px o superiore)
- **cv.pdf:** Il tuo Curriculum Vitae in formato PDF

### 3. Contenuti
- **research.astro:** Aggiungi le tue pubblicazioni e working papers
- **teaching.astro:** Elenca i tuoi corsi e materiali didattici
- **cv.astro:** Il CV verrà visualizzato automaticamente se sostituisci il file PDF

### 4. Link
Aggiorna i link placeholder:
- Link LinkedIn in `index.astro` e `Footer.astro`
- Link alle pubblicazioni in `research.astro`

## 🛠️ Tecnologie Utilizzate

- **[Astro](https://astro.build/)** - Framework per siti statici
- **CSS Vanilla** - Styling con CSS personalizzato
- **Google Fonts** - Lora e Source Sans 3

## 📱 Responsive Design

Il sito è completamente responsive e si adatta automaticamente a:
- **Desktop** (>768px)
- **Tablet** (768px - 480px)
- **Mobile** (<480px)

## 🎯 SEO e Performance

- HTML semantico
- Meta tag ottimizzati
- Caricamento veloce
- Immagini ottimizzate
- Struttura accessibile

## 📄 Licenza

Questo progetto è fornito come template. Puoi utilizzarlo e modificarlo liberamente per i tuoi scopi personali o accademici.

## 🆘 Supporto

Per questioni o personalizzazioni avanzate, consulta la [documentazione di Astro](https://docs.astro.build/).

---

**Nota:** Ricorda di sostituire tutti i contenuti placeholder con le tue informazioni personali prima di pubblicare il sito.
