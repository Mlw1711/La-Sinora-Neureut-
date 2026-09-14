# Barber Shop – Website-Entwurf

Ein einfacher, einseitiger Gestaltungsvorschlag für einen Barbershop im "Golden Barber"-Stil (Schwarz/Gold), auf Basis des mitgelieferten Logos und Shop-Fotos.

Hinweis: Dieses Repository war zuvor ein Entwurf für die Ristorante Pizzeria La Signora und wurde auf Wunsch komplett auf dieses neue Projekt umgebaut.

## Ansehen

Einfach `index.html` im Browser öffnen – keine Installation, kein Build-Schritt nötig.

Alternativ mit einem lokalen Server:

```bash
python3 -m http.server 8000
# dann im Browser: http://localhost:8000
```

## Struktur

```
index.html          Startseite (Hero, Leistungen, Über uns, Galerie, Kontakt)
impressum.html       Impressum (Entwurf)
datenschutz.html     Datenschutzerklärung (Entwurf)
css/style.css        Gesamtes Styling
js/main.js           Mobile-Navigation, aktuelles Jahr im Footer
images/               Bilder (siehe images/README.md)
```

## Was noch fehlt (bewusst offen gelassen)

- **Hero-Foto** – das Innenraum-Foto des Shops soll als Hintergrund in den Hero, ist aber noch nicht hochgeladen
- **Echter Name, Adresse, Telefon, E-Mail, Öffnungszeiten** – bislang nur "Barber Shop" laut Logo, keine weiteren Angaben vorhanden
- **Echte Leistungen & Preise** – aktuell eine beispielhafte, klar gekennzeichnete Preisliste
- **Weitere Fotos** für "Über uns" und Galerie
- **Google-Maps-Karte** – folgt, sobald eine Adresse feststeht
- **Vollständiges Impressum** – Inhaber:in-Name und Kontaktdaten fehlen noch

## Übernommene Daten

- Logo: `images/barber-logo.png` (freigestellt)
- Referenz-Look: Innenraum-Foto mit schwarzen Wänden, Waben-LED-Deckenlicht, goldenen Barbierstühlen
