# Cyanines Computational Chemistry Research Project

This is the central GitHub repository for Inhoo Chang's computational chemistry research project on the excitations of cyanines.

In total, 49 calculations were performed in 10 sets, of which only 25 were mainly used within the paper (5 for each molecule, 1 for each functional). The other 24 were initial calculations that were later re-performed due to a mistake within the calculation process. Some of these mistakes were an incorrect CPCM model, an incorrectly modeled molecule, and an error during optimization. Additional details on each of these 49 calculations can be found within the file `computations.md`.

Here is a short description of each computational set, and why they were (or weren't) chosen to be included in the final paper. 

 

 - **Set #1:** Unused due to having used an incorrect structure that lacked substituents and gem-dimethyls, and lacked a CPCM.
 - **Set #2:** Unused in favor of Section #6 due to changing to a CPCM methanol solvation model for excitations.
 - **Set #3:** Unused in favor of Section #6 due to changing to a CPCM water solvation model for geometrical optimization.
 - **Set #4: Main computation used for the Cy5 series.**
 - **Set #5: Main computation used for the Cy7 series.**
 - **Set #6: Main computation used for the Cy3 series.**
 - **Set #7:** Unused in favor of Section #9 due to an incorrectly optimized final model that included cis transfigurations in the central carbon chain.
 - **Set #8:** Unused in favor of Section #10 due to an incorrectly optimized final model that included cis transfigurations in the central carbon chain.
 - **Set #9: Main computation used for the Cy9 series.**
 - **Set #10: Main computation used for the Cy11 series.**

Inside each folder, the files with the extension `.inp` are the ORCA input files, and the files in the same folder with the extension `.out` are its corresponding ORCA output files. 