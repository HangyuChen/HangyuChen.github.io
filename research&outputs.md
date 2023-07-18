---
layout: page
permalink: /research&outputs/index.html
title: Research&Outputs
---

<!-- # Hobbies -->

## Design of ASCMS (Active Scattering Camouflage Metasurfaces) Inspired by ‘Chessboard’ Method

<div class="third">
<img src="/images/ascms1.jpg">
<img src="/images/ascms2.jpg">
<img src="/images/ascms3.jpg">
</div>
<br>Low radar cross section (RCS) metasurfaces contribute to the stealth performance of aircrafts overhead on account of their low RCS characteristic consistent with the broad sky. However, when it comes to some equipment on the ground, that is another story. Given that background alters to the ground or forests, low RCS metasurfaces will have the opposite effect on the safety of equipment since it directly exposes equipment to the radar detections from the air. To address this issue, ASCMS, composed of uniform units loaded with PIN diodes, is proposed in this research. Some key points of this reserach can be concluded as follows:

- Analyze and build up the algorithm to synthesize and manipulate the scattering of ASCMS, then verify algorithm in Matlab.
- Design and simulate ASCMS units loaded with PIN diodes in CST Studio to satisfy both amplitude and phase requirement in algorithm.
- Implement units in CST Studio with specific distribution of units corresponding to the set scattering goal via co-simulation method. Then, transform the simulation model in CST Studio into Printed Circuit Board file in Altium Designer and fabricate ASCMS.
- Code each ASCMS unit as set forth via microcontroller STM32F407VGT6 and conduct measurement.

This research has been summarized into an academic article and submitted to IEEE Transaction on Antenna and Propagation, welcome to review this research in PDF format by [clicking here](https://HangyuChen.github.io/file/resume-hangyuchen.pdf).

---

## Design of Wideband Cascaded Slot Feed Phased Array with Low Sidelobe

<!-- <div class="third">
<img src="/images/swimming2.JPG">
<img src="/images/swimming.JPG">
<img src="/images/surfing1.JPG">
</div> -->
<div>
<img src="/images/doublelayer.jpg" class="chy">
</div>
<br>A linear array comprised of 16 antenna elements are devised to achieve wide operation band and low sidelobe level. For single element, patches are cascaded vertically and fed by slots. Furthermore, EM energy, output by T/R modules and travelling along microstrip line, is coupled into slots. My contributions are listed below:

- Design and optimize the double layer patch antenna element according to performance indexes such as operation bandwidth in ANSYS HFSS.
- Calculate the specific excitation power weight to achieve set sidelobe level goal and array elements linearly in HFSS to verify sidelobe level.
- Design one to sixteen power divider in HFSS and simulate both power divider and linear array. Insert attenuator, digital phase shifter and LNA and conduct measurement.

---

## Design of Non-uniform Dual-frequency Phased Array with Wide Scanning Angle

To achieve a phased array operating at two distinct frequencies and realize wide-angle scanning of high frequency array, both quasi hexagonal patch array and dipole array are deployed. My contributions are listed below:

- Design and optimize patch antenna and erected dipole antenna in HFSS, including the balun transformer to rectify the beam.
- Deploy and synthesize the whole array in a proper way to extend the scanning angle and depress grating lobe compared with conventional rectangular lattice array and verify deployment in Matlab.
- Array antenna elements and assign port excitations in HFSS with the stimuli derived from numerical calculation and conduct simulation.

---

## Antenna Scattering Analysis and Extraction Based on Radar 1D and 2D Imaging

To modify conventional method of extracting the scattering of antenna and detect the working status of MIMO array, a detection and extraction method based on both 1-D and 2-D microwave imaging is investigated in this research. My contributions are listed below:

- Learn radar one-dimensional and two-dimensional imaging algorithm and implement algorithm in Matlab.
- Analyze the scattering constituents of antenna and conduct the simulation in FEKO, where electric fields are extracted to verify the analysis in 1-D and 2-D imaging algorithm.
- Separate structural scattering from mode scattering of the antenna and extract complete scattering of antenna via electric field data stemmed from FEKO in Matlab.

This research has been summarized into an academic article and published in International Journal of Distributed Sensor Networks. Welcome to leave your precious feedback after reviewing this research article in PDF format by [clicking here](https://HangyuChen.github.io/file/resume-hangyuchen.pdf).


---
