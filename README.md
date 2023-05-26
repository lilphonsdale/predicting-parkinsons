# predicting-parkinsons

In these notebooks, I analyze 3 datasets which contain information on Parkinson's Disease patients - their UPDRS scores, protein and peptide levels, taken over a series of visits.

In the EDA notebook, I use the random library to get a look at a single patient over the course of their visits, which helped me to understand the UPDRS scores.

After that, I use random again to look at that same patient's protein and peptide levels in a sample taken from a single visit. This revealed the complexity of the biological data, which motivate me to search for the right model to leverage machine learning to tease out some sense from these numbers.

In the ML notebook, I clean the data in order to prepare for a feature importance analysis. While the predictive model (random forest) doesn't accurately predict severe UPDRS 3 scores, the feature importance does give a starting point for further investigation into peptides and proteins of interest.

Acknowledgements

Thanks to Pandas, Matplotlib, Seaborn, SKLearn and my teammates, Rashed Alkanawi, Ezgi Booth, Emily Pompa, Marc Roca, along with the instructinal team.
