# Religious Environmental Mobilization ABM

This repository contains the NetLogo model, simulation outputs, figures, and supplementary documentation for the article:

**From Religious Environmental Belief to Environmental Mobilization: A Theoretical Agent-Based Model**

Author: Sezai Doruk Soyata  
Affiliation: Department of Sociology, Koç University, Istanbul, Turkey

## Overview

This project develops a theoretical, literature-informed agent-based model of religious environmental mobilization. The model examines when religious environmental belief remains symbolic and when it becomes collective environmental mobilization.

The model is designed for mechanism clarification rather than empirical prediction. It does not estimate real-world levels of religious environmental activism in any specific country, religious tradition, organization, or environmental movement.

## Repository structure

The repository contains four main folders:

- `Model/` contains the NetLogo model file.
- `Data/` contains the raw simulation outputs exported from NetLogo BehaviorSpace.
- `Figures/` contains PNG and PDF versions of the manuscript figures.
- `Supplement/` contains the ODD protocol and model documentation.

## Model

The model represents 1,000 agents distributed across 20 religious communities. Agents vary in stewardship belief, trust in science, trust in religious leaders, political identity, climate risk exposure, perceived activism cost, environmental concern, moral obligation, community norm strength, mobilization score, and mobilization status.

Agents can occupy one of six statuses:

- passive
- concerned
- symbolic steward
- norm supporter
- mobilized
- resistant

The model examines 12 main scenarios:

1. baseline
2. high stewardship
3. high risk
4. activist leader
5. skeptical leader
6. high polarization
7. high capacity
8. risk + activist
9. risk + capacity
10. activist + capacity
11. combined activation
12. full alignment

Each main scenario is run for 150 ticks and repeated 30 times. A threshold sensitivity analysis is also conducted for selected scenarios.

## Data

The `Data` folder contains two raw simulation output files:

- `main_scenarios_raw.csv`
- `threshold_sensitivity_raw.csv`

These files were exported from NetLogo BehaviorSpace. No human-subject data were used in this study.

## How to run the model

1. Open the NetLogo Model file in the `Model` folder.
2. Open BehaviorSpace in NetLogo.
3. Run the `main_scenarios` experiment to reproduce the main scenario results.
4. Run the `threshold_sensitivity` experiment to reproduce the threshold sensitivity results.
5. Compare the exported outputs with the files in the `Data` folder.

## Supplementary material

The `Supplement` folder contains the ODD protocol and model documentation.

## Citation

Please cite the associated article when using this repository.
