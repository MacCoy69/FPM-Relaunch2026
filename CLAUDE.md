# Finest Properties Mallorca – Relaunch 2026

## Projektbeschreibung
Website-Relaunch für **Finest Properties Mallorca (FPM)**, einen Premium-Immobilienmakler auf Mallorca.
Zielgruppe: HNWI (High Net Worth Individuals), internationale Investoren, Luxus-Käufer.
Fokusregionen: Südwesten (Port d'Andratx), Palma & Son Vida, Serra de Tramuntana.

## Tech Stack
- **HTML5** mit semantischen Tags
- **Tailwind CSS** via CDN (Prototyping) – später Purge/Build-Pipeline
- **Vanilla JavaScript** – kein Framework (vorerst)
- **Google Fonts**: Inter (Body, sans-serif), Playfair Display (Headlines, serif)
- **Schema.org** Structured Data (JSON-LD) für AI/SEO-Optimierung

## Design-System
- **Style**: Apple-inspiriert, minimalistisch, Glassmorphism
- **Primärfarbe**: Orange `#EA580C` (Tailwind `orange-600`)
- **Neutrals**: Grau-Palette (gray-50 bis gray-900)
- **Glassmorphism**: `backdrop-filter: blur(20px)`, semi-transparenter weißer Hintergrund
- **Schriftarten**:
  - Body: `Inter` (300, 400, 500, 600)
  - Headlines (h1-h4): `Playfair Display` (400, 600, italic)
- **Border-Radius**: Großzügig (rounded-2xl, rounded-full für Buttons)
- **Schatten**: Subtil (shadow-sm Standard, shadow-2xl für Hero-Elemente)

## Seitenstruktur (index.html)
1. **Cookie Banner** – DSGVO-konformer Platzhalter (Borlabs-Integration geplant)
2. **Navigation** – Fixed, Glass-Panel, Responsive mit Mobile-Hamburger
3. **Hero** – Fullscreen-Bild, Tagline, Property-Finder (Region/Typ/Budget)
4. **Marktdaten & Karte** – Interaktive SVG-Map von Mallorca mit Wachstumsraten
5. **Featured Investments** – Horizontal-Scroll Cards (3 Objekte)
6. **FAQ (Investor)** – Akkordeon mit `<details>`, AI-Grounding-optimiert
7. **Footer** – 4-Spalten: Brand, Immobilien-Links, Investment-Links, Kontakt

## Immobilien-Daten (Beispiele aus Prototyp)
| ID    | Typ                  | Preis      | Region                    |
|-------|----------------------|------------|---------------------------|
| 81400 | Agroturismo / Trophy | 23 Mio EUR | Zwischen Palma & Valldemossa |
| 81733 | Herrenhaus / Palma   | 24.5 Mio EUR | Palma Südlage           |
| 81868 | Finca / Tramuntana   | 6.6 Mio EUR | Tramuntana               |

## SEO & AI-Readiness
- Schema.org `RealEstateAgent` JSON-LD im Head
- FAQ-Sektion mit semantischen Fragen (AI Snippet-Optimierung für Gemini, ChatGPT etc.)
- Meta-Description vorhanden
- Sprachattribut `lang="de"` gesetzt

## Kontaktdaten
- **Adresse**: Carrer de la Mar, Palma, 07001, Illes Balears, ES
- **Telefon**: +34 971 000 000
- **E-Mail**: hello@finestproperties.com
- **Social**: Instagram, LinkedIn

## Offene Aufgaben / Roadmap
- [ ] Eigene Bilder statt Unsplash-Platzhalter
- [ ] Tailwind Build-Pipeline (PostCSS, Purge)
- [ ] Borlabs Cookie-Integration (DSGVO-konform)
- [ ] Property-Finder-Funktionalität (Backend/API)
- [ ] Weitere Unterseiten (Listings, Über uns, Kontakt-Formular)
- [ ] CMS-Anbindung oder Headless-Backend
- [ ] Performance-Optimierung (Bilder, Lazy Loading)
- [ ] Mehrsprachigkeit (DE/EN/ES)
- [ ] Analytics & Tracking Setup

## Konventionen
- Deutsche Sprache für Inhalte, englische Fachbegriffe wo branchenüblich
- Mobile-First Responsive Design
- Barrierefreiheit beachten (alt-Texte, Kontraste)
- Commits auf Deutsch oder Englisch
