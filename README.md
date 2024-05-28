# Statistics-Script
This repository contains the script implemented to generate the box plots and to conduct the statistical analysis per metric per reference structure. 
The script includes some example numbers for the values of each metrics (RMSD, common contacts, LGA, LCS and GDT), and also the models names in the vectors in order to create the data frames. 
From this data, the script is programmed to provide:
- Box plots for each of the addressed metrics
- Pre-hoc analysis: Fligner-Killeen's and Levene's tests
- Kruskal-Wallis test
- Post-hoc analysis: Dunn-Bonferroni's and Conover-Iman tests

**Please, notice how the script includes the lines to generate the LCS box plot appart from the rest of the metrics. This is because in this case, the LCS data frame does not share the same dimensions as the ones for RMSD, common contacts, LGA or GDT. 
