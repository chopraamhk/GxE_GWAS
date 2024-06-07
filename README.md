# GxE_GWAS
Tutorial: https://jpritikin.github.io/gwsem/GeneEnvironmentInteraction.html
Exploring the potential of genetic sensitivity in different environments. Some consequences and antecedents could lead to the differentially sensitive nature of genetic variants to environmental stimuli. The phenomena involved could be evolutionary pressures and epigenetic effects, 


Installation:
```
#OpenMx is required before:
install.packages("OpenMx")
git clone https://github.com/jpritikin/gwsem
cd gwsem
chmod +x tools/rox
./tools/rox
cd ..  ##go to the parent directory
R CMD INSTALL gwsem R_LIBS_USER
Rscript tools/test.R #make sure that you are in the gwsem directory
library(gwsem)
```


