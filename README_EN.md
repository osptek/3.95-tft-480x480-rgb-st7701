# 3.95" 480×480 TFT RGB module (ST7701) — documentation & samples

**简体中文：** [`README.md`](README.md)

---

> This repository provides an **ESP-IDF sample** (RGB + LVGL9). Datasheets and specifications will be added to `docs/` when available.

## Product overview

| Item | Description |
|:--|:--|
| Module | 3.95-inch **TFT** panel, **480×480** resolution |
| Interface | **RGB** (16-bit; panel init over 3-wire SPI) |
| Driver IC | **ST7701** |
| Spec ID | **`3.95-tft-480x480-rgb-st7701`** is the common product designation in documentation |
| MIPI variant | Same size **ST7102 MIPI** is in **`3.95-tft-480x480-mipi-st7102`** — different interface, separate repo |

---

## Repository layout

### Top-level

| Path | Contents |
|:--|:--|
| `docs/` | Datasheets and specifications (**to be added**) |
| `examples/` | **Sample projects** |

### `examples/` layout

| Location | Description |
|:--|:--|
| `examples/` root | ESP32-S3 + IDF5; ST7701 RGB + LVGL9; optional FT5x06 touch via menuconfig |

### Sample project paths

| Description | Path |
|:--|:--|
| ST7701 RGB + LVGL9 | `examples/esp32s3-idf5_st7701-rgb_lvgl9/` |
