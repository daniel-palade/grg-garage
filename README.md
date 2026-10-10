# GRG Garage — Site oficial

**Live:** https://daniel-palade.github.io/grg-garage/ · **Repository:** https://github.com/daniel-palade/grg-garage

**Studio de detailing auto** — retapitări premium, detailing, recondiționare faruri și lumini ambientale.
Galați · Brăila · [TikTok @grggarage99](https://www.tiktok.com/@grggarage99) · 0724 341 598

## Structura proiectului

```
index.html          → tot site-ul (one-page, fără framework-uri)
assets/img/         → pozele procesate & optimizate pentru web
assets/video/       → 3 video-uri din atelier
README.md
```

## Design

- Temă **negru profund + violet neon** (#A78BFA / #6D28D9), atmosferă premium/luxury
- Tipografie: **Cormorant Garamond** (titluri serif elegante) + **Manrope** (text)
- Fără emoji-uri — iconițe SVG minimalist desenate la linie
- Hero cinematografic — **Audi-ul crem cu steluțe și ambient violet**, poză reală din atelier + parallax subtil
- Banda de servicii statică, eleganță tip editorial (fără animație)
- **5 secțiuni detaliate de servicii** — fiecare rând din lista de servicii duce prin scroll
  la secțiunea lui, cu text motivațional, materiale premium, argumente pro și CTA WhatsApp.
  Fiecare secțiune are un **slider Înainte/După**: **lucrări reale** pentru Detailing interior (scaun
  murdat→curat) și Polish faruri (far matuit→polimerizat); exemple stock (Pexels, licență liberă)
  pentru Polish vopsea și Ambient, etichetate onest „Exemplu”. La Retapitări: **galerie în 3 pași**
  (plafon+stâlpi retapițați → steluțe → rezultat final), fără before/after
- Galerie masonry cu captions la hover
- **Cele mai vizionate 3 clipuri TikTok** integrate cu player-ul oficial (view-count real)
- Pași de proces, **FAQ cu 5 întrebări** (acordeon, cu schema FAQPage pentru Google), ofertă personalizată, bandă CTA, contact
- **Adresă reală + hartă Google** — Strada Combinatului nr. 7, Galați (dark-map stilizat)
- **Secțiune Colaborări** pentru firme partenere (service-uri, dealeri, spălătorii, shop-uri)
- **Strip de încredere** (materiale premium, garanție, ofertă clară, răspuns rapid) sub lista de servicii
- **Buton „înapoi sus”** care apare la scroll + buton WhatsApp flotant
- **Tranziții cinematice**: intro cu perdele + monograma, titlul hero literă-cu-litră (blur-in),
  prăfușcă violetă plutind pe canvas, film grain peste tot site-ul (textură generată cu Python),
  nebula violetă mascată în zona titlului (generată cu Python), cursor cu aură, butoane magnetice,
  linie de progres la scroll, reveal editorial cu clip-path pe galerie
- Toate efectele respectă `prefers-reduced-motion` (se dezactivează pentru utilizatorii sensibili)
- 100% responsive (desktop / tabletă / mobil)

## Cum îl deschizi

Doar dublu-click pe `index.html` — funcționează în orice browser, fără instalare.

## Publicare pe GitHub Pages (gratuit)

1. Creează un cont pe [github.com](https://github.com) (dacă nu ai)
2. Click pe **New repository** → nume: `grg-garage` → **Create**
3. Încarcă fișierele: butonul **Add file → Upload files** → trage tot conținutul acestui folder (index.html + assets + README.md) → **Commit changes**
4. În repository: **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**
5. În ~1 minut site-ul e live la `https://USERNAME.github.io/grg-garage/`

Alternativ, din linia de comandă (dacă ai git instalat):

```bash
cd acest-folder
git init && git add . && git commit -m "Site GRG Garage"
git remote add origin https://github.com/USERNAME/grg-garage.git
git push -u origin main
```

## SEO (implementat)

- Titlu + descriere + keywords optimizate: *retapitari Galați/Brăila, steluțe în plafon, detailing auto,
  polish faruri, cosmetica auto, polish mașini, lumini ambientale*
- **JSON-LD LocalBusiness** (areaServed Galați + Brăila, telefon, catalog de servicii)
- `sitemap.xml` + `robots.txt` incluse
- Imagini cu `alt` descriptive + încărcare lazy
- **Următorii pași (manual, gratuit)**: înscrie site-ul în Google Search Console și creează un
  **Google Business Profile** pentru GRG Garage — profilul de firmă Google e factorul #1 pentru
  căutările locale de tip „retapitari Galați”

## Domeniu propriu (opțional)

`grggarage.ro` se poate lega de GitHub Pages (Settings → Pages → Custom domain) sau de orice hosting clasic — site-ul e static, funcționează oriunde.
