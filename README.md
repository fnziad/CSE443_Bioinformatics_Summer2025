# CSE443 - Bioinformatics (Summer 2025)

## Course Information

- **Course Code:** CSE443
- **Course Title:** Bioinformatics
- **Credit Hours:** 3 (Theory)
- **Contact Hours:** 3 (Theory)
- **Category:** Program Elective
- **Type:** Theory, Lecture + Lab
- **Prerequisites:** CSE221: Algorithms
- **Co-requisites:** None
- **Semester:** Summer 2025
- **University:** BRAC University
- **Department:** Computer Science and Engineering
- **Student:** Fahad Nadim Ziad
- **Student ID:** 24341216
- **Email:** fahad.nadim.ziad@g.bracu.ac.bd

## 👨‍🏫 Course Instructor

**Professor Swakkhar Shatabda**

- **Position:** Professor, Department of Computer Science and Engineering
- **Education:**
  - BSc in CSE, BUET 2007
  - PhD, Griffith University, Australia, 2014
- **Contact:**
  - Email: swakkhar.shatabda@bracu.ac.bd
- **Research Interests:**
  - Applied Machine Learning
  - Artificial Intelligence Search
  - Computational Biology

## �📖 Course Overview

This repository contains my coursework and materials for CSE443 Bioinformatics course at BRAC University.

### Course Catalog Description

Introduction to molecular biology and genetics: cell structure, central dogma, regulation of gene expression, Mendel's laws; Sequencing based assays: RNA-seq, ChIP-seq; Genome assembly; Sequence alignment and multiple sequence alignment: Needleman-Wunsch algorithm, Smith-Waterman algorithm; Phylogenetics: neighbor joining, statistical phylogenetics; Biological Databases: gene ontology, protein and nucleotide databases, data retrieval; Genome annotation: gene finding, regulatory motifs; Gene expression analysis: clustering, classification; Association Mapping; Single Cell RNA-Seq: challenges and applications; Structure, alignment and function prediction of RNA and Proteins; Protein Translational Modifications; Protein-protein interactions (PPI): introduction, experimental detection, prediction, dynamic PPI, PPI network; Drug design: docking and binding; Epigenetics; Gene Editing; Topics in population genetics: mutation, fixation, selection, drift, migration; Systems biology: pathways, networks.

### Course Objectives

- Understand the fundamentals of molecular biology, genetics, and gene regulation
- Learn core sequencing technologies (e.g., RNA-seq, ChIP-seq) and genome assembly methods
- Apply sequence alignment and phylogenetic techniques to analyze biological data
- Use biological databases for gene, protein, and functional annotation
- Analyze gene expression data through clustering, classification, and association mapping
- Explore protein structure, function prediction, interactions, and drug design principles
- Examine advanced topics including single-cell RNA-seq, epigenetics, gene editing, and systems biology

### Course Outcomes

| #   | Course Outcome                                                                                                                           | Program Outcome |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| CO1 | Apply fundamental biological concepts and computational methods to analyze DNA, RNA, and protein sequences                               | b               |
| CO2 | Utilize bioinformatics tools and databases (e.g., BLAST, GenBank, UniProt) for sequence alignment, annotation, and functional prediction | e               |
| CO3 | Interpret results from genome assembly, phylogenetic analysis, and structural bioinformatics to solve biological problems                | d               |
| CO4 | Design and implement basic pipelines for high-throughput biological data analysis using scripting languages and statistical approaches   | c               |

### Assessment Structure

| Assessment Tool | Weightage | Details                                                  |
| --------------- | --------- | -------------------------------------------------------- |
| Attendance      | 5%        | Minimum 70% attendance required to sit for final exam    |
| Assignments     | 15%       | 2 Programming Assignments                                |
| Quiz            | 15%       | Best 3 out of 4-5 quizzes (No makeup for missed quizzes) |
| Midterm Exam    | 30%       | Comprehensive exam covering pre-midterm topics           |
| Final Exam      | 35%       | Comprehensive exam covering post-midterm topics          |

**Important Notes:**

- Minimum 70% attendance required to sit for final exam
- Late assignment submissions may receive grade penalties
- Follow department procedure for missed exams

## 📁 Repository Structure

```
├── Assignments/
│   ├── assignment_1/          # Assignment 1 solutions and data
│   │   ├── 24341216_443_p1.ipynb    # Problem 1 solution
│   │   ├── 24341216_443_p2.ipynb    # Problem 2 solution
│   │   ├── eulerian_path.txt         # Eulerian path data
│   │   ├── rosalind_ba2f.txt         # Rosalind problem data
│   │   └── rosalind_ba3g.txt         # Rosalind problem data
│   └── assignment_2/          # Assignment 2 solutions and data
│       ├── 24341216_443_p1.ipynb    # Problem 1 solution (Sequence Alignment)
│       ├── 24341216_443_p2.ipynb    # Problem 2 solution (HMM Viterbi Algorithm)
│       └── sample_inputs/            # Sample input files
├── Books/
│   ├── Bioinformatics Algorithms - An Active Learning Approach (Volumes 1 & 2)
│   ├── Genome Scale Algorithm Design.pdf
│   └── handson/               # Practical bioinformatics resources
├── Lecture/
│   ├── Mid/                   # Mid-term lecture materials
│   │   ├── CSE_443__01_Introduction.pdf
│   │   ├── CSE_443__02_Origin_of_Replication.pdf
│   │   ├── CSE_443__03_Motif_Search.pdf
│   │   ├── CSE_443__04_Genome_Assembly.pdf
│   │   ├── CSE_443__05_Sequences_DNA_and_Beyond.pdf
│   │   ├── CSE_443__06_String_Matching_for_Read_Mapping.pdf
│   │   ├── CSE_443__07_Gene_Expression_Analysis___I.pdf
│   │   ├── CSE_443__08_Gene_Expression_Analysis___II.pdf
│   │   └── String_Matching,_Sequence_and_Reads.ipynb
│   └── Final/                 # Final term lecture materials
│       ├── CSE_443__10_Sequence_Alignment.pdf
│       ├── CSE_443__11_Phylogeny_Construction.pdf
│       ├── CSE_443__13_Supervised_Machine_Learning.pdf
│       ├── CSE_443__14_Neural_Networks.pdf
│       ├── CSE_443__15_Network_Analysis.pdf
│       └── Additional resources (HMM, Viterbi examples, etc.)
├── Outline/
│   └── Course_Outline_CSE443_Summer2025.md  # Official course outline
├── Practice+Notes/
│   ├── mid/                   # Mid-term preparation notes
│   ├── final/                 # Final term preparation notes
│   └── Problems collections
├── Quiz Questions/            # Quiz questions and solutions
├── Project/                   # Term project materials
│   └── CSE_443__Term_Project_Report.pdf
└── README.md                  # This file
```

## 📋 Course Outline (Professor Swakkhar Shatabda)

### Pre-Midterm Topics

| Lecture | Topic                                                                          | Course Outcome |
| ------- | ------------------------------------------------------------------------------ | -------------- |
| 1       | Introduction to Bioinformatics                                                 | CO1            |
| 2       | Sequence Alignment, Dynamic Programming                                        | CO1, CO2       |
| 3       | Hidden Markov Models, HMM Profile, Coding Regions                              | CO3            |
| 4       | Genome Assembly: Read Mapping, Variant Calling, De-Bruijn Graphs, Suffix Trees | CO2, CO4       |
| 5       | Gene Expression Analysis: Clustering, Visualization, Dimensionality Reduction  | CO2, CO4       |
| 6       | Single Cell RNA-Seq and Spatial Transcriptomics                                | CO2, CO4       |

**📝 Midterm Exam**

### Post-Midterm Topics

| Lecture | Topic                                                                         | Course Outcome |
| ------- | ----------------------------------------------------------------------------- | -------------- |
| 7       | Phylogenetic Trees                                                            | CO3            |
| 8       | Biological Networks                                                           | CO4            |
| 9       | Gene Ontology and Biological Pathways                                         | CO4            |
| 10      | Evolutionary Genomics, Comparative Genomics                                   | CO4            |
| 11      | Representation Learning, Contrastive Learning and Alignment in Bioinformatics | CO1, CO4       |
| 12      | Drug and Protein Structures, Proteomics, Generative AI                        | CO3            |

**📝 Final Exam**

## 📚 Official Textbooks and References

**Primary Textbooks:**

- [B1] Bioinformatics Algorithms: An Active Learning Approach Vol I&II - Pavel A. Pevzner and Phillip Compeau
- [B2] Genome-Scale Algorithm Design: Bioinformatics in the Era of High-Throughput Sequencing, Second Edition - Makinen et al.

**Additional References:**

- Understanding Bioinformatics - Jeremy Baum and Marketa J. Zvelebil
- A First Course in Systems Biology - Eberhard Voit

## 🛠️ Technologies and Tools Used

- **Programming Languages:** Python, R
- **Libraries:**
  - NumPy, Pandas for data manipulation
  - Matplotlib, Seaborn for visualization
  - Biopython for biological sequence analysis
  - Scikit-learn for machine learning
- **Notebooks:** Jupyter Notebook for interactive analysis
- **Data Sources:** Rosalind Project problems, NCBI databases
- **Platforms:** Google Colab for cloud computing

## 📝 Assignments and Projects

### Assignment 1

- **Problem 1:** Motif finding using Gibbs sampling algorithm
- **Problem 2:** Genome assembly using De Bruijn graphs

### Assignment 2

- **Problem 1:** Sequence alignment with affine gap penalties
- **Problem 2:** Hidden Markov Model implementation (Viterbi algorithm)

### Term Project

Comprehensive bioinformatics analysis project covering multiple algorithms and real biological data analysis.

## 📚 Study Materials

All notes and study materials in this repository are **personally prepared** by me during the course. They include:

- Detailed algorithm explanations
- Implementation examples
- Problem-solving strategies
- Key concept summaries

## 🏆 Learning Outcomes

By completing this course, I have gained expertise in:

- Fundamental bioinformatics algorithms and their implementations
- Analysis of biological sequences (DNA, RNA, proteins)
- Statistical methods for biological data
- Machine learning applications in computational biology
- Network analysis and systems biology approaches
- Practical skills in biological data processing and visualization

## 🔗 Useful Resources

- [Rosalind Project](http://rosalind.info/) - Bioinformatics problems and challenges
- [NCBI](https://www.ncbi.nlm.nih.gov/) - National Center for Biotechnology Information
- [Biopython](https://biopython.org/) - Python tools for computational biology
- Course textbooks available in the `Books/` directory

## 📄 License

This repository is for educational purposes. Please refer to BRAC University's academic integrity policies when using these materials.

## 📧 Contact

**Fahad Nadim Ziad**

- Email: fahad.nadim.ziad@g.bracu.ac.bd
- Student ID: 24341216
- Institution: BRAC University, Department of Computer Science and Engineering

---

_This repository represents my journey through the fascinating world of computational biology and bioinformatics algorithms during Summer 2025 at BRAC University._
