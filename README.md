"""
## Classifying-EMPA-mineral-data

This project is for CMPT 3830: ML Work Integrated Project course at Norquest College, and is completed by Laura Brin

The model uses measurements from 12 element oxides to classify the EMPA sample into one of 7 minerals: olivine, garnet, clinopyroxene, orthopyroxene, nickel oxide, chromite and spinel. The samples used for training come from MG-rich peridoties and as such the model is not sutible for use on other rock compositions at the moment. 

The purpose of this workbook was to test KNN Classification and Decision Tree models to determine which performs better at this task. Hyperparameter testing was then completed. Validation using an unseen data set was performed with both models producing high accuracy.

An input model for new samples is roughly sketched up with both the code and the new data template being in a development phase


## Future work/additions
>add component for including detection limits

>add postprocessing stoichiometry

>create seperate notebook for submitting new EMPA data and receiving classification using same excel document

>add new minerals

>add new compositions of current minerals

>explore if trends seen in other analysis (PGE, whole rock, ICPMS) can be identified by a ML algorithm to help direct future work on samples



If you have any questions please contact me at laura.e.brin@gmail.com