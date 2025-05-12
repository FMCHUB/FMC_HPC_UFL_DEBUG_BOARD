# FMC_HPC_UFL_DEBUG_BOARD
FMC HPC Debug Board with 156 U.FL Breakouts and SMA Probing – Open Hardware

# FMC HPC U.FL Debug Board

A flexible breakout and debugging platform for High-Pin Count (HPC) FPGA Mezzanine Cards (FMC).  
Provides 156 signal connections via U.FL connectors, plus SMA and clamp probing options for signal measurement and testing.

📄 [**View Online Datasheet**](https://fmchub.github.io/projects/FMC_HPC_UFL_DEBUG_BOARD/Datasheet/FMC_HPC_UFL_DEBUG_BOARD_datasheet.html)

---

## 🔧 Features

- FMC HPC (VITA 57.1) compatible connector
- 156 signals broken out to U.FL connectors
- 68 LA (LPC) + 48 HA (HPC) + 8 CLK + 16 MGT differential signals
- 8 SMA connectors for high-speed probing
- 8 clamp connectors for low-speed oscilloscope probing
- Breakout of power pins, JTAG, and I²C (solderable pin headers)
- Stackable mechanical assembly with standoff mounting holes
- Open-source hardware

---

## 📚 Documentation

| Resource | Link |
|----------|------|
| Datasheet | [HTML Version](https://fmchub.github.io/projects/FMC_HPC_UFL_DEBUG_BOARD/Datasheet/FMC_HPC_UFL_DEBUG_BOARD_datasheet.html) |
| Schematics | `/Drawings/T0017_HPC_UFL_DEBUG_BOARD_SCHEMATICS_2024_12_13_REV_A.pdf` |
| PCB Layers | `/Drawings/T0017_HPC_UFL_DEBUG_BOARD_LAYERS_2024_12_13_REV_A.pdf` |
| Mechanical Drawings | `/Drawings/T0017_HPC_UFL_DEBUG_BOARD_MECHANICAL_2024_12_13_REV_A.pdf` |
| Bill of Materials | `/BOM.csv` |

---

## 🛠️ Assembly & Usage Notes

- Board exceeds FMC single-width outline → check mechanical clearance in your setup.
- Use spacers or standoffs to prevent mechanical stress.
- For JTAG/I²C use, solder standard 2.54 mm pin headers to breakout pads.
- SMA and U.FL connectors are intended for signal probing. Ensure correct termination.

---

## ⚠️ Warnings

- **Incorrect loopback or interconnects can damage connected hardware**. Always verify voltage levels and signal directions before making U.FL cable connections.
- Clamp connectors are suitable for low-frequency probing only.

---

## 💡 Applications

- FMC-based FPGA system debugging
- Signal probing (low-speed and high-speed)
- Loopback and interconnect test setups
- Educational FPGA labs and research environments

---

## 📘 License

This project is licensed under the **Do What The Fuck You Want To Public License (WTFPL)**.

> See [`LICENSE`](./COPYING) for full text.

---

## ✉️ Contact

Feedback and contributions welcome via GitHub Issues or Pull Requests.

