## Hi there 👋

I am a battery systems researcher working on research software, data infrastructure, and diagnostic methods for advanced energy storage systems.

My work sits at the intersection of experimental battery characterisation, electrochemical modelling, statistical learning, and battery management. I develop tools for organising battery datasets, standardising cycler exports, fitting electrochemical impedance spectra, and building reproducible workflows for degradation analysis, SOC/SOH estimation, and pack-level diagnostics.

## Selected open-source software

### Battery monitoring and modelling resources

- [Iontech](https://github.com/shiyunliu-battery/Iontech)  
  Open-source battery monitoring and modelling resources.

### Battery data infrastructure

- [battery-data-standard](https://github.com/shiyunliu-battery/battery-data-standard)  
  Python library and CLI for converting battery cycler exports into clean, analysis-ready CSV and Parquet files, with intake QA and metadata-aware processing.

This project addresses one of the most common bottlenecks in battery research: inconsistent raw cycler exports. It provides a structured data layer for downstream diagnostics, degradation modelling, and algorithm validation.

### Electrochemical and degradation diagnostics

- [Battery-EIS-Fit](https://github.com/shiyunliu-battery/Battery-EIS-Fit)  
  Python tools for electrochemical impedance spectroscopy fitting and equivalent-circuit parameter analysis.

- [Battery-Feature-Lab](https://github.com/shiyunliu-battery/Battery-Feature-Lab)  
  Feature-engineering toolkit for battery degradation analysis, cycle-level summaries, diagnostic evidence extraction, and reproducible ageing studies.

These repositories focus on extracting interpretable diagnostic information from battery experiments, including impedance parameters, degradation-sensitive features, and structured evidence for capacity-fade analysis.

### State estimation and BMS algorithm examples

- [LFP-ARSR-EKF](https://github.com/shiyunliu-battery/LFP-ARSR-EKF)  
  OCV-region-aware SOC estimation and closed-loop BMS validation framework for LiFePO4 batteries.

This MATLAB framework implements bounded online effective ECM parameter adaptation, region-aware EKF correction, closed-loop current limiting, robustness testing, and automated regression checks. The project demonstrates an engineering-style workflow for battery algorithm development rather than a single-script SOC estimation example.

### Lab assistant demo

- [batterylab.online](https://github.com/shiyunliu-battery/batterylab.online)  
  A web-based battery lab assistant demo for presenting research software, organising methods, and supporting reproducible battery analysis workflows.
