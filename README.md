# bmd600_220104735
 Terence Tse Ei Kwan's Final Year Project on Podisma's mtDNA 

ABSTRACT
Mitochondrial Genotypic Divergence & Fitness in Podisma pedestris
(Terence Tse Ei Kwan & Dr. Richard Alan Nichols)
Running Title: Conservation Analysis of Non-Synonymous Mutations Between Mitotypes 
Keywords: P. pedestris; Mitotypes; Non-synonymous mutation; Fixed Difference
Background: The mitochondrial hybrid zone of Podisma pedestris is displaced ≈5km north of the chromosomal hybrid zone. 
Results: Southern mitotype variants showed higher concordance with conserved amino acid residues across species, while northern variants showed reduced conservation at corresponding sites. 
Conclusion: The northern mitochondrial lineage has accumulated non-synonymous mutations, consistent with functionally optimisation in the southern mitotype.
Significance: Mitochondrial protein divergence provides molecular evidence for selective cline displacement and advances understanding of mitotype-driven introgression.
The spatial displacement between mitochondrial and chromosomal hybrid zones in Podisma pedestris constitutes a well-documented example of differential introgression across unlinked genomic regions. Following postglacial recolonisation, both mitochondrial and chromosomal clines are believed to have initially coincided at a common secondary contact zone ≈10,000 years ago. However, subsequent asymmetrical introgression has resulted in a northward displacement of the mitochondrial cline by ≈5km relative to the chromosomal cline. Such spatial displacement is inconsistent with expectations under neutral diffusion models and instead supports directional selection acting on the southern mitochondrial lineage. Phylogenetic comparisons of substitution rates between the northern and southern haplotypes suggest that southern variants confer a ≈1% survival advantage to individuals carrying them. Prior studies by the Nichols group have identified fixed polymorphisms within the mitochondrial genome, but their functional significance has not been explored. To investigate the molecular basis of mitotype divergence, this study identified 23 non-synonymous mutations between the southern and northern mitochondrial genomes and inferred their relative likelihood of deleteriousness from cross-species conservation at corresponding residues. Evaluation of each mitotype-specific amino acid variant in the context of related taxa enables distinction between residues likely to impair protein function and those consistent with ancestral or tolerated states. By integrating sequence divergence with measures of evolutionary constraint, this analysis offers a molecular perspective on the inferred selective advantage of the southern haplotype and advances current understanding of the role of mitochondrial variation in shaping patterns of asymmetric introgression.

################### Directory after inputing SIFT scores with main dataset ###################


bmd600_220104735/
├── becher_nichols/
│   ├── ref_11.fasta  
│   ├── ref_11_reverse.fasta
│   ├── mitoVarsFreeb12dupsMarked.vcf  
│
├── podisma_samples/
│   ├── Sample_1.fasta  
│   ├── Sample_2.fasta  
│   ├── Sample_3.fasta  
│   ├── ...
│   ├── Sample_52.fasta  
│   ├── combined_raw_podisma_only.fasta  
│
├── fixed_differences/
│   ├── filtered_fixed_differences_northern_and_southern.fasta  
│
├── northern_mtDNA.fasta                           
├── northern_mtDNA_reverse.fasta  
│
├── tables_all_possible_ORFs_podisma/        
│   ├── southern_table.tsv
│   ├── southern_reverse_table.tsv
│   ├── northern_table.tsv
│   ├── northern_reverse_table.tsv
│   ├── all_potential_northern_ORFs.tsv   
│   ├── all_potential_southern_ORFs.tsv    
│   ├── true_southern_ORFs.tsv             
│   ├── true_northern_ORFs.tsv             
│   ├── true_ORFs_comparison.tsv 
│   ├── true_ORFs_synonymous_mutations.tsv          
│   ├── true_ORFs_non_synonymous_mutations.tsv     
│   ├── filtered_non_synonymous_mutations.tsv   
│   ├── unfiltered_non_synonymous_mutations_podisma_vs_orthoptera.tsv    
│   ├── filtered_non_synonymous_mutations_podisma_vs_orthoptera.tsv 
│   ├── filtered_non_synonymous_mutations_podisma_vs_orthoptera_with_melanoplus.tsv  
│   ├── filtered_non_synonymous_mutations_with_SIFT_UniProtKB.tsv           # findings from SIFT were manually included here
│
├── number_of_orthopterans_matching_northern_and_southern.csv  
│
├── aligned_proteins_with_orthopterans/       
│   ├── ATP6.fasta
│   ├── ATP8.fasta
│   ├── COX3.fasta
│   ├── CYTB.fasta
│   ├── ND1.fasta
│   ├── ND2.fasta
│   ├── ND3.fasta
│   ├── ND4.fasta
│   ├── ND4L.fasta
│   ├── ND5.fasta
│   ├── ND6.fasta
