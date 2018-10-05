---
title: "Performance of the GaugeCam image-based water level measurement system"
author: François Birgand, Ken Chapman, Arnab Hazra, Troy Gilmore, Andrew Brown, Ana-Maria Staicu
date: '05 October, 2018'
documentclass: article
output: 
  bookdown::html_document2:
    toc: false
    number_sections: false
    keep_md: true
  bookdown::pdf_document2:
    toc: true
    number_sections: true
  bookdown::word_document2:
    reference_docx: template.docx
    fig_width: 4
    fig_height: 3
    fig_caption: true
bibliography: [articleFWM.bibtex]
biblio-style: apalike
pandoc_args: [ "--csl", "hydrological-processes.csl" ]
link-citations: yes
---





# Abstract

# Introduction

- Much of what we know in hydrology today takes root at one point in the ability to observe and record on a near continuous basis the rapid changes in water stages in rivers, lakes, and estuaries
- To this day, most of flow rates calculated in the thousands of hydrologic stations around the world are still calculated from the water level or stage measurements.
- Since the first hydrologic station installed on the Mississippi river in the 1880s, there have been many devices installed to record water stages
    - The mechanisms to measure stages used until now include fully mechanical pulley and float based systems, pressure transducers immerserd in water, pressure transducers in air in equilibrium with the water column or bubblers, radar systems, ultrasonic systems placed above or under the water. 
- In all measuruments there is an intermediate operation between the raw signal and the stage values recorded. In other words the raw signals always require interpretation before a number is assigned to a measurement.  All measurements are essentially indirect. For example, the mechanical vertical movements of a float are transfered to a pulley, and the rotation of the pulley is recorded as a voltage at the potentiometer electrodes, or as a pen trace on paper. Same thing with pressure transducers, etc.
- In all past and current systems, the interpretation of the raw signal is done in the field
- Because of wear with time and of the variable temperature and moisture conditions where the instruments are installed, the relationship between the water level and the raw signal may drift over time (e.g. float weigh changes because of biofilm growth on it; membrane of a pressure transducer diforms over time), and/or the interpretation system of the raw signal also drifts (e.g., potentiometer).
- In all cases, regular calibrations are required to maintain the quality of stage measurements. But because the interpretation of the raw data is done in the field, the calibration must also be done in the field, which means that qualified personel must go to the field at regular intervals (monthly or more often).
- Additionally, none of the existing system provide means to independently verify data
- The GaugeCam image based systems provides solutions to the drawbacks of existing systems: the interpretation of the raw data is performed remotely, on a server, and the raw data itseld can be reinterpreted at any times and can be visually verified. 
- The obvious advantages are that maintainance does not require highly qualified personnel, and the timing for maintainance can be detected by the user (e.g., seen in the raw data itself, i.e., in the image), and every single measurement is visually verifiable. 
- This means that the system can be installed virtually anywhere in the world where a cell phone connection is possible for live measurements
- The GaugeCam system uses images streaming from the field at a high frequency basis to a server where the images are analyzed and a water level measurement made. The system then stores both the measurement and the images corresponding to each measurement.
- The article reports the field performance and calculates the uncertainty of the system in the field

# Method

# Results

# Discussion

# Conclusion

# References



