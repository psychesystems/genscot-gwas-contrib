# Cohort Description Template

## Generation Scotland

### Overview

Generation Scotland (GS) is a family-based study of 23,960 individuals between the ages of 17 and 99 years old, residing in Scotland at the time of recruitment between 2006-2011. Genetic, epigenetic, proteomic, clinical, lifestyle and sociodemographic information are available for the participants of GS. All components of GS received ethical approval from the NHS Tayside Committee on Medical Research Ethics (REC reference no. 05/S1401/89). GS has also been granted Research Tissue Bank status by the East of Scotland Research Ethics Service (REC reference no. 20-ES-0021), providing generic ethical approval for a wide range of uses within medical research. 

### Genotyping, Imputation, and Quality Control

#### Genotyping platform(s) and DNA source

Blood (or occasionally saliva) samples from GS participants were collected, processed and stored using standard operating procedures and managed through a laboratory information management system at the Edinburgh Clinical Research Facility, University of Edinburgh The genotyping used the Illumina HumanOmniExpressExome-8 v1.0 BeadChip or the Illumina HumanOmniExpressExome-8 v1.2 BeadChip, with Infinium chemistry for both.

#### Pre-imputation QC steps: SNP-level and sample-level filters.

Genotyping quality control was performed using the following procedures: individuals with a call rate less than 98% were removed, as were SNPs with a call rate less than 98% or Hardy-Weinberg equilibrium p value less than 1 × 10^–6^. Mendelian errors, determined using relationships recorded in the pedigree, were removed by setting the individual-level genotypes at erroneous SNPs to missing.

#### Imputation reference panel and software used.

The genotyped data was imputed utilising the Sanger Imputation Service using the HRC panel v1.1 Autosomal haplotypes were checked to ensure consistency with the reference panel (strand orientation, reference allele, position) then pre-phased using Shapeit2 v2r837 [using the Shapeit2 duohmm option11, taking advantage of the cohort family structure in order to improve the imputation quality. Monogenic and low imputation quality (INFO < 0.4) variants were removed from the imputed dataset leaving 24,111,857 variants available for downstream analysis.

### Acknowledgements

Generation Scotland received core support from the Chief Scientist Office of the Scottish Government Health Directorates [CZD/16/6] and the Scottish Funding Council [HR03006] and is currently supported by the Wellcome Trust [216767/Z/19/Z]. Genotyping of the GS samples was carried out by the Genetics Core Laboratory at the Edinburgh Clinical Research Facility, University of Edinburgh, Scotland and was funded by the Medical Research Council UK and the Wellcome Trust (Wellcome Trust Strategic Award “STratifying Resilience and Depression Longitudinally” (STRADL) Reference 104036/Z/14/Z).

#### Participant acknowledgements

We are grateful to all the families who took part, the general practitioners and the Scottish School of Primary Care for their help in recruiting them, and the whole Generation Scotland team, which includes interviewers, computer and laboratory technicians, clerical workers, research scientists, volunteers, managers, receptionists, healthcare assistants and nurses.

## References

### Key publication(s) describing the cohort.

- Smith BH, et al. Cohort profile: Generation scotland: Scottish Family Health Study (GS:SFHS). The study, its participants and their potential for genetic research on health and illness. Int. J. Epidemiol. 2012;42:689–700. doi: 10.1093/ije/dys084.
