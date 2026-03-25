# VGA Font Viewer

A simple web app for testing monochrome bitmap fonts and exporting them to VHDL format.

## Features

- Load 8x16 bitmap fonts from a BMP file
- Display custom text using the loaded font
- Export font data in VHDL-compatible format

## Usage

1. Place your `font.bmp` file (16x16 grid of 8x16 characters) in the same directory
2. Start a local web server:
   ```bash
   python -m http.server
   ```
3. Open `http://localhost:8000` in your browser
4. Enter text to display and view the rendered output
5. Copy the VHDL font data from the text area as needed

## Font Format

The font bitmap should be a 16x16 grid containing 256 characters, each 8x16 pixels.
