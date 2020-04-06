# Combinatorial_BileAcids_DB_COSMIC
Repository for the creation of the Combinatorial Bile Acids Database for COSMIC.

## Instructions
See the notebooks in the *Processing_notebook* for a representating workflow.
- The **Generic** notebook contains the results for all the positional isomers of bile acids (28,630 compounds).
- The **Unique** noteboook contains the results of one representative bile acid per positional isomer (7,010 compounds). The rational is " Since without reference compound, isomerical resolution is limited by fragmentation spectra mass spectrometry, when multiple scaffolds were positional isomers (i.e hydroxyl position on the scaffold), only one representative compound was kept."

## Informations
The combinatorial database is generated with SmiLib 2.0. 

The executable was obtained on [http://melolab.org/smilib/](http://melolab.org/smilib/) and is provided in the *SmiLib_executable* folder.

Citations:
Schüller, A., Hähnke, V. & Schneider, G. SmiLib v2.0: A Java-Based Tool for Rapid Combinatorial Library Enumeration. QSAR Comb. Sci. 26, 407–410 (2007). [https://doi.org/10.1002/qsar.200630101](https://doi.org/10.1002/qsar.200630101).

Schüller, A., Schneider, G. & Byvatov, E. SMILIB: Rapid Assembly of Combinatorial Libraries in SMILES Notation. QSAR Comb. Sci. 22, 719–721 (2003). [https://doi.org/10.1002/qsar.200310008](https://doi.org/10.1002/qsar.200310008).
