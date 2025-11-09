# 3D Solar System Explorer

An interactive, responsive 3D solar system visualization website built with React and CSS 3D transforms. Explore planets, moons, asteroids, stars, galaxies, exoplanets, and spacecraft with detailed information panels.

## Features

- **3D Visualization**: CSS 3D transforms create a smooth, interactive solar system
- **Comprehensive Content**: 
  - 8 planets with orbital animations
  - Multiple moons orbiting their parent planets
  - Asteroids in the asteroid belt
  - Stars including the Sun and nearby stars
  - Galaxies including the Milky Way
  - Exoplanets discovered beyond our solar system
  - Major spacecraft like ISS, Hubble, Voyager, and more
- **Interactive Features**:
  - Click any object to view detailed information
  - Hover effects for visual feedback
  - Zoom controls (0.5x to 3x)
  - Rotation speed controls (0x to 3x)
  - Search functionality to filter objects
- **Responsive Design**: Optimized for both mobile and desktop devices
- **Smooth Animations**: CSS keyframe animations for orbital motion and rotations

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository or navigate to the project directory
2. Install dependencies:

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build

Create a production build:

```bash
npm run build
```

### Preview

Preview the production build:

```bash
npm run preview
```

## Usage

1. **Explore Objects**: Click on any celestial object to view detailed information
2. **Zoom**: Use the zoom slider to get closer or further from the solar system
3. **Control Speed**: Adjust the rotation speed slider to speed up or pause animations
4. **Search**: Type in the search box to filter and find specific objects
5. **Mobile**: On mobile devices, tap objects to interact and use touch gestures

## Technology Stack

- **React 18+**: UI framework
- **Vite**: Build tool and dev server
- **CSS 3D Transforms**: For 3D visualization
- **CSS Animations**: For smooth orbital motion

## Project Structure

```
src/
├── components/
│   ├── SolarSystem.jsx    # Main 3D container
│   ├── Planet.jsx         # Planet component
│   ├── Moon.jsx           # Moon component
│   ├── Asteroid.jsx       # Asteroid component
│   ├── Star.jsx          # Star component
│   ├── Galaxy.jsx        # Galaxy component
│   ├── Exoplanet.jsx     # Exoplanet component
│   ├── Spacecraft.jsx    # Spacecraft component
│   ├── InfoPanel.jsx     # Information display
│   └── Navigation.jsx   # Controls and search
├── data/
│   └── celestialData.js  # All celestial object data
├── styles/
│   ├── App.css          # Main application styles
│   ├── SolarSystem.css  # 3D transforms and animations
│   └── responsive.css   # Mobile responsive styles
├── App.jsx
└── main.jsx
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available for educational purposes.

