# Marine Propeller Design – Wageningen B-Series

**Status:** 🚧 Work in progress  
**Author:** Andreas Nohr Olaisen – Mechanical Engineering (BSc), NTNU Trondheim

## Goal
Design and optimise a marine propeller for a given vessel using the Wageningen B-series,
then verify the design with CFD and plan its manufacture.

## Project phases
| Phase | Content | Status |
|---|---|---|
| 1 | B-series open-water model in MATLAB, validated against published charts | ⏳ In progress |
| 2 | Design case + optimisation of P/D, A<sub>E</sub>/A<sub>0</sub> and Z with cavitation constraint (Keller) | ⬜ Planned |
| 3 | Blade geometry generated in MATLAB → CAD in SolidWorks | ⬜ Planned |
| 4 | Open-water CFD in SolidWorks Flow Simulation, mesh study, comparison with MATLAB | ⬜ Planned |
| 5 | Parameter study and design improvement | ⬜ Planned |
| 6 | Manufacturing: process selection and 5-axis CAM / G-code | ⬜ Planned |

## Results
*(Figures will be added here as the project progresses.)*

## Repository structure
```
matlab/    MATLAB code (B-series model, optimisation, geometry)
cad/       SolidWorks files and STEP exports
cfd/       Simulation setup and results
cam/       Toolpaths and G-code
figures/   Plots used in this README and the report
report/    Project report
```

## How to run
*(Will be added when the first scripts are in place.)*

## Limitations
*(Assumptions and known limitations will be documented here.)*

## References
1. Bernitsas, M.M., Ray, D. & Kinley, R.B. (1981). *K<sub>T</sub>, K<sub>Q</sub> and Efficiency Curves for the
   Wageningen B-Series Propellers.* Report No. 237, Dept. of Naval Architecture and Marine Engineering,
   University of Michigan.
2. Oosterveld, M.W.C. & van Oossanen, P. (1975). Further computer-analyzed data of the Wageningen B-screw series.
   *International Shipbuilding Progress*, 22(251).
3. Carlton, J. *Marine Propellers and Propulsion.* Butterworth-Heinemann.
