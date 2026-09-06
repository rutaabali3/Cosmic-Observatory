<div align="center">

# COSMIC OBSERVATORY

### An Interactive Web Platform for Exploring Astronomy, Astrophysics, and Space Exploration

[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=for-the-badge)](https://github.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.style=for-the-badge)](LICENSE)

<br />

```
===================================================================================
     ____ ____ ____  __  ____ ____    ____ ___  ____ ____ ____ _  _ ____ ___  ____ ___  _  _
     |    |  | [__   |  | |___ |      |  | |__] [__  |___ |__/ |  | |__|  |   |  | |__/  \/
     |___ |__| ___]  |__| |___ |___   |__| |__] ___] |___ |  \  \/  |  |  |   |__| |  \  ||
===================================================================================
```

[Explore Features](#key-features) • [Installation](#quick-start-guide) • [Architecture](#project-architecture) • [Documentation](#sub-page-directory) • [Contributing](CONTRIBUTING.md)

---

</div>

## Executive Summary

**Cosmic Observatory** is a feature-rich, high-performance responsive web application engineered to make astronomical phenomena, astrophysics, and space exploration accessible and engaging.

Built with modern web standards, liquid layout components, dynamic data visualizers via Chart.js, and smooth entrance transitions via AOS (Animate On Scroll), Cosmic Observatory presents scientific information across nine specialized astronomical domains.

---

## Key Features

| Feature Module | Description | Interactive Capabilities |
| :--- | :--- | :--- |
| **Interactive Solar & Stellar Visualizations** | Dynamic orbit physics simulations and real-time canvas rendering. | Particle system floating background, orbital rotation physics, animated scale bars. |
| **Galaxy Distance Calculator** | Real-time computation of galactic distances and travel times. | Dynamic dropdown selector, live calculation updates, light-travel time translation. |
| **Data Analytics & Charting** | Visual data analytics using Chart.js. | Responsive stellar mass distribution charts, galaxy diameter comparison bar graphs. |
| **Space Exploration Timeline** | Chronological journey through cosmic history and human spaceflight. | Interactive scroll-triggered animations (AOS) with offset transitions. |
| **Integrated AI Celestial Assistant** | Embedded Chatling AI widget for real-time astronomical Q&A. | Instant interactive answers to user inquiries about celestial objects. |
| **Cosmic Scale Visualizer** | Graphical comparative display ranging from Earth to the Observable Universe. | CSS gradient progress tracks with dynamic percentage rendering. |

---

## Visual Architecture Overview

```
                          +-------------------------------+
                          |     Index Landing Page        |
                          |  (Hero, Stats, Comparison)    |
                          +---------------+---------------+
                                          |
        +---------------------------------+---------------------------------+
        |                                 |                                 |
+-------v-------+                 +-------v-------+                 +-------v-------+
|   Galaxies    |                 |     Stars     |                 |    Planets    |
| (Charts, Calc)|                 | (H-R Diagram) |                 | (Solar System)|
+---------------+                 +---------------+                 +---------------+
        |                                 |                                 |
+-------v-------+                 +-------v-------+                 +-------v-------+
|      Sun      |                 |  Black Holes  |                 |    Nebulae    |
| (Solar Flare) |                 | (Singularities|                 | (Nurseries)   |
+---------------+                 +---------------+                 +---------------+
        |                                 |                                 |
+-------v-------+                 +-------v-------+                 +-------v-------+
|   Asteroids   |                 |   Cosmology   |                 |  Exploration  |
| (Near Earth)  |                 |  (Big Bang)   |                 | (Missions)    |
+---------------+                 +---------------+                 +---------------+
```

---

## Sub-Page Directory

The application consists of a main landing hub and nine targeted sub-pages located in the `pages/` directory:

1. **Galaxies (`pages/galaxies.html`)**
   - Detailed analysis of Spiral, Elliptical, Lenticular, and Irregular galaxies.
   - Interactive Galaxy Distance Calculator and size comparison metrics.
   - Chart.js galaxy diameter visualizer.

2. **Stars (`pages/stars.html`)**
   - Stellar evolutionary stages from protostars to white dwarfs and neutron stars.
   - Stellar mass distribution chart and classification breakdowns.

3. **Planets (`pages/planets.html`)**
   - Comprehensive breakdown of Terrestrial and Gas Giant planets.
   - Planetary orbital periods, atmospheric compositions, and satellite counts.

4. **Sun (`pages/sun.html`)**
   - Solar atmospheric layers (Core, Radiative Zone, Convection Zone, Photosphere, Chromosphere, Corona).
   - Solar activity tracking including sunspots, solar flares, and coronal mass ejections.

5. **Black Holes (`pages/blackholes.html`)**
   - Event horizons, singularities, accretion disks, and hawking radiation.
   - Classification covering Stellar-mass, Intermediate, and Supermassive black holes.

6. **Nebulae (`pages/nebulae.html`)**
   - Stellar nurseries, Emission, Reflection, Dark, and Planetary nebulae.
   - Deep-space imaging descriptions and gas composition breakdowns.

7. **Asteroids (`pages/asteroids.html`)**
   - Near-Earth Objects (NEOs), Asteroid Belt dynamics, and Trojan asteroids.
   - Composition classifications (C-type, S-type, M-type).

8. **Cosmology (`pages/cosmology.html`)**
   - Big Bang theory, Cosmic Microwave Background (CMB) radiation, Dark Energy, and Dark Matter.
   - Expansion metrics and cosmic timeline breakdown.

9. **Exploration (`pages/exploration.html`)**
   - Historic and active space missions (Apollo, Voyager, Hubble, James Webb Space Telescope, Artemis).
   - Future deep-space trajectories and Mars colonization initiatives.

---

## Technical Architecture & File Structure

```
.
|-- index.html                 # Primary landing page and core dashboard
|-- css/
|   `-- style.css              # Custom styling, dark mode theme variables, glassmorphism, animations
|-- js/
|   `-- main.js                # Core JS logic, Chart.js initializations, animations, calculators
|-- pages/                     # Category-specific deep-dive pages
|   |-- asteroids.html
|   |-- blackholes.html
|   |-- cosmology.html
|   |-- exploration.html
|   |-- galaxies.html
|   |-- nebulae.html
|   |-- planets.html
|   |-- stars.html
|   `-- sun.html
|-- images/                    # Graphical assets and favicons
|   |-- chatbot.png
|   `-- image.ico
|-- CONTRIBUTING.md            # Guidelines for open-source contributors
|-- LICENSE                    # MIT License documentation
`-- README.md                  # Project documentation
```

---

## Interactive Component Spotlight

### Galaxy Distance Calculator Example

The calculator dynamically determines light travel times across various deep-space targets:

```javascript
// Dynamic distance calculation logic from main.js
const galaxies = {
    milkyWay: 26500,
    andromeda: 2537000,
    triangulum: 2730000,
    largeMagellanicCloud: 163000,
    smallMagellanicCloud: 200000
};

function formatDistance(lightYears) {
    if (lightYears >= 1000000) {
        return `${(lightYears / 1000000).toFixed(2)} million light-years`;
    }
    return `${lightYears.toLocaleString()} light-years`;
}
```

---

## Quick Start Guide

### Prerequisites

To run this repository locally, you only need a modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari). No complex build steps or Node.js server dependencies are strictly required.

### Local Execution

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/cosmic-observatory.git
   cd cosmic-observatory
   ```

2. **Serve locally:**
   - **Option A (Direct File Entry):** Open `index.html` directly in your web browser.
   - **Option B (Python Local Server):**
     ```bash
     python3 -m http.server 8000
     ```
     Navigate to `http://localhost:8000` in your browser.
   - **Option C (VS Code Live Server):** Right-click `index.html` and select **Open with Live Server**.

---

## Technologies Used

- **HTML5**: Semantic document structure for enhanced accessibility and SEO.
- **CSS3**: Custom CSS custom properties, Flexbox/Grid layouts, glassmorphism UI, keyframe animations.
- **JavaScript (ES6+)**: Dynamic DOM manipulation, async initialization, modules, event listeners.
- **Bootstrap 5.3.0**: Responsive grid, navigation bars, utility classes, and modular layout components.
- **Chart.js**: Responsive HTML5 canvas-based interactive charts and data visualizations.
- **AOS (Animate On Scroll)**: Smooth viewport-triggered scroll animations.
- **Font Awesome 6.4.0**: Scalable vector icons for user interface navigation.

---

## Development & Testing Checklist

Before submitting code changes, verify:
- Responsive display across Mobile (320px+), Tablet (768px+), and Desktop (1024px+).
- W3C HTML validation compatibility.
- Zero JavaScript console errors.
- Smooth performance on animations without frame drops.

---

## Future Roadmap

- [ ] **3D Solar System Visualizer**: Integrate Three.js for interactive WebGL 3D planet models.
- [ ] **Real-time NASA API Integration**: Fetch live APOD (Astronomy Picture of the Day) and NEO (Near-Earth Object) tracking data.
- [ ] **Exoplanet Database Search**: Implement real-time filtering and search for confirmed exoplanet systems.
- [ ] **Multilingual Support**: Add internationalization (i18n) localization options.

---

## License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full details.

---

<div align="center">
<strong>Cosmic Observatory</strong> - Exploring the universe, one discovery at a time.
</div>
