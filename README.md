# STX_Hydration_Equilibria
DFT calculations for Gibbs free energy of ketone hydration (dG_hydration) model across a series of saxitoxin (STX) derivatives (collaboration with the Looper Lab, University of Utah).
- All energies reported in kcal/mol
- Final models built with dG_hydration for STX set to 0.00 kcal/mol (relative hydration energies with respect to STX).
- Low energy conformers (LECs can be found in the original SI)
Please cite the use of these calculations in future work with the following:
Wenyuan, Li.; Paladugu, S.; Liles, J. P.; Karthikeyan, M.; Chase, K.; Raghuraman, S.; Sigman, M. S.; Looper, R. E. Macrocyclic Analogs of (+)-Saxitoxin: insights into the structure of Zeteketoxin AB. _manuscript in progress_.__
-------------------------------------------------------------------------------------------------------------
Packages & Details:
Schrödinger MacroModel (release 2022-1)
Number of Steps: 10,000
Energy Window: 5 kcal/mol
Force Field: OPLS4
Solvent: Water
- All conformers were taken forward and optimized further at the DFT level of theory. Single point energetic corrections were then applied (vida infra).

Gaussian16 (Revision C.01)
-------------------------------------------------------------------------------------------------------------
Optimization Method: wB97XD
Optimization Basis Set: Def2-SVP
Optimization Solvation Model: SMD, Solvent=Water
- Verified by frequency computations as minima (no imaginary frequencies)
  
Single Point Method:
Single Point Basis Set: Def2-TZVP
Single Point Solvation Model: SMD, Solvent=Water
- NBO (3.1)
- ChelpG, Hirshfeld, and CM5 charges
- NMR shifts (GIAO) 
-------------------------------------------------------------------------------------------------------------
