# PhylTree

Using the Unweighted Pair Group Method with Arethmatic mean(UPGMA) to make Phylogenetic Trees.

## Input Data
- DNA sub-sequences have been given in the "Nucleotide_alignment.txt" file, for the first question. <br>
- Protien sub-sequences hae been given in "Protein_alignment.txt" file for the second question.
- "BLOSUM62.txt" is to be used for the scoring function in the 2nd question.

## Aim

<b>1. Construct a phylogenetic relationship for the given nucleotide sequences. </b><br>
 <b>a.</b> Write a script to generate a distance matrix csv file for the sequences present in the data
file. Name the distance matrix file as 'Ndistance.txt'.<br>
 <b>b.</b> Write a script that uses 'Ndistance.txt' and generate phylogeney relationship between the
organisms using UPGMA method.

<b>2. Construct a phylogenetic relationship for the given protein sequences.</b> <br>
 <b>a.</b> Write a script to generate a distance matrix csv file for the sequences present in the data
file. Name the distance matrix file as 'Pdistance.txt'. <br>
 <b>b.</b> Write a script that uses 'Pdistance.txt' and generate phylogeney relationship between the
organisms using UPGMA method.

## Procedure
- Scoring functions are used to generate a distance matrix in the part <b>a.</b> of the question.
- The distance matrix is used to get the Phylogenetic Trees using the UPGMA method in part <b>b.</b>
