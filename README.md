# Parallel PDF Viewer
A web-based tool for comparing two PDF documents side-by-side with multiple navigation options.
## Features
- **Dual PDF Viewing**: Display two PDFs simultaneously in split-screen
- **Multiple Navigation Modes**:
  - Synchronized scrolling (1:1 page correlation)
  - Direct page number input with validation
  - Keyboard navigation (Enter to jump)
- **Interactive Controls**:
  - Real-time page number display with input fields
  - Toggle synchronization on/off
  - Zoom controls (+/- buttons)
- **Smart Rendering**:
  - High-resolution rendering with PDF.js
  - Progressive loading for better performance
  - Automatic page range calculation
- **Responsive Design**: Works on desktop and tablets
## How to Use
1. Open the https://github.com/Aaron-Z-Y/parallel-pdf-viewer
2. Upload PDFs using "Choose Left PDF" and "Choose Right PDF" buttons
3. Navigate using:
   - Scroll wheel/trackpad for page-by-page viewing
   - Type page numbers in input fields + press Enter
   - Arrow keys while focused on input fields
4. Adjust view with:
   - Zoom buttons (+/-) for resolution changes
   - Sync toggle to enable/disable coordinated scrolling
   - Window resize for layout adjustments
## Technical Enhancements
- **Page Tracking System**:
  - Real-time scroll position monitoring
  - Input-field synchronized navigation
  - Cross-browser input validation
- **Performance Optimizations**:
  - Debounced scroll events
  - Cached page positions
  - Smart re-rendering
- **UI Features**:
  - Input constraints (min/max page numbers)
  - Total page counter updates
  - Active element detection for input sync
## Installation
End users: Simply open `index.html` in a modern browser.
Developers:
```bash
git clone https://github.com/Aaron-Z-Y/parallel-pdf-viewer.git
cd parallel-pdf-viewer
# Start local server (optional)
python -m http.server 8000
# Open http://localhost:8000 in browser

