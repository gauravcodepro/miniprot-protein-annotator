# miniprot-protein-annotations

- a protein coding regions annotator that will take the alignment file in the PAF/GFF format and will generate the fasta from the corresponding fasta files for the aligned regions.
- implemented faster rates so that you can parse as many aligned regions as you want.
- you can also create the protein tokenzier from the same for machine learning.

```
 # align your genome with the given protein  using the miniprot such as 
   miniprot --gff genome.fasta protein.fasta > sample.gf
```
 - and then run the proteinannotator to extract all the complete coding regions *
 ```
generatingAlignments("/home/gaurav/Desktop/final_code_push/multi.gff", 
                        "/home/gaurav/Desktop/final_code_push/multi.fasta", 
                               "/home/gaurav/Desktop/final_code_push/multiout.fasta")
```
Gaurav Sablok \
Academic Staff Member \
Bioinformatics \
Institute for Biochemistry and Biology \
University of Potsdam \
Potsdam,Germany
