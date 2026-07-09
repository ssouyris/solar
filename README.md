# Accelerating the Adoption of Residential Solar Power Systems: Supplementary Data

This repository hosts supplementary data for the manuscript "Accelerating the Adoption of Residential Solar Power Systems: Policy Analysis using a Dynamic Structural Model" (Souyris, Duan, Balakrishnan, and Rai). The paper develops and estimates a forward-looking dynamic structural model of residential rooftop-solar adoption and uses it for policy analysis.

This release contains data only. It currently provides the Appendix A supplementary material.

## Contents

```
solar/
├── README.md            # this file
├── LICENSE              # CC-BY-4.0; governs the data in this repository
├── CITATION.cff         # machine-readable citation metadata
└── data/
    └── appendix_A_household_incentive_survey/
        ├── Household_Incentive_Survey.pdf          # narrative appendix
        ├── Household_Incentive_Survey_Matrix.xlsx  # machine-readable program matrix
        └── README.md                               # data dictionary and provenance
```

## Appendix A: Household-technology incentive survey

Appendix A catalogues 221 U.S. federal and state household-technology incentive programs: 16 federal programs and 205 state and major-utility programs across all fifty states. Each program is coded against the four structural features of the adoption model: an NPV-based durable good, a time-varying incentive path, visibility to neighbors, and a forward-looking timing margin. Sources include the Database of State Incentives for Renewables and Efficiency (DSIRE), Internal Revenue Service guidance, and U.S. Department of Energy program documentation, current to June 2026. The folder-level `README.md` gives the full data dictionary, coding scheme, and caveats.

## Licensing

The materials in this repository are data and are released under the Creative Commons Attribution 4.0 International License (CC-BY-4.0). The full text is in `LICENSE`. Reuse is free provided the accompanying manuscript is cited.

This release does not include source code. If analysis or replication code is added in a future release, it will be licensed separately under the MIT License, and this section will be updated to record the split between the code license and the data license.

## How to cite

Please cite the accompanying manuscript. Machine-readable metadata is in `CITATION.cff`.

Souyris S, Duan J, Balakrishnan A, Rai V (2026) Accelerating the adoption of residential solar power systems: Policy analysis using a dynamic structural model. Manuscript under review.

## Contact

Questions about the data may be directed to the corresponding author (Sebastian Souyris, souyrs@rpi.edu).
