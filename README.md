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
│   ├── ref_11.fasta                         #template fasta from becher paper
│   ├── ref_11_reverse.fasta                 #reverse complement of the template fasta
│   ├── mitoVarsFreeb12dupsMarked.vcf        #vcf containing variant call data from all samples
│
├── podisma_samples/                         #all 52 samples you'd get from the becher paper
│   ├── 1T.fasta  
│   ├── 2T.fasta  
│   ├── 3T.fasta  
│   ├── 4T.fasta  
│   ├── 5T.fasta  
│   ├── 6T.fasta  
│   ├── 7T.fasta  
│   ├── 8T.fasta  
│   ├── 9T.fasta  
│   ├── 10T.fasta  
│   ├── 11T.fasta  
│   ├── 12T.fasta  
│   ├── 13T.fasta  
│   ├── 14T.fasta  
│   ├── 15T.fasta  
│   ├── 16T.fasta
│   ├── 17T.fasta  
│   ├── 18T.fasta  
│   ├── 19T.fasta  
│   ├── 20T.fasta  
│   ├── 21T.fasta  
│   ├── 22T.fasta  
│   ├── 23T.fasta  
│   ├── 24T.fasta
│   ├── 25F.fasta  
│   ├── 26F.fasta  
│   ├── 27F.fasta  
│   ├── 28U.fasta  
│   ├── 29U.fasta  
│   ├── 30U.fasta  
│   ├── 31U.fasta  
│   ├── 32F.fasta
│   ├── 33F.fasta  
│   ├── 34U.fasta  
│   ├── 35U.fasta  
│   ├── 36F.fasta  
│   ├── 37F.fasta  
│   ├── 38F.fasta  
│   ├── 39F.fasta  
│   ├── 40U.fasta
│   ├── 41U.fasta  
│   ├── 42U.fasta  
│   ├── 43U.fasta  
│   ├── 44U.fasta  
│   ├── 45U.fasta  
│   ├── 46U.fasta  
│   ├── H11.fasta  
│   ├── H13.fasta
│   ├── H16.fasta  
│   ├── H25.fasta  
│   ├── H26.fasta  
│   ├── H27.fasta  
│   ├── combined_raw_podisma_only.fasta                              #just a consolidated file of all the samples
│
├── fixed_differences/
│   ├── filtered_fixed_differences_northern_and_southern.fasta       #clearly states the fixed difference between northern and southern samples
│   ├── fixed_differences_northern_and_southern.fasta                #the entry for every sample only at those fixed sites
│
├── northern_mtDNA.fasta                                             #the northern mtDNA consensus sequence
├── northern_mtDNA_reverse.fasta                                     #reverse complement of the northern mtDNA consensus sequence
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
│   ├── filtered_non_synonymous_mutations_with_SIFT_UniProtKB.tsv           
│
├── number_of_orthopterans_matching_northern_and_southern.csv  
│
├── aligned_proteins_with_orthopterans/                             #all fasta files with northern and southern mt proteins aligned with homologous sequences of 55 orthopterans
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
