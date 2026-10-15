## Steps in Exploring Lysosomal Enzymes Using NCBI and R

This activity used NCBI and RStudio to study the human GALC protein. The protein sequence was downloaded and analyzed to identify the amino acids present and find possible N-glycosylation motifs.

<img width="892" height="559" alt="image" src="https://github.com/user-attachments/assets/538eb242-1061-4d21-ab03-eecd48eeb0ff" />

*Figure 1.* NCBI Protein database with the search query “GALC Homo sapiens” entered to find the human GALC protein sequence.

<img width="890" height="483" alt="image" src="https://github.com/user-attachments/assets/5f7a2422-50fe-4780-bc2d-8a8d2e2e2e5f" />

*Figure 2.* NCBI search results showing the human GALC (galactosylceramidase) gene entry, including Gene ID 2581 and the RefSeq Sequences section.

<img width="1156" height="755" alt="image" src="https://github.com/user-attachments/assets/7a4847bf-6f27-4d6e-9d92-e1959f609697" />

*Figure 3.* NCBI Datasets transcript and protein records for human GALC, showing the selected MANE Select transcript (NM_000153.4) and its corresponding protein accession (NP_000144.2), which was used for the sequence analysis.

<img width="837" height="33" alt="image" src="https://github.com/user-attachments/assets/d776dd20-dfab-48eb-aabb-f27d17fc4ed2" />

*Figure 4.* A project folder named lysosomal_enzyme-GALC was created to organize the R analysis files, including the data, results, and figures subfolders.

The R script was opened in RStudio, and the gene symbol and protein accession were set to GALC and NP_000144.2, respectively. The remaining code was kept unchanged to perform the sequence analysis and generate the required results and figures.

<img width="1258" height="711" alt="image" src="https://github.com/user-attachments/assets/c22948e0-4e66-48e1-9c60-ab2863b076ce" />
<img width="1108" height="682" alt="image" src="https://github.com/user-attachments/assets/98cf412e-0442-4b3f-9083-16d4c571f221" />
<img width="1041" height="289" alt="image" src="https://github.com/user-attachments/assets/9528b4ad-1cd0-4ef2-afe2-f7d013cee058" />
<img width="1104" height="733" alt="image" src="https://github.com/user-attachments/assets/142090ef-eac2-4926-86f5-1538e81ef88e" />
<img width="1036" height="544" alt="image" src="https://github.com/user-attachments/assets/19e1909a-7e66-4433-9c67-746d88240d63" />
<img width="1047" height="733" alt="image" src="https://github.com/user-attachments/assets/4f17bbc3-6850-46b1-a028-05b52a9a13e9" />
<img width="1071" height="456" alt="image" src="https://github.com/user-attachments/assets/2ff7c9a0-0372-407a-befb-a54da6400351" />

*Figure 5.* R script setup and protein sequence retrieval for GALC. The script specifies the gene symbol and protein accession, checks the required packages (`rentrez` and `ggplot2`), creates the data, results, and figures folders, and retrieves and validates the human GALC protein sequence from NCBI before saving it as a FASTA file.

<img width="1201" height="367" alt="image" src="https://github.com/user-attachments/assets/ad332e3b-878d-4c0a-9837-837994ef4d99" />

*Figure 6.* The lysosomal-enzyme-GALC project folder after running the R script, showing the analysis script and the data, results, and figures folders containing the generated files for the GALC protein sequence analysis.

After the script was run in RStudio, the human GALC protein sequence was downloaded from NCBI and saved as a FASTA file. The script analyzed the protein's amino acid composition and identified potential N-glycosylation motifs. It also generated CSV files containing the results and two figures showing the amino acid composition and motif positions.

The analysis showed that the GALC protein contains 685 amino acids and six potential N-glycosylation motifs. Leucine (L) was the most abundant amino acid, with 68 occurrences, followed by glycine (G), with 62 occurrences. The results were saved in the data, results, and figures folders.
