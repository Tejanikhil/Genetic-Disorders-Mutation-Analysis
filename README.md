# Bioinformatics Project

This project utilizes pattern matching techniques, specifically the Hamming distance algorithm, to analyze genetic mutations associated with various diseases. It is well-established that many diseases, including Down syndrome, cancer, and viral infections like COVID-19, are linked to genetic disorders. Approximately 40% of diseases are attributed to genetic mutations.

Genetic disorders typically arise from mutations in specific genes, which can be caused by external factors, lifestyle choices, and environmental influences. Understanding these genetic changes is crucial for diagnosing and treating various diseases. Mutations can generally be categorized into two types: point mutations and frameshift mutations.

## 1. Point Mutations: 
Point mutations involve changes at a single nucleotide position within a gene. One common type of point mutation is substitution.

### i. Substitution Mutation: 
Substitution mutations occur when one nucleotide is replaced by another. For example:

Original gene: ATCGATGCTAGGCTGACCAGTCCAAAA  
Mutated gene: ATCG*C*TGCTAGGCTG*T*CCAGTCCAAAA  

In this example, the mutations are caused by the substitution of nucleotides, as indicated by the bolded characters.

## 2. Frameshift Mutations: 
Frameshift mutations occur when the addition or deletion of nucleotides alters the reading frame of the gene, resulting in a change in the entire protein coding sequence.

### i. Insertion Mutation:
Insertion mutations involve the addition of one or more nucleotides into the gene sequence. For example:

Original gene: ATCGATGCTAGGCTGACCAGTCCAAAA  
Mutated gene: ATCGAT**G**GCTAGGC**C**TGACCAGTCCAAAA  

In this example, the bolded nucleotides represent the inserted sequence, which shifts the reading frame and alters the protein coding.

### ii. Deletion Mutation:
Deletion mutations involve the removal of one or more nucleotides from the gene sequence. For example:

Original gene: ATCGATGCTAGGCTGA**C**CAGTCCAAAA  
Mutated gene: ATCGATGCTAGGCTGACAGTCCAAAA  

In this example, the bolded nucleotide is deleted, causing a shift in the reading frame and altering the protein coding.

Understanding these mutations and their effects on gene expression and protein synthesis is essential for studying genetic disorders and developing effective treatments.
