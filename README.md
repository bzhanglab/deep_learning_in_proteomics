# [Deep learning in proteomics](https://doi.org/10.1002/pmic.201900335)
This is a list of applications of deep learning methods in proteomics. 

Wen, B., Zeng, W.-F., Liao, Y., Shi, Z., Savage, S. R., Jiang, W., Zhang, B., [Deep Learning in Proteomics](https://doi.org/10.1002/pmic.201900335). Proteomics 2020, 20, 1900335.

<img src="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7757195/bin/PMIC-20-1900335-g004.jpg" width="600" height="AUTO">

### Table of contents:

- [Peptide MS/MS spectrum prediction](#peptide-msms-spectrum-prediction)
- [Peptide retention time prediction](#peptide-retention-time-prediction)
- [Peptide CCS prediction](#peptide-ccs-prediction)
- [Peptide detectability prediction](#peptide-detectability-prediction)
- [MS/MS spectrum quality prediction](#msms-spectrum-quality-prediction)
- [Peptide identification](#peptide-identification)
- [Data-independent acquisition mass spectrometry](#data-independent-acquisition-mass-spectrometry)
- [Protein post-translational modification site prediction](#protein-post-translational-modification-site-prediction)
- [MHC-peptide binding prediction](#mhc-peptide-binding-prediction)
- [Benchmarking](#benchmarking)
- [Reviews about deep learning in proteomics](#reviews-about-deep-learning-in-proteomics)


#### Peptide MS/MS spectrum prediction

1. **pDeep**
	- Source code: http://pfind.ict.ac.cn/software/pdeep3
	- Pre-trained models: http://pfind.ict.ac.cn/software/pdeep3
	- Reference:  
		- Zeng, Wen-Feng, et al. "[MS/MS spectrum prediction for modified peptides using pDeep2 trained by transfer learning](https://pubs.acs.org/doi/10.1021/acs.analchem.9b01262)." *Analytical chemistry* 91.15 (2019): 9724-9731.
		- Zhou, Xie-Xuan, et al. "[pDeep: predicting MS/MS spectra of peptides with deep learning](https://pubs.acs.org/doi/10.1021/acs.analchem.7b02566)." *Analytical chemistry* 89.23 (2017): 12690-12697.
		- Ching Tarn, Wen-Feng Zeng. "[pDeep3: Toward More Accurate Spectrum Prediction with Fast Few-Shot Learning](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.0c05427)." *Analytical chemistry* 2021.

2. **Prosit**
	- Source code: https://github.com/kusterlab/prosit
	- Pre-trained models: https://www.proteomicsdb.org/prosit/
	- Prediction: https://www.proteomicsdb.org/prosit/, web server.
	- Reference:  
		- Gessulat, Siegfried, et al. "[Prosit: proteome-wide prediction of peptide tandem mass spectra by deep learning](https://www.nature.com/articles/s41592-019-0426-7)." *Nature methods* 16.6 (2019): 509-518.
	- Application:
		- Verbruggen, Steven, et al. "[Spectral prediction features as a solution for the search space size problem in proteogenomics](https://doi.org/10.1016/j.mcpro.2021.100076)." Molecular & Cellular Proteomics (2021): 100076.
		- Wilhelm, M., Zolg, D.P., Graber, M. et al. [Deep learning boosts sensitivity of mass spectrometry-based immunopeptidomics](https://www.nature.com/articles/s41467-021-23713-9). Nat Commun 12, 3346 (2021).

3. **DeepMass**
	- Web: https://github.com/verilylifesciences/deepmass
	- Pre-trained models: DeepMass::Prism is provided as a service using Google Cloud Machine Learning Engine.
	- Reference:  
		- Tiwary, Shivani, et al. "[High-quality MS/MS spectrum prediction for data-dependent and data-independent acquisition data analysis](https://www.nature.com/articles/s41592-019-0427-6/)." *Nature methods* 16.6 (2019): 519-525.

4. **Predfull**
	- Source code: https://github.com/lkytal/PredFull
	- Pre-trained models: https://github.com/lkytal/PredFull and http://predfull.com/
	- Reference:  
		- Liu, Kaiyuan, et al. "[Full-Spectrum Prediction of Peptides Tandem Mass Spectra using Deep Neural Network](https://pubs.acs.org/doi/10.1021/acs.analchem.9b04867)." *Analytical Chemistry* 92.6 (2020): 4275-4283.

5. **Guan et al.**
	- Source code: https://zenodo.org/record/2652602#.X16LZZNKhTZ
	- Pre-trained models: https://zenodo.org/record/2652602#.X16LZZNKhTZ
	- Reference:  
		- Guan, Shenheng, Michael F. Moran, and Bin Ma. "[Prediction of LC-MS/MS properties of peptides from sequence by deep learning](https://www.mcponline.org/content/18/10/2099.full)." *Molecular & Cellular Proteomics* 18.10 (2019): 2099-2107.

6. **MS<sup>2</sup>CNN**
	- Source code: https://github.com/changlabtw/MS2CNN
	- Pre-trained models: https://github.com/changlabtw/MS2CNN
	- Reference:  
		- Lin, Yang-Ming, Ching-Tai Chen, and Jia-Ming Chang. "[MS2CNN: predicting MS/MS spectrum based on protein sequence using deep convolutional neural networks](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-019-6297-6)." *BMC genomics* 20.9 (2019): 1-10.

7. **DeepDIA**:
	- Source code: https://github.com/lmsac/DeepDIA/
	- Pre-trained models: https://github.com/lmsac/DeepDIA/
	- Reference:  
		- Yang, Yi, et al. "[In silico spectral libraries by deep learning facilitate data-independent acquisition proteomics](https://www.nature.com/articles/s41467-019-13866-z)." *Nature communications* 11.1 (2020): 1-11.

8. **pDeepXL**:
	- Source code: https://github.com/pFindStudio/pDeepXL
	- Pre-trained models: https://github.com/pFindStudio/pDeepXL
	- Reference:  
		- Chen, Zhen-Lin, et al. "[pDeepXL: MS/MS Spectrum Prediction for Cross-Linked Peptide Pairs by Deep Learning](https://pubs.acs.org/doi/10.1021/acs.jproteome.0c01004)." *J. Proteome Res.* 2021.

9. **Alpha-Frag**:
	- Source code: https://github.com/YuAirLab/Alpha-Frag
	- Pre-trained models: https://github.com/YuAirLab/Alpha-Frag
	- Reference:  
		- Jian, Song, et al. "[Alpha-Frag: a deep neural network for fragment presence prediction improves peptide identification by data independent acquisition mass spectrometry](https://doi.org/10.1101/2021.04.07.438629)." *bioRxiv.* 2021.
		
10. **Prosit Transformer**:
	- Source code: 
	- Pre-trained models: 
	- Reference:  
		- Jian, Song, et al. "[Prosit Transformer: A transformer for Prediction of MS2 Spectrum Intensities](https://pubs.acs.org/doi/10.1021/acs.jproteome.1c00870)." *Journal of Proteome Research* 2022.

11. **PrAI-frag**
	- Source code: https://github.com/bertis-prai/PrAI-frag
	- Pre-trained models: https://github.com/bertis-prai/PrAI-frag
	- Prediction: http://www.prai.co.kr/, web server.
	- Reference:  
		- HyeonSeok Shin, Youngmin Park, Kyunggeun Ahn, and Sungsoo Kim "[Accurate Prediction of y Ions in Beam-Type Collision-Induced Dissociation Using Deep Learning](https://pubs.acs.org/doi/10.1021/acs.analchem.1c03184)." *Analytical Chemistry* May 24, 2022.
	

#### Peptide retention time prediction

1. **AutoRT**
	- Source code: https://github.com/bzhanglab/AutoRT
	- Pre-trained models: https://github.com/bzhanglab/AutoRT
	- Reference:  
		- Wen, Bo, et al. "[Cancer neoantigen prioritization through sensitive and reliable proteogenomics analysis](https://www.nature.com/articles/s41467-020-15456-w)." *Nature communications* 11.1 (2020): 1-14.
	- Application:
		- Li, Kai, et al. "[DeepRescore: Leveraging Deep Learning to Improve Peptide Identification in Immunopeptidomics](https://doi.org/10.1002/pmic.201900334)." Proteomics 20.21-22 (2020): 1900334.
		- Rivero-Hinojosa, S., Grant, M., Panigrahi, A. et al. [Proteogenomic discovery of neoantigens facilitates personalized multi-antigen targeted T cell immunotherapy for brain tumors](https://doi.org/10.1038/s41467-021-26936-y). *Nat Commun* 12, 6689 (2021).
		- Daisha Van Der Watt, Hannah Boekweg, Thy Truong, Amanda J Guise, Edward D Plowey, Ryan T Kelly, Samuel H Payne. "[Benchmarking PSM identification tools for single cell proteomics](https://doi.org/10.1101/2021.08.17.456676)." *bioRxiv* 2021.
		- Jiang W, Wen B, Li K, et al. "[Deep learning-derived evaluation metrics enable effective benchmarking of computational tools for phosphopeptide identification](https://doi.org/10.1016/j.mcpro.2021.100171)." *Molecular & Cellular Proteomics*, 2021: 100171.
		- Nekrakalaya, Bhagya, et al. "[Towards Phytopathogen Diagnostics? Coconut Bud Rot Pathogen Phytophthora palmivora Mycelial Proteome Analysis Informs Genome Annotation](https://pubmed.ncbi.nlm.nih.gov/35353641/)." *OMICS: A Journal of Integrative Biology* (2022).
		- Eric B Zheng, Li Zhao (2022) "[Protein evidence of unannotated ORFs in Drosophila reveals diversity in the evolution and properties of young proteins](https://elifesciences.org/articles/78772)" *eLife* 11:e78772.
		- Xiang H, Zhang L, Bu F, Guan X, Chen L, Zhang H, Zhao Y, Chen H, Zhang W, Li Y, Lee LJ, Mei Z, Rao Y, Gu Y, Hou Y, Mu F, Dong X. [A Novel Proteogenomic Integration Strategy Expands the Breadth of Neo-Epitope Sources](https://doi.org/10.3390/cancers14123016). **Cancers**. 2022; 14(12):3016.
		

2. **Prosit**
	- Source code: https://github.com/kusterlab/prosit
	- Pre-trained models: https://www.proteomicsdb.org/prosit/
	- Prediction: https://www.proteomicsdb.org/prosit/, web server.
	- Reference:  
		- Gessulat, Siegfried, et al. "[Prosit: proteome-wide prediction of peptide tandem mass spectra by deep learning](https://www.nature.com/articles/s41592-019-0426-7)." *Nature methods* 16.6 (2019): 509-518.
	- Application:
	 	- Wilhelm, M., Zolg, D.P., Graber, M. et al. [Deep learning boosts sensitivity of mass spectrometry-based immunopeptidomics](https://www.nature.com/articles/s41467-021-23713-9). Nat Commun 12, 3346 (2021).

3. **DeepMass**
	- Web: https://github.com/verilylifesciences/deepmass
	- Pre-trained models: DeepMass::Prism is provided as a service using Google Cloud Machine Learning Engine.
	- Reference:  
		- Tiwary, Shivani, et al. "[High-quality MS/MS spectrum prediction for data-dependent and data-independent acquisition data analysis](https://www.nature.com/articles/s41592-019-0427-6/)." *Nature methods* 16.6 (2019): 519-525.

4. **Guan et al.**
	- Source code: https://zenodo.org/record/2652602#.X16LZZNKhTZ
	- Pre-trained models: https://zenodo.org/record/2652602#.X16LZZNKhTZ
	- Reference:  
		- Guan, Shenheng, Michael F. Moran, and Bin Ma. "[Prediction of LC-MS/MS properties of peptides from sequence by deep learning](https://www.mcponline.org/content/18/10/2099.full)." *Molecular & Cellular Proteomics* 18.10 (2019): 2099-2107.

5. **DeepDIA**:
	- Source code: https://github.com/lmsac/DeepDIA/
	- Pre-trained models: https://github.com/lmsac/DeepDIA/
	- Reference:  
		- Yang, Yi, et al. "[In silico spectral libraries by deep learning facilitate data-independent acquisition proteomics](https://www.nature.com/articles/s41467-019-13866-z)." *Nature communications* 11.1 (2020): 1-11.

6. **DeepRT**:
	- Source code: https://github.com/horsepurve/DeepRTplus
	- Pre-trained models: https://github.com/horsepurve/DeepRTplus
	- Reference:  
		- Ma, Chunwei, et al. "[Improved peptide retention time prediction in liquid chromatography through deep learning](https://pubs.acs.org/doi/10.1021/acs.analchem.8b02386)." *Analytical chemistry* 90.18 (2018): 10881-10888.

7. **DeepLC**:
	- Source code: https://github.com/compomics/DeepLC
	- Pre-trained models: https://github.com/compomics/DeepLC
	- Reference:  
		- Bouwmeester, R., Gabriels, R., Hulstaert, N. et al. [DeepLC can predict retention times for peptides that carry as-yet unseen modifications](https://doi.org/10.1038/s41592-021-01301-5). *Nat Methods* 18, 1363–1369 (2021). 


7. **xiRT**:
	- Source code: https://github.com/Rappsilber-Laboratory/xiRT
	- Pre-trained models: https://github.com/Rappsilber-Laboratory/xiRT
	- Reference:  
		- Giese, S.H., Sinn, L.R., Wegner, F. et al. [Retention time prediction using neural networks increases identifications in crosslinking mass spectrometry](https://www.nature.com/articles/s41467-021-23441-0). *Nat Commun* 12, 3237 (2021).


#### Peptide CCS prediction

1. **DeepCollisionalCrossSection**:
	- Source code: https://github.com/theislab/DeepCollisionalCrossSection
	- Pre-trained models: https://github.com/theislab/DeepCollisionalCrossSection
	- Reference:  
		- Meier, F., Köhler, N.D., Brunner, AD. et al. [Deep learning the collisional cross sections of the peptide universe from a million experimental values](https://www.nature.com/articles/s41467-021-21352-8). Nat Commun 12, 1185 (2021).


#### Peptide detectability prediction

1. **Yu et. al.**:
	- Source code: https://github.com/yuminzhe/yuminzhe-Prediction-of-peptide-detectability-based-on-CapsNet-and-CBAM-module
	- Pre-trained models: https://github.com/yuminzhe/yuminzhe-Prediction-of-peptide-detectability-based-on-CapsNet-and-CBAM-module
	- Reference:  
		- Yu M, Duan Y, Li Z, Zhang Y. [Prediction of Peptide Detectability Based on CapsNet and Convolutional Block Attention Module](https://doi.org/10.3390/ijms222112080). *International Journal of Molecular Sciences*. 2021; 22(21):12080. 


#### MS/MS spectrum quality prediction

1. **SPEQ**:
	- Source code: https://github.com/sor8sh/SPEQ
	- Reference:  
		- Soroosh Gholamizoj, Bin Ma. [SPEQ: Quality Assessment of Peptide Tandem Mass Spectra with Deep Learning](https://doi.org/10.1093/bioinformatics/btab874). *Bioinformatics*. 2022; btab874.


#### Peptide identification

1. **DeepNovo**: De novo peptide sequencing
	- Source code: https://github.com/nh2tran/DeepNovo
	- Pre-trained models: https://github.com/nh2tran/DeepNovo
	- Reference:  
		- Tran, Ngoc Hieu, et al. "[De novo peptide sequencing by deep learning](https://www.pnas.org/content/114/31/8247)." *Proceedings of the National Academy of Sciences* 114.31 (2017): 8247-8252.

2. **DeepNovo-DIA**: De novo peptide sequencing
	- Source code: https://github.com/nh2tran/DeepNovo-DIA
	- Pre-trained models: https://github.com/nh2tran/DeepNovo-DIA
	- Reference:  
		- Tran, Ngoc Hieu, et al. "[Deep learning enables de novo peptide sequencing from data-independent-acquisition mass spectrometry](https://www.nature.com/articles/s41592-018-0260-3)." *Nature methods* 16.1 (2019): 63-66.

3. **SMSNet**: De novo peptide sequencing
	- Source code: https://github.com/cmb-chula/SMSNet
	- Pre-trained models: https://github.com/cmb-chula/SMSNet
	- Reference:  
		- Karunratanakul, Korrawe, et al. "[Uncovering thousands of new peptides with sequence-mask-search hybrid de novo peptide sequencing framework](https://www.mcponline.org/content/18/12/2478)." *Molecular & Cellular Proteomics* 18.12 (2019): 2478-2491.

4. **DeepRescore**: Leveraging deep learning to improve peptide identification
	- Source code: https://github.com/bzhanglab/DeepRescore
	- Reference:  
		- Li, Kai, et al. "[DeepRescore: Leveraging Deep Learning to Improve Peptide Identification in Immunopeptidomics](https://doi.org/10.1002/pmic.201900334)." Proteomics 20.21-22 (2020): 1900334.

5. **PointNovo**: De novo peptide sequencing
	- Source code: https://github.com/volpato30/PointNovo
	- Pre-trained models: https://github.com/volpato30/PointNovo
	- Reference:  
		- Qiao, R., Tran, N.H., Xin, L. et al. "[Computationally instrument-resolution-independent de novo peptide sequencing for high-resolution devices](https://doi.org/10.1038/s42256-021-00304-3)." *Nat Mach Intell* 3, 420–425 (2021). 


6. **pValid 2**: Leveraging deep learning to improve peptide identification
	- Homepage: http://pfind.ict.ac.cn/software/pValid2/index.html
	- Reference:  
		- Zhou, Wen-Jing, et al. "[pValid 2: A deep learning based validation method for peptide identification in shotgun proteomics with increased discriminating power](https://www.sciencedirect.com/science/article/abs/pii/S1874391921003134)." *Journal of Proteomics* (2021): 104414. 


7. **Casanovo**: De novo peptide sequencing
	- Source code: https://github.com/Noble-Lab/casanovo
	- Pre-trained models: https://github.com/Noble-Lab/casanovo
	- Reference:  
		- Melih Yilmaz, William E. Fondrie, Wout Bittremieux, Sewoong Oh, William Stafford Noble. "[De novo mass spectrometry peptide sequencing with a transformer model](https://doi.org/10.1101/2022.02.07.479481)". *bioRxiv*. 2022.
		
8. **PepNet**: De novo peptide sequencing
	- Source code: https://github.com/lkytal/PepNet
	- Pre-trained models: https://github.com/lkytal/PepNet
	- Reference:  
		- Kaiyuan Liu, Yuzhen Ye, Haixu Tang. "[PepNet: A Fully Convolutional Neural Network for De novo Peptide Sequencing](https://www.researchsquare.com/article/rs-1341615/v1)". *Research Square*. 2022.
		
9. **DePS**: De novo peptide sequencing
	- Source code: Not available
	- Pre-trained models: Not available
	- Reference:  
		- Cheng Ge, Yi Lu, Jia Qu, Liangxu Xie, Feng Wang, Hong Zhang, Ren Kong, Shan Chang. "[DePS: An improved deep learning model for de novo peptide sequencing](https://arxiv.org/pdf/2203.08820.pdf)". *arXiv*. 2022.

10. **DeepSCP**: Utilizing deep learning to boost single-cell proteome coverage
	- Source code: https://github.com/XuejiangGuo/DeepSCP
	- Reference:  
		- Bing Wang, Yue Wang, Yu Chen, Mengmeng Gao, Jie Ren, Yueshuai Guo, Chenghao Situ, Yaling Qi, Hui Zhu, Yan Li, Xuejiang Guo, [DeepSCP: utilizing deep learning to boost single-cell proteome coverage](https://doi.org/10.1093/bib/bbac214). Briefings in Bioinformatics, 2022;, bbac214.
		
11. **SpeCollate**: Deep cross-modal similarity network for mass spectrometry data based peptide deductions
	- Source code: https://pcdslab.github.io/SpeCollate/
	- Reference:  
		- Tariq, Muhammad Usman, and Fahad Saeed. [SpeCollate: Deep cross-modal similarity network for mass spectrometry data based peptide deductions](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0259349)." PloS one 16.10 (2021): e0259349.
		
12. **yHydra**: Deep Learning enables an Ultra Fast Open Search by Jointly Embedding MS/MS Spectra and Peptides of Mass Spectrometry-based Proteomics
	- Source code: https://github.com/tzom/yHydra
	- Reference:  
		- Altenburg, Tom, Thilo Muth, and Bernhard Y. Renard. [yHydra: Deep Learning enables an Ultra Fast Open Search by Jointly Embedding MS/MS Spectra and Peptides of Mass Spectrometry-based Proteomics](https://www.biorxiv.org/content/10.1101/2021.12.01.470818v2) bioRxiv (2021).

13. **MSBooster**:  Improving Peptide Identification Rates using Deep Learning-Based Features
	- Source code: https://github.com/Nesvilab/MSBooster
	- Reference:  
		- Kevin L Yang, Fengchao Yu, Guo Ci Teo, Vadim Demichev, Markus Ralser, Alexey I Nesvizhskii. "[MSBooster: Improving Peptide Identification Rates using Deep Learning-Based Features](https://doi.org/10.1101/2022.10.19.512904)" bioRxiv (2021).
			

#### Data-independent acquisition mass spectrometry

1. **Alpha-XIC**
        - Source code: https://github.com/YuAirLab/Alpha-XIC
	- Reference:  
		- Jian Song, Changbin Yu. "[Alpha-XIC: a deep neural network for scoring the coelution of peak groups improves peptide identification by data-independent acquisition mass spectrometry](https://doi.org/10.1093/bioinformatics/btab544)." *Bioinformatics*, btab544 (2021). 

2. **DeepDIA**:
	- Source code: https://github.com/lmsac/DeepDIA/
	- Pre-trained models: https://github.com/lmsac/DeepDIA/
	- Reference:  
		- Yang, Yi, et al. "[In silico spectral libraries by deep learning facilitate data-independent acquisition proteomics](https://www.nature.com/articles/s41467-019-13866-z)." *Nature communications* 11.1 (2020): 1-11.

3. **DeepPhospho**:
	- Source code: https://github.com/weizhenFrank/DeepPhospho
	- Pre-trained models: https://github.com/weizhenFrank/DeepPhospho
	- Web server: http://shuilab.ihuman.shanghaitech.edu.cn/DeepPhospho
	- Reference:  
		- Lou, R., Liu, W., Li, R. et al. [DeepPhospho accelerates DIA phosphoproteome profiling through in silico library generation](https://doi.org/10.1038/s41467-021-26979-1). *Nat Commun* 12, 6685 (2021). 
		

#### Protein post-translational modification site prediction

1. **DeepACE**
	- Source code: https://github.com/jiagenlee/DeepAce
	- Reference:  
		- Zhao, Xiaowei, et al. "[General and species-specific lysine acetylation site prediction using a bi-modal deep architecture](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8487006)." *IEEE Access* 6 (2018): 63560-63569.

2. **Deep-PLA**
	- Web: http://deeppla.cancerbio.info/
	- Prediction: http://deeppla.cancerbio.info/
	- Reference:  
		- Yu, Kai, et al. "[Deep learning based prediction of reversible HAT/HDAC-specific lysine acetylation](https://doi.org/10.1093/bib/bbz107)." *Briefings in Bioinformatics* (2019).


3. **DeepAcet**
	- Source code: https://github.com/Sunmile/DeepAcet
	- Reference:  
		- Wu, Meiqi, et al. "[A deep learning method to more accurately recall known lysine acetylation sites](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2632-9)." *BMC bioinformatics* 20.1 (2019): 49.

4. **DNNAce**
	- Source code: https://github.com/QUST-AIBBDRC/DNNAce/
	- Reference:  
		- Yu, Bin, et al. "[DNNAce: Prediction of prokaryote lysine acetylation sites through deep neural networks with multi-information fusion](https://www.sciencedirect.com/science/article/pii/S0169743919305453)." *Chemometrics and Intelligent Laboratory Systems* (2020): 103999.

5. **pKcr**
	- Web: http://www.bioinfogo.org/pkcr/
	- Prediction: http://www.bioinfogo.org/pkcr/
	- Reference:  
		- Zhao, Yiming, Ningning He, Zhen Chen, and Lei Li. "[Identification of Protein Lysine Crotonylation Sites by a Deep Learning Framework With Convolutional Neural Networks](https://ieeexplore.ieee.org/abstract/document/8959202)." *IEEE Access* 8 (2020): 14244-14252.


6. **DeepGly**
	- Reference:  
		- Chen, Jingui, et al. "[DeepGly: A Deep Learning Framework With Recurrent and Convolutional Neural Networks to Identify Protein Glycation Sites From Imbalanced Data](https://ieeexplore.ieee.org/abstract/document/8852736)." *IEEE Access* 7 (2019): 142368-142378.

7. **Longetal2018**
	- Reference:  
		- Long, Haixia, et al. "[A hybrid deep learning model for predicting protein hydroxylation sites](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6164125/)." *International Journal of Molecular Sciences* 19.9 (2018): 2817.

8. **MUscADEL**
	- Web: http://muscadel.erc.monash.edu/
	- Prediction: http://muscadel.erc.monash.edu/
	- Reference:  
		- Chen, Zhen, et al. "[Large-scale comparative assessment of computational predictors for lysine post-translational modification sites](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6954452/)." *Briefings in bioinformatics* 20.6 (2019): 2267-2290.

9. **LEMP**
	- Web: http://www.bioinfogo.org/lemp
	- Prediction: http://www.bioinfogo.org/lemp
	- Reference:
		- Chen, Zhen, et al. "[Integration of a deep learning classifier with a random forest approach for predicting malonylation sites](ncbi.nlm.nih.gov/pmc/articles/PMC6411950/)." *Genomics, proteomics & bioinformatics* 16.6 (2018): 451-459.

10. **DeepNitro**
	- Web: http://deepnitro.renlab.org/
	- Prediction: http://deepnitro.renlab.org/, both web server and standalone.
	- Reference:
		- Xie, Yubin, et al. "[DeepNitro: prediction of protein nitration and nitrosylation sites by deep learning](https://www.sciencedirect.com/science/article/pii/S1672022918303474)." *Genomics, proteomics & bioinformatics* 16.4 (2018): 294-306.

11. **MusiteDeep**
	- Source code: https://github.com/duolinwang/MusiteDeep
	- Pre-trained models: https://github.com/duolinwang/MusiteDeep
	- Reference:
		- Wang, Duolin, et al. "[MusiteDeep: a deep-learning framework for general and kinase-specific phosphorylation site prediction](https://pubmed.ncbi.nlm.nih.gov/29036382/)." *Bioinformatics* 33.24 (2017): 3909-3916.

12. **NetPhosPan**
	- Web: https://services.healthtech.dtu.dk/service.php?NetPhospan-1.0
	- Prediction: https://services.healthtech.dtu.dk/service.php?NetPhospan-1.0, both web server and standalone.
	- Reference:  
		- Fenoy, Emilio, et al. "[A generic deep convolutional neural network framework for prediction of receptor–ligand interactions—NetPhosPan: application to kinase phosphorylation prediction](https://academic.oup.com/bioinformatics/article/35/7/1098/5088322)." *Bioinformatics* 35.7 (2019): 1098-1107.

13. **DeepPhos**
	- Source code: https://github.com/USTC-HIlab/DeepPhos
	- Pre-trained models: https://github.com/USTC-HIlab/DeepPhos
	- Reference:  
		- Luo, Fenglin, et al. "[DeepPhos: prediction of protein phosphorylation sites with deep learning](https://academic.oup.com/bioinformatics/article/35/16/2766/5270665)." *Bioinformatics* 35.16 (2019): 2766-2773.

14. **EMBER**
	- Source code: https://github.com/gomezlab/EMBER
	- Reference:  
		- Kirchoff, Kathryn E., and Shawn M. Gomez. "[EMBER: Multi-label prediction of kinase-substrate phosphorylation events through deep learning](https://www.biorxiv.org/content/10.1101/2020.02.04.934216v1)." *BioRxiv* (2020).

15. **DeepKinZero**
	- Source code: https://github.com/tastanlab/DeepKinZero
	- Pre-trained models: https://github.com/tastanlab/DeepKinZero
	- Reference:
		- Deznabi, Iman, et al. "[DeepKinZero: zero-shot learning for predicting kinase–phosphosite associations involving understudied kinases](https://academic.oup.com/bioinformatics/article/36/12/3652/5733725)." *Bioinformatics* 36.12 (2020): 3652-3661.

16. **CapsNet_PTM**
	- Source code: https://github.com/duolinwang/CapsNet_PTM
	- Pre-trained models: https://github.com/duolinwang/CapsNet_PTM
	- Reference:
		- Wang, Duolin, Yanchun Liang, and Dong Xu. "[Capsule network for protein post-translational modification site prediction](https://academic.oup.com/bioinformatics/article/35/14/2386/5232223)." *Bioinformatics* 35.14 (2019): 2386-2394.

17. **GPS-Palm**
	- Web: http://gpspalm.biocuckoo.cn
	- Prediction: http://gpspalm.biocuckoo.cn, standalone version.
	- Reference:
		- Ning, Wanshan, et al. "[GPS-Palm: a deep learning-based graphic presentation system for the prediction of S-palmitoylation sites in proteins](https://doi.org/10.1093/bib/bbaa038)." *Briefings in Bioinformatics* (2020).

18. **CNN-SuccSite**
	- Web: http://csb.cse.yzu.edu.tw/CNN-SuccSite/
	- Prediction: http://csb.cse.yzu.edu.tw/CNN-SuccSite/, web server.
	- Reference:
		- Huang, Kai-Yao, Justin Bo-Kai Hsu, and Tzong-Yi Lee. "[Characterization and Identification of Lysine Succinylation Sites based on Deep Learning Method](https://www.nature.com/articles/s41598-019-52552-4)." *Scientific reports* 9.1 (2019): 1-15.

19. **DeepUbiquitylation**
	- Source code: https://github.com/jiagenlee/deepUbiquitylation
	- Pre-trained models: https://github.com/jiagenlee/deepUbiquitylation
	- Reference:  
		- He, Fei, et al. "[Large-scale prediction of protein ubiquitination sites using a multimodal deep architecture](https://link.springer.com/article/10.1186/s12918-018-0628-0)." *BMC systems biology* 12.6 (2018): 109.

20. **DeepUbi**
	- Source code: https://github.com/Sunmile/DeepUbi
	- Reference:  
		- Fu, Hongli, et al. "[DeepUbi: a deep learning framework for prediction of ubiquitination sites in proteins](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2677-9)." *BMC bioinformatics* 20.1 (2019): 1-10.

21. **Sohoko-Kcr**
	- Web server: https://sohoko-research-9uu23.ondigitalocean.app/
	- Reference:  
		- Sian Soo Tng, et al. "[Improved Prediction Model of Protein Lysine Crotonylation Sites Using Bidirectional Recurrent Neural Networks
](https://pubs.acs.org/doi/10.1021/acs.jproteome.1c00848)." *J. Proteome Res.* 2021.


#### MHC-peptide binding prediction

1. **ConvMHC**
	- Web: http://jumong.kaist.ac.kr:8080/convmhc
	- Prediction: http://jumong.kaist.ac.kr:8080/convmhc, web server.
	- Reference:  
		- Han, Youngmahn, and Dongsup Kim. "[Deep convolutional neural networks for pan-specific peptide-MHC class I binding prediction](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1997-x)." *BMC bioinformatics* 18.1 (2017): 585.

2. **HLA-CNN**
	- Source code: https://github.com/uci-cbcl/HLA-bind
	- Pre-trained models: https://github.com/uci-cbcl/HLA-bind
	- Reference:  
		- Vang, Yeeleng S., and Xiaohui Xie. "[HLA class I binding prediction via convolutional neural networks](https://academic.oup.com/bioinformatics/article/33/17/2658/3746909)." *Bioinformatics* 33.17 (2017): 2658-2665.

3. **DeepMHC**
	- Web: http://mleg.cse.sc.edu/deepMHC/
	- Prediction: http://mleg.cse.sc.edu/deepMHC/, web server.
	- Reference:  
		- Hu, Jianjun, and Zhonghao Liu. "[DeepMHC: Deep convolutional neural networks for high-performance peptide-MHC binding affinity prediction](https://doi.org/10.1101/239236)." *bioRxiv* (2017): 239236.

4. **DeepSeqPan**
	- Source code: https://github.com/pcpLiu/DeepSeqPan
	- Pre-trained models: https://github.com/pcpLiu/DeepSeqPan
	- Reference:  
		- Liu, Zhonghao, et al. "[DeepSeqPan, a novel deep convolutional neural network model for pan-specific class I HLA-peptide binding affinity prediction](https://www.nature.com/articles/s41598-018-37214-1)." *Scientific reports* 9.1 (2019): 1-10.

5. **AI-MHC**
	- Web: https://baras.pathology.jhu.edu/AI-MHC/index.html
	- Prediction: https://baras.pathology.jhu.edu/AI-MHC/index.html, web server.
	- Reference:  
		- Sidhom, John-William, Drew Pardoll, and Alexander Baras. "[AI-MHC: an allele-integrated deep learning framework for improving Class I & Class II HLA-binding predictions](https://www.biorxiv.org/content/10.1101/318881v1.full)." *bioRxiv* (2018): 318881.

6. **DeepSeqPanII**
	- Source code: https://github.com/pcpLiu/DeepSeqPanII
	- Pre-trained models: https://github.com/pcpLiu/DeepSeqPanII
	- Reference:  
		- Liu, Zhonghao, et al. "[DeepSeqPanII: an interpretable recurrent neural network model with attention mechanism for peptide-HLA class II binding prediction](https://www.biorxiv.org/content/10.1101/817502v1)." *bioRxiv* (2019): 817502.

7. **MHCSeqNet**
	- Source code: https://github.com/cmb-chula/MHCSeqNet
	- Pre-trained models: https://github.com/cmb-chula/MHCSeqNet
	- Reference:  
		- Phloyphisut, Poomarin, et al. "[MHCSeqNet: a deep neural network model for universal MHC binding prediction](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2892-4)." *BMC bioinformatics* 20.1 (2019): 270.

8. **MARIA**
	- Web: https://maria.stanford.edu/
	- Prediction: https://maria.stanford.edu/, web server.
	- Reference:
		- Chen, Binbin, et al. "[Predicting HLA class II antigen presentation through integrated deep learning](https://www.nature.com/articles/s41587-019-0280-2)." *Nature biotechnology* 37.11 (2019): 1332-1343.

9. **MHCflurry**
	- Source code: https://github.com/openvax/mhcflurry
	- Pre-trained models: https://github.com/openvax/mhcflurry
	- Reference:
		- O'Donnell, Timothy J., et al. "[MHCflurry: open-source class I MHC binding affinity prediction](https://www.sciencedirect.com/science/article/pii/S2405471218302321)." *Cell systems* 7.1 (2018): 129-132.

10. **DeepHLApan**
	- Source code: https://github.com/jiujiezz/deephlapan
	- Pre-trained models: https://github.com/jiujiezz/deephlapan
	- Prediction: http://biopharm.zju.edu.cn/deephlapan/, web server.
	- Reference:
		- Wu, Jingcheng, et al. "[DeepHLApan: a deep learning approach for neoantigen prediction considering both HLA-peptide binding and immunogenicity](https://www.frontiersin.org/articles/10.3389/fimmu.2019.02559/full)." *Frontiers in Immunology* 10 (2019): 2559.

11. **ACME**
	- Source code: https://github.com/HYsxe/ACME
	- Pre-trained models: https://github.com/HYsxe/ACME
	- Reference:
		- Hu, Yan, et al. "[ACME: pan-specific peptide–MHC class I binding prediction through attention-based deep neural networks](https://academic.oup.com/bioinformatics/article/35/23/4946/5497763)." *Bioinformatics* 35.23 (2019): 4946-4954.

12. **EDGE**
	- Source code: [Supplementary data](https://static-content.springer.com/esm/art%3A10.1038%2Fnbt.4313/MediaObjects/41587_2019_BFnbt4313_MOESM48_ESM.zip)
	- Reference:
		- Bulik-Sullivan, Brendan, et al. "[Deep learning using tumor HLA peptide mass spectrometry datasets improves neoantigen identification](https://www.nature.com/articles/nbt.4313)." *Nature biotechnology* 37.1 (2019): 55-63.

13. **CNN-NF**
	- Source code: https://github.com/zty2009/MHC-I
	- Reference:
		- Zhao, Tianyi, et al. "[Peptide-Major Histocompatibility Complex Class I Binding Prediction Based on Deep Learning With Novel Feature](https://www.frontiersin.org/articles/10.3389/fgene.2019.01191/full)." *Frontiers in Genetics* 10 (2019).

14. **MHCnuggets**
	- Web: https://karchinlab.org/apps/appMHCnuggets.html
	- Source code: https://github.com/KarchinLab/mhcnuggets
	- Pre-trained models: https://github.com/KarchinLab/mhcnuggets
	- Reference:
		- Shao, Xiaoshan M., et al. "[High-throughput prediction of MHC class i and ii neoantigens with MHCnuggets](https://cancerimmunolres.aacrjournals.org/content/8/3/396.abstract)." *Cancer Immunology Research* 8.3 (2020): 396-408.

15. **DeepNeo**
	- Web: https://omics.kaist.ac.kr/resources
	- Reference:
		- Kim, Kwoneel, et al. "[Predicting clinical benefit of immunotherapy by antigenic or functional mutations affecting tumour immunogenicity](https://www.nature.com/articles/s41467-020-14562-z)." *Nature communications* 11.1 (2020): 1-11.

16. **DeepLigand**
	- Source code: https://github.com/gifford-lab/DeepLigand
	- Pre-trained models: https://github.com/gifford-lab/DeepLigand
	- Reference:
		- Zeng, Haoyang, and David K. Gifford. "[DeepLigand: accurate prediction of MHC class I ligands using peptide embedding](https://academic.oup.com/bioinformatics/article/35/14/i278/5529131)." *Bioinformatics* 35.14 (2019): i278-i283.

17. **PUFFIN**
	- Source code: http://github.com/gifford-lab/PUFFIN
	- Pre-trained models: https://github.com/gifford-lab/PUFFIN
	- Reference:
		- Zeng, Haoyang, and David K. Gifford. "[Quantification of uncertainty in peptide-MHC binding prediction improves high-affinity peptide Selection for therapeutic design](https://doi.org/10.1016/j.cels.2019.05.004)." *Cell systems* 9.2 (2019): 159-166.

18. **NeonMHC2**
	- Web: https://neonmhc2.org/
	- Source code: https://bitbucket.org/dharjanto-neon/neonmhc2
	- Prediction: https://neonmhc2.org/, web server and standalone version.
	- Reference:
		- Abelin, Jennifer G., et al. "[Defining HLA-II ligand processing and binding rules with mass spectrometry enhances cancer epitope prediction](https://www.sciencedirect.com/science/article/pii/S1074761319303632)." *Immunity* 51.4 (2019): 766-779.

19. **USMPep**
	- Source code: https://github.com/nstrodt/USMPep
	- Reference:
		- Vielhaben, Johanna, et al. "[USMPep: universal sequence models for major histocompatibility complex binding affinity prediction](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-03631-1#Sec14)." *BMC bioinformatics* 21.1 (2020): 1-16.

20. **MHCherryPan**
	- Reference:
		- Xie, Xuezhi, Yuanyuan Han, and Kaizhong Zhang. "[MHCherryPan. a novel model to predict the binding affinity of pan-specific class I HLA-peptide](https://ieeexplore.ieee.org/abstract/document/8982962)." 2019 *IEEE International Conference on Bioinformatics and Biomedicine (BIBM). IEEE*, 2019.

21. **DeepAttentionPan**
	- Source code: https://github.com/jjin49/DeepAttentionPan
	- Pre-trained models: https://github.com/jjin49/DeepAttentionPan
	- Reference:
		- Jin, Jing, et al. "[Attention mechanism-based deep learning pan-specific model for interpretable MHC-I peptide binding prediction](https://doi.org/10.1101/830737)." *bioRxiv* (2019): 830737.


#### Benchmarking

1. Xu R, Sheng J, Bai M, et al. "[A comprehensive evaluation of MS/MS spectrum prediction tools for shotgun proteomics](https://doi.org/10.1002/pmic.201900345)". *Proteomics*, 2020, 20(21-22): 1900345.
2. Wenrong Chen, Elijah N. McCool, Liangliang Sun, Yong Zang, Xia Ning, Xiaowen Liu. "[Evaluation of Machine Learning Models for Proteoform Retention and Migration Time Prediction in Top-Down Mass Spectrometry](https://pubs.acs.org/doi/10.1021/acs.jproteome.2c00124)". *J. Proteome Res.* (2022).
3. Emily Franklin, Hannes L. Röst, "[Comparing Machine Learning Architectures for the Prediction of Peptide Collisional Cross Section](https://doi.org/10.1101/2022.03.01.482566)". *bioRxiv* (2022).


#### Reviews about deep learning in proteomics

1. Wen, B., Zeng, W.-F., Liao, Y., Shi, Z., Savage, S. R., Jiang, W., Zhang, B., "[Deep Learning in Proteomics](https://doi.org/10.1002/pmic.201900335)". *Proteomics* 2020, 20, 1900335.
2. Meyer, Jesse G. "[Deep learning neural network tools for proteomics](https://doi.org/10.1016/j.crmeth.2021.100003)". *Cell Reports Methods* (2021): 100003.
3. Matthias Mann, Chanchal Kumar, Wen-Feng Zeng, Maximilian T. Strauss, [Artificial intelligence for proteomics and biomarker discovery](https://doi.org/10.1016/j.cels.2021.06.006). *Cell Systems* 12, August 18, 2021.
4. Yang, Y., Lin L., Qiao L., "[Deep learning approaches for data-independent acquisition proteomics](https://doi.org/10.1080/14789450.2021.2020654)". *Expert Review of Proteomics* 17 Dec 2021.
5. Cox, J. "[Prediction of peptide mass spectral libraries with machine learning](https://doi.org/10.1038/s41587-022-01424-w)". *Nat Biotechnol* (2022).




