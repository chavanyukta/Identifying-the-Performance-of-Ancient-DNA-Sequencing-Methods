# Identifying the Performance of Ancient DNA Sequencing Methods

**Final Report**  
Author: Yukta Sanjiv Chavan (Student ID: a1873167)  
Date: August 09, 2024  
School of Mathematical Sciences, University of Adelaide  
Project Supervisor: Dr. Indu Bala

---

## Project Overview

This project evaluates the performance of two ancient DNA sequencing methodologies — the Twist Bioscience capture assay and the 1240k capture assay — using the EAGER dataset. The aim is to determine the most effective method for sequencing degraded and contaminated ancient DNA samples by employing advanced statistical techniques including linear and logistic regression, mixed effects models, and beta regression.

---

## Abstract

Ancient DNA (aDNA) sequencing plays a vital role in understanding human evolution and migration. However, analyzing aDNA is challenging due to contamination and degradation. This study compares the Twist and 1240k capture assays using performance metrics such as SNP coverage, mapped reads, endogenous DNA percentage, and contamination estimates. Advanced statistical models reveal that the Twist assay generally outperforms the 1240k assay in efficiency, data quality, and coverage consistency. These findings provide important guidance for future aDNA research.

---

## Dataset Source

The dataset used in this project is the **EAGER ancient DNA sequencing dataset**, which contains metrics from sequencing experiments such as SNPs, input reads, mapped reads, endogenous DNA percentages, and other key variables.

This dataset was provided by Dr. Indu Bala and is based on sequencing results from ancient DNA samples processed using the Twist Bioscience and 1240k capture assays.

For more information on related datasets and sequencing methodologies, see:

- Mathieson et al. (2015), *Genome-wide patterns of selection in 230 ancient Eurasians*, Nature.  
- Lipson et al. (2017), *Parallel palaeogenomic transects reveal complex genetic history of early European farmers*, Nature.

**Note:** The dataset contains sensitive genetic data and should be handled with appropriate ethical considerations.

---

## Methods

- Data filtering and preprocessing including missing data handling, outlier removal, normalization, and scaling.  
- Statistical modeling: linear regression, linear mixed effects models, mixed effects generalized regression, and beta regression.  
- Model selection based on p-values, ANOVA, AIC/BIC, likelihood ratio tests, and assessment of fixed and random effects.  
- Diagnostic visualizations including QQ plots and density plots to assess model assumptions and data distributions.

---

## Key Findings

- **Twist assay outperforms 1240k** in most performance metrics, including higher SNP coverage, more mapped reads, higher endogenous DNA percentage, and better GC content stability.  
- Twist requires fewer enrichment cycles, improving efficiency and reducing contamination risk.  
- Mixed effects models capture variability across samples and confirm the significance of sequencing method effects.  
- Beta regression models effectively analyze proportional data such as contamination and duplication rates.  
- Diagnostic plots show Twist provides more consistent SNP coverage across samples.

---

## Conclusion

The Twist Bioscience capture assay provides a more reliable and effective method for ancient DNA sequencing compared to the traditional 1240k assay. Its superior performance in SNP coverage, data quality, and reduced redundancy makes it a preferred choice for ancient DNA studies. These results emphasize the importance of selecting appropriate sequencing technologies to ensure accurate genetic analysis and improve our understanding of human genetic history.

---

## Acknowledgements

I sincerely thank Dr. Ben Rohrlach and Dr. Indu Bala for their invaluable guidance and support throughout this project. Their expertise in ancient DNA sequencing and statistical modeling greatly contributed to the success of this study.

---

## References

1. Paabo, S., et al., 2004. Genetic Analyses from Ancient DNA. *Annual Review of Genetics*, 38, pp.645-679.  
2. Willerslev, E. and Cooper, A., 2005. Ancient DNA. *Proceedings of the Royal Society B*, 272(1558), pp.3-16.  
3. Mathieson, I., et al., 2015. Genome-wide patterns of selection in 230 ancient Eurasians. *Nature*, 528(7583), pp.499-503.  
4. Pickrell, J.K., et al., 2014. Ancient west Eurasian ancestry in southern and eastern Africa. *PNAS*, 111(7), pp.2632-2637.  
5. Gunther, T. and Nettelblad, C., 2019. Reference bias in population genomic studies of prehistoric human populations. *PLOS Genetics*, 15(7), p.e1008302.  
6. Kuhn, M. and Johnson, K., 2013. *Applied Predictive Modeling*. New York: Springer.  
7. Little, R.J.A. and Rubin, D.B., 2019. *Statistical Analysis with Missing Data*. 3rd ed. Wiley.  
8. Montgomery, D.C., et al., 2021. *Introduction to Linear Regression Analysis*. 6th ed. Wiley.  
9. Bolger, A.M., Lohse, M. and Usadel, B., 2014. Trimmomatic: a flexible trimmer for Illumina sequence data. *Bioinformatics*, 30(15), pp.2114-2120.  
10. Lipson, M., et al., 2017. Parallel palaeogenomic transects reveal complex genetic history of early European farmers. *Nature*, 551(7680), pp.368-372.

---

## Appendix

- Diagnostic plots (Residuals vs Fitted, QQ-plots) for model evaluation.  
- Detailed tables of model outputs and performance metrics.

---

