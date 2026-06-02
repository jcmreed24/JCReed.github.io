<h1 style="text-align: center; font-size: 4rem; margin-bottom: 0.5rem;">
Embedded Systems Human Machine Interface (HMI)
</h1>

![HMI Project Image](static/images/JC Reed - Final Subsystem.jpg){ style="display: block; margin: 1rem auto 2rem auto; width: 85%; max-width: 900px; border-radius: 16px;" }

<div style="max-width: 900px; margin: auto;">

<h2 style="margin-top: 1.5rem;">Embedded Systems Design Project</h2>

<strong>Arizona State University Polytechnic</strong><br>
<strong>Course:</strong> Embedded Systems Design (EGR 314)

<p>
Designed and implemented a complete Human Machine Interface (HMI) subsystem for an educational STEM exhibit known as the Element Sorter. The HMI served as the primary user interaction point, allowing users to classify chemical elements while communicating decisions to other embedded subsystems through a custom UART protocol.
</p>

<p>
The project required full-stack embedded development including PCB design, schematic capture, firmware development, serial communication architecture, power system design, component selection, and CAD integration.
</p>

</div>

---

## Demonstration Video
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 12px; margin-bottom: 2rem;">
<iframe src="https://www.youtube.com/embed/n4pkgeSHHNY?si=4GZxvWbXj-kQadvP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
</iframe>
</div>

---

## System Architecture

![Block Diagram](static/images/BlockDiagram.png)

The HMI served as the front-end controller for a larger multi-device embedded system consisting of an RGB sensor, MQTT communication node, actuator subsystem, and user interface. The ESP32-S3 communicated through UART while simultaneously managing user inputs and an OLED display through GPIO and I2C interfaces.

---

## Key Engineering Contributions

### Embedded Firmware Development
Developed a MicroPython-based application utilizing asynchronous task scheduling, state-machine architecture, and serial communication handling. The software managed user interaction, display updates, message validation, and subsystem communication while maintaining responsive operation.

### Schematic, PCB, and Hardware Design
![Schematic](static/images/HMI-Schematic.png)

Individually designed a custom PCB incorporating an ESP32-S3 microcontroller, power regulation circuitry, UART communication headers, OLED display connectivity, and user input hardware. The board was manufactured, assembled, and successfully integrated into the final system.

### System Integration

Designed and implemented a custom UART messaging protocol that enabled reliable communication between independently developed subsystems. This required close coordination with teammates to ensure compatibility across the complete Element Sorter platform.

### Mechanical Design

Created custom CAD models and 3D-printed mounting hardware to improve display visibility, packaging, and overall user experience.

---

## Technical Skills Demonstrated

<div style="display: flex; gap: 4rem;">

<ul>
<li>Embedded Systems Design</li>
<li>ESP32 Development</li>
<li>MicroPython Programming</li>
<li>UART & I2C Communication</li>
</ul>

<ul>
<li>PCB Design</li>
<li>Power Electronics</li>
<li>CAD Modeling</li>
<li>Systems Integration</li>
</ul>

</div>

---

## Key Outcomes
- Designed and manufactured a custom embedded hardware platform
- Developed firmware for user interaction and subsystem control
- Implemented reliable communication between four independent embedded systems
- Successfully integrated electrical, software, and mechanical subsystems into a functional STEM exhibit