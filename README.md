firebehavioR
================

An R package for predicting fire behavior using the Rothermel modelling system or the Crown Fire Initiation & Spread modelling system.

Features
--------

Fire behavior predictions using:
* the Rothermel modelling system, similar to BehavePlus, NEXUS, and FuelCalc
* the Crown Fire Initiation & Spread modelling system

Helper functions which can:
* Calculate the wind adjustment factor, using a little or alot of site-specific forest canopy information
* Predict canopy fuels characteristics such as canopy bulk density and canopy fuel load

Helper data:
* Stylized surface fuel models
* Surface fuel moisture scenarios

Installation
------------

You can install firebehavioR from GitHub for the development version.

    devtools::install_github("zieg9479/firebehavioR")

There are no package dependencies, but you should have R (&gt;= 3.4.1) installed.

Usage
-----

The vignette in the above references GitHub repo will help you get up and going.

Future Development
-----

This package is a continual work in progress. Suggestions for improvements are welcomed. Currently, additional helper functions are planned: 
* Incorporation of models to estimate dead and live fuel moistures using RAWS weather observations 
* Additional methods to estimate canopy fuels characteristics
* Visual interpretation of fire behavior results via the Fire Characteristics Chart

Authors
-------

-   **Justin Ziegler** - developer and maintainer, <Justin.Ziegler@Colostate.edu>

License
-------

GPL (&gt;= 2)