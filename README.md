# cancer_prostate

## Multiomic Data Analytics Integration in Prostate Cancer

### Background  
Prostate cancer (PCa) is the commonest hormone-dependent oncological disease, which is the second leading cause of tumor-related deaths among males worldwide (Siegel et al. 2019; Bray et al., 2020). Clinically, PCa is characterized by indolent phenotypes, rapid progression and aggressive metastatic disease. In comparison to other tumors, PCa progression is slow yet still harms the patient’s long-term health (Eggener., 2015). The multifocal and heterogeneity nature of primary PCa is associated with poor prognosis (Wang et al. 2018. Current clinicopathological indicators do not distinguish well between patients based on their outcomes at the initial stage of the disease (Zhang et al. 2016), as such intervention for patients with metastasis are still urgently needed. The efficient identification of the risk level of prostate cancer patients and precise therapeutic targets has always been an important equation to solve in PCa. 

In spite of its highest genetic diversity, the African population is reported to have higher prevalence and associated mortality rate of Pca (Cacciatore et al., 2021) in the world. Comparative studies conducted mainly in Africa are crucial to investigate the genetic basis of prostate cancer and its phenotypic adaptation in Africa. Using the African ancestry, some studies successfully fine-mapped important PCa variants, however, these could only explain 30–33% of prostate cancer heritability/variability among individuals/populations (El Jaddaoui et al. 2020). A distinct genomic landscape of PCa and genetic polymorphisms associated with specific ethnic groups may lead to different metabolic adaptations that permit tumor cells to proliferate (Cacciatore et al., 2021). The lack of adequate genetic reference information from the African genome is one of the major obstacles in exploring the benefits of precision oncology in the African context. The high ethnic diversity and prevalence of aggressive PCa in the African population represents an opportunity for biomedical research. Current poor understanding of Pca pathogenesis has limited the effective clinical management of patients with the Pca condition (Sathianathen et al., 2018).

The recent past has seen rapid development and use of high-throughput technologies, such as genomics, transcriptomics, epigenomics, proteomics and metabolomics in attempts of understanding PCa (Kerr et al., 2020). In as much as the single omics technologies have identified and shed light on the mechanisms of the tumor progression, subtypes and finding new treatment targets, the multisystem and multilevel pathological nature of the disease calls for a holistic molecular perspective of the mechanisms, prospective biomarkers and drug targets and responses. This multi-layered analysis can only be uncovered when a systems biology approach is adopted. Hence in the current study we used good quality omics data sets (genomics, and targeted transcriptomics) from public databases to gain a better understanding of tumor progression, subtyping and finding novel biomarkers that potentially address individual variations in drug responses among prostate cancer patients. In addition, we shall also provide a simplified protocol for routine integration of multi-omics data sets to answer biological questions.


### Aim
Identify African descent biomarkers associated with Prostate cancer using multi omics available data for better management of patients. 

### Objectives

1.Explain prostate cancer biological complexity using multi omics approach

2.Provide a simplified and standardized African specific prostate cancer management 

### Outcome Measures 

1.	Genetic profiling results - Mutation identified via whole-genome sequencing will be recorded.
2.	Transcriptional profiling results - Determining the transcriptomic information of prostate cancer

### Methods

#### Workflow

- Single omics 

![Single omics pathways](https://user-images.githubusercontent.com/102041566/161955431-539e2ed4-c488-4e74-978e-ab74649aa6aa.PNG)


- Multi omics 

![image](https://user-images.githubusercontent.com/102041566/161955384-bdb603ec-f4fc-4853-9ddb-937009b3a510.png)


### Tools and software

Whole genome sequence: 
SRA toolkit (url): for sequence retreival
FastQC (url): for sequence read quality analysis, 
BWA (url): Read mapping to reference (hg38) genome, 
Bcftools (url): variant calling, 
snpEff (url): variant annotation and effect prediction 

Targeted RNASeq:
feature count: , 
HTSeq, 
Sleuth, 

Workfolw platforms:
Single-omics analysis can run in Unix and Linux environments.  
Multi-omics analysis pipeline can be run in R. 

### Input and output

Output from single omics will be in .tsv format, which is based on different features (SNPs, transcripts)



## Team structure

### Core members

1-Team lead: [Zedias Chikwambi](https://github.com/zchikambi)

2-Co-lead: [Marie Hidjo](https://github.com/mariehidjo/cancer_prostate)

3-Technical lead: [Pageneck Chikondowa](github.com/pageneck)

4-Writer (Github): [Glory Jayeoba](https://github.com/gloryife)

5-Writer (Manuscript): [Lawrence Afolabi](https://github.com/itslawrenceb)

### Scripting and Workflow team 

1-[David enoma](https://github.com/davidenoma)

2-Glory Jayeoba

3-[Marie Hidjo](https://github.com/mariehidjo/cancer_prostate)

4-[Vincent Aketch Nyangwara](https://github.com/vinaketch)

5-Pageneck Chikondowa

### Manuscript team 

1-[Zedias Chikwambi](https://github.com/zchikambi/) 

2-Lawrence Afolabi

3-David Juma

4-[Mohammed Emon](https://github.com/aakilkhanemon)

### Slides 

1-Zedias Chikwambi

2-Marie Hidjo



### References 

C. Manzoni, D. A. Kia, J. Vandrovcova et al., “Genome, transcriptome and proteome: the rise of omics data and their integration in biomedical sciences,” Briefings in Bioinformatics, vol. 19, no. 2, pp. 286–302, 2018. 

Sung, H.; Ferlay, J.; Siegel, R.L.; Laversanne, M.; Soerjomataram, I.; Jemal, A.; Bray, F. Global Cancer Statistics 2020: GLOBOCAN Estimates of Incidence and Mortality Worldwide for 36 Cancers in 185 Countries. CA Cancer J. Clin. 2021, 71, 209–249. 

Sathianathen, N.J.; Konety, B.R.; Crook, J.; Saad, F.; Lawrentschuk, N. Landmarks in Prostate Cancer. Nat. Rev. Urol. 2018, 15, 627–642. 

Gómez-Cebrián, N.; Poveda, J.L.; Pineda-Lucena, A.; Puchades-Carrasco, L. Metabolic Phenotyping in Prostate Cancer Using Multi-Omics Approaches. Cancers 2022, 14, 596. https://doi.org/10.3390/ cancers14030596
R.L. Siegel, K.D. Miller, A. Jemal, Cancer statistics, 2019, CA Cancer J. Clin. 69 (1)
(2019), https://doi.org/10.3322/caac.21551 (PubMed PMID: 30620402). 

P. Mertins, D.R. Mani, K.V. Ruggles, M.A. Gillette, K.R. Clauser, P. Wang. Proteogenomics connects somatic mutations to signalling in breast cancer, Nature 534 (7605) (2016) 55–62, https://doi.org/10.1038/nature18003 (PubMed PMID: 27251275).

 H. Zhang, T. Liu, Z. Zhang, S.H. Payne, B. Zhang, J.E. McDermott, et al., Integrated
proteogenomic characterization of human high-grade serous ovarian cancer, Cell 166 (3) (2016) 755–765, https://doi.org/10.1016/j.cell.2016.05.069 (PubMed PMID: 27372738).

S.E. Eggener, A.S. Cifu, C. Nabhan, Prostate cancer screening, JAMA 314 (8) (2015) 825–826, https://doi.org/10.1001/jama.2015.8033 (PubMed PMID:26305653). 

G. Wang, D. Zhao, D.J. Spring, R.A. DePinho, Genetics and biology of prostate cancer, Genes Dev. 32 (17–18) (2018) 1105–1140, https://doi.org/10.1101/gad. 315739.118 (PubMed PMID: 30181359). 
R.L. Siegel, K.D. Miller, A. Jemal, Cancer statistics, 2019, CA Cancer J. Clin. 69 (1) (2019), https://doi.org/10.3322/caac.21551 (PubMed PMID: 30620402). 

A. Sinha, V. Huang, J. Livingstone, J. Wang, N.S. Fox, N. Kurganovs, et al., The Proteogenomic landscape of curable prostate cancer, Cancer Cell 35 (3) (2019), https://doi.org/10.1016/j.ccell.2019.02.005 (PubMed PMID: 30889379). 



