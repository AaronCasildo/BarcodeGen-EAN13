# 🏷️ Barcode Generator

> A simple and powerful desktop application for batch generating EAN-13 barcodes with a graphical interface.

![Python Version](https://img.shields.io/badge/python-3.7%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)

---

## Features

- **Batch Generation**: Create hundreds of barcodes in seconds
- **PNG Format**: High-quality images ready for printing
- **Auto-Organization**: Automatic timestamped folders for each batch
- **Real-Time Progress**: Visual progress bar during generation
- **Auto-Open**: Automatically opens the destination folder upon completion
- **EAN-13 Standard**: Industry-standard barcode format with automatic check digit

---

## Main Interface
<img width="300" alt="image" src="https://github.com/user-attachments/assets/d8022a8b-8201-4a5f-a08d-a9b44ae7bbef" />

## Generated Barcodes
<img width="300" alt="Code_008" src="https://github.com/user-attachments/assets/ef80aa63-b851-42de-9277-f37b4bafb7da" />

---


## ⚙️ Configuration

The application maintains internal settings for:
- Number of barcodes to generate
- Destination folder path

Settings are per-session (do not persist between runs).

### 📂 Output Structure

Generated barcodes are organized in timestamped folders:

```
Selected_Folder/
└── Barcodes_2025-10-01_14-30-45/
    ├── Code_001.png
    ├── Code_002.png
    ├── Code_003.png
    └── ...
```
---

## Use Cases

- **Retail**: Generate product barcodes for inventory
- **Events**: Create unique barcodes for tickets
- **Asset Management**: Label company equipment
- **Warehousing**: Track items and locations
- **Testing**: Generate sample barcodes for development


---

## Ideas for Future Development

- Add different barcode formats (QR, Code128, etc.)
- Implement custom code number ranges
- Add CSV export with code numbers
- Create batch printing functionality
- Add barcode customization options (colors, sizes)

---

## Acknowledgments

This project uses the [python-barcode](https://github.com/WhyNotHugo/python-barcode) library, created and maintained by **Hugo Osvaldo Barrera ([@WhyNotHugo](https://github.com/WhyNotHugo))**.

---

<div align="center">

**⭐ If you find this project useful, consider giving it a star! ⭐**

</div>
