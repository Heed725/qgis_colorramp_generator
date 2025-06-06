# QGIS Color Ramp Generator

![Version](https://img.shields.io/badge/version-4.0-blue.svg)

The **QGIS Color Ramp Generator** is a web-based tool designed to help GIS professionals, cartographers, and data visualization specialists easily create and export custom color ramps for use in [QGIS](https://qgis.org). It supports creating multiple color ramps with visual previews, tagging, validation, and exporting to the QGIS-compatible `.xml` style format.

---

## 🌐 Access the Tool

🔗 **Launch the app here**: [https://qgis-colorramp-generator-v4.netlify.app/](https://qgis-colorramp-generator-v4.netlify.app/)

---

## 🌟 Features

- 🎨 Add up to 10 custom color ramps.
- 💡 Visual preview of color codes as swatches.
- ✅ Real-time hex color code validation.
- 🏷️ Add custom names and tags to each ramp.
- 📁 Export all ramps to a QGIS `.xml` style file.
- 📝 Set a general name for the exported XML file.
- ❌ Easily delete unwanted ramps before export.

---

## 🚀 Getting Started

1. Visit [https://qgis-colorramp-generator-v4.netlify.app/](https://qgis-colorramp-generator-v4.netlify.app/)
2. Enter a name for the XML file (optional).
3. Click **"Add Ramp"** to create a new color ramp.
4. Input comma-separated hex color codes (e.g. `#FF0000, #00FF00, #0000FF`).
5. Assign each ramp a name and tags.
6. Click **"Generate XML"** to download your file.

> 💡 Tip: Valid hex codes must be 3 or 6 digits, beginning with `#`. Invalid codes will be flagged visually.

---

## 🧰 Use Cases

Use this generator to create classified color schemes for:
- Land use or land cover maps
- Elevation models
- Soil or vegetation indexes
- Thematic GIS data layers

### How to use in QGIS:

Import the `.xml` file via:  
**Settings → Style Manager → Import/Export → Import from XML**

---

## 📂 Output Format

The tool generates a QGIS-compliant XML file including:
- Color stops as `preset_color_X`
- Optional color names
- Tags and metadata
- Support for QGIS 3.x+

---

## 🤝 Contributing

We welcome contributions!

1. Fork this repo
2. Create a feature branch
3. Push your changes
4. Open a pull request

---

## 🙋 Maintainers

This tool is maintained by the **QGIS Color Ramp Generator** team.  
Feel free to reach out or open an issue if you have feedback or feature requests.
