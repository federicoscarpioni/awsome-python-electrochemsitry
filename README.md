# Awesome Python Electrochemistry [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Python packages for experimental and theoretical electrochemistry.

Inspired by [awesome-python](https://awesome-python.com) and [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry).

> The landscape of Python packages for electrochemistry evolves continuously. This list focuses on packages that are documented and actively maintained or developed. Contributions and suggestions are welcome!

## Table of Contents

- [Instrumentation and Data Acquisition](#instrumentation-and-data-acquisition)
- [Data Conversion from Proprietary Formats](#data-conversion-from-proprietary-formats)
- [Data Handling and Visualization](#data-handling-and-visualization)
- [Electroanalysis](#electroanalysis)
- [Electrochemical Impedance Spectroscopy](#electrochemical-impedance-spectroscopy)
- [Cyclic Voltammetry](#cyclic-voltammetry)
- [Battery Technology](#battery-technology)
- [Fuel Cells](#fuel-cells)
- [Laboratory Automation](#laboratory-automation)
- [See Also](#see-also)

---

## Instrumentation and Data Acquisition

*Packages for controlling potentiostats and other electrochemical instrumentation.*

- [pyeclab](https://github.com/federicoscarpioni/pyeclab) - Python library for controlling Bio-Logic potentiostats at channel level.
- [Easy Biologic](https://github.com/bicarlsen/easy-biologic) - Python interface for communicating with Bio-Logic potentiostat at device level.
- [hardpotato](https://github.com/jrlLAB/hardpotato) - Unified control library for potentiostats from multiple manufacturers.

## Data Conversion from Proprietary Formats

*Packages for reading and converting proprietary instrument data files into open formats.*

- [galvani](https://github.com/echemdata/galvani) - Reads electrochemical data files from multiple potentiostat manifacturers into pandas DataFrames.
- [eclabfiles](https://github.com/vetschn/eclabfiles) - Parser for Bio-Logic EC-Lab binary (.mpr) and text (.mpt) data files.

## Data Handling and Visualization

*Packages for loading, processing and visualising electrochemical datasets.*

- [ixdat](https://github.com/ixdat/ixdat) - Integrated experimental data analysis toolkit with a focus on in-situ and operando electrochemistry.
- [SciBatt](https://github.com/amundmr/SciBatt) - Battery data analysis and visualisation toolkit.

## Electrochemical Impedance Spectroscopy

*Packages for EIS data acquisition, analysis, equivalent circuit fitting, and DRT calculation.*

- [pyimpspec](https://github.com/vyrjana/pyimpspec?tab=readme-ov-file) - EIS data analysis with equivalent circuit fitting, DRT calculation, and validation tools.
- [DearEIS](https://github.com/vyrjana/DearEIS) - Graphical user interface for EIS analysis built on pyimpspec.
- [impedance.py](https://github.com/ECSHackWeek/impedance.py) - Simple and extensible library for fitting EIS data with equivalent circuit models.
- [pyEIS](https://github.com/kbknudsen/PyEIS/tree/master) - EIS data analysis and equivalent circuit fitting toolkit.
- [pyDRTtools](https://github.com/ciuccislab/pyDRTtools) - Distribution of relaxation times (DRT) calculation from EIS spectra.
- [PyDRT](https://github.com/robertleonhardt/PyDRT?tab=readme-ov-file) - DRT calculation and analysis for electrochemical impedance data.
- [EISFittinpython](https://github.com/Sheyigold/EISFitpython) - Fit multiple impedance spectra at once, preserving inter-parameter relationships and propagating uncertainties.
- [ISEA/EIS Data Analytics](https://git.rwth-aachen.de/isea/eis_data_analytics) - EIS data analysis and state estimation tools developed at RWTH Aachen University.

## Cyclic Voltammetry

*Packages for the analysis and simulation of cyclic voltammetry experiments.*

### Analysis

- [pyEIA](https://github.com/thomastu/pyEIA) - Analysis tools for cyclic voltammetry and impedance data.
- [Polarographica](https://github.com/Polarographica/Polarographica_program) - Simulation and analysis software for polarographic and voltammetric experiments.

### Simulation

- [Python Cyclic Voltammetry Simulation Software](https://github.com/kiranvad/pyMECSim?tab=readme-ov-file) - Cyclic voltammetry simulation for mechanistic studies (wraps MECSim).
- [Simulations of Cyclic Voltammetry for a Quasireversible System](https://github.com/tristanCB/quasi-reversible-cyclic-voltametry) - Simulation of cyclic voltammetry for quasireversible electrode kinetics.
- [RedoxPySolid](https://github.com/Aleksei-Marianov/RedoxPySolid) - Simulation of solid-state redox reactions via cyclic voltammetry.
- [ElectroKitty](https://github.com/RedrumKid/ElectroKitty/tree/master) - Cyclic voltammetry simulation and experimental data fitting.

## Batteries

*Packages for battery data handling, analysis, state estimation and simulation.*

### Data Handling

- [PyProBE](https://github.com/ImperialCollegeLondon/PyProBE?tab=readme-ov-file) - Battery testing data handling and analysis framework developed at Imperial College London.
- [cellpy](https://github.com/jepegit/cellpy) - Battery cell data processing, analysis and comparison framework.

### Data Analysis

- [PyBOP](https://github.com/pybop-team/PyBOP) - Battery optimisation package for parameter identification and model selection.
- [Arbin Electrochemical Tools](https://github.com/vince-wu/electrochem) - Analysis tools for data produced by Arbin battery cyclers.
- [BatteryRateCap](https://github.com/BatteryDesign/BatteryRateCap) - Rate capability analysis and modelling for battery cells.
- [pyICI](https://github.com/Joe-Arroyo/pyICI) - Intermittent current interruption (ICI) analysis for battery diagnostics.
- [GalvAnalyze](https://github.com/LukasRier/GalvAnalyze) -  Analysis galvanostatic charge-discharge cycling of batteries.

### Impedance Analysis and State Estimation

- [ISEA/EIS Data Analytics](https://git.rwth-aachen.de/isea/eis_data_analytics) - EIS-based state-of-health and state-of-charge estimation for battery systems.

### Aging and Lifetime Prediction

- [Battery Evaluation and Early Prediction (BEEP)](https://github.com/tri-amdd/beep) - Platform for battery evaluation, feature extraction and early cycle-life prediction.

### Simulation

- [MPET](https://github.com/TRI-AMDD/mpet) - Multi-particle electrode theory simulation for porous battery electrodes.
- [PyBaMM](https://github.com/pybamm-team/PyBaMM) - Fast and flexible battery mathematical modelling framework.
- [liionpack](https://github.com/pybamm-team/liionpack) - Lithium-ion battery pack simulation built on top of PyBaMM.

## Fuel Cells

*Packages for the simulation and analysis of fuel cell systems.*

### PEM Fuel Cells

- [opem](https://github.com/ECSIM/opem) - Open source simulation tool for proton exchange membrane (PEM) fuel cells.
- [AlphaPEM](https://github.com/gassraphael/AlphaPEM) - Physics-based dynamic model for PEM fuel cells.

### SOFC

- [NGFC-Lib](https://github.com/NGFC-Lib/NGFC-Lib) - Simulation and analysis tools for natural gas fuel cells (SOFC).

## Laboratory Automation

*Packages for automating electrochemical experiments and laboratory workflows.*

### Chemistry and Flow Automation

- [flowchem](https://github.com/cambiegroup/flowchem) - Framework for automated chemistry workflows, with a focus on flow chemistry and electrochemistry.
- [Octopus](https://github.com/richardingham/octopus) - Laboratory automation framework for flow chemistry experiments.

See [LABS](https://aces.onlinelibrary.wiley.com/doi/full/10.1002/asia.202300380) for a review of Python tools for automated electrochemical synthesis.

### Instrument Control

- [pyLabLib](https://github.com/AlexShkarin/pyLabLib/tree/main?tab=readme-ov-file) - Python library for controlling a wide range of laboratory instruments.

---

## See Also

- [awesome-python-chemistry](https://github.com/lmmentel/awesome-python-chemistry) - A broader list of Python packages for chemistry, including quantum chemistry, cheminformatics, and molecular simulation.
- [Python Tools for Electrochemistry (IOP, 2023)](https://iopscience.iop.org/article/10.1149/2754-2734/acff0b) - Peer-reviewed overview of the Python electrochemistry software ecosystem that inspired this list.
