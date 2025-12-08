<!-- Top navigation bar -->
<nav style="position: fixed; top: 0; width: 100%; background-color: #1B1B1B; padding: 10px 0; z-index: 1000;">
  <div style="max-width: 900px; margin: auto; display: flex; justify-content: space-around;">
    <a href="#research" style="color: #fff; text-decoration: none;">Research</a>
    <a href="#bio" style="color: #fff; text-decoration: none;">Bio</a>
    <a href="#cv" style="color: #fff; text-decoration: none;">CV</a>
    <a href="#publications" style="color: #fff; text-decoration: none;">Publications</a>
    <a href="#software" style="color: #fff; text-decoration: none;">Software</a>
    <a href="#contact" style="color: #fff; text-decoration: none;">Contact</a>
  </div>
</nav>

<div style="max-width: 900px; margin: 80px auto 50px auto; padding: 0 20px; line-height: 1.6;">

## <a id="research"></a>Research Statement

I am always excited to work on open projects in algorithmic bioinformatics. With my experience in developing algorithms and pipelines for handling big datasets, I am capable of developing scalable and intuitive solutions that assist in biological studies. My background involves enhancing storage efficiency for sequence analysis tools and facilitating faster analysis of sequencing data. I am particularly inclined towards studying sequence similarities through k-mer based approaches, error-correction in assembly, and optimizing the performance of bioinformatics tools.

---

## <a id="bio"></a>Bio

I obtained my PhD from Department of Computer Science and Engineering, Pennsylvania State University on August 2023. Before joining Penn State, I obtained my Bachelor's degree in Computer Science and Engineering from Bangladesh University of Engineering and Technology (BUET). I also served as a lecturer in the CSE department at United International University, Bangladesh. During my PhD, I was a recipient of CBIOS Trainee Fellowship (CBIOS: Computation, Bioinformatics and Statistics, an NIH funded Predoctoral Training Program). 

{%
  include figure.html
  image="/docs/assets/images/bw.jpeg"
  caption="Biological Data Science Meeting, CSHL, November 2022"
  width="70%" 
%}

---

## <a id="cv"></a>CV

My most recent CV can be found [here](https://www.dropbox.com/scl/fi/dkl7gyjply3cl9b6y7vke/cv_amatur_aug25_2023.pdf?rlkey=0mkrxd2w0tduwhce3701w1bc3&dl=0) (last updated on August 25, 2023). 

---

## <a id="publications"></a>Publications

You can also check my publications through [dblp](https://dblp.uni-trier.de/pers/hd/r/Rahman:Amatur) or [Google Scholar](https://scholar.google.com/citations?hl=en&user=28hqEC4AAAAJ).

- **Compression algorithm for colored de Bruijn graphs.**  
_Amatur Rahman, Yoann Dufresne and Paul Medvedev_  
[ [paper (preprint)](https://doi.org/10.1101/2023.05.12.540616) ]

- **Assembler artifacts include misassembly because of unsafe unitigs and under-assembly because of bidirected graphs.**  
_Amatur Rahman and Paul Medvedev_  
Genome Research, 32:1-8, 2022  
[ [paper (free version)](https://doi.org/10.1101/2022.01.20.477068), [paper (journal version)](https://doi.org/10.1101/gr.276601.122), [talk](https://www.youtube.com/watch?v=VxvEOmKHLHM) ]

- **The K-mer File Format: a standardized and compact disk representation of sets of k-mers.**  
Y. Dufresne, T. Lemane, P. Marijon, P. Peterlongo, A. Rahman, M. Kokot, P. Medvedev, S. Deorowicz, and R. Chikhi  
Bioinformatics, 2022  
[ [paper](https://doi.org/10.1093/bioinformatics/btac528) ]

- **GPU-accelerated and pipelined methylation calling.**  
Yilin Feng, Gulsum Gudukbay Akbulut, Xulong Tang, Jashwant Raj Gunasekaran, Amatur Rahman, Paul Medvedev, Mahmut Kandemir  
Bioinformatics Advances, Volume 2, Issue 1, 2022  
[ [paper](https://doi.org/10.1093/bioadv/vbac088) ]

- **Disk compression of k-mer sets.**  
_Amatur Rahman, Rayan Chikhi and Paul Medvedev_  
WABI 2020 (accepted), Algorithms for Molecular Biology, 16(10), 2021  
[ [full version (journal)](https://doi.org/10.1186/s13015-021-00192-7), [conference](https://doi.org/10.4230/LIPIcs.WABI.2020.16) ]

- **Representation of k-mer sets using spectrum-preserving string sets.**  
_Amatur Rahman and Paul Medvedev_  
Journal of Computational Biology, 28(4):381-394, 2021  
Extended abstract appeared in RECOMB 2020, LNCS 12074:152-168. **(Best Paper Award)**  
[ [preprint](https://doi.org/10.1101/2020.01.07.896928), [talk](https://youtu.be/QJyTBjN71Pw) ]

---

## <a id="software"></a>Software

- [ESS-Color](https://github.com/medvedevgroup/ESSColor) – C++/Snakemake software that compresses colored de Bruijn graphs  
- [ESS-Compress](https://github.com/medvedevgroup/ESSCompress) – C++ software to compress a set of k-mers for disk storage  
- [UST](https://github.com/medvedevgroup/UST) – C++ software to build a spectrum-preserving string set representation of a set of k-mers

---

## <a id="contact"></a>Contact Info

Email: aur1111 "at" psu "dot" edu, amatur003 "at" gmail "dot" com

</div>

<!-- Optional smooth scrolling -->
<script>
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function (e) {
    e.preventDefault();
    document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
  });
});
</script>
