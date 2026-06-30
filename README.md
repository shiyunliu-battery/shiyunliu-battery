## Hi there 👋

I am a battery systems researcher working on research software, data infrastructure, and diagnostic methods for advanced energy storage systems.

My work sits at the intersection of experimental battery characterisation, electrochemical modelling, statistical learning, and battery management. I develop tools for organising battery datasets, standardising cycler exports, fitting electrochemical impedance spectra, and building reproducible workflows for degradation analysis, SOC/SOH estimation, and pack-level diagnostics.

## Selected open-source software

### Battery monitoring and modelling resources

- [Iontech](https://github.com/shiyunliu-battery/Iontech) curates open-source datasets and resources for battery monitoring, state estimation, degradation analysis, and thermal-electrochemical modelling.

### Battery data infrastructure

- [battery-data-standard](https://github.com/shiyunliu-battery/battery-data-standard) is a local Python library and command-line tool for converting battery cycler exports into validated, analysis-ready CSV or Parquet files with auditable conversion reports.

### Electrochemical and degradation diagnostics

- [Battery-EIS-Fit](https://github.com/shiyunliu-battery/Battery-EIS-Fit) is a lightweight Python package for fitting electrochemical impedance spectroscopy data and extracting equivalent-circuit parameters.

- [Battery-Feature-Lab](https://github.com/shiyunliu-battery/Battery-Feature-Lab) extracts battery cycling features from BDS-style exports and common cycler tables for SOH/RUL modelling, feature screening, explainability, and diagnostic summaries.

### State estimation and BMS algorithm examples

- [LFP-ARSR-EKF](https://github.com/shiyunliu-battery/LFP-ARSR-EKF) is a MATLAB battery-algorithm validation framework for LiFePO4 SOC estimation using OCV-region-aware ARSR-EKF, closed-loop BMS simulation, robustness testing, and automated regression checks.

### Lab assistant demo

- [batterylab.online](https://github.com/shiyunliu-battery/batterylab.online) is a local, Windows-first battery lab assistant demo for registry-backed chemistry and method lookup, protocol planning, preflight QA, deterministic CSV analysis, KPI summaries, and structured reporting.
