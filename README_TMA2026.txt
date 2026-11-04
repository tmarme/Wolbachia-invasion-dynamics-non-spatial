gyp_sim.cpp (version 04/11/2026) is an adaptation of the original model by Dr Penelope A. Hancock, by Thomas M. Arme.

The aim of these changes are to adapt the original model of unidirectional CI in Aedes aegypti, to a bidirectional system replicating Wolbachia releases in natural Aedes albopictus populations.

Changes made to the original model are indicated with "--NEW--". Please refer to other README file for original unedited features of the model.

To run gyp_sim use the command gyp_sim.exe<gyp_sim_inits.txt
The file gyp_sim_inits.txt contains the following inputs:

Cohort_means.txt (a file for storing the mean development times of
uninfected larvae in each cohort)
Cohort_means_wolb.txt (a file for storing the mean development times
of infected larvae in each cohort)
Cohort_stds.txt (a file for storing the standard deviations of the 
development times of uninfected larvae in each cohort)
Cohort_stds_wolb.txt (a file for storing the standard deviations of
the development times of infected larvae in each cohort)
mu_p.txt (a file for storing the number of uninfected pupae that eclose
on each day)
L_file.txt (a file for storing the number of uninfected larvae present
on each day)
A_file.txt (a file for storing the number of uninfected adults present
on each day)
mu_p_wolb.txt (a file for storing the number of infected pupae that eclose
on each day)
L_wolb_file.txt (a file for storing the number of infected larvae present
on each day)
A_wolb_file.txt (a file for storing the number of infected adults present
on each day)
FreqA2_file.txt (a file for storing the Wolbachia frequency on the final day
of release)
lambda.txt (a file for storing the per-capita female fecundity at the time
that each cohort is hatched)
release_size.txt (a file for storing the size of each Wolbachia release)
700 (the day of the first release) 
0.1 (additional density-INdependent daily mortality experienced by adults 
in the field environment)
0.1 (additional density-INdependent daily mortality experienced by larvae 
 in the field environment)
1 (--NEW-- The strength of CI from the resident population, or the fraction of eggs
from released females that are lost when they mate with resident males)
