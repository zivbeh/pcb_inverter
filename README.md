## Converter Topology

This board uses two compact inverting converters:
- One channel generates **-5V**
- One channel generates **-15V**

Each converter requires:
- Proper **input decoupling**
- Proper **flying/switching capacitors**
- Proper **output capacitors**

## Final Board Size:
-- 22.6mm x 13.4mm

<img width="1085" height="646" alt="image" src="https://github.com/user-attachments/assets/4e0c0998-8c8e-47b4-9a2d-ca49dbcc7ce9" />

---

## I/O Pinout

### Input (Power In)
- **+5V** — feeds the -5V converter
- **+15V** — feeds the -15V converter
- **GND** — common ground reference

### Output (Power Out)
- **-5V**
- **-15V**
- **GND**

---

## Constraints

### Electrical
- **Inputs:** +5V, +15V, GND
- **Outputs:** -5V, -15V
- **Target load:** up to ~**100 mA**
- **Goal:** stable rails for analog/mixed-signal (low droop, reasonable ripple with proper caps/layout)
- **Simple build:** minimal parts, easy assembly

### Mechanical
- **Board size:** **≤ 26 mm × 16 mm**
- **I/O:** large pads for power in/out (hand wiring friendly)

---

## Datasheets

- LTC3261 datasheet (:contentReference[oaicite:0]{index=0}):  
  https://www.analog.com/media/en/technical-documentation/data-sheets/3261fb.pdf

- LM27761 datasheet (:contentReference[oaicite:1]{index=1}):  
  https://www.ti.com/lit/ds/symlink/lm27761.pdf?utm_source=chatgpt.com

---

## License
Choose one:
- **MIT**

---

## Credits
Designed for the 3D Ultrasound image reconstruction PCB at the **Liwei Lin Lab** by **Ziv Behar**.
