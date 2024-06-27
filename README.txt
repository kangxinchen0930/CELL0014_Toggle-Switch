This folder contains code for the report on Genetic Toggle Switch (and other ones that are not included in the report).

There are two folders.
1) CODE: contain al the codes required for this report.
2) FIGURES: contain all the figures generated for this report, even those that are not included.

Each folder is divided into three folders: PART A, PART B and Optional.

- figure included in report
* figure not included in report
_______________________________

PART A: Simplified model

* {*Figure 1} is not included in the report and corresponds to the steady state values of P in a model for gene expression under a repressor

- The files {Figure 3}, {Figure 4}, {Figure 5},  {Figure 6} and {Figure 7} contain codes for the simple ODE model.
    - {Figure 3} -> Protein steady state level over a range of repressor level for different n values
    - {Figure 4} -> ODE toggle switch model simulation showing the protein copies over time for different n
    - {Figure 5} -> Bifurcation plot of the ODE toggle switch model
    - {Figure 6} -> Phase plots of the simplified ODE toggle switch model for different n
    - {Figure 7} -> 2D-bifurcation plot of the simple ODE model.

_______________________________

PART B: Extended model

- The file {Figure 8,9,10} contains code for the deterministic extended model comparing with the reduced model, including the simulations and phase-plots.

* The code for the reduced model is found in file {Figure 8, 9, 10}. A separate file code is provided named {Reduced model}.
* The extended simulation showing whether the stochastic states are stable over a long period, as well as the corresponding phase plots are found in file {Figure 11B, 12, 13, 14A (lowP1_highP2)} and {Figure 11A, 14B (highP1_lowP2)} with the corresponding initial conditions.

- The file {Figure 11B, 12, 13, 14A (lowP1_highP2)} contains code for the stochastic extended model with initial conditions of high P1 and low P2. The file {Figure 11A, 14B (highP1_lowP2)} contains code for the stochastic extended model with initial conditions of low P1 and high P2.
    - For figure 12 and 13, they contain codes for stochastic stimulation of multiple runs (either 5 or 200 runs).
    - The file by default shows the code for 200 runs.
    - To run the code for 5 runs, uncomment #n_runs = 5 and comment #n_runs = 200
    - Also uncomment #n_runs = 5 and comment #n_runs = 200
    - The corresponding figures for high P1 and low P2 can found in the file FIGURES as:
        - fig12_highP1.png
        - fig13_highP1.png
        
/!\ CAUTION: running 200 runs will take a least a good 3 minutes. Please run as appropriate. Alternatively find the appropriate figures in the report or you can find it in the file FIGURES.

______________________________

Optional: includes the basal transcription rate

- The file {Basal_simulations} contains the optional task model simulation which including basal transcription rates. {Figure 15} is the corresponding 2D bifurcation plot.

* Phase plot for the optional task code can be found in {*Figure 16}, which is saved as phase_plot_basal.png in FIGURES.
__________________________________________

Other files:

- {helper_function.py} is required for running the file {Figure 6}.
- {helper_function1.py} is required for running the file {Figure 8,9,10}.