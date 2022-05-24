---
title: Simulation, control & experimental testing on a helicopter system (CE150)
summary: 'Esynov (2017)'
tags:
  - Helicopter System
date: ''

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Photo by DVA Nguyen
  focal_point: Smart

links:
  - icon: folder-open
    icon_pack: fab
    name: Link
    url: https://esisar.grenoble-inp.fr/fr/l-ecole/plateau-sacco-les-projets-d-innovation
url_code: ''
url_pdf: ''
url_slides: ''
url_video: https://www.youtube.com/watch?v=KukWmFRKifo

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

The project will focus on modeling and closed-loop controls (PID, LQR, MPC) of a laboratory helicopter using conventional control methods. The system consists of a body, carrying two propellers driven by DC motors, and a massive support. The body has two degrees of freedom. Both body position angles (elevation and azimuth) are influenced by rotation of propellers. Center of gravity is changed by moving small weight along the main horizontal axis of helicopter by a servomotor. The mathematical model of the helicopter system is a typical MIMO 2x2 system with significant cross-couplings. The electromechanical system can be linearized to a linear sixth-order model when operating near the steady state. A multifunctional card MF624 is used as interface module between PC based controller and helicopter system. It is designed for data acquisition and transmission. The card can be optimized for use with MATLAB/Simulink Real Time Toolbox. It also provides implementation of the control algorithms from the PC to the helicopter system. The user communicates with the system via Real Time Toolbox interface, all input/output signals are dimensionless and scaled into the MU (Machine Unit). The MATLAB/Simulink xPC Target Toolbox can be used to perform the experiments in real time applications.

This project is funded by [ANR](https://anr.fr/en/) (Agence Nationale de la Recherche) with the partners including [CHRUB](https://www.chu-besancon.fr/) (Centre Hospitalier Régional Universitaire de Besançon), [INSERM](https://www.inserm.fr/en/home/) (Institut National de la Santé et de la Recherche Médicale), [FEMTO-ST](https://www.femto-st.fr/en) (Franche-Comté Électronique Mécanique Thermique et Optique - Sciences et Technologies), and [ISIR](https://www.isir.upmc.fr/?lang=en) (Institut des Systèmes Intelligents et de Robotique). The project coordinator is Professor Laurent Tavernier, head of ENT Service at CHRUB.

As member of the µRoCS project, the work of Mr. Nguyen focuses on the mechatronics discipline of the proposed hybrid continuum robot for middle ear surgery. The main contributions including the specifications, design, modelling, prototype fabrication and low-level control of the proposed microrobot based on anatomic constraints.
