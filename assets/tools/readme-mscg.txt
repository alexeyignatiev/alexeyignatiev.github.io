### README for the MSCG MaxSAT solver

MSCG implements core-guided MaxSAT algorithms. Depending on the type of instance, MSCG executes the following algorithms:

* MSU1   - for plain MaxSAT instances            [FM06, MMSP09]
* PRGBCD - for partial MaxSAT instances          [IMMLMS14]
* OLLI   - for weighted partial MaxSAT instances [MDMS14]

Given a MaxSAT instance in <file>, execute MSCG as:

% mscg <file>


References:

[FM06] Z. Fu, S. Malik: On Solving the Partial MAX-SAT Problem. SAT 2006: 252-265

[MMSP09] V. Manquinho, J. Marques-Silva, J. Planes: Algorithms for Weighted Boolean Optimization. SAT 2009: 495-508

[IMMLMS14] A. Ignatiev, A. Morgado, V. Manquinho, I. Lynce, J. Marques-Silva: Progression in Maximum Satisfiability. ECAI 2014: 453-458

[MDMS14] A. Morgado, C. Dodaro, J. Marques-Silva: Core-Guided MaxSAT with Soft Cardinality Constraints. CP 2014: 564-573


Authors: Joao Marques-Silva, Alexey Ignatiev, and Antonio Morgado
Contributors: Carmine Dodaro, Ines Lynce, and Vasco Manquinho

## Copyright 2014 Joao Marques-Silva, Alexey Ignatiev, and Antonio Morgado
