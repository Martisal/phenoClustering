# phenoClustering

This repository contains the complete results of the experiments presented in the paper:

M. Saletta, A. Bombarda, M. Bellini, L. Goisis, P. Cazzaniga, M. Iascone and D.F. Savo. "*Automated Phenotype-Based Clustering of Clinical Reports Using Large Language Models*". Submitted to International Conference on Artificial Intelligence in Medicine (AIME). 2025.

The files [`textclusters.html`](https://htmlpreview.github.io/?https://github.com/Martisal/phenoClustering/blob/main/textclusters.html) and [`phenoclusters.html`](https://htmlpreview.github.io/?https://github.com/Martisal/phenoClustering/blob/main/phenoclusters.html) are 2-dimensional visualizations (obtained by reducing the dimensionality with t-SNE) of the document vectors obtained from the original text and from the extracted phenotypes, respectively. 

The identified clusters are summarized in the following table, along with the corresponding silhouette scores:

|ID | From text | From phenotypes |
|---|-----------|-----------------|
|0| Dilated cardiomyopathy - 0.74 | Disorders of the skeletal system - 0.14|
|1 |   Epilepsy - 0.12 |Hypertrophic cardiomyopathy - 0.92 |
|2 |  Hypertrophic cardiomyopathy - 0.38 |  Developmental delay - 0.05 |        
|3 |  Heterogeneous phenotypes - 0.11| Heterogeneous phenotypes - 0.01 |         
|4 |  Neurodevelopmental disorders associated with autism - 0.17 |Wilson disease - 0.30 |      
|5 | Heterogeneous phenotypes - 0.53 |Heterogeneous phenotypes - 0.05|          
|6 | Psychomotor delay associated with neurological disorders - 0.14 |Brugada syndrome - 0.97|
|7 | Heterogeneous phenotypes - 0.08 |Cardiac arrest - 0.45|          
|8 | Brugada syndrome - 0.73 |ARVC - 0.78|          
|9 | Hypertrophic cardiomyopathy - 0.90 |Collagen disorder - 0.90|          
|10| Heterogeneous phenotypes - 0.04 |Dilated cardiomyopathy - 0.78|          
|11| Problems with the circulatory system - 0.02 | Developmental delay - 0.10|           
|12| Neurofibromatosis - 0.53 |Developmental delay - 0.09|          
|13| Neurodevelopmental disorders without autism - 0.02 |Neurofibromatosis - 0.64|          
|14|  Heterogeneous phenotypes - 0.03 |RASopathy - 1.00|            
|15|  Prolonged QT interval - 0.63 |Heterogeneous phenotypes - 0.02 |         
|16|  Heterogeneous phenotypes - 0.01 |Alterations in brain morphology - 0.02 |             
|17|  Heterogeneous phenotypes - 0.06 |Epilepsy + other varied phenotypes - 0.04|          
|18|  Disorders of the skeletal system - 0.00 |Heterogeneous phenotypes - 0.04|           
|19|  Cholestasis - 0.54 |Left ventricular noncompaction or alterations - 0.33|           
|20|  Epilepsy along with other neurodevelopmental disorders - 0.07 |Prolonged QT interval - 0.80 |  
|21|  Cardiomyopathy and heart disease - 0.14 |Autism spectrum/neurodevelopmental disorders - 0.23|          
|22|  Myocardial disorders - 0.03 |Cholestasis - 0.37|           
|23|  Psychomotor delay - 0.08 |Alterations in aorta morphology - 0.15|          
|24|  Heterogeneous phenotypes - 0.02 |Disorders of the corpus callosum - 0.17|           
|25|  Heterogeneous phenotypes - 0.06 |Marfanoid habitus - 0.86|           
|26|  Neurodevelopmental disorders associated with psychomotor delay - 0.08 |Heterogeneous phenotypes - 0.01|         
|27|  Heterogeneous phenotypes - 0.05 |Hypoglycemia - 0.11|           
|28| Heterogeneous phenotypes - 0.04 |Ehlers-Danlos syndrome - 0.56|           
|29|  Heterogeneous phenotypes - 0.03 |Neurodevelopmental disorders - 0.06|           
|30|  Heterogeneous phenotypes - 0.07 |Intellectual disability - 0.08|          
|31|  LVNC - 0.55 |Heterogeneous phenotypes - 0.04|           
|32|  Neurodevelopmental disorders - 0.01 |Heart disorders - 0.03|          
|33|  Heterogeneous phenotypes - 0.13 |Autism spectrum/neurodevelopmental disorders - 0.11|            
|34|  Aortic aneurysm - 0.27 |Epilepsy + other varied phenotypes - 0.20|           
|35|  Cardiac/circulatory arrest - 0.37 |Hormonal problems (thyroid, gonads, ambiguous genitalia) - 0.03|         
|36|  Disorders in fetuses - 0.06 |Heterogeneous phenotypes - 0.01|            
|37|  Neurodevelopmental disorders associated with language disorders - 0.11 |   Disorders of the digestive system - 0.04|   
|38|  Heterogeneous phenotypes - 0.03 |Intellectual disability - 0.13 |          
|39|  Heterogeneous phenotypes - 0.01 |Heterogeneous phenotypes - 0.02|         
|40|  Various diseases (Pompe, Gaucher, Caroli, Wilson) - 0.35 |Sensourineural hearing impairment - 0.29 |       
|41|  Prolonged QT interval - 0.31 |Amyloidosis - 0.44|          
|42|  Aortic disorders - 0.12 |Heterogeneous phenotypes - 0.03|            
|43|  Neonatal disease - 0.08 |Epileptic disorders - 0.09|          
|44|  Poor grouth - 0.06 |Elevated LDL Cholesterol - 0.75 |           
|45|  Neurodevelopmental disorders associated with autism - 0.08 |Fetal or perinatal disorders - 0.00|           
|46|  Amyloidosis - 0.30 |Liver disorders - 0.13| 
|47|  Cardiomyopathy and heart disease - 0.05 |Muscle problems - 0.06|          
|48|  Respiratory disorders - 0.08|Skeletal dysplasia - 0.25|           
|49|  Language disorders - 0.01|Fetal anomalies - 0.09|           
|50|  Cardiomyopathy - 0.17|Immunological disorders - 0.10|            
|51|  Male fetus with potential genetic issues - 0.16|Kidney disorders - 0.09|           
|52|  Heterogeneous phenotypes - 0.00|Various diseases (Alagille, Meckel, Coffin-Siris) - 0.03|           
|53|  Neurodevelopmental disorders associated with psychomotor delay and language disorder - 0.19 |Disorders of the skeletal system - 0.03|        
|54|  Bone or muscle problems due to neurological issues - 0.01 |Arterial dissection - 0.27|        
|55|  Epileptic encephalopathy - 0.22 |Arterial aneurysm - 0.30|         
|56|   Intellectual disability - 0.11 |Head disorders (vision, bones, cartilage) - 0.06|
|57| Heterogeneous phenotypes - 0.01 |Migraine - 0.53|         

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
