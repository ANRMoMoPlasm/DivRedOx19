# DivRedOx19
The DivRedOx19 database is a chemical dataset containing 19 reduction and oxidation potentials of 19 diverse organic molecules.

The archive contains 57 structures fully optimized at DFT level (i.e., PBE0/def2-TZVPP) and their respective SCF and Gibbs free energies. It counts
- 19 ground-state structures: file name *_gn.xyz
- 19 oxidized structures: file name *_ox.xyz
- 19 reduced structures: file name *_rd.xyz

The name of each xyz file (i.e., xx_aa_bb.xyz) is decomposed such as:
- xx: molecule name
- aa: charge of the system: {0n: 0, 1a: -1, 2a: -2, 1c: +1, 2c: +2}
- bb: ground-state (gn), oxidized (ox) or reduced (rd) structure
