# Realistiq Website

Officiële website voor Realistiq FiveM Server.

## 📁 Structuur

```
realistiq_website/
├── index.html          # Hoofdpagina
├── apv.html            # Regels pagina (toevoegen indien aanwezig)
├── css/
│   └── styles.css      # Styling
├── js/
│   └── script.js       # Navigatie, promo bar, player count
├── images/
│   └── rqlogo.png      # Logo
├── media/
│   └── herovideo.mp4   # Hero achtergrond video
├── vercel.json         # Vercel routing configuratie
└── .gitignore
```

## 🚀 Deployen op Vercel via GitHub

### Stap 1 – GitHub repository aanmaken
1. Ga naar [github.com](https://github.com) en log in
2. Klik op **New repository**
3. Geef het een naam, bijv. `realistiq-website`
4. Zet op **Public** of **Private**
5. Klik op **Create repository**

### Stap 2 – Bestanden uploaden
1. Klik in de lege repo op **uploading an existing file**
2. Sleep alle bestanden en mappen hierheen (of gebruik Git CLI)
3. Klik op **Commit changes**

### Stap 3 – Vercel koppelen
1. Ga naar [vercel.com](https://vercel.com) en log in met GitHub
2. Klik op **Add New → Project**
3. Selecteer je GitHub repository `realistiq-website`
4. Framework Preset: **Other** (geen framework nodig)
5. Klik op **Deploy**

✅ Je site is live! Vercel geeft je automatisch een domein, bijv. `realistiq-website.vercel.app`

### Stap 4 – Eigen domein koppelen (optioneel)
1. Ga in Vercel naar je project → **Settings → Domains**
2. Voeg je domein toe, bijv. `realistiq.nl`
3. Volg de DNS instructies van Vercel

## 🔧 Aanpassen

| Wat aanpassen | Bestand |
|---|---|
| Discord link | `js/script.js` → zoek op `discord.gg/realistiq` |
| Store link | `js/script.js` → `donateAnchor` + `index.html` |
| Promo bar teksten | `js/script.js` → `promo-item` spans |
| Logo | Vervang `images/rqlogo.png` |
| Hero video | Vervang `media/herovideo.mp4` |
| Kleuren / stijlen | `css/styles.css` |
