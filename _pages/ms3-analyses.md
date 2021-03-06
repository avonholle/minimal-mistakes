---
layout: single
title: "Analyses for manuscript 3: Infant growth as an effect modifier of genetic-lipid associations: evidence from a Chilean infancy cohort"
permalink: /diss/ms3-analyses/
---

<sub><sup>Aim 3 of my dissertation examines the associations between lipid SNPs and lipids conditional on growth classes. In this framework the growth classes function as effect modifiers of the SNP-lipid association. Both candidate lipid SNPs, chosen on the basis of marginal effects with adequate power, as well genetic risk scores will be covariates in the models. To characterize infant body size change I will use two analytic approaches as in aims 1 and 2: nonlinear mixed effects (SITAR) and latent growth mixture models (LGMM).</sup></sub>

## Manuscript

<!--  * Draft manuscript in
    * [word format](../../unc-dissertation-markdown-p2/includes/scripts/paper3/draft/ms3.docx)
    * [pdf format](../../unc-dissertation-markdown-p2/includes/scripts/paper3/draft/ms3.pdf)
    * [html format](../../unc-dissertation-markdown-p2/includes/scripts/paper3/draft/ms3.html)
-->

<!--
[Tables and figures, html version](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper2/bch-read-all.Rmd)  
-->

  * [Tables and figures, pdf version](../../unc-dissertation-markdown-p2/includes/scripts/paper3/ms3-read-all-pdfversion.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/ms3-read-all-pdfversion.Rmd) 


## AHA Epi/Lifestyle 2018

[Poster](../../unc-dissertation-markdown-p2/includes/scripts/paper3/aha2018/m3-infant-growth-effect-poster.pdf)

[Submitted abstract](../../unc-dissertation-markdown-p2/includes/scripts/paper3/aha2018/abstract-m3.html) -- [word version](../../unc-dissertation-markdown-p2/includes/scripts/paper3/aha2018/abstract-m3.docx)


## Statistical analysis plan

[Statistical analysis plan (SAP)](../../unc-dissertation-markdown-p2/includes/scripts/paper3/sap3.html) -- [code for SAP](../../unc-dissertation-markdown-p2/includes/scripts/paper3/sap3.Rmd)


[Information for genetic risk score -- data handling and list of variants](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/snp-description.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/snp-description.Rmd)

## Misc

### Risk scores

* [Information for genetic risk score -- data handling and list of variants](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/snp-description.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/snp-description.Rmd)


<!--
## Overall summary

[Overall summary of results](../../unc-dissertation-markdown-p2/includes/scripts/paper3/overall-summary.html)

## 2. Scripts to read in genetic data

1. [script to read in vcf data on longleaf and extract relevant snps](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/read-vcf-snps.R)
-->

<!--2. [script to summarize snp data](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/look-vcf-snps.Rmd)-->

<!--
2. [Information for genetic risk score -- data handling and list of variants](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/snp-description.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/snp-description.Rmd)

3. [Power calcs for marginal effects](../../unc-dissertation-markdown-public/includes/scripts/power/aim3/power-calcs-ind-assoc.html) -- [code](../../unc-dissertation-markdown-public/includes/scripts/power/aim3/power-calcs-ind-assoc.Rmd)

## 3. SITAR analysis: gene-environment interaction test for SITAR growth parameters and genotype

[Tables 2 and 3](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table2.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table2.Rmd)
-->

<!--

## 4. LGMM analysis: variation in association between genotype and univariate distal lipid outcome by growth classes

*NOTE*: The significant results have somewhat sparse cell counts and should be considered with caution. See [this document](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile-mplus/m3-check-results.html) for cell frequencies by most likely latent class and allele counts for the significant associations.

[Results, .pdf](../../unc-dissertation-markdown-p2/includes/scripts/paper3/ms3-read-all-pdfversion.pdf) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/ms3-read-all-pdfversion.Rmd)

-->

<!--
### Pooled by sex of child

[Table 4, revised](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-ms3-3step-bch-pooled.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-ms3-3step-bch-pooled.Rmd)

  - [step 1 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/pooled/template-m3-mplus-univ-distal-step1-pooled.txt)

  
  - [step 3 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/pooled/template-m3-mplus-univ-distal-step3-2class-pooled.txt)

---

**Adjusted**

[Table 4, revised](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-ms3-3step-bch-pooled-adj.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-ms3-3step-bch-pooled-adj.Rmd)

  - [step 1 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/pooled-adj/template-m3-mplus-univ-distal-step3-2class-pooled-adj.txt)

  
  - [step 3 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/pooled-adj/template-m3-mplus-univ-distal-step1-pooled-adj.txt)

  
### Sex-stratified

[Table 4, sex stratified](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-3step-bch-stratify.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-3step-bch-stratify.Rmd)

  - [step 1 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/strat/template-m3-mplus-univ-alt-distal-step1.txt)
  
  - [step 3 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/strat/template-m3-mplus-univ-alt-distal-step3-2class.txt)

---

**Adjusted**

[Table 4, sex stratified](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-3step-bch-stratify-adj.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table4-3step-bch-stratify-adj.Rmd)

  - [step 1 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/strat-adj/template-m3-mplus-univ-alt-distal-step1-adj.txt)
  
  - [step 3 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/longleaf/compile/mplus-tempates/strat-adj/template-m3-mplus-univ-alt-distal-step3-2class-adj.txt)
-->

<!--
## 5. LGMM analysis: variation in association between genotype and CFA distal lipid outcome by growth classes


[Table 5, candidate snps](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table5-3step-bch.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table5-3step-bch.Rmd)

  - [step 3 Mplus template](../../unc-dissertation-markdown-p2/includes/scripts/paper3/lgmm/virtuallab/distal/template-m3-mplus-cfa-alt-distal-step3.txt)
  - NOTE: use the same step 1 template as for section 4 above.

[Table 6, genetic risk score](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table6-3step-bch.html) -- [code](../../unc-dissertation-markdown-p2/includes/scripts/paper3/table6-3step-bch.Rmd)
-->
