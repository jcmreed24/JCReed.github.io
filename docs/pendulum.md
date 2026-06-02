<h1 style="text-align: center; font-size: 4rem; margin-bottom: 0.5rem;">
Inverted Pendulum Dynamic System Modeling
</h1>

![Simulink Model Overview](static/images/JC%20Reed%20-%20Simulink%20Pendulum.png)

<div style="max-width: 900px; margin: auto;">

<h2 style="margin-top: 1.5rem;">Modeling & Simulation Project</h2>

<strong>Arizona State University Polytechnic</strong><br>
<strong>Course:</strong> Transforms & Systems Modeling (EGR433)

<p>
Developed a nonlinear dynamic model of an inverted pendulum on a cart using MATLAB and Simulink. The project focused on deriving the system equations of motion, implementing the coupled dynamics within Simulink, and analyzing the open-loop response of the cart-pendulum system.
</p>

<p>
The simulation provided insight into the behavior of unstable mechanical systems and served as a foundation for future controller design techniques commonly used in robotics, automation, and aerospace applications.
</p>

</div>

---

## System Model
The model implemented the nonlinear equations of motion governing both cart translation and pendulum rotation. Simulink integrator blocks were used to compute position, velocity, angular position, and angular velocity while capturing the coupling between cart motion and pendulum dynamics.

The simulation incorporated system parameters including cart mass, pendulum mass, rotational inertia, damping, and gravitational effects to accurately represent real-world behavior.

---

## Engineering Analysis

### Dynamic System Modeling

Developed a mathematical representation of an inverted pendulum system and implemented the governing differential equations within Simulink. The model captured the interaction between translational and rotational motion while accounting for gravitational and damping effects.

### Numerical Simulation

Utilized MATLAB and Simulink to simulate system response over time and evaluate the behavior of the coupled mechanical system under open-loop conditions.

### Controls Engineering Foundations

Analyzed the response of an inherently unstable system frequently used as a benchmark problem in controls engineering. The project provided practical experience with state variables, system dynamics, stability concepts, and simulation-based validation.

---

## Simulation Results

### Cart Position Response

![Cart Position Response](static/images/Pendulum%20Position.png)

The position response illustrates the translational movement of the cart over time as it reacts to the pendulum dynamics. Oscillatory behavior is observed due to the interaction between the cart and pendulum system.

---

### Pendulum Angle Response

![Pendulum Angle Response](static/images/Pendulum%20Angle.png)

The angular response demonstrates the oscillatory motion of the pendulum throughout the simulation. The results highlight the unstable nature of the inverted pendulum problem and illustrate the influence of damping and system inertia on overall behavior.

---

## MATLAB Model Parameters

![MATLAB Parameters](static/images/MATLAB%20parameters.png)

The simulation utilized physical system parameters including:

- Cart Mass
- Pendulum Mass
- Rotational Inertia
- Damping Coefficient
- Pendulum Length
- Gravitational Acceleration

These parameters were used to construct a realistic dynamic model representative of a physical inverted pendulum system.

---

## Technical Skills Demonstrated

<div style="display: flex; gap: 4rem;">

<ul>
<li>MATLAB</li>
<li>Simulink</li>
<li>Dynamic System Modeling</li>
<li>Differential Equations</li>
<li>Numerical Simulation</li>
</ul>

<ul>
<li>Controls Engineering</li>
<li>Mechanical System Analysis</li>
<li>System Dynamics</li>
<li>Engineering Mathematics</li>
<li>Data Analysis</li>
</ul>

</div>

---

## Key Outcomes

- Developed a complete nonlinear Simulink model of an inverted pendulum system
- Simulated coupled translational and rotational dynamics
- Evaluated open-loop response characteristics of an unstable mechanical system
- Applied engineering mathematics to model real-world physical behavior
- Strengthened foundational knowledge in controls engineering and dynamic system analysis