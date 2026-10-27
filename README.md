# PIC18 Solar-Panel Tracker

Embedded controller that continuously orients a solar panel toward the brightest light source using **LDR** sensors, a PWM-driven servo, and wind-speed protection.

## Highlights
- **Adaptive algorithm** - real-time light balance and wind-threshold shutdown.
- **Low-power design** - sleeps between adjustments.
- **Full schematics & notes** in `docs/Documento_Tecnico_Panel_Solar_PIC18F45K22.pdf`.

## Getting started
```bash
git clone https://github.com/Alexis-c-d/pic18-solar-tracker.git
cd pic18-solar-tracker/src
# Add your hardware config, then build with MPLAB X.
```

🗂️ **Docs** - technical sheet in `docs/Documento_Tecnico_Panel_Solar_PIC18F45K22.pdf`.

---

## Repository layout
```
pic18-solar-tracker/
├─ src/        # Source files
├─ sim/        # Proteus project
└─ docs/       # Documento_Tecnico_Panel_Solar_PIC18F45K22.pdf
```

## License
MIT - feel free to use or adapt for your own renewable energy projects.
