# radiusofgyration_pdb
Bash + gfortran code that calculates the radius of gyration of a molecular dynamics trajectory file (in PDB format) and provides a frequency distribution (resolution 1A).

How to use it:

Copy the PDB file(s), rog.bash and rog.f90 files in a common directory and run:

./rog.bash your_pdb.pdb

You will get two results files:

results-your_pdb.pdb.dat with listing #frame Rog (in Angstrom)

distr-rog-last1000ns-your_pdb.pdb.dat with Rog(in Angstrom, at 2A, 3A, 4A...99A) Freq (Rog(i) in %)

Any doubt, contact me: santiago.alonso.gil@univie.ac.at or dr.s.alonso-gil@gmx.com

Cheers!
