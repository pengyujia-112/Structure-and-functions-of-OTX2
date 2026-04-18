## Structure-and-functions-of-OTX2
Pipeline of analysis structure and functions of mouse OTX2.
# Preparation
The main software of the pipeline contains `IQtree`,`mafft`,`MACS` that can be downloaded on https://github.com/iqtree/iqtree3,https://github.com/GSLBiotech/mafft and https://github.com/macs3-project/MACS.
The reference genome contains [GRCm39](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_000001635.27/),the `.fastq` file [SRR10172882](https://trace.ncbi.nlm.nih.gov/Traces/index.html?run=SRR10172882) and [SRR10172850](https://trace.ncbi.nlm.nih.gov/Traces/index.html?run=SRR10172850) obtained via `SRA Toolkit`.
# Highly conserved domain of OTX2
Multiple sequence alignment software `MAFFT` L-INS-i algorithm are used for finding vertebrates orthologous OTX2 conserved amino acid sequences
