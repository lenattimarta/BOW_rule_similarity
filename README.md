# BOW_rule_similarity
Python codes (v 3.8.7) for comparing set of rules extracted from classification models, related to the manuscript entitled “Characterization of Synthetic Health Data through Rule-based Artificial Intelligence Models” by Marta Lenatti, Alessia Paglialonga, Vanessa Orani, Melissa Ferretti, and Maurizio Mongelli submitted to the IEEE Journal of Biomedical and Health Informatics, Special Issue Advanced machine learning algorithms for biomedical data and imaging. 

The proposed measure of rule similarity relies on a Bag of Words representation of the rules coupled with cosine similarity and takes into account rules structure, cut-off values and rules covering.


## Contents
* [General info](#general-info)
* [Technologies](#technologies)

### General info
This repository includes:
- a Python notebook for the definition and application of the proposed rule similarity measure
- two examples of rulesets extracted from LLM (Logic Learning Machine) models trained on synthetic hearing screening data
- an example of synthetic dataset 
Note: The proposed examples are based on dummy data. Thus, results obtained with these rulesets will not coincide with published results on real data.

### Technologies
Required libraries:
- pandas
- numpy
- sklearn.metrics.pairwise
- seaborn
- matplotlib

### Notes
The proposed code works with rules derived from LLM (Logic Learning Machine) models, but can be easily adapted to any other kind of machine learning classification methods that allows a rule extraction.
