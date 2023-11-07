---
layout: archive
title: "Research Project"
permalink: /research_project/
author_profile: true
---

[ Simulation and Analysis of Modon Motion in an Inviscid and Confined Fluid Environment ](https://georget27.github.io/files/Modon.pdf)

The objective of this paper is to explore the nature of dipole vortices and investigate their interaction dynamics. The analysis begins in Section 2, where we derive the quasigeostrophic equation by starting with the basic rotating shallow water equations. This equation proves to be invaluable for the examination of dipole vortices.

In Section 3, we employ the implicit function theorem to derive a vorticity equation. Drawing inspiration from the influential work of Meleshko and van Heijst (1994), we introduce a linear relationship for the derived vorticity
equation. Furthermore, we present distinct equations for both the stationary frame and the relative moving frame. These equations serve a vital purpose in establishing the initial conditions necessary for the subsequent Python simulation. By considering both frames, we gain a comprehensive understanding of the dynamics and behaviors of the dipole vortices within different reference frames.

In Section 4, a concise introduction outlines the formation of dipole vortices. I then delve into a detailed explanation of the solutions to the quasigeostrophic equation described in Sections 2 and 3. To aid compre-
hension, visual illustrations in the form of Python plots are presented providing a visual understanding of the dipole vortex shapes.

I utilized the Dedalus package in Python to conduct simulations of dipole vortices, which serves as the focal point of our analysis. Section 5 delves into the implementation details, providing comprehensive explanations
of the underlying mathematics at play. i.e. To address errors arising from numerical analysis, additional terms were introduced into the system, which were not originally part of our problem. One such concept is Numerical
viscosity, which I introduced to account for the impact of the Gibbs phenomenon that arises due to the use of a finite grid model with Fourier approximation functions. Consequently, the dipole vortices fail to converge when they intersect the boundary. Subsequently in this section, I examine various types of motion exhibited by the dipole vortices, considering different scattering effects.

In section 6, I propose treating the dipole vortices as a point vortex model. Within this chapter, I employ Python to generate plots illustrating the trajectories of the point vortices. Remarkably, I discover that their
paths coincide with the simulations presented in section 5.

