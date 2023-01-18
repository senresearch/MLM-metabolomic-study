# Matrix Linear Models for connecting metabolite composition to individual characteristics

Gregory Farage<sup>1</sup>, Chenhao Zhao<sup>2</sup>, Suneeta Godbolec<sup>3</sup>, Michelle Puchowicz<sup>4</sup>, Marshall B.
Elame<sup>5, 6</sup>, Rajendra Raghow<sup>6</sup>, Timothy J. Garrett<sup>7</sup>, Katerina Kechrisc<sup>3</sup>,  Śaunak Sen<sup>1</sup>

><sup>1</sup>Department of Preventive Medicine, University of Tennessee Health Science Center, Memphis, TN 38163   
<sup>2</sup>Geisel School of Medicine, Dartmouth College, Hanover, NH 03755  
<sup>3</sup>Department of Biostatistics & Informatics, Colorado School of Public Health, University of Colorado Anschutz Medical Campus, Aurora, CO 80045   
<sup>4</sup>Department of Pediatrics, University of Tennessee Health Science Center, Memphis, TN 38163   
<sup>5</sup>Department of Pharmacology, University of Tennessee Health Science Center, Memphis, TN 38163   
<sup>6</sup>Department of Medicine, University of Tennessee Health Science Center, Memphis, TN 38163   
<sup>7</sup>Department of Pathology, Immunology and Laboratory Medicine, University of Florida Health,Gainesville, FL 32610  

### Abstract     
Extracting information from high-throughput omics data remains a significant challenge. MatrixLinear Models (MLM) is a family of bilinear models we developed to investigate associations in high-throughput data. This approach allows for the aggregation of signals across samples and features within a single model, which differs from typical statistical metabolomics analysis, where each metabolite is first analyzed separately for correlations with sample characteristics. Then, another investigation is necessary to identify patterns among similar features. MLM algorithm unifies these two steps and provides measures of statistical significance. We illustrate MLM's flexibility, speed, and effectiveness by applying it to two metabolomic studies. We demonstrate how the MLM framework can also estimate relationships between metabolites based on their common characteristics, such as type or pathway, or numerical properties, like the number of double bonds in triglycerides. We show how our method further enables us to differentiate between two related attributes of triglycerides: the number of carbon atoms and the number of double bonds, which would be lost when lipids are analyzed separately. We have implemented our method in an open-source Julia package called MatrixLM, and it can be further explored using interactive notebooks.

### Materials

- [Pluto notebook Analysis](https://htmlview.glitch.me/?https://github.com/senresearch/MLM-metabolomic-study/blob/main/PlutoReportMLMtriglycerideGwithFishOil.jl.html)

### References:

- Liang, J. W., Nichols, R. J., & Sen, Ś. (2019). Matrix linear models for high-throughput chemical genetic screens. Genetics, 212(4), 1063–1073. doi: [10.1534/genetics.119.302299.](https://academic.oup.com/genetics/article/212/4/1063/5931246)
- Liang, J. W. & Sen, Ś. (2021). Sparse matrix linear models for structured high-throughput data. To appear in The Annals of Applied Statistics. [arXiv preprint: arXiv:1712.05767 [stat.CO].](https://arxiv.org/abs/1712.05767)
- Gillenwater, Lucas A., Katerina J. Kechris, Katherine A. Pratte, Nichole Reisdorph, Irina Petrache, Wassim W. Labaki, Wanda O’Neal, Jerry A. Krishnan, Victor E. Ortega, Dawn L. DeMeo, and Russell P. Bowler. 2021. "Metabolomic Profiling Reveals Sex Specific Associations with Chronic Obstructive Pulmonary Disease and Emphysema" Metabolites 11, no. 3: 161. [https://doi.org/10.3390/metabo11030161](https://doi.org/10.3390/metabo11030161)
- Koelmel, J. P. (2018). Lipidomics for wildlife disease etiology and biomarker discovery: a case study of pansteatitis outbreak in South Africa (part-I), NIH Common Fund's National Metabolomics Data Repository (NMDR) website, the Metabolomics Workbench, https://www.metabolomicsworkbench.org, Summary of Study ST001052, doi: 10.21228/M8JH5X

### Resources:

- [MatrixLM.jl package](https://github.com/senresearch/MatrixLM.jl)
- [MatrixLMnet.jl](https://github.com/senresearch/MatrixLMnet.jl)
- [MetabolomicsWorkbenchAPI.jl](https://github.com/senresearch/MetabolomicsWorkbenchAPI.jl)
- [Sen Research Group Resources](https://senresearch.github.io/)





