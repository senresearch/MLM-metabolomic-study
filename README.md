# Matrix Linear Models: an application to a metabolomic study


Gregory Farage<sup>1</sup>, Timothy J. Garrett<sup>2</sup>, Michelle A. Puchowicz<sup>3</sup>, Qingming Dong<sup>4</sup>, Christopher J. Cieker<sup>4</sup>, Dale Childress<sup>5</sup>, Edwards A. Park<sup>4</sup>, Claire L. Simpson<sup>6</sup>, Rajendra Raghow<sup>4</sup>, Marshall B. Elam<sup>4, 5</sup>, Saunak Sen<sup>1</sup>

><sup>1</sup>Department of Preventive Medicine, College of Medicine, University of Tennessee Health Science Center, Memphis, TN   
<sup>2</sup>Department of Pathology, Immunology and Laboratory Medicine, University of Florida Health, Gainesville, FL    
<sup>3</sup>Department of Pediatrics, College of Medicine, University of Tennessee Health Science Center, Memphis, TN   
<sup>4</sup>Department of Pharmacology, College of Medicine, University of Tennessee Health Science Center, Memphis, TN   
<sup>5</sup>Department of Medicine, College of Medicine, University of Tennessee Health Science Center, Memphis, TN   
<sup>6</sup>Department of Genetics, Genomics & Informatics, College of Medicine, University of Tennessee Health Science Center, Memphis, TN   

     
Identifying the relevant clinical information within high-throughput omics data remains a significant challenge. Integrating multiple data sources, such as different -omics or environmental datasets, makes it possible to highlight potentially underestimated information in analyzing just one source level. Our objective was to examine differences in the metabolomic profiling of plasma samples between patients with and without statin-associated muscle symptoms (SAMS) and how the statins alter metabolomes in patients with SAMS. A confounding factor in these associations was fish oil supplementation which we adjusted for in our analysis. We used our Matrix Linear Models (MLMs) framework, a family of bilinear models for studying associations in structured high-throughput data. This framework allows estimating relationships in metabolites sharing known characteristics, whether categorical (e.g., type of metabolite or lipid) or numerical (e.g., number of double bonds in triglycerides). In more classical omic analyses, methods tend to uncover novel associations between high-throughput data and sample covariates separately, ignoring the potential information in the correlation between measurements. The MLM method lays out a flexible structure to find those connections between sample characteristics and attributes of measures. This framework can be applied to various studies where attributes of measures are known, such as drug screening of cancer cell lines or eQTL experiments.

### Materials

- [Pluto notebook Analysis](https://htmlview.glitch.me/?https://github.com/senresearch/MLM-metabolomic-study/blob/main/PlutoReportMLMtriglycerideGwithFishOil.jl.html)

### References:

- Liang, J. W., Nichols, R. J., & Sen, Ś. (2019). Matrix linear models for high-throughput chemical genetic screens. Genetics, 212(4), 1063–1073. doi: [10.1534/genetics.119.302299.](https://academic.oup.com/genetics/article/212/4/1063/5931246)
- Liang, J. W. & Sen, Ś. (2021). Sparse matrix linear models for structured high-throughput data. To appear in The Annals of Applied Statistics. [arXiv preprint: arXiv:1712.05767 [stat.CO].](https://arxiv.org/abs/1712.05767)


### Resources:

- [MatrixLM.jl package](https://github.com/senresearch/MatrixLM.jl)
- [MatrixLMnet.jl](https://github.com/senresearch/MatrixLMnet.jl)
- [Sen Research Group Resources](https://senresearch.github.io/)





