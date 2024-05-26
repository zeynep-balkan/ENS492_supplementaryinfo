# ENS492 Graduation Project

## Executive Summary
The project aims to discover cryptic sites on proteins: hidden, transient pockets in proteins for binding that are not observable using traditional methods. The protein this project focuses on is TEM-1 β-lactamase enzyme, an enzyme that is involved in resistance mechanisms. By concentrating on this enzyme, which is a crucial component of resistance to β-lactam antibiotics, the project tackles the vital problem of antibiotic resistance. The wild-type enzyme effectively breaks down penicillin but exhibits minimal activity against third-generation cephalosporins like ceftazidime (CAZ) and cefotaxime (CTX).

The project used a TEM-1 β-lactamase enzyme, with the code 1ZG4 in Protein Data Bank (PDB). The protein coded 1ZG4 is an apoenzyme, meaning that it lacks a coenzyme bound to it. The reason a TEM-1 β-lactamase enzyme was chosen is that the enzyme was shown to have cryptic sites.

The project uses an enhanced-sampling method, accelerated MD (aMD), as its main technique. Accelerated MD is a tool that reduces energy barriers, allowing for the exploration of rare events and conformational changes in biomolecules. Accelerated MD does this by applying a bias potential to smoothen the energy landscape, thus reducing energy barriers.

The project found that accelerated MD can be a viable method to be used in finding allosteric sites within the protein. It significantly reduces the time needed to reach higher energy levels required for finding cryptic sites.

## Problem Statement
The project aims to tackle the pressing problem of antibiotic resistance by detecting allosteric sites in the TEM-1 β-lactamase enzyme. The project's goal is to help build more potent antibiotics that can overcome current resistance by identifying these locations.

Accelerated MD speeds up the exploration of rare events and protein shape changes by lowering energy barriers. This makes it better at uncovering hidden pockets in proteins, which standard MD might miss because it samples more slowly. While the observation of rare events might take over 500 nanoseconds, this can be achieved using aMD much more quickly and with less computational power.

Accelerated MD allows the protein to explore different energy states more effectively, avoiding the bottlenecks that can trap it in certain conformations during standard molecular dynamics (sMD).

## Files and Directories
- `scripts/`: Directory containing the scripts used in this project.
- `data/`: Directory containing input data files.
- `results/`: Directory where output results are saved.
- `config/`: Configuration files used for molecular dynamics simulations.

### Prerequisites
List any software or libraries required to run your project.
- VMD
- NAMD
- Python

## Contributing
If you welcome contributions to your project, provide guidelines on how others can contribute.

## Contact
For questions, bugs, or feature requests, please open an issue in this repository.
