# IFC Viewer

A modern, web-based IFC (Industry Foundation Classes) viewer built with Three.js and web-ifc. This application allows you to view and interact with IFC models directly in your browser.

## Features

- 🏗️ Load and view IFC models in 3D
- 🔍 Interactive model exploration
- 📊 View element properties and attributes
- ⚙️ Configurable display settings:
  - Grid visibility
  - Axes visibility
  - Shadow rendering
  - Model opacity control
- 📱 Responsive design
- 🎯 Element selection and highlighting
- 🗂️ Multiple model support

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

## Setup

1. Clone the repository:

```bash
git clone [your-repository-url]
cd ifc-viewer
```

2. Install dependencies:

```bash
npm install
```

## Development

To run the development server:

```bash
npm run dev
```

This will start the development server at `http://localhost:3000` (or another available port if 5173 is in use).

## Building for Production

To create a production build:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## Usage

1. Open the application in your web browser
2. Click the "Load Model" button in the Models panel
3. Select an IFC file from your computer
4. Use the following controls to navigate:
   - Left mouse button: Rotate camera
   - Right mouse button: Pan camera
   - Mouse wheel: Zoom in/out
   - Click on model elements to view their properties

## Settings

The viewer includes several configurable settings:

- **Show Grid**: Toggle the ground grid visibility
- **Show Axes**: Toggle the coordinate axes visibility
- **Enable Shadows**: Toggle real-time shadows
- **Model Opacity**: Adjust the transparency of the model

## Technical Details

Built with:

- Three.js v0.162.0
- web-ifc v0.0.66
- TypeScript
- Vite

## License

AGPL-3.0
