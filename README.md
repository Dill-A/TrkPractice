# 🚛 TrkPractice — 53ft Trailer Backing Simulator

A browser-based truck and trailer backing simulator built for practicing dock maneuvers on both mobile and desktop.

## Play It

**<https://dill-a.github.io/TrkPractice>**

Works on iPhone, Android, and Windows. On iPhone, tap **Share → Add to Home Screen** to install it as a fullscreen app.

-----

## Features

- Realistic articulated trailer physics
- Two warehouses with multiple dock doors and scoring
- Score grading system — Perfect, Great, Good, Fair, Poor
- Tandem axle sliding (highway / city mode)
- Pinch to zoom on mobile, scroll wheel on desktop
- Side mirrors with real-time rear view
- Organized truck yard with parked trailers and hazard cones
- Asphalt yard with concrete dock apron
- Collision and jackknife detection
- Animated score and collision popups
- Detailed truck cab and 53ft trailer visuals
- Frame-rate independent physics (consistent on all devices)
- Installable as a PWA on iOS and Android

## Controls

### Mobile (Touch)

|Button          |Action                             |
|----------------|-----------------------------------|
|▲ Fwd           |Accelerate                         |
|▼ Rev           |Reverse                            |
|◀ Left / ▶ Right|Steer                              |
|Brake           |Brake                              |
|Center          |Straighten steering                |
|Tandems         |Toggle highway / city axle position|
|Reset           |Reset truck and regenerate yard    |

### Desktop (Keyboard)

|Key         |Action         |
|------------|---------------|
|W / ↑       |Forward        |
|S / ↓       |Reverse        |
|A / ←       |Steer Left     |
|D / →       |Steer Right    |
|Q           |Brake          |
|E           |Center Steering|
|R           |Reset          |
|F           |Toggle Tandems |
|Scroll Wheel|Zoom           |

### Desktop (Mouse)

|Input                |Action |
|---------------------|-------|
|Left Click Hold      |Forward|
|Right Click Hold     |Reverse|
|Move Mouse Left/Right|Steer  |

## Scoring

Each dock attempt is scored out of 100 points:

- **40 pts** — Lateral alignment (how centred the trailer is on the door)
- **40 pts** — Trailer angle (how straight into the dock)
- **20 pts** — Truck/trailer alignment (jackknife angle)

## Built With

- Vanilla HTML, CSS, and JavaScript — no frameworks or libraries
- Single HTML file, runs entirely in the browser
- `manifest.json` — enables “Add to Home Screen” as a fullscreen PWA on iOS and Android
- Hosted via GitHub Pages

## Repository Files

|File           |Description                              |
|---------------|-----------------------------------------|
|`index.html`   |The full game                            |
|`manifest.json`|PWA manifest for home screen installation|

## Credits

Built collaboratively by **Dill-A** and **Claude** (Anthropic).

The concept, design direction, and real-world trucking knowledge came from Dill-A — an experienced trucker who knew exactly how a simulator should feel. Claude assisted with the code architecture, physics modeling, UI layout, and iterative improvements throughout the project.

From trailer physics and dock scoring to iOS touch fixes and yard layout — this was a true team effort. 🚛