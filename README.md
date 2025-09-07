# SVG Stroke to Fill Converter

A simple tool to convert stroke-based SVG icons to fill-based SVG icons using oslllo-svg-fixer.

## Getting Started

Follow these steps to convert your stroke-based SVG icons to fill-based icons:

### Prerequisites

Make sure you have Node.js and Yarn installed on your system.

### Installation

1. Install dependencies:

   ```bash
   yarn
   ```

### Usage

2. Create a folder named `stroke-based-icons` in the project root and place your stroke-based SVG icons inside it.

3. Run the conversion command:

   ```bash
   yarn fix
   ```

4. After the command completes, a new folder named `fixed-svgs` will be created containing your converted fill-based SVG icons.

## Documentation

For more detailed information about the SVG fixer tool, please visit: https://docs-oslllo-com.onrender.com/svg-fixer/master/#/

## Project Structure

```
project-root/
├── stroke-based-icons/     # Input folder for stroke-based SVG icons
├── fixed-svgs/            # Output folder for converted fill-based SVG icons (auto-generated)
├── package.json
└── README.md
```
