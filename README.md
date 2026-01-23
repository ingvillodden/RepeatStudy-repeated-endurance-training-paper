### RepeatStudy-repeated-endurance-training-paper

# Limited individual reproducibility of physiological adaptations to repeated endurance exercise training

Ingvill Urianstad Odden, Håvard Hamarsland, Tomas Urianstad Odden, Daniel Hammarström, Anne Mette Rustaden, Lise Koll, Marita Hanestadhaugen, Steen Larsen, Stian Ellefsen, Joar Hansen, Håvard Nygaard, Carsten Lundby, Knut Sindre Mølmen

------------------------------------------------------------------------

This repository contains the code needed to reproduce the analyses presented in the manuscript titled "Limited individual reproducibility of physiological adaptations to repeated endurance exercise training".

## Repository structure

Scripts with all code are stored in the `./R` folder.

-   **libs.R:** Contains a list of all packages used in most scripts.

-   **data-preparation:** All data is loaded from the RepeatData package (not publicly available) and prepared for analyses.

-   **pre-test-analysis:** Calculating 1) Test-retest reliability, and 2) Reproducibility of individual pre-test values

-   **activity-level-analysis:** Calculating mean and individual reproducibility of recreational activity level

-   **training-characteristics-analysis:** Calculating 1) Adherence to prescribed interval sessions, 2) Mean (sd) and individual reproducibility of training characteristics, and 3) Reproducibility of individual MMPO 4x5-min response slopes

-   **mmpo4x5min-development-figure2:** Creating a figure showing the development of MMPO 4x5-min per two weeks of training in training periods 1 and 2 (5 sessions per period) with a point estimate indicating whether the mean response slopes of training periods 1 and 2 differ

-   **training-characteristics-figure3:** Creating a figure with nine panels, showing reproducibility of training characteristics for the 4x5-min, 4x8-min, and 6x6-min interval sessions, respectively

-   **training-responses-analysis:** Calculating 1) Mean training responses in training periods 1 and 2, and difference in change, and 2) Reproducibility of individual training responses

-   **group-and-individual-training-responses-figure4:** Creating a figure with 6 panels showing A-C) individual and group mean development in training outcomes in period 1 and 2, and D-F) individual and group mean change scores in period 2 and 2

-   **individual-training-responses-figure5:** Creating a figure with 3 panels showing associations between individual change scores in period 1 and 2

-   **associations-between-outcomes-analysis:** Explorative analysis of whether within-individual response variability in one outcome was associated the within-individual response variability in another outcome

