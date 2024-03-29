# Software & Computing for NSN Physics
This repository contains a project for partial fulfilment for the course of Software & Computing for Nuclear and Subnuclear Physics.

## Testbeam data analysis for Silicon Pixel detector

## Introduction
For the HL-LHC upgrade of ATLAS detector, high rate detectors are needed. Currently, HV-MAPS collaboration at Heidelberg University is building prototype for ATLAS tracking detector using new High Voltage-Monolithic Active Pixel Sensors (HV-MAPS) in contrast to Hybrid Pixel sensors which are currently in use in various detectors at LHC and other experiments.


The data whixh is analyzed in this project has been taken for ATLASpix prototype sensor for the HL-LHC upgrade of ATLAS detector with Timepix3 telescope layers using The Super Proton Synchroton beam at CERN.

The following data set is used:

**ATLASpix at SPS:**
- Run 29663 taken in November 2018 by CLICdp (Contact: Dominik Dannheim at CERN)
- total length 480sec
- telescope read out with SPIDR
- DUT read out with Caribou
- Information about the DUT:
	- **ATLASpix_Simple**: 
		- ID: w23s11
		- Substrate Resitivity: 200 Ohm cm
		- Thickness: 100 um
	- bias = -75V
	- threshold = 950 mV -> slightly inefficient
	- clock_cycle = 8ns
	- ckdivend2 = 15

### Objectives
1) To understand the o understand the working principle of silicon pixel detectors
2) To analyse a set of test-beam data in order to characterise a pixel sensor prototype and investigate its performance

### Requirements
This analysis and data visualisation is carried out using ROOT and Correyvreckan. Corryvreckan is a flexible, fast and lightweight test beam data reconstruction framework based on a modular concept of the reconstruction chain. It is written in C++ with well documention and ready to use.
