# parallel-pdf-viewer
An web based project display 2 PDFs in a split window with synchronized scrolling

This is a web-based tool for comparing two PDF documents side-by-side with synchronized page-by-page scrolling.

## Features

- View two PDFs simultaneously in a split-screen interface
- Synchronized page-by-page scrolling (1:1 page correlation)
- High-resolution rendering with zoom controls
- Toggle synchronization on/off
- Responsive design works on desktop and tablets
- No server required - works entirely in the browser

## How to Use

1. Open the https://github.com/Aaron-Z-Y/parallel-pdf-viewer
2. Click "Choose Left PDF" and "Choose Right PDF" to upload documents
3. Scroll using mouse wheel/trackpad - both PDFs will advance pages together
4. Use the zoom buttons (+/-) to adjust viewing resolution
5. Toggle sync button to enable/disable synchronized scrolling

## Technical Details

- Built with PDF.js (Mozilla's PDF rendering library)
- Pure client-side JavaScript - no server processing
- Page-based synchronization algorithm
- High-DPI display support

## Installation

No installation needed for end users - just open the HTML file in a modern browser.

For developers:

```bash
git clone https://github.com/Aaron-Z-Y/parallel-pdf-viewer.git
cd parallel-pdf-viewer
# Open index.html in your browser
