AOG Drawing Pad
A professional, iPad-optimized drawing application designed for site documentation and technical sketches. Built with vanilla JavaScript and Canvas API.

Features
Drawing Tools
Pen - Freehand drawing with smooth curves
Line - Straight lines with snapping support
Arrow - Directional lines with arrowheads
Rectangle - Customizable rectangles with fill options
Circle - Ellipses and circles
Text - Multi-line text with custom fonts and sizes
Measure - Distance measurement tool with unit conversion
Eraser - Remove drawn elements
Advanced Features
Symbol Library - Electrical, gas, and site symbols (generators, transfer switches, propane tanks, etc.)
Color Picker - Full color selection for stroke and fill
Stroke Width Control - Three preset widths (thin, normal, thick)
Grid & Snap - Optional grid display with snap-to-grid drawing
Zoom & Pan - Mouse wheel zoom and middle-button panning
Undo/Redo - Full drawing history (50-level stack)
Object Selection - Select, move, duplicate, copy/paste objects
Layer Control - Bring to front/send to back
Opacity Control - Adjust transparency for all drawing elements
Export Options
PNG Export - High-resolution raster image
PDF Export - Print-friendly document format
Mobile Features
iPad Optimized - Touch-friendly interface with multi-touch support
Pinch to Zoom - Two-finger pinch zoom gesture
Two-Finger Pan - Multi-touch panning
Long-Press Menu - Context menu for object operations
Auto-Save - Automatic saving every 10 seconds
Safe Area Support - Notch-safe layout for modern devices
UI Features
Dark/Light Mode - System preference detection with manual toggle
Collapsible Toolbar - Hide toolbar to maximize canvas space
Status Bar - Real-time coordinates, zoom level, object count
Responsive Design - Works on tablets, mobile, and desktop
Keyboard Shortcuts - Full keyboard support for all tools
Keyboard Shortcuts
Tools



Key	Tool
V	Select
P	Pen
L	Line
A	Arrow
R	Rectangle
C	Circle
T	Text
M	Measure
E	Eraser
Edit



Shortcut	Action
Ctrl+Z	Undo
Ctrl+Y / Ctrl+Shift+Z	Redo
Ctrl+C	Copy
Ctrl+V	Paste
Delete	Delete selected
Escape	Deselect
View



Shortcut	Action
+/-	Zoom in/out
Alt+Drag	Pan canvas
G	Toggle grid
S	Toggle snap
?	Help menu
Usage
Getting Started
Select a tool from the toolbar (or use keyboard shortcuts)
Click and drag on the canvas to draw
Use the color swatches to change stroke/fill colors
Adjust stroke width using the width buttons
Use the measure tool to document distances
iPad Tips
Pinch with two fingers to zoom
Drag with two fingers to pan
Long-press on objects to access context menu
Drag object corners to resize shapes
Drawings auto-save every 10 seconds to browser storage
Symbols
Click the ⚡ Symbols button or press the tool icon
Browse categories or search by name
Select a symbol to place it on canvas
Choose a color from the color panel
Click to place the symbol
Technical Details
Technology Stack
HTML5 Canvas - Rendering engine
Vanilla JavaScript - No framework dependencies
LocalStorage - Persistent saving
CSS Grid/Flexbox - Responsive layout
Google Fonts - Orbitron, Share Tech Mono, Exo 2
Browser Support
Chrome/Edge 90+
Firefox 88+
Safari 14+
iOS Safari (iPad)
Android Chrome
Performance
Optimized canvas rendering
Efficient redraw system
Touch event debouncing
Memory-safe undo/redo with 50-item limit
File Structure


index.html          # Complete single-file application
├── HTML           # Semantic markup
├── CSS            # Responsive styling with dark mode
└── JavaScript     # Application logic
    ├── State management
    ├── Canvas rendering
    ├── Touch/pointer events
    ├── Drawing tools
    ├── UI controls
    └── Export/save functions
Storage
Theme preference - Saved to localStorage
Toolbar state - Saved to localStorage
Drawing data - Auto-saves to localStorage every 10 seconds
Maximum size - ~4MB per drawing (browser dependent)
Customization
Colors
Edit CSS variables in :root and body.dark-mode:

css


--cyan: #D97706;        /* Primary accent */
--text: #1F2937;        /* Text color */
--bg: #FFFFFF;          /* Background */
--canvas-bg: #ffffff;   /* Canvas background */
Grid
gridSize = 20 - Modify grid spacing
Toggle grid with G key
Symbols
Edit the SYMBOLS array in JavaScript to add custom symbols:

javascript


{ 
  cat: 'Category', 
  name: 'Symbol Name', 
  draw: (ctx, w, h) => { /* Canvas drawing code */ } 
}
Known Limitations
Single drawing per session (no multi-document support)
Symbol image data increases file size
Grid snapping only available in grid mode
Text input limited to single textarea element
Bitmap export only (no vector format)
Future Enhancements
 Vector export (SVG)
 Multi-page support
 Collaborative drawing
 Shape templates library
 Advanced text formatting
 Layer panel
 Drawing history viewer
 Cloud sync
License
© Always On Generators - All rights reserved

Support
For issues, feature requests, or feedback, please contact the Always On Generators development team.

Built for professionals. Optimized for iPad. Simple to use.
