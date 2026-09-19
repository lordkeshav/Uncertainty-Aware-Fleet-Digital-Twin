# Uncertainty-Aware-Fleet-Digital-Twin
This repository provides the dataset, numerical results, Python implementation, and reproducibility resources associated with the research work “Privacy-Preserving Uncertainty-Aware Fleet Digital Twin for Predicting PMSM Efficiency Under Unseen Electric-Vehicle Load Profiles.” 
UA-FedFDT Dataset and Reproducibility Package

This repository provides the dataset, numerical results, Python implementation, and reproducibility resources associated with the research work “Privacy-Preserving Uncertainty-Aware Fleet Digital Twin for Predicting PMSM Efficiency Under Unseen Electric-Vehicle Load Profiles.”

The repository is intended to support reproducibility, validation, visualization, and further research on Permanent Magnet Synchronous Motor (PMSM) efficiency prediction, fleet digital twins, federated learning, uncertainty-aware modeling, and electric-vehicle drive-cycle analysis.

Dataset Contents

The package contains structured CSV datasets representing the numerical parameters and results reported in the study, including:

- PMSM machine parameters
- Model-update strategy comparisons
- Fleet posterior parameter estimates
- Validation results
- WLTP ablation-study results
- Benchmark protocol information
- Performance metrics
- Digitized electric-vehicle drive-cycle profiles
- Digitized trust-score and out-of-distribution (OOD) results

The numerical datasets corresponding to the manuscript tables and reported performance metrics are direct transcriptions of the values reported in the study.




The repository contains Python scripts implementing key mathematical components of the UA-FedFDT framework, including:

- Precision-weighted posterior fusion
- PMSM dq-axis modeling
- Thermal-state estimation
- Temperature-dependent parameter modeling
- Magnetic saturation modeling
- Electromagnetic torque calculation
- Motor-loss estimation
- Drive-cycle efficiency calculation

The supplied reproduction script can regenerate selected figures, visualize the digitized drive-cycle and OOD datasets, and verify the principal numerical results reported for the WLTP benchmark.


A detailed record of the origin and status of each dataset is provided in "DATA_PROVENANCE.csv" and "FIGURE_DATA_STATUS.csv".

Intended Applications

This repository may be useful for researchers working on PMSM digital twins, electric-vehicle energy-efficiency modeling, federated learning, uncertainty quantification, privacy-preserving fleet analytics, out-of-distribution detection, predictive maintenance.
