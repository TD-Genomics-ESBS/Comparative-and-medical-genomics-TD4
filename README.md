# Comparative-and-medical-genomics-TD4

## Structural variant
Go to [dbVar](https://www.ncbi.nlm.nih.gov/dbvar/) (Database of Genomic Structural Variation) at NCBI.

Search the human TRPM1 gene, for that use the _dbVar Advanced Search Builder_.

> :question: How many genomic variations listed in dbVar involve TRPM1 (in human)? What type of variants is the most represented? How many variants are pathogenic?

Search the nsv3924913 variant.

> :question:  What is the size of the region involved in the variation?

> :question: Can we specifically assign these phenotypes to the TRPM1 gene? (in other words, this variant impact the TRPM1 gene?)

> :question: On how many variant calls is this structural variant based?

> :question: According to Genome view, is it the only structural variant in this genomic region? Display other studies using Genome view.

> :question: Return to nsv3924913. What is the type (s) of variation for this variant?

> :question: Display "clinical assertions". What are the 3 links to ClinVar? What are the clinical features observed in patient with this variation associated with the loss a copy ? For that open the link begining with VCV00...

> :question: On [HPO](https://hpo.jax.org). Search phenotypes associated with the loss of copy. Is the "Seizures" phenotype specific to a single disease?

## Small variants
Go to [dbSNP](https://www.ncbi.nlm.nih.gov/snp/) (Database of Short Genetic Variations) at NCBI. 

Search the human TRPM1 gene, for that use the _dbVar Advanced Search Builder_.

> :question: How many entries from the SNP database are linked to the TRPM1 gene?

> :question: Among them, how many are pathogenic or likely pathogenic?

> :question: What are their functional consequences? Why are some variants associated to several functional consequences?

##### Display the entry rs191205969

> :question: What type of variant is it?

> :question: What is the reference allele and the alternative one?

> :question: What is the variant MAF in the 1000 genomes project? Can we speak of polymorphism?

> :question: What is the meaning of NM_001252020.1: c.413T>C?

> :question: What is the functional consequence of this variant? Is it associated with type 1C CSNB? - Is this variant present in all tested populations?

##### Display the entry rs267607140

> :question: There are several functional consequences for this variant. Why?

##### Ensembl

In the Ensembl genome browser, display the TRPM1 gene and configure the page to display small variants from the 1000 genomes project and phenotypes associated.

For that, open the _Configure Page_ windows.
- Open _Variation_: activate _1000 Genomes - All - short variants (SNPs and indels)_ and _1000 Genomes - All - common - short variants (SNPs and indels)_ (with _Normal_ style).
- Open _Variation > Phenotype, disease and curated variants_: activate _All phenotype-associated - short variants (SNPs and indels)_ (with _Normal_ style).
  
> :question: What can you say about the distribution of these variants? 

> :question: What can you say about the location of variants associated to a phenotype?

> :question: What other phenotypes and diseases are associated to TRPM1 variants in human?

## Analysis of mutations

The TRPM1 gene of patients with CSNB (and in some cases their families) has been sequenced to find causative mutations for this rare disease.

> :question: Several mutations identified in patients were considered non-pathogenic (see table below). Using this table and the SNP database (NCBI), explain why these mutations are not pathogenic.

| Exon | Nucleotide exchange | Allele state | Protein effect | SNP ID    | Control Alleles (Mut/WT)         |
|------|---------------------|--------------|----------------|-----------|----------------------------------|
| 1    | c.16C>T             | het or hom   | p.Arg6Trp      | New       | 8/350 (T occurs also in Patypus) |
| 11   | c.1305G>A           |              | p.Thr435Thr    | rs1035705 |                                  |
| 3    | c.161G>A            |              | p.Ser54Asn     | rs2241493 |                                  |
| 27   | c.4123G>T           | het          | p.Glu1375X     | New       | 20/320                           |

To find more informations about the two mutations already recorded in public database, use [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/).

> :question: Mutations provided on Moodle were found in 3 patients and were considered as pathogenic. In each case, explain: why do they seem pathogenic, and the mode of transmission causing the disease.
