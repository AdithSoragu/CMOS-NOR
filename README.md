# ⚡ CMOS NOR Gate Design using Cadence Virtuoso

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Cadence%20Virtuoso-blue">
  <img src="https://img.shields.io/badge/Technology-CMOS-orange">
  <img src="https://img.shields.io/badge/Simulation-Transient-success">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen">
</p>

---

# 📌 Project Overview

This project demonstrates the design and simulation of a **CMOS NOR Gate** using **Cadence Virtuoso**.

The NOR gate was implemented using:
- PMOS transistors
- NMOS transistors
- CMOS logic design principles

The circuit was designed at transistor level and verified using transient analysis in Cadence Virtuoso Analog Design Environment (ADE).

The project focuses on:
- CMOS digital logic design
- Schematic implementation
- Transient simulation
- Waveform analysis
- VLSI design fundamentals

---

# 🎯 Objectives

The major objectives of this project are:

- Design a CMOS NOR gate at transistor level
- Understand CMOS logic operation
- Implement PMOS and NMOS transistor networks
- Simulate logic behavior using Cadence Virtuoso
- Verify output waveform using transient analysis
- Learn VLSI schematic design workflow

---

# 🧠 Introduction to CMOS NOR Gate

A NOR gate is a universal digital logic gate whose output becomes HIGH only when all inputs are LOW.

---

# 📖 NOR Gate Truth Table

| Input A | Input B | Output Y |
|---------|---------|----------|
| 0 | 0 | 1 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 0 |

---

# 🏗️ CMOS NOR Gate Architecture

The CMOS NOR gate consists of:
- Two PMOS transistors connected in series
- Two NMOS transistors connected in parallel

---

# 📌 PMOS Network

The PMOS pull-up network connects:
- Output to VDD

The output becomes HIGH only when:
```text
A = 0 and B = 0
```

---

# 📌 NMOS Network

The NMOS pull-down network connects:
- Output to Ground (VSS)

If any input becomes HIGH:
```text
A = 1 or B = 1
```

the output becomes LOW.

---

# 📂 Project Structure

```text
CMOS_NOR_Gate/
│
├── NOR_schematic.png         # CMOS NOR Schematic
├── testbench.png             # Testbench Circuit
├── waveform_output.png       # Simulation Waveforms
├── cadence_files/            # Cadence Project Files
└── README.md                 # Documentation
```

---

# ⚙️ Software and Tools Used

| Tool | Purpose |
|------|----------|
| Cadence Virtuoso | Schematic Design |
| ADE L | Simulation |
| Spectre Simulator | Transient Analysis |

---

# 🛠️ Technologies Used

- CMOS Technology
- VLSI Design
- Digital Electronics
- Analog Simulation

---

# 📌 Circuit Components

| Component | Function |
|-----------|-----------|
| PMOS Transistors | Pull-Up Network |
| NMOS Transistors | Pull-Down Network |
| VDD Source | Power Supply |
| Ground (VSS) | Reference Ground |
| Pulse Voltage Sources | Input Signals |
| Capacitor | Output Load |

---

# 🔄 Working Principle

The CMOS NOR gate operates based on CMOS pull-up and pull-down transistor networks.

---

# 📌 Case 1: A = 0, B = 0

- PMOS transistors turn ON
- NMOS transistors turn OFF
- Output connects to VDD

```text
Output = 1
```

---

# 📌 Case 2: A = 1, B = 0

- One NMOS transistor turns ON
- Output connects to Ground

```text
Output = 0
```

---

# 📌 Case 3: A = 0, B = 1

- One NMOS transistor turns ON
- Output becomes LOW

```text
Output = 0
```

---

# 📌 Case 4: A = 1, B = 1

- Both NMOS transistors turn ON
- Strong pull-down path created

```text
Output = 0
```

---

# 🧩 Schematic Design

The CMOS NOR schematic was designed using:
- PMOS transistor series connection
- NMOS transistor parallel connection

The design includes:
- VDD connection
- VSS grounding
- Input terminals A and B
- Output terminal VOUT

---

# 🧪 Testbench Design

The testbench includes:
- Pulse voltage sources for inputs
- Power supply source
- Capacitive load
- Output measurement node

The transient simulation verifies the logic functionality of the NOR gate.

---

# 📊 Simulation Analysis

Transient analysis was performed using:
```text
ADE L + Spectre Simulator
```

The waveform verifies:
- Correct NOR logic operation
- Proper output transitions
- CMOS switching behavior

---

# 📈 Waveform Observation

The simulation waveform shows:
- Input A waveform
- Input B waveform
- Output VOUT waveform

The output remains HIGH only when:
```text
A = 0 and B = 0
```

which confirms correct NOR gate functionality.

---

# ⚡ Advantages of CMOS NOR Design

- Low power consumption
- High noise immunity
- Compact transistor implementation
- Reliable switching operation
- Suitable for VLSI applications

---

# 🚀 Applications

CMOS NOR gates are widely used in:

- Digital Logic Circuits
- VLSI Systems
- Memory Design
- Arithmetic Circuits
- Embedded Systems
- Microprocessors
- Logic Controllers

---

# 📚 Learning Outcomes

Through this project, the following concepts were learned:

- CMOS Logic Design
- PMOS/NMOS Operation
- Cadence Virtuoso Usage
- Transistor-Level Schematic Design
- Transient Simulation
- Waveform Analysis
- VLSI Design Fundamentals

---

# 🔮 Future Enhancements

The project can be extended by adding:

- Layout Design
- DRC and LVS Verification
- Power Analysis
- Delay Analysis
- Multi-input NOR Gate Design
- CMOS NAND/NOR Combination Circuits

---

# 👨‍💻 Author

## Adith Soragu

Electronics and Communication Engineering

---

# ⭐ GitHub Repository

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is developed for educational and learning purposes only.
