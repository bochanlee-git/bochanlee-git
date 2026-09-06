# TRAC — Texas A&M Rotorcraft Analysis Code

**TRAC (Texas A&M Rotorcraft Analysis Code)** is a comprehensive rotorcraft flight dynamics analysis and simulation framework developed during my doctoral research at **Texas A&M University**.

The framework was developed to support rotorcraft modeling, simulation, flight dynamics analysis, and flight-control research. A key aspect of the development was the validation of the rotorcraft model using **UH-60 Black Hawk flight-test data**.

TRAC provided the computational foundation for subsequent research in rotorcraft flight dynamics, flight-control systems, and autonomous flight.

---

## Overview

Rotorcraft flight dynamics involve strongly coupled aerodynamic, rigid-body, rotor, and control-system effects. Accurate modeling and simulation are therefore essential for understanding aircraft behavior and developing advanced flight-control and autonomy systems.

TRAC was developed as a research-oriented framework to provide an integrated environment for:

* Rotorcraft flight-dynamics modeling
* Trim and equilibrium analysis
* Dynamic simulation
* Linearized system analysis
* Flight-control research
* Flight-test data comparison
* Autonomous flight research

The framework bridges theoretical aircraft modeling with experimentally observed aircraft behavior through validation against flight-test data.

---

## Research Context

TRAC was developed as part of my Ph.D. research in Aerospace Engineering at **Texas A&M University**.

The broader research program focused on:

* Rotorcraft flight dynamics
* Aircraft modeling and simulation
* Flight-control systems
* Autonomous flight
* UAV and VTOL aircraft
* Autonomous ship landing

TRAC served as a foundational modeling and simulation framework for this research.

---

## Key Capabilities

### Rotorcraft Flight Dynamics

TRAC provides a computational representation of rotorcraft flight dynamics for analyzing aircraft response under different flight conditions.

The framework considers the coupled behavior of:

* Aircraft translational motion
* Aircraft rotational motion
* Rotorcraft aerodynamic effects
* Aircraft attitude
* Control inputs
* Dynamic aircraft states

---

### Trim Analysis

TRAC can be used to determine equilibrium flight conditions and corresponding control inputs.

Trim analysis provides the initial conditions required for subsequent dynamic simulations and control-system analysis.

Typical applications include:

* Steady-level flight
* Forward flight
* Climb and descent conditions
* Control-input determination
* Equilibrium-state analysis

---

### Dynamic Simulation

The framework supports time-domain simulation of rotorcraft flight dynamics.

Dynamic simulations can be used to investigate:

* Aircraft response to control inputs
* Transient behavior
* Stability characteristics
* Flight-condition changes
* Control-system performance

---

### Linearized Model Analysis

TRAC can generate linearized representations of the nonlinear rotorcraft model around selected operating conditions.

This capability enables analysis of:

* Local stability
* Dynamic modes
* System response
* Control-system design
* Linear control analysis

---

## Flight-Test Validation

One of the central aspects of TRAC is its validation against real aircraft flight-test data.

The rotorcraft model was developed and evaluated using **UH-60 Black Hawk flight-test data**, providing a connection between the computational model and observed aircraft behavior.

The general validation workflow is:

```text
                 UH-60 Flight-Test Data
                           │
                           ▼
                  Data Processing
                           │
                           ▼
                  Rotorcraft Model
                           │
                           ▼
                         TRAC
                           │
                           ▼
                   Dynamic Simulation
                           │
                           ▼
              Simulation / Flight-Test
                    Comparison
                           │
                           ▼
                    Model Evaluation
```

This validation approach is particularly important for rotorcraft because aerodynamic and dynamic characteristics can differ significantly from simplified theoretical assumptions.

---

## Research Workflow

TRAC was developed as part of a broader model-based research workflow:

```text
Rotorcraft Physics
       │
       ▼
Mathematical Modeling
       │
       ▼
TRAC Implementation
       │
       ▼
Trim Analysis
       │
       ▼
Dynamic Simulation
       │
       ▼
Flight-Test Validation
       │
       ▼
Flight-Control Development
       │
       ▼
Autonomous Flight
```

This progression connects fundamental rotorcraft dynamics with advanced flight-control and autonomous-flight research.

---

## Applications

TRAC can support research in several areas.

### Rotorcraft

* Flight dynamics analysis
* Stability and control
* Aircraft modeling
* Dynamic simulation
* Flight-test analysis

### Flight Control

* Control-system development
* Dynamic response analysis
* Linearized-system analysis
* Model-based control research

### Autonomous Flight

* Autonomous flight-control research
* Guidance and control
* Autonomous landing
* Shipboard landing research

### UAV / VTOL Aircraft

The modeling and simulation methodology developed through TRAC can also provide a foundation for research involving:

* UAVs
* VTOL aircraft
* Autonomous rotorcraft
* Advanced air mobility
* eVTOL flight-control systems

---

## Relationship to My Research

TRAC represents the **flight-dynamics and simulation foundation** of my broader research program.

My research has progressed from fundamental rotorcraft dynamics and modeling toward flight control and autonomous aircraft operations.

```text
Rotorcraft Flight Dynamics
            │
            ▼
    Modeling & Simulation
            │
            ▼
     Flight-Test Validation
            │
            ▼
     Flight-Control Systems
            │
            ▼
       Autonomous Flight
            │
            ▼
      Autonomous Landing
```

This progression reflects a research philosophy of developing advanced autonomy on top of validated aircraft dynamics and control models.

---

## Technical Ecosystem

The broader research ecosystem associated with TRAC includes:

* Rotorcraft flight dynamics
* Numerical simulation
* Flight-test data analysis
* Flight-control systems
* Python-based computational tools
* Gazebo simulation
* Computer vision

TRAC focuses primarily on the **aircraft dynamics and simulation layer**, while other research projects extend this foundation toward autonomous flight and landing.

---

## Repository Structure

The repository is organized to separate the TRAC documentation, research materials, examples, and future implementation components.

```text
TRAC/
│
├── README.md
│
├── publications/
│   └── ...
│
├── figures/
│   └── ...
│
├── examples/
│   ├── trim/
│   ├── flight_dynamics/
│   └── validation/
│
└── docs/
    └── ...
```

Additional implementation and example files will be added as the repository develops.

---

## Academic Foundation

TRAC was developed during my doctoral research in Aerospace Engineering at **Texas A&M University**.

The development of the framework and its application to rotorcraft autonomous flight research are documented in my doctoral dissertation.

**Dissertation**

Lee, B. (2021). *On the Complete Automation of Vertical Flight Aircraft Ship Landing*. Doctoral dissertation, Texas A&M University.

The dissertation provides the broader academic context for the development and application of TRAC.

---

## Citation

If you use TRAC, its modeling framework, or material derived from this repository in academic research, please cite my doctoral dissertation:

> Lee, B. (2021). *On the Complete Automation of Vertical Flight Aircraft Ship Landing*. Doctoral dissertation, Texas A&M University.

### BibTeX

```bibtex
@phdthesis{lee2021complete,
  author = {Lee, Bochan},
  title = {On the Complete Automation of Vertical Flight Aircraft Ship Landing},
  school = {Texas A&M University},
  year = {2021},
  type = {Doctoral dissertation},
  address = {College Station, Texas}
}
```

For the complete academic context of TRAC and its application to autonomous rotorcraft operations, please refer to the dissertation.

---

## Author

**Bochan Lee, Ph.D.**

Ph.D. in Aerospace Engineering
Texas A&M University

### Research Interests

* Rotorcraft Flight Dynamics
* Aircraft Modeling & Simulation
* Flight-Control Systems
* Autonomous Flight
* UAV / VTOL Aircraft
* Autonomous Landing

---

## Related Research

TRAC forms the aircraft-dynamics foundation for related research projects involving:

* Autonomous ship landing
* Flight-control systems
* UAV / VTOL simulation
* Computer-vision-based autonomous flight
* Autonomous landing systems

These projects will be documented separately as the research portfolio develops.

---

## Disclaimer

TRAC is provided primarily for **research and educational purposes**.

The models and simulation results should not be interpreted as certified representations of an operational aircraft or as a substitute for aircraft-specific engineering analysis, qualification, or flight-test procedures.

---

## License

See the `LICENSE` file for the applicable terms of use.
