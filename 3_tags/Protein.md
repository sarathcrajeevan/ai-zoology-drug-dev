
two type of protein 
 1-fibrous protein
  2-globular

proteins are polymer made up of [[Amino acid]]



### proteins conformation is stabilized largely by weak interactions

folded conformation are called native proteins

stability is the tendency of protein to maintain a native conformation. these are marginally stable

protein with the lowest free energy(most stable) is the protein with the maximum number of weak interactions 

### packing of hydrophobic amino acid away from water favors the protein folding

when the water surrounds the hydrophobic molecules optimal arrangement of molecule result in the highly structured shell or solvation layer

when the non polar groups cluster together the extent of solvation layer decreases and non [[polar]] amino acid tend to concentrate in the interior of the protein


### peptide bond

peptide bond is rigid and planar

peptide conformations are defined by the three dihedral angles also known as torsion angles called $\phi$ (phi),  $\psi$ (psi), and $\omega$ (omega) 



## Secondary structure


a regular secondary structure occurs when the dihedral angle remain the same

few type of secondary structure are stable that is $\alpha$ helix and $\beta$ conformation 

another common type is $\beta$ turn 

secondary structures without a regular pattern are called random coils

### alpha helix   

Pauling and Corey  

in this structure the polypeptide backbone is tightly wound around the imaginary longitudinal in the middle of the helix

there are right handed and left handed $\alpha$ helix 

why does alpha helix forms more readily than many other conformation?
    optimal use of intrahelical hydrogen bond. the structure is stabilized by the hydrogen bond between the hydrogen atom attached to the [[electronegative]] nitrogen atom of peptide linkage  and the electronegative carbonyl oxygen atom of fourth amino acid


##### Amino acid sequence affects stability of alpha helix

not all amino acid have [[intrinsic propensity]] to form $\alpha$ helix, reflecting the properties of the R group 

alanine shows greatest tendency to form $\alpha$ helix 

a constraint in formation of the alpha helix is presence of Pro or [[Glycine (Gly, G)]]residue



### Beta Configuration

1951 Pauling and Corey
in $\beta$ conformation the backbone of the polypeptide chains is extended into zigzag manner

either parallel or antiparallel  
$\beta$ turns connect adjacent segment of a antiparallel $\beta$ sheets   


Ramachandran plot is the visual representation of combination of $\psi$ and $\phi$ dihedral angles  that are permitted in a peptide backbone


## Tertiary and Quaternary structure

three dimensional arrangement of the protein is referred to as the protein's tertiary structure 

arrangement of protein structure in the three dimensional space is called quaternary structure 

protein are classified on the base of higher structure into the fibrous protein with polypeptide chain arranged in long strand or sheets; globular proteins, with polypeptide chains folded into sprerical or globular shape


## PBD protein data bank


resolution less is better

first four letter code is pdb id unique identifier

annotation tab get a idea about the class fold etc

sequence tab get the idea about the where the beta sheet is formed


## Missing Residues

amino acid sequence which are absent in the amnio acid sequence but present in the x ray crystallography



## Fixing missing residues using modeller

download pdb file

to get full length protein sequence download fasta format

inside bin copy paste the repair1 folder which contain the python scripts

open modeller open repair1 folder in modeller 

type mod10.8 script1.py

new file will appear .seq file

script one basically extracted the amino acid sequence from the protein data bank file.


to get the align the file we use pairwise alignment 

copy the  .seq sequence and fasta file sequence and paste

https://www.ebi.ac.uk/jdispatcher/psa/emboss_needle/summary?jobId=emboss_needle-I20251119-152829-0341-87626829-p2m

open alignment file first open seq file copy content and paste it there  

and from the fasta file copy the sequence and give gap

run mod10.8 script2.py

it will fill the gaps


smaller the molpdf value better the structure