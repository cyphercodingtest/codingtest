# Cypher Genomics Coding Test

There exists a data file in the repository called data/variant_summary.sample.txt.

The file contains information about genomic variants extracted from the ClinVar database.
The first line is a header line with the names of the fields.

    * AlleleID
    * Type
    * Name
    * GeneID
    * GeneSymbol
    * ClinicalSignificance
    * RS#
    * (dbSNP)
    * RCVaccession
    * PhenotypeIDs
    * Assembly
    * Chromosome
    * Start
    * Stop
    * OtherIDs
    * VariantID
    * ReferenceAllele
    * AlternateAllele


TASK

Transform and organize the data into 3 separate files:

* FILE 1: GenomicCoordinates
The file must contain the genomic coordinate information for ClinVar variants. It will
contain a column header (must start with #) and the following data (order is important):
    * VariantID
    * Assembly
    * Chromosome
    * Start
    * Stop
    * Type
    * ReferenceAllele
    * AlternateAllele
    * GeneID
    * GeneSymbol

* FILE 2: Pathogenicity
The file must contain the pathogenicity information for ClinVar variants.
It will contain a column header (must start with #) and the following data (order is important):

    * VariantID
    * AlleleID
    * PhenotypeID
    * ClinicalSignificance

* FILE 3: Evidence
The file must contain the scientific evidence information for ClinVar variants.
It will contain a column header (must start with #) and data for (order is important):
    * VariantID
    * Name
    * RS#
    * (db SNP)
    * RCVaccession
    * OtherIDs


THE EXERCISE:


* Implement the code in Python using:
    - Interface/Abstract Class
    - Inheritance (Polymorphism)
    - Python Generator
    - List Comprehension

* Proceed following these steps:
    - Write Interface/Abstract class
    - Commit/Push Changes (Git)
    - Branch (Git)
    - Finish implementation
    - Commit/Push/Merge Change (Git)






