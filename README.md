# Parentage_analysis_opposing_homozygositys_offspring_with_all_candidate_parents

Parentage analysis (calculating opposing homozygosity) between individuals and candidate parents. ohFinder is a FORTRAN code that can be downloaded along with a toy example. An example input and output files are shown below and can also be found in the parameter file.

The example is for 3 candidate parents, 5 progeny and 10 markers (missing markers = 5):

An example of 3 parents file
 ----------------------------------------
HO467 1022501150   
192SSe 2201121200   
HO4D 1222550000        

An example of 5 offspring file
----------------------------------------
A2727 0500052202    
R15R 5152525022    
9999 1210002021    
56f 2222100220    
1A02 2021102121    

=========================================================================================#
 The output file contains 9 columns:
----------------------------------------------------------------------------------------
  1. Original ID for the candidate parent
  2. Original ID for the progeny
  3. A new ID for the candidate parent (starts from 1: i.e., the order in the genotype file) 
  4. A new ID for the animal (starts from 1: i.e., the order in the genotype file)
  5. Total number of markers 
  6. Number of informative markers
  7. Number of markers with opposing homozygosity
  8. Number of missing markers for the progeny
  9. Number of missing markers for the parent
 10. Number of missing markers for both (the progeny and the parent)
 11. % Opposing homozygosity
----------------------------------------------------------------------------------------

