# PIC24F16KA101-Multimeter

This is the XC-16 (C language-based code for the PIC24, 16-bit MCU family) code for the PIC24F16KA101.
This multimeter is capable of measuring voltage, resistance, capacitance, and frequency.

Each of these measurements can be displayed on a PC terminal (teraterm).

The Voltmeter and Ohmeter both use the ADC to measure a voltage, which is then calculated into a voltage or resistance.

The capacitance-meter uses the property t=RC*0.63 to determine capacitance. It was programmed without using the in-built CTMU on the PIC24.

The frequency meter checks for a change in square waves, and determines the frequency accordingly.

The frequency-meter is the default mode of the multimeter, and the other modes can be selected by pressing the appropriate button.

This was designed as the Final Application Project for ENCM 511 - Embedded Systems Interfacing.
