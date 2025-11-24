

initial positions of all atoms 


## inter atomic energies


In biological molecules, there can be the [[covalent]] interactions, [[coulomb's interaction]], Van Der Waal's interaction, [[hydrogen bond]]s or electronic interactions.

[[Force]] 

## steps

### 1.preparation of protein 3D structure

Step-1: Clean your structure from water 

grep -v HOH your_structure.pdb > str_clean.pdb

grep command is used to get the string characters 
-v = match character argument
HOH = water molecules
 in this command, we are requesting Linux to get all of the from the test PDB file and remove HOH and store the file with the new name.


### 2.preparation of protein topology file
The force fields are the mathematical description that we use to model how atoms and molecules interact with each other at the Atomic State.

The topology file contains all necessary information to define molecule within a simulation.

gmx pdb2gmx -f str_clean.pdb -o str_processed.gro -water spce

gmx = let the system know to initiate GROMACS

pdb2gmx = GROMACS function to prepare topology file

-f = file input

-o = output file name

 -water = define water system
then we can see menu
The topology files are going to be prepared by using the force field.

These are the 15 type of the force fields which are available in the Gromacs system to prepare the topology
### 3. solvation and ionization

### 4. Energy minimization

 steepest descent algorithm

### 5. Equilibrium phase


### 6.Production stage




