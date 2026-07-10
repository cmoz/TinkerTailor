# 🧵 Tinker Tailor — Code, Libraries & Boards

Official code repository for **[Tinker Tailor](https://tinkertailor.ca)** — a Canadian shop for wearable electronics, hobby components, and one of the largest selections of **conductive fabrics** you'll find anywhere.

If you bought something from us that has a brain in it, the code lives here.

---

## 📦 What's in this repo

This repo supports the products we sell and the hardware we design. It's organized into three areas:

```
/libraries    Libraries we've written for products in the shop
/products     Example code, demos, and firmware for individual products
/boards       Firmware, schematics info, and examples for Tinker Tailor boards
```

**`/libraries`** — Drop-in libraries for components we carry, so you spend your time making instead of decoding datasheets. Each library includes install instructions for both PlatformIO and the Arduino IDE, plus at least one working example.

**`/products`** — Ready-to-flash example code for products in the shop: sensors, displays, LEDs, RFID modules, and soft-circuit materials. Each product folder links back to its shop page and includes wiring notes and pin tables.

**`/boards`** — Support files for boards designed by Tinker Tailor, including our upcoming ESP32-based board series. Firmware, pinout references, getting-started examples, and board definitions will land here as boards are released.

## 🚀 Getting started

**PlatformIO (recommended)**

```bash
git clone https://github.com/cmoz/TinkerTailor.git
```

Open the folder for your product or board in VS Code with the [PlatformIO extension](https://platformio.org/), plug in your board, and hit Upload.

**Arduino IDE**

Most examples also compile in the Arduino IDE. Open the sketch, install any libraries listed in that folder's README, select your board, and upload.

## ✨ Why conductive fabrics?

Soft circuits are our specialty. Many of the examples here show how to pair microcontrollers with conductive fabric and thread — capacitive touch on textiles, fabric switches, and sewn sensor techniques you won't find in a typical electronics tutorial. If you're new to e-textiles, the product folders are a great place to start.

## 🎥 Learn by building

Want to see these components in action? Our founder runs the **[CMozMaker YouTube channel](https://www.youtube.com/@CMozMaker)**, where many of these products get built into full wearable and fashion tech projects, step by step.

## 🛒 Get the parts

Everything supported in this repo is available at **[tinkertailor.ca](https://tinkertailor.ca)** — shipped from Nova Scotia, Canada. 🍁

## 🤝 Support & contributions

- **Something not compiling?** Open an issue with your board, IDE/PlatformIO version, and the full error message.
- **Improved an example or wrote a new one?** Pull requests are welcome.
- **Product questions?** Reach us through [tinkertailor.ca](https://tinkertailor.ca).

## 📜 License

Released under the [CC0-1.0 license](LICENSE) — free to use, remix, and build into your own work. If you make something with it, we'd love to see it.
