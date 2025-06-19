## Objectives
- Simulate subsonic and transonic flow over two airfoils.
- Evaluate lift (CL), drag (CD) and pressure distribution.
- Perform mesh convergence test to ensure accuracy.
- Compare results with experimental benchmarks (NASA and AGARD).

## Tools Used
- **SU2**: Flow simulation (steady, RANS, Spalart-Allmaras)
- **Pointwise**: Mesh generation and grid refinement
- **ParaView**: Post-processing (Cp plots, pressure/mach contours)

## Key Achievements
- Built robust CFD workflow using Pointwise (C-type mesh) and SU2.
- Achieved strong agreement between numerical and experimental results for both airfoils.
- Validated that NACA 2412 suffers significantly higher drag at transonic speeds due to stronger shockwaves.
- Demonstrated the influence of geometry on shock strength and wave drag.
