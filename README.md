# 🚢 Ship Circuit

**ShipCircuit** is a circuit that has two functions, the first is to control an LED with a potentiometer, while the second is to turn on the LEDs only when the button is pressed.

I built the welding project for Hack Club. (https://github.com/hackclub/solder)!

---

## ✨ What It Does

The circuit has one LED controlled by a potentiometer while the other 3 LEDs are controlled by a push button.

---

## 📦 Bill of Materials

| Component         | Quantity | Notes                             |
|------------------|----------|-----------------------------------|
| Potentiometer                 | 1 | Vary current                    |
| Battery Cell                  | 1 | Power                           |
| 220Ω Resistor                 | 3 | Reduce current                  |
| 10µF Electrolytic Capacitor   | 1 | Debounces fast flickers         |
| 5mm LED                       | 4 | Light output                    |
| PCB / Breadboard              | 1 | Custom-designed PCB             |
| Switch Push                   | 1 | current step                    |

---

## 📐 Circuit Design

### 🧠 Schematic
![Captura de pantalla 2025-06-29 222519](https://github.com/user-attachments/assets/c8f4940d-001e-4369-88df-6d17ecb30e32)


### 🧩 PCB Layout

![Captura de pantalla 2025-06-29 223534](https://github.com/user-attachments/assets/14d99f1e-0628-42b3-a9da-41f2cc3714e6)


### 🔭 3D View 1
![Captura de pantalla 2025-06-29 223310](https://github.com/user-attachments/assets/fa944eb1-f1b7-4e2a-83ba-da76c36d46eb)


### 🔬 3D View 2
![Captura de pantalla 2025-06-29 223439](https://github.com/user-attachments/assets/be3012a8-9b90-4b0a-9a0d-e45183cb9609)


### 3D View Back
![Captura de pantalla 2025-06-29 223458](https://github.com/user-attachments/assets/076d7c36-d96b-4a2b-a048-9d3e516ddca6)


> All files live in the `kicad/` and `gerbers/` folders.

---

## 🛠️ Files in This Repo

```

ShipCircuit/
├── kicad/         → KiCad project
├── gerbers/       → Gerber + drill files (for fabrication)
├── images/          → Screenshots: schematic, PCB, 3D views
└── README.md      → You’re here!

```

---

## 🧪 Testing It

Power the circuit using a coin cell.  
Then:
- ✅ Increase or decrease the signal from the potentiometer to the LED.
- ✅ Press the button to turn on all 3 LEDs.

---

## 🙋 Slack Username

Ivan P

SLACK ID: T0266FRGM

---

## 🚀 Why I Made This

Because I had never tried kiCad before and I thought it would be a wonderful idea to be able to learn and create something while being in an environment surrounded by hackers.

---

Built for [Hack Club Solder](https://github.com/hackclub/solder) 💚
