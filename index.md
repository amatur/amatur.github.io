---
layout: default
title: Amatur Rahman
---

Welcome! Use the links below to navigate:

- [Research Statement](#research-statement)
- [Bio](#bio)
- [CV](#cv)
- [Publications](#publications)
- [Software](#software)
- [Contact Info](#contact-info)

---

## Research Statement

I am always excited to work on open projects in algorithmic bioinformatics, evolutionary and population genetics. I develop scalable algorithms and pipelines for large-scale datasets, focusing on accelerating selection scans, k-mer–based compression, and analysis of sequence similarities. I also explore theoretical aspects of bioinformatics, including how tools interpret data and potential pitfalls in downstream analyses, to promote careful and accurate use of genetic and genomic data.

---

## Bio

I am a postdoctoral scholar at Department of Biology, Pennsylvania State University, working with Dr. Zachary Szpiech on computational methods in population genetics. I obtained my PhD from Department of Computer Science and Engineering, Pennsylvania State University on August 2023. Before joining Penn State, I obtained my Bachelor's degree in Computer Science and Engineering from Bangladesh University of Engineering and Technology (BUET). I also served as a lecturer in the CSE department at United International University, Bangladesh. During my PhD, I was a recipient of CBIOS Trainee Fellowship.

{%
  include figure.html
  image="/docs/assets/images/bw.jpeg"
  caption="Biological Data Science Meeting, Cold Spring Harbor Laboratory, November 2022"
  width="70%" 
%}

---

## CV

My most recent CV can be found [here](https://www.dropbox.com/scl/fi/dkl7gyjply3cl9b6y7vke/cv_amatur_aug25_2023.pdf?rlkey=0mkrxd2w0tduwhce3701w1bc3&dl=0).

---

## Publications

You can also check my publications through [Google scholar](https://scholar.google.com/citations?hl=en&user=28hqEC4AAAAJ).

- **EGGS: Empirical Genotype Generalizer for Samples.**  
_T. Quinn Smith, Amatur Rahman, and Zachary A. Szpiech_  
bioRxiv, 2025-10.  
[ [paper](https://www.biorxiv.org/content/10.1101/2025.10) ]

- **Selection scans and downstream analysis with selscan.**  
_Amatur Rahman*, T. Quinn Smith*, and Zachary A. Szpiech_  
bioRxiv, 2025-10. (Under revision at _Genome Biology and Evolution_)  
(* joint first author)  
[ [paper](https://www.biorxiv.org/content/10.1101/2025.10) ]

- **Fast and memory-efficient dynamic programming approach for large-scale EHH-based selection scans.**  
_Amatur Rahman, T. Quinn Smith, and Zachary A. Szpiech_  
_Molecular Biology and Evolution_, 42(11):msaf275, 2025.  
[ [paper](https://doi.org/10.1093/molbev/msaf275) ]

- **Compression algorithm for colored de Bruijn graphs.**    
_Amatur Rahman, Yoann Dufresne and Paul Medvedev_  
[ [paper (preprint)](https://doi.org/10.1101/2023.05.12.540616) ]


- **Assembler artifacts include misassembly because of unsafe unitigs and under-assembly because of bidirected graphs.**    
_Amatur Rahman and Paul Medvedev_
Genome Research, 32:1-8, 2022.
An abstract appeared in RECOMB 2022, LNCS 13278:377–379 (Alternative title: Uncovering hidden assembly artifacts: when unitigs are not safe and bidirected graphs are not helpful.)
[ [paper (free version)](https://doi.org/10.1101/2022.01.20.477068), [paper (journal version)](https://doi.org/10.1101/gr.276601.122) ][ [talk] ](https://www.youtube.com/watch?v=VxvEOmKHLHM)

- **The K-mer File Format: a standardized and compact disk representation of sets of k-mers.**    
Y. Dufresne, T. Lemane, P. Marijon, P. Peterlongo, A. Rahman, M. Kokot, P. Medvedev, S. Deorowicz, and R. Chikhi
Bioinformatics, 2022.
[ [paper](https://doi.org/10.1093/bioinformatics/btac528) ]

- **GPU-accelerated and pipelined methylation calling.**    
Yilin Feng, Gulsum Gudukbay Akbulut, Xulong Tang, Jashwant Raj Gunasekaran, Amatur Rahman, Paul Medvedev, Mahmut Kandemir
Bioinformatics Advances, Volume 2, Issue 1, 2022, [ [paper](https://doi.org/10.1093/bioadv/vbac088) ] 

- **Disk compression of k-mer sets.**  
_Amatur Rahman, Rayan Chikhi and Paul Medvedev._  WABI 2020 (accepted)
Algorithms for Molecular Biology, 16(10), 2021.
An extended abstract appeared in WABI 2020, LIPIcs 16:1–16:18.
[ [full version (journal)](https://doi.org/10.1186/s13015-021-00192-7), [conference](https://doi.org/10.4230/LIPIcs.WABI.2020.16) ]

- **Representation of k-mer sets using spectrum-preserving string sets.**      
_Amatur Rahman and Paul Medvedev._  
Journal of Computational Biology, 28(4):381-394, 2021.
An extended abstract appeared in RECOMB 2020, LNCS 12074:152-168. **(Best Paper Award)** [ [preprint] ](https://doi.org/10.1101/2020.01.07.896928)[ [talk] ](https://youtu.be/QJyTBjN71Pw)

- **kRISP-meR: A Reference-free Guide-RNA Design Tool for CRISPR/Cas9.**    
_Mahmudur Rahman Hera, Amatur Rahman and Atif Hasan Rahman._ bioRxiv, 2019 

- **An Adaptive IoT Platform on Budgeted 3G Data Plans.**   
_Mahmudur Rahman Hera, Amatur Rahman, Hua-Jun Hong, Li-Wen Pan, Md. Yusuf Sarwar Uddin, Nalini Venkatasubramanian, Cheng-Hsin Hsu._ Elsevier Journal of Systems Architecture, 2018

- **Adaptive Sensing Using Internet-of-Things with Constrained Communications.**   
_Mahmudur Rahman Hera, Hua-Jun Hong, Amatur Rahman, Pei-Hsuan Tsai, Afia Afrin, Md. Yusuf Sarwar Uddin, Nalini Venkatasubramanian, Cheng-Hsin Hsu._ In Proceedings of Adaptive and Reflexive Middleware, ACM, Las Vegas, Nevada, USA, 2017

- **AQBox: An Air Quality Measuring Box from COTS Gas Sensors.**   
_Mahmudur Rahman Hera, Amatur Rahman, Afia Afrin, Md. Yusuf Sarwar Uddin, and Nalini Venkatasubramanian._ In Proceedings of 2017 International Conference on Networking, Systems and Security (NSysS), Dhaka, Bangladesh, 2017


---

## Bioinformatics Software Development (Projects Led)

- [selscan v3](https://github.com/szpiech/selscan) –  Fully redesigned and implemented EHH-based selection scans, achieving major improvements in speed, memory efficiency, and usability for downstream genomic analyses.
- [ESS-Color](https://github.com/medvedevgroup/ESSColor) – C++/Snakemake software for compressing colored de Bruijn graphs.
- [ESS-Compress](https://github.com/medvedevgroup/ESSCompress) – C++ tool to compress a set of k-mers for disk storage.
- [UST](https://github.com/medvedevgroup/UST) – C++ software to build a spectrum-preserving string set representation of k-mer sets.

---

## Contact Info

Email: aur1111 "at" psu "dot" edu, amatur003 "at" gmail "dot" com
