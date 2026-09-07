<div align="center">

# Calvin Yang

**Computer Science & Engineering @ UC Irvine**

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=9EE5D1&center=true&vCenter=true&width=600&lines=Two-stage+coil+gun+at+~11+m%2Fs;Python+physics+sim+validated+to+6e-14;ANSYS+Maxwell+to+Arduino+stage+timing;Embedded+systems+%7C+electromagnetics;Where+code+meets+hardware"/>

<br>

<a href="https://someheresy.github.io/"><img src="https://img.shields.io/badge/Portfolio-someheresy.github.io-9EE5D1?style=for-the-badge&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/calvinyang07/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://www.youtube.com/@SomeHeresyGaming"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
<a href="mailto:calviny7@uci.edu"><img src="https://img.shields.io/badge/Email-EDBA72?style=for-the-badge&logo=gmail&logoColor=1a1a1a"/></a>

</div>

---

## About

I build things where the software has to survive contact with real hardware — sensors that drift, timing that matters in milliseconds, and parts that have to physically line up.

The through-line is a two-stage electromagnetic accelerator I have been rebuilding since 2022, now on its third version. Getting it working meant learning electromagnetic simulation, CAD, fabrication, and embedded timing, because the problem refused to be solved by any one of them alone.

Most recently I wrote the physics simulator for it from scratch — a numerical model that explains *why* the hardware performs the way it does, and told me that nearly half the muzzle velocity was being lost to a coil effect I could not see on the bench.

Outside engineering I run a gaming channel that has passed **50,000 subscribers** and **150M views**, which has taught me more about shipping on a schedule and iterating against real feedback than any class has.

---

## Featured work

| Project | What it is | |
|---|---|---|
| **Electromagnetic Accelerator** | Two-stage coil gun, ~11 m/s with a 54.64 g projectile. Coil timing derived from ANSYS Maxwell 2D, switched through optocouplers by an Arduino. | [Code](https://github.com/SomeHeresy/Electromagnetic-Accelerator) · [Case study](https://someheresy.github.io/projects/electromagnetic-accelerator.html) |
| **Coilgun Timing Simulator** | Python physics engine coupling capacitor discharge to projectile motion through position-dependent inductance. Custom RK4 solver, energy conserved to 6e-14, 22 tests in CI. Found a 46.8% suckback loss on my own hardware. | [Code](https://github.com/SomeHeresy/Coilgun-Simulator) · [Case study](https://someheresy.github.io/projects/coilgun-simulator.html) |
| **EMCG Control** | Multi-sensor OLED interface over I²C — the first prototype of a control panel for the accelerator. | [Code](https://github.com/SomeHeresy/2026-summer-projects/tree/main/Arduino/Advanced) · [Case study](https://someheresy.github.io/projects/arduino-sensor-control.html) |
| **American Rocketry Challenge** | R&D and simulation lead for a seven-person team. Iterative OpenRocket analysis improved flight prediction accuracy by 23.2%; official score 139.8. | [Case study](https://someheresy.github.io/projects/american-rocketry-challenge.html) |
| **Portfolio site** | Built with AI to my own design direction and content — the code is Claude's, the look and the writing are mine. Static, no framework, no build step, zero dependencies. |  [Code](https://github.com/SomeHeresy/SomeHeresy.github.io) · [Live](https://someheresy.github.io/) |

> The portfolio site is the one item above I did not write the code for — it was built with AI from my design direction and my content. The hardware, firmware, and simulation work is mine.

---

## Currently building

- **Testing the simulator's prediction on real hardware** — it says moving the projectile 12 mm further back should gain ~37% muzzle velocity
- **Coil gun V4 on ESP32** — moving to interrupt-driven timing and closed-loop control, so stage 2 fires from *measured* projectile position instead of a fixed delay
- **Sharpening C and C++** ahead of embedded coursework
- Looking for **UCI project teams and undergraduate research** in embedded systems, power electronics, or robotics

---

## Toolbox

**Languages**

<img src="https://skillicons.dev/icons?i=c,cpp,java,python" />

**Development**

<img src="https://skillicons.dev/icons?i=arduino,vscode,git,github,html,css,js" />

**Engineering & design**

<p><img src="assets/ansys-maxwell.webp" height="48" alt="ANSYS Maxwell"/>&nbsp;&nbsp;&nbsp;<img src="assets/fusion360.webp" height="48" alt="Fusion 360"/>&nbsp;&nbsp;&nbsp;<img src="assets/openrocket.png" height="48" alt="OpenRocket"/>&nbsp;&nbsp;&nbsp;<img src="assets/easyEDA.jpg" height="48" alt="EasyEDA"/>&nbsp;&nbsp;&nbsp;<img src="assets/capcut.png" height="48" alt="CapCut"/></p>

---

## Goals for 2026

- Get coil gun V4 running closed-loop on ESP32
- Join an engineering project team at UCI
- Land undergraduate research in embedded systems or power electronics
- Reach 100,000 subscribers

---

<div align="center">

**Open to internships, research, and project teams** — embedded systems, electronics, firmware, simulation.

[someheresy.github.io](https://someheresy.github.io/) · [calviny7@uci.edu](mailto:calviny7@uci.edu)

</div>
