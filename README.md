# AgRhythm Platform - 3D Structure Visualization

An interactive 3D visualization of the AgRhythm Platform's architecture, built with Three.js. This project provides a comprehensive view of the platform's components, connections, and data flow through an immersive 3D interface.

## Features

- **Interactive 3D Visualization**: Navigate through a three-dimensional representation of the platform structure
- **Multiple Layout Options**: 
  - Force Graph: Dynamic force-directed layout
  - Hierarchical: Organized by component levels
  - Circular: Grouped by functional areas
- **Real-time Interaction**: 
  - Hover to highlight connections
  - Click nodes for detailed information
  - Smooth camera controls (rotate, pan, zoom)
- **Color-coded Components**:
  - 🔴 Entry/Login Pages
  - 🟢 Core Platform Components  
  - 🔵 Dashboard Sections
  - 🟡 Operators/Specialists
  - 🟣 External Systems

## Quick Start

1. Open `index.html` in a modern web browser
2. Use mouse controls to navigate:
   - **Left Click + Drag**: Rotate the view
   - **Right Click + Drag**: Pan the camera
   - **Scroll**: Zoom in/out
   - **Hover**: Highlight node connections
   - **Click**: Show node details

## Project Structure

```
agrhythm-3d-platform/
├── index.html          # Main visualization file
├── assets/
│   ├── js/            # JavaScript files
│   ├── css/           # Stylesheets
│   └── images/        # Image assets
├── docs/              # Documentation
├── README.md          # Project documentation
└── package.json       # Project configuration
```

## Platform Components

The visualization represents the following AgRhythm Platform components:

### Core Platform
- **AgRhythm Hub**: Central platform hub
- **Dashboard**: Main dashboard interface
- **AI Chat**: AI-powered chat system
- **Insights**: Data insights and analytics
- **Collected Data**: Data storage and management

### Dashboard Sections
- Reports, Audits, Maps, Crops
- Infrastructure, Health & Safety
- Stock, Tasks/Todo, Finances

### User Access Points
- Profile/Edit, Billing
- Operator Login, Farmer Login
- Drone Operators, Other Specialists

### External Integrations
- API Access gateway
- Cameras, Gallagher systems
- IoT Devices, Necklaces
- Companies, Products, Referrals

## Technology Stack

- **Three.js r128**: 3D graphics and rendering
- **HTML5 Canvas**: Dynamic text rendering
- **CSS3**: Modern styling with backdrop filters
- **Vanilla JavaScript**: Core application logic

## Development

This is a client-side application that runs entirely in the browser. No build process or server setup required.

For development:
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes and refresh to see updates

## Browser Support

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

Requires WebGL support for 3D rendering.

## License

[Add your license information here]

## Contributing

[Add contribution guidelines here]