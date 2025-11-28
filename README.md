# Vlotwerk - Website & Automatisering

Een professionele, converterende website voor Vlotwerk, gericht op Nederlandse ZZP'ers en kleine bedrijven.

## 🚀 Features

- **Responsive Design** - Werkt perfect op desktop, tablet en mobiel
- **Snelle laadtijd** - Gebouwd met Astro voor optimale performance
- **SEO geoptimaliseerd** - Meta tags, semantische HTML, snelle laadtijd
- **Converterende copy** - Nederlands, gericht op de doelgroep
- **Moderne aesthetiek** - Professioneel, betrouwbaar, onderscheidend

## 📁 Project Structuur

```
karel-site/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Problems.astro
│   │   ├── Services.astro
│   │   ├── About.astro
│   │   ├── Process.astro
│   │   ├── Testimonials.astro
│   │   ├── FAQ.astro
│   │   ├── Contact.astro
│   │   └── Footer.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🛠️ Installatie

1. Installeer dependencies:
```bash
npm install
```

2. Start development server:
```bash
npm run dev
```

3. Bouw voor productie:
```bash
npm run build
```

4. Preview productie build:
```bash
npm run preview
```

## ✏️ Aanpassingen maken

### Teksten aanpassen
Alle teksten staan direct in de component bestanden in `src/components/`. Open het betreffende bestand en pas de Nederlandse teksten aan.

### Kleuren aanpassen
De kleurpalet staat in `src/styles/global.css` onder `:root`. De belangrijkste kleuren:
- `--color-primary`: Hoofdkleur (teal/groen)
- `--color-accent`: Accent kleur (amber/geel)
- `--color-ink`: Tekstkleur (donkerblauw)
- `--color-canvas`: Achtergrondkleur (off-white)

### Contactformulier koppelen
Het contactformulier staat in `src/components/Contact.astro`. Je kunt dit koppelen aan:
- **Netlify Forms** - Voeg `data-netlify="true"` toe aan het form element
- **Formspree** - Verander de action naar je Formspree endpoint
- **Custom backend** - Pas de submit handler aan in de `<script>` tag

### Foto's toevoegen
1. Plaats je foto in de `public/` folder
2. Pas de `About.astro` component aan om een `<img>` te gebruiken in plaats van de placeholder

## 📱 Responsiveness

De site is volledig responsive met breakpoints op:
- Mobile: < 768px
- Tablet: 768px - 1023px
- Desktop: ≥ 1024px

## 🔍 SEO

- Meta description in Layout.astro
- Semantische HTML structuur
- Open Graph tags voor social media
- Snelle laadtijd (Lighthouse 90+)

## 📝 Volgende stappen

1. [ ] Eigen foto toevoegen in About sectie
2. [ ] Contactformulier koppelen (Netlify/Formspree/etc.)
3. [ ] Google Analytics toevoegen
4. [ ] Echte testimonials toevoegen
5. [ ] KVK/BTW nummers aanpassen in Footer
6. [ ] E-mailadres aanpassen
7. [ ] Privacybeleid pagina maken
8. [ ] Algemene voorwaarden pagina maken

## 🌐 Deployment

### Netlify (aanbevolen)
1. Push naar GitHub
2. Verbind met Netlify
3. Build command: `npm run build`
4. Publish directory: `dist`

### Vercel
1. Push naar GitHub
2. Import in Vercel
3. Framework preset: Astro

---

Gemaakt met ❤️ voor Vlotwerk
# vlotwerk
