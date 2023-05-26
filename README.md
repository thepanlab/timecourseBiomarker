### Introduction

This is the code repository for the GLMM analysis of metabolomic biomarker discovery in the paper “Persistent Biofluid Small Molecule Alterations Induced by Trypanosoma Cruzi Infection Are Not Restored by Antiparasitic Treatment.”

### Folder structure

├── data       
│   ├── Biomarkers Full Data ... wMeta_TIC_plasma_20210520.csv	**data for plasma**      
│   └── Biomarkers Full Data ... wMeta_TIC_saliva_20210520.csv	**data for saliva**      
├── result      
│   ├── plasma       
│   ├── plasma_isoproterenol	**result for plasma under isoproterenol treatment**      
│   ├── saliva      
│   └── saliva_isoproterenol      
└── script      
    ├── plasma_drawSignificantGlmm.Rmd	**visualize GLMM result**      
    ├── plasma_glmmRealTime.Rmd	**for GLMM analyze**      
    ├── plasma_isoproterenol_drawSignificantGlmm.Rmd      
    ├── plasma_isoproterenol_glmmRealTime.Rmd      
    ├── saliva_drawSignificantGlmm.Rmd      
    ├── saliva_glmmRealTime.Rmd      
    ├── saliva_isoproterenol_drawSignificantGlmm.Rmd      
    └── saliva_isoproterenol_glmmRealTime.Rmd      