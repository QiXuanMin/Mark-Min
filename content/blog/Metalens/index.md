---
title: Varifocal Metalens for Compact and Accurate Quantitative Phase Imaging
summary: ACS Photonics
date: 2024-07-03

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Concept of the Metalens based QPI'

authors:
  - admin
#  - Ted

tags:
  - Computational Imaging
  - Metasurface
  - Master
---

[🔗Paper Link](https://pubs.acs.org/doi/10.1021/acsphotonics.4c00658)

{{< toc mobile_only=true is_open=true >}}

## Abstract

The transport of intensity equation (TIE) is a non-interferometric method for quantitative phase imaging (QPI). TIE enables the characterization of transparent objects and is widely applied in fields such as biomedicine, materials science, and optical metrology. Traditional TIE methods require the mechanical movement of detectors to capture multiple images, which limits integration, stability, and speed of the system. 

In this work, we designed a linear polarization-dependent varifocal metalens for TIE based QPI. This approach allows the acquisition of multiple defocused images without mechanical movement. Coupled with the High-order TIE algorithm, it yields a compact, stable, and accurate phase-imaging technique. 

## Design

We simulated the nanostructures  by using *Lumerical FDTD Solution*, we scanned the parameter of nanostructure to get the phase and the transmittance distribution under different width and length. Figure 1 shows the schematics and design of the metalens.

<img src=".\fig1.jpg" style="zoom:20%;" />

<center style="font-size:14px"><p>Figure 1. Schematics and design of the varifocal metalens. (a−c) Schematic illustration of a unit cell of the metalens, nanopillar have W or L from 75 to 350 nm, and H = 600 nm, with center-to-center spacing P = 400 nm. (d) Schematic diagram of polarization-related continuous zoom. (e)Phase and transmittance distribution maps corresponding to different W and L of nanopillars under TE mode polarized light illumination. (f, g)Photos of metalens taken under the microscope and SEM.</p></center>

## Characterization

We characterized the focusing performance of the metalens by scanning the PSF and measuring the focusing efficiency of the metalens. The measurements  results are shown in Figure 2.

<img src=".\fig2.jpg" style="zoom:23%;" />

<center style="font-size:14px"><p>Figure 2. Experimental characterization results of the metalens. (a) Focusing performance of the metalens at different polarization angles. (b) Focal
length variation curves in simulation and experiment, as well as experimentally measured focusing efficiency of the metalens under 0−90° polarized
light illumination. (c) Focal spot intensity and full width at half-maximum (fwhm) of the metalens under TE polarization (0°) illumination.</p></center>


## QPI Performance

The metalens was then used for QPI. Multi-plane defocus images are obtained by changing the polarization angle of the incident light. Based on the high-order TIE method, the research group has demonstrated the ability to perform quantitative phase imaging of transparent objects with precision and reliability. As shown in Figure 3, the results indicate that this method can also give good results for objects with slowly varying phase.

<img src=".\fig3.jpg" style="zoom:30%;" />

<center style="font-size:14px"><p>Figure 3. Quantitative phase target metrology using the varifocal metalens. (a) Schematic of the metalens-based QPI experimental setup. BF: Bandpass Filter, LP: Linear Polarizer, PO: Phase Object, ML: Metalens, OL: Objective Lens, TL: Tube Lens. (b) Experimentally measured intensity of the phase object under 0−90° polarized light illumination. The image under 45° polarization is the focused image, while the others are defocused images. (c) The height ground truth obtained from the white light interferometer (WLI), as well as the heights reconstructed using a multiple frames approach and two frames. (d) Comparison and residual of the phase distribution in the dashed line. MF: Multiple Frames, TF:Two Frames, MR: Residual of Multiple Frames, TR: Residual of Two Frames.</p></center>

