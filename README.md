# phenoClustering

This repository contains the complete results of the experiments presented in the paper:

M. Saletta, A. Bombarda, M. Bellini, L. Goisis, P. Cazzaniga, M. Iascone and D.F. Savo. "*Automated Phenotype-Based Clustering of Clinical Reports Using Large Language Models*". Submitted to International Conference on Artificial Intelligence in Medicine (AIME). 2025.

The files [`textclusters.html`](https://htmlpreview.github.io/?https://github.com/Martisal/phenoClustering/blob/main/textclusters.html) and [`phenoclusters.html`](https://htmlpreview.github.io/?https://github.com/Martisal/phenoClustering/blob/main/phenoclusters.html) are 2-dimensional visualizations (obtained by reducing the dimensionality with t-SNE) of the document vectors obtained from the original text and from the extracted phenotypes, respectively. 

The identified clusters are summarized in the following table:

|ID | From text | From phenotypes |
|---|-----------|-----------------|
|0| Dilated cardiomyopathy | Disorders of the skeletal system |
|1 |   Epilepsy |Hypertrophic cardiomyopathy|
|2 |  Hypertrophic cardiomyopathy  |  Developmental delay |        
|3 |  Heterogeneous phenotypes | Heterogeneous phenotypes  |         
|4 |  Neurodevelopmental disorders associated with autism |Wilson disease|      
|5 | Heterogeneous phenotypes  |Heterogeneous phenotypes|          
|6 | Psychomotor delay associated with neurological disorders |Brugada syndrome|
|7 | Heterogeneous phenotypes |Cardiac arrest|          
|8 | Brugada syndrome |ARVC |          
|9 | Hypertrophic cardiomyopathy  |Collagen disorder |          
|10| Heterogeneous phenotypes |Dilated cardiomyopathy|          
|11| Problems with the circulatory system | Developmental delay|           
|12| Neurofibromatosis |Developmental delay|          
|13| Neurodevelopmental disorders without autism |Neurofibromatosis |          
|14|  Heterogeneous phenotypes |RASopathy |            
|15|  Prolonged QT interval |Heterogeneous phenotypes           
|16|  Heterogeneous phenotypes|Alterations in brain morphology|             
|17|  Heterogeneous phenotypes |Epilepsy + other varied phenotypes |          
|18|  Disorders of the skeletal system |Heterogeneous phenotypes|           
|19|  Cholestasis |Left ventricular noncompaction or alterations|           
|20|  Epilepsy along with other neurodevelopmental disorders |Prolonged QT interval   
|21|  Cardiomyopathy and heart disease |Autism spectrum/neurodevelopmental disorders|          
|22|  Myocardial disorders |Cholestasis|           
|23|  Psychomotor delay |Alterations in aorta morphology|          
|24|  Heterogeneous phenotypes |Disorders of the corpus callosum|           
|25|  Heterogeneous phenotypes |Marfanoid habitus |           
|26|  Neurodevelopmental disorders associated with psychomotor delay |Heterogeneous phenotypes|         
|27|  Heterogeneous phenotypes |Hypoglycemia|           
|28| Heterogeneous phenotypes|Ehlers-Danlos syndrome|           
|29|  Heterogeneous phenotypes |Neurodevelopmental disorders|           
|30|  Heterogeneous phenotypes |Intellectual disability           
|31|  LVNC |Heterogeneous phenotypes|           
|32|  Neurodevelopmental disorders  |Heart disorders |          
|33|  Heterogeneous phenotypes |Autism spectrum/neurodevelopmental disorders |            
|34|  Aortic aneurysm  |Epilepsy + other varied phenotypes|           
|35|  Cardiac/circulatory arrest |Hormonal problems (thyroid, gonads, ambiguous genitalia)|         
|36|  Disorders in fetuses |Heterogeneous phenotypes|            
|37|  Neurodevelopmental disorders associated with language disorders  |   Disorders of the digestive system|   
|38|  Heterogeneous phenotypes  |Intellectual disability|          
|39|  Heterogeneous phenotypes    |Heterogeneous phenotypes|         
|40|  Various diseases (Pompe, Gaucher, Caroli, Wilson) |Sensourineural hearing impairment|       
|41|  Prolonged QT interval |Amyloidosis |          
|42|  Aortic disorders |Heterogeneous phenotypes|            
|43|  Neonatal disease |Epileptic disorders |          
|44|  Poor grouth  |Elevated LDL Cholesterol|           
|45|  Neurodevelopmental disorders associated with autism  |Fetal or perinatal disorders|           
|46|  Amyloidosis |Liver disorders | 
|47|  Cardiomyopathy and heart disease  |Muscle problems|          
|48|  Respiratory disorders |Skeletal dysplasia|           
|49|  Language disorders |Fetal anomalies|           
|50|  Cardiomyopathy |Immunological disorders |            
|51|  Male fetus with potential genetic issues |Kidney disorders|           
|52|  Heterogeneous phenotypes |Various diseases (Alagille, Meckel, Coffin-Siris)|           
|53|  Neurodevelopmental disorders associated with psychomotor delay and language disorder |Disorders of the skeletal system|        
|54|  Bone or muscle problems due to neurological issues   |Arterial dissection|        
|55|  Epileptic encephalopathy  |Arterial aneurysm |         
|56|   Intellectual disability |Head disorders (vision, bones, cartilage)|
|57| Heterogeneous phenotypes |Migraine|         

# Citation

If you find this repository useful for your work, please include the following citation:

```
@inproceedings{phenoClustering,
  author       = {Martina Saletta, Andrea Bombarda, Matteo Bellini, Lucrezia Goisis, Paolo Cazzaniga, Maria Iascone and Domenico Fabio Savo},
  title        = {Automated Phenotype-Based Clustering of Clinical Reports Using Large Language Models},
  booktitle    = {International Conference on Artificial Intelligence in Medicine (AIME) [submitted]},
  year         = {2025}
}
```
