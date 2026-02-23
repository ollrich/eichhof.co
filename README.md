# eichhof.co

Interaktive 3D-Partikel-Visualisierung eines Smileys, gebaut mit Three.js.

## Demo

[eichhof.co](https://eichhof.co)

## Features

- **42.000 Partikel** formen einen 3D-Smiley mit Augen und Lächeln
- **Animierter Aufbau**: Partikel starten aus dem Zentrum und formieren sich sanft zur Smiley-Form (5 Sekunden Ease-in-out Animation)
- **Interaktive Steuerung**:
  - Ziehen (Drag) zum Drehen des Smileys
  - Mausrad / Pinch-Zoom zum Rein- und Rauszoomen
  - Doppelklick / Doppeltap für Spezialeffekte
- **Spezialeffekte** (zufällig bei Doppelklick):
  - **Explosion**: Partikel fliegen auseinander und kehren zurück
  - **Regenbogen-Farbwechsel**: Alle Partikel durchlaufen einen Regenbogen-Zyklus
- **Sanfte Auto-Rotation** nach dem initialen Aufbau
- **Responsive**: Passt sich an alle Bildschirmgrößen an
- **Touch-Support**: Vollständige Unterstützung für mobile Geräte

## Technologie

- [Three.js](https://threejs.org/) für WebGL-basiertes 3D-Rendering
- Vanilla JavaScript (keine weiteren Abhängigkeiten)
- CSS Gradient-Hintergrund

## Lokale Entwicklung

Einfach `index.html` in einem Browser öffnen oder einen lokalen Server starten:

```bash
python -m http.server 8000
# oder
npx serve .
```

## Struktur

```
├── index.html      # Komplette Anwendung (HTML, CSS, JS)
├── three.min.js    # Three.js Library (r128)
└── README.md
```
