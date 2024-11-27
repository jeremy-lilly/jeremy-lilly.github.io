---
layout: about
title: about
permalink: /
subtitle:
profile:
  align: right
  image: headshot.jpg
  image_circular: false # crops the image to make it circular
  more_info:
news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

I'm a postdoc working at Los Alamos National Laboratory in the Computational Physics and Methods group (CCS-2).
I recently graduated from Oregon State University, where I completed my PhD in Mathematics, supervised by Robert Higdon.

[My PhD dissertation](https://ir.library.oregonstate.edu/concern/graduate_thesis_or_dissertations/rr172599c) focuses on developing computationally efficient time-stepping methods for the shallow water equations, with the long term goal of speeding up realistic simulations of the ocean and atmosphere at the climate scale.
By combining a CFL optimized method, a certain operator splitting, and local time-stepping, we achieved a speedup of more than 10x in the US Department of Energy's ocean model, MPAS-Ocean.

Currently, I'm working on developing new numerical methods, targeted at geophysical fluids on the sphere, that use tensor decompositions to fight the "curse of dimensionality" in large problems.
We hope that this new approach will speed up computationally expensive climate models, while also allowing them to make use of emerging HPC hardware normally targeted at machine learning applications.
This would allow climate researchers to run larger suites of simulations, at higher resolutions, in less time.
