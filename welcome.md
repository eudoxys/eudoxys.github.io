---
layout: page
title: Welcome to Eudoxys Sciences LLC
permalink: /
redirect_from:
  - /welcome
---

We are an independent consulting that provides models and simulations to help the electric power industry plan for an increasingly uncertain and unpredictable future. We serve electric utilities, regulators, reliability organizations, and government agencies by developing, validateing, and maintaining electric power system models, simulation, analyses, and forecasts for residential, commercial, industrial, agricultural, and transportation loads. We use physics-based and data-driven modeling techniques in tools that use GridLAB-D as the core modeling and simulation technology. 

## Modeling

We focus on developing high-fidelity load models for electric power system simulation and analysis. We create static, quasi-steady, and dynamic load models for GridLAB-D, CYME, PSLF, and PSS/E. All load models are developed from a combination of physics-based models, end-use load surveys, and measured power and/or energy data. Static load models are defined for a particular location and moment in time. Quasi-steady models vary in time and can include mid-term dynamics such as building thermal response and load controls. Dynamic models are used for power system transient analysis and include the composite load models according to the NERC load modeling guidelines.

We also develop transmission and distribution GridLAB-D models that include flexible loads and distributed resources for Linux Foundation’s Arras Energy, NRECA’s Open Modeling Framework (OMF), and Hitachi’s GLOW simulation systems. We support converting network and static load models from CYME and PSS/E to GridLAB-D for use in Arras Energy, OMF, and GLOW.

## Simulations

We prepare and validate GridLAB-D transmission and distribution simulations for models of all sizes and complexity. 

Simulations are typically run on custom-built AWS images that have been optimized for GridLAB-D models are varying sizes and complexity. Data is usually delivered and collected in CSV files for analysis.

Model validation depends on the model scale. For smaller distribution system models, AMI data is preferred for validation. For large distribution and transmission system models SCADA data is needed instead.

## Analysis

We conduct system reliability and resilience analysis for transmission and distribution systems using GridLAB-D. The following analyses are currently available:

* IEEE 1366 metrics, including SAIDI, SAIFI, CAIDI, MAIFI.
* Tariff design cost and revenue analysis.
* Deep electrification impacts analysis.
* Pole failure analysis during extreme weather.
* Conservation voltage reduction energy and revenue analysis.
* Voltage fluctuations and thermal limits with high renewable and/or storage.
* Distribution-level optimal power flow analysis under high renewable and/or storage.

## Forecasting

We develop short-term and long-term load forecasts for all major electric customer sectors from local to national scale.

Short-term load forecasting spans roughly 1 hour to 1 week using AMI and/or SCADA data. We typically use a high-order transfer function to estimate both the static and dynamic response of loads at the time-scale of hours to days.

Long-term load forecasting spans 5-20 years using the SLAC load forecasting tool developed for NERC. This tool allows load forecasts to be developed using varying end-use electrification adoption rates.

## Controls

We develop, analyze, and assist in validation and deployment of advanced load and distributed resource control strategies. In particular, we focus on transactive energy solutions where prices or price-like signals are used to coordinate and optimally dispatch distributed energy resources.

## Training

We provide training course for utility engineers, academic faculty and students, and regulatory agency staff. Two-hour training courses available include the following

1. Introduction - An overview of the motivation, theory, and history of GridLAB-D.
1. GridLAB-D Use-Cases - Explore ways GridLAB-D is used to address power grid challenges.
1. Building GridLAB-D - How to build a development version of GridLAB-D.
1. GridLAB-D modeling - Modeling systems in GridLAB-D.
1. Testing and validation - Testing and validating GridLAB-D systems.
1. Modules and classes - Modules and classes used in power system modeling.
1. Core engine and solvers - Deep dive into how GridLAB-D simulates systems.
1. Python libraries and extensions - Deep dive into the Python libraries and APIs.
1. Data and model converters - Importing and exporting data and models.
1. Geodata packages - Geographic data packages in GridLAB-D
1. Subcommands - Creating subcommands to provide services in GridLAB-D.
1. Tools and utilities - Creating scripts and programs to help users of GridLAB-D.
1. Production and release - Distribution and dissemination of GridLAB-D software.
1. Working with LF Energy - Learn how to become part of the LF Energy open-source software community.

## Get a Quote

You can request a quote for our services by filling out this [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfFTSw6FNu5hPFrv3ZSZTXRx0zniyAALJIRvbfamTEo_cjPHw/viewform).
