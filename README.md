# 🧾 ScanBon – Simple Android App for Receipt Management

**ScanBon** is a lightweight Android application designed for small shops and personal use. It allows users to:

- 📷 Scan products using barcodes  
- 🧾 Generate and save receipts locally  
- 📦 View, add, and delete products from a local database  
- 📂 Browse receipt history  

The app offers a fast and intuitive way to manage simple point-of-sale operations using only your phone.

---

## 🔧 Built With

- [Jetpack Compose](https://developer.android.com/jetpack/compose) – modern declarative UI toolkit  
- [CameraX](https://developer.android.com/training/camerax) + [ML Kit Barcode Scanning](https://developers.google.com/ml-kit/vision/barcode-scanning)  
- [GSON](https://github.com/google/gson) – to handle JSON serialization  
- [Material 3](https://m3.material.io/) – for clean UI and UX

---

## 📁 Project Structure

- `MainScreen.kt` – Main navigation screen  
- `GenereazaBonActivity.kt` – Receipt generation logic  
- `ScannerActivity.kt` – Handles barcode scanning  
- `AdaugaProdusActivity.kt` – Add new products manually  
- `SelectProdusActivity.kt` – Select product when scan fails  
- `VeziBonActivity.kt` – Display saved receipts  
- `produse.json` – Local product storage (JSON)

---

## ✅ Status

📱 Fully functional  
✅ Works offline  
📦 Tested on Android 8.0+ (API 24+)

---

## 📸 Screenshots

> *(Add screenshots here if available to showcase the UI)*

---

## 📤 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/ScanBon.git
