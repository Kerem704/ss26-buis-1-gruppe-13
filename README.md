# Oldenburger Fahrradmanufaktur (OFM)

**Betriebliche Umweltinformationssysteme I · SoSe 2026 · Gruppe 13**  
Carl von Ossietzky Universität Oldenburg

---

## Live-Website

**https://kerem704.github.io/ss26-buis-1-gruppe-13/**

---

## Über das Projekt

Die Oldenburger Fahrradmanufaktur (OFM) ist ein fiktives, mittelständisches Unternehmen mit Hauptsitz in Oldenburg, spezialisiert auf urbane Singlespeeds und Fixies. Im Rahmen eines Generationswechsels wird das Unternehmen nachhaltig umstrukturiert.

Dieses Projekt dokumentiert die Nachhaltigkeitstransformation der OFM im Rahmen der Lehrveranstaltung **Betriebliche Umweltinformationssysteme I** und erfüllt die Aufgaben 1–8 der Projektaufgabe SoSe 2026.

---

## Seitenstruktur

| Seite | URL | Inhalt |
|-------|-----|--------|
| Startseite | `/startseite/` | Hero, Unternehmensvorstellung, 4 Werte, EcoFix-Teaser |
| Manufaktur | `/manufaktur/` | Firmengeschichte, Standorte, Umweltmanagement-Konzept |
| EcoFix | `/ecofix/` | Produktfeatures, Ökobilanz-Kennzahlen, Bestellformular |
| Nachhaltigkeit | `/nachhaltigkeit/` | Vollständiger Nachhaltigkeitsbericht (Aufgabe 7) |

---

## Technologie

| Komponente | Technologie |
|------------|-------------|
| Framework | [Jekyll 4.3](https://jekyllrb.com/) (Static Site Generator) |
| Hosting | [GitHub Pages](https://pages.github.com/) |
| CI/CD | GitHub Actions (automatischer Build bei Push) |
| Fonts | Space Grotesk + Fraunces (Google Fonts) |
| Farbschema | Cyan `#00A8E8` · Schwarz `#111111` · Off-White `#F5F5F0` |

---

## Projektstruktur

```
ss26-buis-1-gruppe-13/
├── _layouts/          # HTML-Layouts (default.html)
├── _includes/         # Wiederverwendbare Komponenten (nav, footer)
├── assets/
│   ├── css/           # Stylesheet (main.css)
│   ├── js/            # JavaScript (main.js)
│   └── images/        # Bilder & Logo
├── startseite/        # Startseite
├── manufaktur/        # Manufaktur-Seite
├── ecofix/            # EcoFix Produktseite
├── nachhaltigkeit/    # Nachhaltigkeitsbericht
├── _config.yml        # Jekyll-Konfiguration
└── Gemfile            # Ruby-Abhängigkeiten
```

---

## Hinweis

Dies ist ein **Lehrprojekt** der Carl von Ossietzky Universität Oldenburg. Die Oldenburger Fahrradmanufaktur ist ein fiktives Unternehmen, das ausschließlich zu Bildungszwecken erstellt wurde.

---

*BUIS I · SoSe 2026 · Gruppe 13 · Carl von Ossietzky Universität Oldenburg*
