[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/27410/group-assignment-2021-group-9-surfactin/main)

# 27410 - Group assignment - Group 9 - Surfactin production in Bacillus subtilis

## Project summary
The aim of this project is to evalulate surfactin production in *Bacillus subtillis*. For this purpose four surfactin reactions have been added to an already known GSM of *B. subtillis* s. 168. After surfactin knock-in, different strategies for getting a higher yield have been tested. This includes changing carbon source, upregulation of genes that effect yield found via FSEOF, co-factor swap, and knockout of target genes. 
Phenotypic phase plans have been used to evaulate the changes in carbon source and yield calculations have been made to follow the production of surfactin throughout changes made to the model. 

## Project overview
The 'Pictures' folder includes pictures used in the project.
'Report.ipynb' has the written report to this project. 
Under the 'Analysis' folder you can find our code, where each assessment has its own file.
- Calculations: Includes flux and yield calculations.
- Cofactorswapanalysis: Cofactor swap analysis
- Gene_targets: Computed gene targets for downregulation/upregulation.
- Manual_knockouts: Knocking out reactions suggested by scientific papers.
- model_sucrose: Model with sucrose as carbon source. 
- model: Model with added surfactin production.
- OptGene: Runs the OptGene algorithm.
- OptKnock: Runs the OptKnock algorithm.
- Phenotypic_phase_planes: PPP analysis.
- Production_pathways: Computing surfactin production pathways.