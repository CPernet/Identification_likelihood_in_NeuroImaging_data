# Identification_-likelihood_in_NeuroImaging_data  
Data and analysis supporting expert consensus rating on identification  likelihood in NeuroImaging data.  
In this project, experts independently listed data types and evidence of re-identification risk. From those lists, tables of data types were built and used to make a survey. The survey data are analysed here.

## Analysis

The results are from two surveys (data type order counter-balanced) and analysed in the [Jupyter notebook above](https://github.com/CPernet/Identification_likelihood_in_NeuroImaging_data/blob/main/ratings_analysis.ipynb).

## Outcomes

- All but one imaging type has data rated from 1 to 5, i.e. even among neuro-imaging experts, there are debates depending on data type. This is also likely due to the large variability in data types, and no one can be an expert in all of them.
- Only Raw MRI/CT data are seen at high risk in any cases, which is easily understandable given that faces can be reconstructed/rendered as images.
- Likelihood of re-identification and singling-out are mildly corrected for data type (~0.5), given that re-identification is possible, so is singling out, but the counterpart is not always true. 

