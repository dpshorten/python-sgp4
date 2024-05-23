# SGP4 Implementation of python-sgp4

Author: David Shorten <dpshorten@gmail.com>

## Background

This package was created as part of the SmartSat CRC project P2.11: Trusted AI Frameworks for Change and Anomaly Detection 
in Observed ISR. This project was mostly conducted from early 2022 to early 2024 at the Univerity of Adelaide.

The goal of the project was to develop techniques for detecting manoeuvres from the Two-Line-Element data made available 
by the USA's 18th Space Defense Squadron.

This is a utility package which provides a python implementation of the SGP4 propagator.  


## Package Structure

This package is a fork of the original `python-sgpy` package (<github.com/brandon-rhodes/python-sgp4>). 
It contains only minor changes. Specifically, the Kozai to Brouwer conversion has been removed. This is instead performed
within the `TLE_utilities` package as an initial step in the processing of the TLE data. 
