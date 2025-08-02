# HandoverSim



> **LEO-5GSim – Simplified 5G NTN Protocol Stack**
> Simulated user-to-satellite handovers and resource scheduling in Low Earth Orbit satellite-based 5G networks using NS-3 and 3GPP Release 17 standards.
---

## 📄 GitHub README Template

```markdown
# 🛰️ LEO-5GSim: Simplified 5G NTN Protocol Stack Simulation

A simulation framework built with NS-3 to model handover and scheduling in a Low Earth Orbit (LEO)-based Non-Terrestrial Network (NTN) for 5G communication, following 3GPP Release 17.

---

## 📌 Overview

LEO-5GSim demonstrates how user equipment (UE) connects to moving LEO satellites acting as gNBs (5G base stations), triggering dynamic handovers and resource scheduling based on satellite mobility and signal strength.

Key concepts:
- Handover due to satellite movement
- Simplified scheduler (round-robin or fair share)
- Performance evaluation: latency, throughput, and handover delay

---

## 🧱 Architecture

```

\[UE moving on Earth] ⇄ \[LEO Satellite 1] ⇄ \[5G Core (Simulated)]
⇄ \[LEO Satellite 2]
⇄ \[LEO Satellite 3]

````

- Satellites modeled as mobile base stations
- UE connects to nearest satellite using signal threshold
- Inter-satellite handovers based on RSSI and geometry

---

## 🛠️ Tech Stack

- **Simulator**: NS-3 (C++)
- **Modules Used**: LTE/NR, Mobility, Internet Stack
- **Visualization**: NetAnim (NS-3), Python (Matplotlib for graphs)
- **Specs Followed**: 3GPP TR 38.821 (NTN guidelines)

---

## 🧪 Key Features

- 🌐 Simulates NTN-based 5G radio access
- 🛰️ LEO satellite movement and orbit modeling
- 🔁 Dynamic UE-to-satellite handover based on signal degradation
- 📊 KPI monitoring: handover delay, packet loss, throughput
- 🎯 Basic scheduler implementation (e.g., round-robin)

---

## 📋 How to Run

1. **Install NS-3** (version >= 3.35)
2. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/leo-5gsim.git
   cd leo-5gsim
````

3. Build the project:

   ```bash
   ./waf configure
   ./waf build
   ```
4. Run the simulation:

   ```bash
   ./waf --run "leo-5g-sim"
   ```

---

## 📈 Results

| Metric           | Value (Sample)       |
| ---------------- | -------------------- |
| Handover Latency | 20–60 ms             |
| Avg Throughput   | 10–50 Mbps           |
| Packet Loss      | < 2% during handover |

---

## 📚 References

* 📖 3GPP TR 38.821 – Study on New Radio (NR) to support NTN
* 📘 NS-3 Documentation: [https://www.nsnam.org/docs/](https://www.nsnam.org/docs/)

---

## 🚀 Future Work

* AI-based handover prediction (mobility-aware)
* Inter-satellite communication and relaying
* Integration with real satellite TLE data (Celestrak)
* Power-aware or QoS-aware scheduling

---

## 📄 License

MIT License

---

Created by Abhinandan – UVCE, Bengaluru

```

