# Grobelnik Bojan s.p. - Spletna stran

Profesionalna spletna stran za podjetje Grobelnik Bojan s.p., ki se ukvarja s transportom, logistiko in gradbeno mehanizacijo.

## 📁 Struktura projekta

```
Transport_logitsics_B_G/
├── index.html          # Glavna HTML stran
├── style.css           # CSS slogi
├── script.js          # JavaScript funkcionalnost
└── README.md          # Dokumentacija
```

## 🚀 Zagon

Odprite `index.html` v poljubnem spletnem brskalniku:

```bash
# Na Windows
start index.html

# Na Mac
open index.html

# Na Linux
xdg-open index.html
```

Ali pa uporabite lokalni strežnik:

```bash
# Python 3
python -m http.server 8000

# Node.js (http-server)
npx http-server
```

Nato odprite `http://localhost:8000` v brskalniku.

## 📄 Sekcije spletne strani

| Sekcija | Opis |
|---------|------|
| **Domov** | Hero sekcija z glavnim sporočilom, statistika, CTA gumbe |
| **Storitve** | 4 storitvene kartice: transport, izkopi, mehanizacija, interventni prevozi |
| **Zakaj izbrati nas** | Prednosti podjetja z izkušenj badge-om |
| **Vozni park** | Prikaz vozil in mehanizacije |
| **O nas** | Zgodba podjetja in ključne lastnosti |
| **Kontakt** | Kontaktni podatki in obrazec za povpraševanje |

## 🎨 Tehnologije

- **HTML5** - Semantična struktura
- **CSS3** - Moderni slogi (CSS Grid, Flexbox, CSS spremenljivke)
- **JavaScript** - Vanilla JS za interaktivnost
- **Google Fonts** - Montserrat & Open Sans

## 📱 Odziven dizajn

Spletna stran je optimizirana za:

- Desktop (1024px+)
- Tablice (768px - 1024px)
- Mobilne naprave (< 768px)

## ⚙️ Funkcionalnosti

- Fiksna navigacija z efektom ob scrollu
- Mobilni hamburger menu
- Gladko premikanje (smooth scroll)
- Hover efekti na kartice in gumbe
- Kontaktni obrazec (zahteva backend za delovanje)

## 🔧 Prilagoditev

### Sprememba barv

Barve so definirane v CSS spremenljivkah na začetku `style.css`:

```css
:root {
    --primary: #1a365d;       /* Glavna barva */
    --accent: #f6ad55;        /* Poudarna barva */
    --dark: #1a202c;          /* Temna barva */
    /* ... */
}
```

### Sprememba kontaktnih podatkov

Podatki so v `index.html`:
- Telefonska številka: `tel:+38631234567`
- E-pošta: `info@transport-grobelnik.eu`

### Dodajanje slik

Zamenjajte URL-je slik v `index.html` z lastnimi slikami:
```html
<img src="https://images.unsplash.com/..." alt="...">
```

## 📋 SEO

### Meta podatki
- **Title:** Grobelnik Bojan s.p. | Transport, logistika in gradbena mehanizacija
- **Description:** Zanesljiv partner za transport, logistiko in gradbena dela
- **Keywords:** transport, logistika, gradbena mehanizacija, prevozi, izkopi, tovorna vozila

### Ključne besede za Slovenijo
- transport Slovenija
- tovorni prevozi
- gradbena mehanizacija najem
- izkopi in zemeljska dela
- prevoz materiala
- logistične storitve
- najem bagerja
- tovornjak prevoz
- gradbeni transport
- interventni prevozi 24/7

## 📄 Licenca

© 2024 Grobelnik Bojan s.p. Vse pravice pridržane.

---

**Grobelnik Bojan s.p.** - Vaš zanesljiv partner za transport in logistiko že od leta 2004.
