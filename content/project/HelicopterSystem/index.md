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

The project focused on modeling and closed-loop controls (PID, LQR, MPC) of a laboratory helicopter using conventional control methods. The system consisted of a body, carrying two propellers driven by DC motors, and a massive support. The body had two degrees of freedom. Both body position angles (elevation and azimuth) were influenced by rotation of propellers. Center of gravity was changed by moving small weight along the main horizontal axis of helicopter by a servomotor. The mathematical model of the helicopter system was a typical MIMO 2x2 system with significant cross-couplings. The electromechanical system can be linearized to a linear sixth-order model when operating near the steady state. A multifunctional card MF624 was used as interface module between PC based controller and helicopter system. It was designed for data acquisition and transmission. The card can be optimized for use with MATLAB/Simulink Real Time Toolbox. It also provided implementation of the control algorithms from the PC to the helicopter system. The user communicates with the system via Real Time Toolbox interface, all input/output signals were dimensionless and scaled into the MU (Machine Unit). The MATLAB/Simulink xPC Target Toolbox can be used to perform the experiments in real time applications.

This project is funded by [Grenoble INP-UGA](https://www.grenoble-inp.fr/en) at the [Esynov platform](https://www.esynov.fr/) under the supervision of Professor (Associate) [Ionela Prodan](https://scholar.google.com/citations?user=OSiQW5cAAAAJ&hl=en).

As member of the innovation project, Mr. Nguyen started his work as a research intern in the summer of 2017, then became the team leader of this project (Sep-Dec, 2017).
