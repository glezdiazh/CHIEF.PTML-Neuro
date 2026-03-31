# CHIEF.PTML-Neuro

# Title: CHIEF.PTML: Chirality Models for Compounds Targeting  Proteins Expressed in Brain Regions.

# Authors: 
Brenda Fundora-Ortiz,1; Harbil Bediaga,2; Maider Baltasar-Marchueta, 1; Matthew M Montemore,3; 
Sonia Arrasate,1; Nuria Sotomayor,1; Esther Lete,1 and Humberto González-Díaz,1,4,5,*

# Affiliations:
1 Department of Organic and Inorganic Chemistry, University of the Basque Country UPV/EHU, 48940, Leioa, Spain.
2 MIK, Bussiness Inovation Technology Center, Mondragon University, 48011, Bilbao, Spain.
3 Department of Chemical and Biomolecular Engineering, Tulane University, 6823 St. Charles Avenue, New Orleans, Louisiana 70118, United States.
4 Biofisika Institute, CSIC-UPV/EHU, 48940, Leioa, Spain.
5 IKERBASQUE, Basque Foundation for Science, 48011, Bilbao, Spain.

* Corresponding authors: HGD = humberto.gonzalezdiaz@ehu.eus
  
# ABSTRACT. 
In this work we introduce the Chirality Information Encoding Fusion Perturbation Theory Machine Learning (CHIEF.PTML) methodology. These new functions can discriminate enantiomers/stereoisomers with multiple stereogenic elements (stereogenic centers, axes, planes, helixes). The new CHIEF.PTML model was trained/validated with the same dataset as our previous model containing 794108 preclinical assays with n(c₀) = 369 output biological properties, n(c₁) = 124 gen, n(c₂) = 134 target proteins, n(c₃) = 70 cell lines, n(c₄) = 6 brain regions, n(c₅) = 28 assay organisms, and n(c₆) = 9 original organisms. The model gives sensitivities, specificities, and accuracies of 80-81% on the training and validation series, including 65538 unique chiral/non-chiral compounds. Specifically, the model shows values Sn, Sp, and Ac = 80-85% in training/validations series for 226836 assays of 24424 unique chiral compounds, including 890 pairs of enantiomers/diasteromers. Additional nonlinear classification models were constructed using the Python scikit-learn package. Among these, the random forest (RF) model (CHIEF.PTML-RF) demonstrated the highest predictive capability, attaining accuracy exceeding 95%, precision above 75%, recall (sensitivity) above 70%, F1-score above 72%, and an area under the receiver operating characteristic curve (AUROC) greater than 0.96 in both the training and validation series. This model could be useful to prioritizing enantiomers and stereoisomers as well as no chiral molecules for biological assays in drug discovery endeavors.

# Keywords: 
Chiral compounds; Biological activity; Neurodegenerative diseases; Machine Learning; Brain Protein Expression.

# Authors Contributions:

BF (1st author) = Methodology, Formal analysis, Investigation, Data Curation, Writing - Original Draft, Writing - Review & Editing, Visualization; LL = Data Curation, Writing - Original Draft, Writing - Review & Editing, Visualization; MMM = Methodology, Writing - Review & Editing SA = Conceptualization, Methodology, Formal analysis, Investigation, Data Curation, Writing - Original Draft, Writing - Review & Editing, Visualization, Resources, Supervision, Project administration, Funding acquisition; NS = Conceptualization, Methodology, Formal analysis, Investigation, Data Curation, Writing - Original Draft, Writing - Review & Editing, Visualization, Resources, Supervision, Project administration, Funding acquisition; EL = Conceptualization, Methodology, Formal analysis, Investigation, Data Curation, Writing - Original Draft, Writing - Review & Editing, Visualization, Resources, Supervision, Project administration, Funding acquisition; HGD = Conceptualization, Methodology, Formal analysis, Investigation, Data Curation, Writing - Original Draft, Writing - Review & Editing, Visualization, Resources, Supervision, Project administration, Funding acquisition. Authors with a contribution of 1st author listed above should be considered as first authors of this paper equally.




