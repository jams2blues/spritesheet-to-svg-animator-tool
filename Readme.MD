Spritesheet to SVG Animator Tool - v2.0
=======================================

Summary:
--------
The Spritesheet to SVG Animator Tool v2.0 is a production-ready, browser-based solution designed for on‑chain NFT artists. It converts sprite sheets (PNG files) into animated SVG files. The tool features three distinct input methods—JSON file input, manual input, and a fully interactive Custom JSON Builder modal with granular per‑frame controls (positions and durations). The tool automatically detects and calculates the optimal grid layout (stacked, horizontal, or vertical) based on the sprite sheet dimensions and the specified number of frames, ensuring a precise square-packed animation by default.

Key Features:
-------------
• Input Methods:
  - **JSON File Input:** Upload a sprite sheet PNG along with an Aseprite-exported JSON file to automatically extract frame data. The tool also deduplicates frames to avoid blank entries.
  - **Manual Inputs:** Define the number of frames, frame dimensions, and custom frame durations.
  - **Custom JSON Builder:** An interactive modal that lets you manually adjust each frame’s properties (x, y, width, height, duration) with an immediate live preview.
  
• Automatic Layout Calculation:
  - For “stacked” layouts, the tool calculates a grid (e.g., a square) that evenly packs the frames based on the input file dimensions.
  - It supports horizontal and vertical layouts as needed.

• Live Animation Preview:
  - Generates a native SVG animation using the `<animate>` tag.
  - The preview updates in real time based on input changes.
  - Ensures compatibility with modern browsers, including Apple devices.

• Output Options:
  - Copy the generated SVG code to the clipboard.
  - Download the animated SVG file.
  - Retrieve a Data URI for embedding into on‑chain NFT projects.

Usage:
------
1. **Select Input Method:** Choose between JSON File, Manual Inputs, or Custom JSON Builder.
2. **Upload Files/Enter Data:** Depending on the chosen method, upload your sprite sheet PNG (and optionally an Aseprite JSON file) or define the frame properties manually.
3. **Adjust Animation Settings:** Set scaling options (pixelated or smooth), layout (horizontal, vertical, stacked), loop count, total animation duration, and compression level.
4. **Generate & Preview:** Click “Generate SVG” to view the live animation preview. The output can then be copied, downloaded, or used as a Data URI.

Installation & Compatibility:
-------------------------------
- This tool is implemented as a standalone HTML file with all necessary inline scripts (including minified versions of omggif, pako, and UPNG).
- It is optimized for cross-browser compatibility (Chrome, Firefox, Safari, Edge) and works well on mobile and Apple devices.
- Ideal for embedding in websites or integrating with on‑chain NFT projects.

Contributing:
-------------
- Contributions are welcome! Fork the repository, implement improvements or fixes, and submit a pull request.
- Please ensure your contributions maintain compatibility with modern web standards and the tool’s performance optimizations.

License:
--------
Developed with love for the Tezos community. Please see the LICENSE file for details.
