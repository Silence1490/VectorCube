# VectorCube

Open-source repository containing the raw data, CAD files, and fully reproducible analysis for the VectorCube project. Includes all materials required to rebuild the VectorCube trap, reproduce the statistical analyses (GLMM/GAMM), and regenerate all tables and figures from the associated scientific publication.

## VectorCube – Data, Construction Files & Reproducible Analysis

This repository contains the complete dataset, CAD construction files, and analysis scripts used in the VectorCube study. It enables full reconstruction of the VectorCube trap and complete reproducibility of all statistical analyses and results from the associated scientific publication.

## Contents
Raw and processed data
CAD files and building instructions for the VectorCube
R scripts for GLMM/GAMM analyses
Reproducible environment (renv)
Generated figures and tables

All tables, figures, and models from the manuscript can be regenerated directly from the scripts provided here.

 ## VectorCube Construction (Condensed)

The VectorCube is a modular airflow-based insect trap consisting of a central airflow distributor, an inline duct fan, a pipe-based intake system, and an aluminium frame enclosed by a tarpaulin cover.

### Core components
Interior airflow block (milled or 3D printed),
Inline duct fan (100–125 mm diameter, ~270 CFM),
DN 75 pipes with push-fit sockets (European standard),
20 × 20 mm aluminium square tubing with corner connectors,
Tarpaulin cover with hook-and-loop fasteners,
Optional capture chamber (DN 75 to 50 reducer + Falcon tube)

### Assembly overview
Prepare interior block
Manufacture or print the airflow distributor and ensure smooth internal channels.
Mount fan
Attach the inline duct fan to the top of the block (use adapter for milled version).
The ribbed fan outlet may need to be sanded down to achieve an airtight fit.
Install pipes
Insert four horizontal and one vertical DN 75 pipes into the block. Ensure tight, airtight connections.
Assemble frame
Construct the frame from 20 × 20 mm aluminium square tubing and position the airflow system centrally.
Align openings
Ensure the intake openings in the outer cover align with the pipe ends.
Install cover
Enclose the frame with the custom tarpaulin cover. Close the lid using hook-and-loop fasteners.
Colored foils can be attached externally for visual attraction.
Final setup
Connect the fan to a power supply (e.g., 12V DC) and verify correct airflow direction (upward suction).
Additional notes
An 87° DN 110 pipe elbow can be installed at the fan outlet to prevent rain from entering the system.
CO₂ sources (e.g., yeast fermentation, dry ice, or bottled CO₂) can be added to enhance attraction.
The system is modular and can be adapted with different capture mechanisms.
Full construction manual

For detailed instructions, see:

/docs/VectorCube_Construction_Manual.docx
