Li-840A Calibration
================
Joseph Gaudard
March 20, 2021

## Introduction

Please refer to page 3-25 of the Li-840A manual for the exact procedure
to calibrate the licor. This tutorial aims at providing additional
information specific to the two licors belonging to the Between The
Fjords group.

In short, you will need to run the licor with a gas containing zero
CO<sub>2</sub> and telling it, do the same with a gas with a known
CO<sub>2</sub> concentration (span gas), and check the constants.

Required material:

- Li-840A gas analyzer;
- Tubings and flux meter;
- Battery;
- Computer with Licor communication software and RS-232 cable.

## Zero gas

N<sub>2</sub> is commonly used as a zero gas. At BIO, you will need to
book the fume hood in the lab 3F04 by the marine biologists (no
N<sub>2</sub> on our side of the building).

Steps to follow:

1.  Open the valve for N<sub>2</sub> in the fume hood;
2.  Connect the flux meter and check that it is at 1 L/mn;
3.  Connect the tubes to the Li-840A inlets;
4.  Turn on the Li-840A by connecting the battery;
5.  Connect the Li-840A to the computer and to the software;

Then in the software:

6.  Wait until the cell temperature is at 51°C and the CO<sub>2</sub>
    concentration stable;
7.  View \> Calibration \> Zero \> Make zero
8.  Check if values are stable and near 0.

## Span gaz

The span gas we use is CO<sub>2</sub> at 998ppm. The bottle is stored in
the gas storage and labelled at the name of Susanne Berthelsen. As the
access is restricted, you will need to contact Ann Kristin Frøyset (gas
manager) or Birte Töpper. If both are unavailable, you can also contact
the BIO-guard/security during working hours. They have a key to the gas
storage. The rest of the equipment needed is stored in lab 4D12 (4th
floor), in the drawers on the left of the south facing window. The
procedure is the same as for the zero gas, some extra steps are
described in the figure below. The bottle is under pressure, do not open
the valve fully and make sure to check the flux meter. Do not connect
the Li-840A before making sure that the flux is at 1 L/mn. In the
software, the calibration is done under “span gas”.

![spangas](co2.jpg)

<figcaption>
This is how it should look once mounted. Make sure it is tight before
opening the bottle. Open and close the valves in this order.
</figcaption>

## Constants

Constants are on a piece of paper delivered by Licor and are specifics
to each Li-840A. Check the serie number of the Li-840A. In View \>
Calibration \> Advanced, you can adjust the constants and send them to
the Li-840A. This should be done after the calibration with zero and
span gas.
