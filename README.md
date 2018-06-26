# PNA_ff_Amber
This directory contains Amber forcefield parameters for Peptide Nucleic Acids with optimized backbone torsions described in:
Jasinski et al. JCTC 2018; DOI 10.1021/acs.jctc.8b00291

The file with corrected torsion angles parameters is: ./LIB/pna_par.opt3.frcmod

The directory contains also an example, prepared with Amber16, showing how to prepare a simulation of a PNA:RNA crystal structure (5EMF).
It uses a PDB file with PNA:RNA coplex only (5emf_noh.pdb), to prepare simulation box with water and ions and all necessary parameters.
To run it, change the location of your Amber (AmberTools) distribution in the tleap.sh script and run it.
If the script runs correctly, it will produce the following files: 5emf.crd  5emf.prm  5emf.amber.pdb  leap.log
Example outputs are in folder example_outputs
