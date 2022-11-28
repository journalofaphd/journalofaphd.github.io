---
title: Time-Dependent Density Functional Theory
summary: Simulating laser-driven electron dynamics in solids using TDDFT
tags:
  - Electronic Structure
  - TDDFT
date: '2022-11-24T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: TiO₂ interacting with a laser pulse
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

The field induced changes of the electronic structure affect the optical properties of the medium; the external force polarizes the material and induces oscillatory motion of the excited carriers. The oscillating dipoles emit a polarization wave which can modify temporal and spatial properties of the incident field. For sufficiently strong perturbing fields the polarization response of the medium becomes nonlinear. The nonlinear contribution to the polarization gives rise to a variety of nonlinear optical phenomena. This chapter discusses theoretical description of nonlinear optical pulse propagation in materials and experimental probes to investigate them. 	

Laser-matter interaction dynamics involves the the excitation of the particle-hole pair. The particle and hole carriers affects the electromagnetic response of the material, screening the field depending on its density. These aspects of electron dynamics are included within the framework of time-dependent density functional theory (TDDFT). TDDFT is fully quantum mechanical and does not require any assumptions about the dynamics. The electronic motion within TDDFT is described by the time-dependent Kohn-Sham equation (TDKS) for the evolution of single particle orbitals (Kohn-Sham orbitals). TDKS can be viewed as an alternative formulation of time-dependent quantum mechanics but, in contrast to the normal approach that relies on wave-functions and on the many-body Schrödinger equation, its basic variable is the one-body electron density. From the density obtained by TDKS, we obtain the time-dependent polarizability p(t) of a system with a given external time-dependent potential. p(t) essentially contain all information of the system interacting with the external field. We apply TDDFT to describe the nonlinear weak-field and non-perturbatvie electron dynamics of TiO2 induced by intense ultrashort laser pulses.
