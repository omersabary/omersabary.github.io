---
title: "Decoding for Optimal Expected Normalized Distance over the t-Deletion Channel"
collection: publications
permalink: /publication/2021MLdectdel
excerpt: ''
date: 2022-01-05
venue: '13th Non-Volatile Memories Workshop'
paperurl: ''
citation: 'G. Chaykin, N. Stein, O. Sabary, D. Ben-Shabat, and E. Yaakobi. "DNA-Storalator: End-to-End DNA Storage Simulator,", 13th Non-Volatile Memories Workshop, San Diego, California, 2022.'
---
**Extended Abstract.** 
[Ext. Abstract](http://nvmw.ucsd.edu/nvmw2022-program/nvmw2022-data/nvmw2022-paper36-final_version_your_extended_abstract.pdf)

**Abstract** 

DNA-Storalator is a cross-platform software tool that simulates the complete process of encoding, storing, and decoding digital data in DNA molecules. The simulator receives an input file with the designed DNA strands that store digital data and emulates the different biological and algorithmical components of the storage system. The biological component includes simulation of the synthesis, PCR, and sequencing stages which are expensive and complicated and therefore are not widely accessible to the community. These processes amplify the data and generate noisy copies of each DNA strand, where the errors are insertions, deletions, long-deletions, and substitutions. DNA-Storalator injects errors to the data based on the error rates, as they vary between different synthesis and sequencing technologies. The rates are based on a comprehensive analysis of data from previous experiments but can also be customized. Additionally, the tool can analyze new datasets and characterize their error rates to build new error models for future usage in the simulator. DNA- Storalator also enables control of the amplification process and the distribution of the number of copies per designed strand. The coding components are: 1. Clustering algorithms which partition all output noisy strands into groups according to the designed strand they originated from; 2. State-of-the-art reconstruction algorithms that are invoked on each cluster to output a close/exact estimate of the designed strand; 3. Integration with external error-correcting codes and other encoding and decoding techniques. This end-to-end DNA storage simulator grants researchers from all fields an accessible complete simulator to examine new biological technologies, coding techniques, and algorithms for current and future DNA storage systems.