Analysis of psychoactive chemicals (phenethylamines and tryptamines) listed in PiKHAL/TiKHAL (written by Alex Shulgin) by structural similarity for the Tang Lab (Seattle Children's Research Institute). 
Error messages are included in a few files to show my progress throughout the project.
Below is a very simplifed breakdown of the process.
1. Created .csv file of 234 chemicals and each of their IDs taken from PubChem (https://pubchem.ncbi.nlm.nih.gov/
2. Converted each ID into a SMILES string using RDKit python library --> converted all SMILES strings into .svg files
3. Measured structural similarity of each chemical via Tanimoto coefficient --> heatmap of all chemicals and their coefficients
4. Graphed chemicals in terms of coefficient values/structural similarity
