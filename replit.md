# Y-port Portfolio Template

## Overview
This is a luxurious portfolio website template featuring:
- Stunning 3D animations with Spline viewer
- Smooth scroll effects with Lenis
- Interactive menu system with sound effects
- Responsive design with modern aesthetics
- Custom fonts and visual effects

## Project Structure
```
/
├── index.html          # Main HTML file
├── server.py           # Python HTTP server (serves on port 5000)
├── css/               # Stylesheets
├── js/                # JavaScript bundles (includes Three.js, Spline viewer)
├── fonts/             # Custom fonts
├── images/            # Image assets
└── media/             # Audio files for effects
```

## Technology Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **3D Graphics**: Three.js, Spline 3D viewer
- **Animations**: Lenis smooth scroll, custom CSS animations
- **Server**: Python 3.11 HTTP server

## Recent Changes
- **2025-10-22**: Initial setup for Replit environment
  - Extracted portfolio template from zip archive
  - Renamed `index_with_3dtext.html` to `index.html`
  - Created Python HTTP server with cache-control headers
  - Configured workflow to serve on port 5000 (0.0.0.0)
  - Set up gitignore for Python projects

## Running the Project
The project runs automatically via the configured workflow:
- Server binds to `0.0.0.0:5000`
- Serves static files from the root directory
- Includes cache-control headers for development

## Features
1. **3D Intro Animation**: Interactive Spline 3D viewer on load
2. **Audio Effects**: Ambient sound and UI interaction sounds
3. **Smooth Scrolling**: Lenis library for buttery smooth scrolling
4. **Menu System**: Glass-morphism menu with hover effects
5. **Services Section**: Showcases websites and branding services
6. **Responsive Design**: Works across different screen sizes

## Notes
- The site uses external Spline 3D models hosted at `https://prod.spline.design/`
- WebGL is required for 3D graphics
- Audio files are in WebM format
- All assets are bundled and optimized
