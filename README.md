# HyperAV - 4D Audio Visualizer

An immersive audio-reactive 4D geometry visualizer that brings higher-dimensional mathematics to life with stunning WebGL visuals. HyperAV transforms sound into complex geometric visualizations in real-time.

![HyperAV Demo](screenshot.png)

## Features

- **4D Geometry Rendering**: Visualize hypercubes, hyperspheres, and hypertetrahedrons in interactive 3D space
- **Audio Reactivity**: Microphone input drives dynamic visual parameters for an immersive audiovisual experience
- **Multiple Projection Methods**: Perspective, orthographic, and stereographic projections
- **Responsive UI**: Collapsible controls panel and touch-based parameter controls directly on the canvas
- **Modern Visual Effects**: Glassmorphism, magnification, and neon accents
- **Fallback Simulation**: Generates patterned data when microphone access isn't available
- **Cross-Platform**: Works across desktop and mobile browsers

## Quick Start

No installation or build process required! Simply open `index.html` in a browser, and allow microphone access for audio reactivity.

```bash
# Open in your browser
open index.html
```

## Development

HyperAV uses vanilla JavaScript with ES6+ modules, making it easy to modify and extend:

```bash
# Clone the repository
git clone https://github.com/yourusername/hyperav.git
cd hyperav

# Start a local server (if you have Python)
python -m http.server

# Or use any simple HTTP server
```

## Project Structure

- `core/`: Core visualization engine components
  - `HypercubeCore.js`: Main renderer and state manager
  - `ShaderManager.js`: WebGL shader compilation and management
  - `GeometryManager.js`: 4D geometry generation
  - `ProjectionManager.js`: 4D-to-3D projection methods
- `js/`: Application layer
  - `visualizer-main.js`: UI, audio analysis, and parameter mapping
- `css/`: Styling
  - `enhanced-styles.css`: Visual effects and UI enhancements
  - `neumorphic-style.css`: Base component styling
  - `neumorphic-vars.css`: Design system variables

## Controls

- **Geometry**: Switch between hypercube, hypersphere, and hypertetrahedron
- **Projection**: Select perspective, orthographic, or stereographic projection
- **Parameters**: Adjust morphing, dimensions, rotation, patterns, and more
- **Touch Controls**: Direct manipulation of key parameters from the canvas

## Browser Compatibility

- Chrome/Edge (recommended): Full support for all features
- Firefox/Safari: Good support with some WebGL performance differences
- Mobile browsers: Fully responsive with touch optimization

## License

MIT License

## Credits

Created with WebGL, Web Audio API, and pure JavaScript.

---

Made with 💜 by Claude