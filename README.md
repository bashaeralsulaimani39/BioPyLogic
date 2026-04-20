# 🧬 BioPyLogic

Biopylogic: A student beginner-friendly bioinformatics tool for sequence analysis, BLAST alignment, and phylogenetic visualization.

License: MIT

---

# Overview

BioPyLogic is a simple educational bioinformatics tool created to help students and beginners perform DNA sequence analysis without needing complex software.

Many existing bioinformatics tools are powerful but difficult for beginners to use. Students often struggle to retrieve sequences, understand sequence composition, compare organisms, and visualize evolutionary relationships.

BioPyLogic simplifies these tasks into clear interactive steps.

Users can:

- Fetch DNA sequences directly from NCBI
- Perform sequence analysis
- Compare biological sequences
- Generate simple phylogenetic trees

What makes this project different:

- Beginner-friendly design
- Clear outputs for learning
- Educational focus
- Simple command-based workflow
- Future-ready for blockchain storage integration

---

# 🏆 Hackathon Information

Event: Global Hackfest 2026  
Focus Area: Open Innovation  
Team: Solo Project  
Submission Date: 2026-04-20 

---

# 👥 Team

| Name | Role | GitHub | Discord |
|------|------|---------|----------|
| Bashaeer Alsulaimani | Developer | @bashaeralsulaimani39 | @Bashaeralsu39 |

---

# 🚀 Problem Statement

Bioinformatics tools are often complex and designed for experienced researchers. Students and beginners find it difficult to use professional tools for basic DNA analysis.

This creates several challenges:

- Difficulty retrieving biological data
- Limited understanding of sequence composition
- Lack of simple visualization tools
- Challenges learning phylogenetic relationships
- Limited beginner-focused bioinformatics tools

Why this problem matters:

Bioinformatics is becoming an essential skill in biology and biotechnology education. Students need simple tools to learn sequence analysis before using advanced systems.

Who is affected:

- Biology students
- Bioinformatics beginners
- Researchers learning sequence tools
- Educational institutions

Current limitations:

Most tools are complex, command-heavy, or designed for professional workflows.

This project solves the gap by simplifying biological sequence analysis into clear learning-friendly steps.

---

# 💡 Solution

BioPyLogic provides an interactive bioinformatics workflow that allows users to analyze DNA sequences easily using NCBI.

The system includes three main analysis options:

---

## 1️⃣ Single Sequence Analysis

The user enters:

Gene + organism  
(example: **rbcL Zea mays**)

The program retrieves the sequence from NCBI and performs multiple analyses.

### Outputs displayed:

- Record information:
  - ID  
  - Name  
  - Locus  
  - Accession  
  - Definition  
  - Organism  
  - Sequence length  

- DNA sequence preview (first 100 bp)

- Nucleotide counts:
  - A count  
  - T count  
  - G count  
  - C count  

- GC content percentage  
- TA content percentage  

- Complement sequence  
- Reverse sequence  
- Reverse complement sequence  

- Protein translation preview  

- Top k-mers detection  

- ORFs (Open Reading Frames)  

- BLAST analysis:
  - E-value  
  - E-value Score (−log10)  

---

## 2️⃣ Sequence Comparison

The user enters:

Two gene + organism queries.

Example:

rbcL Ulva lactuca  
rbcL Sargassum latifolium  

The program retrieves both sequences and compares them.

### Outputs displayed:

For Sequence 1:

- Organism name  
- GC content  
- TA content  
- Protein preview  

For Sequence 2:

- Organism name  
- GC content  
- TA content  
- Protein preview  

Comparison results:

- Similarity percentage  
- BLAST E-value for sequence 1  
- BLAST E-value for sequence 2  
- E-value score for sequence 1  
- E-value score for sequence 2  

Biological interpretation:

- Strong similarity  
- Moderate similarity  
- Low similarity  

### Visualization:

A **Bar Chart** is generated to compare:

- GC content  
- TA content  
- Similarity  
- E-value Score  

---

## 3️⃣ Phylogenetic Tree Generator

The user enters:

- One gene name  
- Three organism names  

Example:

Gene: rbcL  

Organisms:

- Ulva lactuca  
- Sargassum latifolium  
- Chlorella vulgaris  

The program retrieves sequences and calculates relationships.

### Outputs displayed:

- Sequence length for each organism  

Pairwise similarity:

- Organism 1 vs Organism 2  
- Organism 1 vs Organism 3  
- Organism 2 vs Organism 3  

Distance Matrix generated from similarity values.

Phylogenetic Tree showing evolutionary relationships.

---

# ✨ Features

## Core Features

### Feature 1 — Single Sequence Analysis

- Fetch sequence data from NCBI  
- Display biological record information  
- Calculate nucleotide counts  
- Compute GC and TA content  
- Generate complement sequences  
- Translate DNA into protein  
- Detect ORFs  
- Run BLAST analysis  
- Calculate E-value score  

---

### Feature 2 — Sequence Comparison

- Compare two biological sequences  
- Calculate similarity percentage  
- Display GC and TA comparison  
- Perform BLAST comparison  
- Generate biological interpretation  
- Display comparison using **Bar Chart visualization**  

---

### Feature 3 — Phylogenetic Tree

- Retrieve three sequences  
- Calculate similarity matrix  
- Generate distance matrix  
- Build simple phylogenetic tree  

---

## Future Features (Roadmap)

- Add graphical user interface (GUI)  
- Store results securely  
- Support multiple sequence alignment  
- Add advanced phylogenetic algorithms  
- Integrate blockchain-based result tracking  

---
## 🎥 Demo Videos

Intro Video:
[Watch Intro Video] ( https://drive.google.com/file/d/145U2ZzSdX52rfDiuNMBDPFsvEPouHFxa/view?usp=sharing )

Demo Video:
[Watch Demo Video] ( https://drive.google.com/file/d/18e7QX_SuFQ5HfH9qBLQ_v9AJr3utlF0U/view?usp=sharing )

# 🛠️ Technology Stack

Backend:

- Python  
- Biopython  
- NCBI Entrez API  
- Matplotlib  

Data Source:

- NCBI Database  

Visualization:

- Matplotlib Bar Charts  

---

# 🏗️ Architecture

User Input  
↓  
NCBI Data Retrieval  
↓  
Sequence Analysis  
↓  
Result Processing  
↓  
Visualization (Bar Chart / Tree)  
↓  
Output Display  

---

# 📋 Prerequisites

Install:

- Python  
- Biopython  
- Matplotlib  

---

# 🚀 Installation

Install required libraries:

```bash
pip install biopython matplotlib

# 💡 Solution

BioPyLogic provides an interactive bioinformatics workflow that allows users to analyze DNA sequences easily using NCBI.

The system includes three main analysis options:

---

## 1️⃣ Single Sequence Analysis

The user enters:

Gene + organism  
(example: **rbcL Zea mays**)

The program retrieves the sequence from NCBI and performs multiple analyses.

### Outputs displayed:

- Record information:
  - ID  
  - Name  
  - Locus  
  - Accession  
  - Definition  
  - Organism  
  - Sequence length  

- DNA sequence preview (first 100 bp)

- Nucleotide counts:
  - A count  
  - T count  
  - G count  
  - C count  

- GC content percentage  
- TA content percentage  

- Sequence processing:
  - Complement sequence  
  - Reverse sequence  
  - Reverse complement  

- Protein translation

- Top k-mers detection

- ORFs (Open Reading Frames)

- BLAST analysis:
  - E-value  
  - E-value Score (−log10)

This helps users understand DNA structure and sequence properties.

---

## 2️⃣ Sequence Comparison

The user enters:

Two gene + organism queries.

Example:

rbcL Ulva lactuca  
rbcL Sargassum latifolium  

The program retrieves both sequences and compares them.

### Outputs displayed:

For Sequence 1:

- Organism name  
- GC content  
- TA content  
- Protein preview  

For Sequence 2:

- Organism name  
- GC content  
- TA content  
- Protein preview  

Comparison results:

- Similarity percentage between sequences  
- BLAST E-value for sequence 1  
- BLAST E-value for sequence 2  
- E-value score for sequence 1  
- E-value score for sequence 2  

Biological interpretation:

- Strong similarity  
- Moderate similarity  
- Low similarity  

### Visualization:

A Bar Chart is generated to compare:

- GC content  
- TA content  
- Similarity  
- E-value Score  

This helps visualize sequence relationships clearly.
## 3️⃣ Phylogenetic Tree Generator

The user enters:

- One gene name  
- Three organism names  

Example:

Gene: rbcL  
Organisms:

- Ulva lactuca  
- Sargassum latifolium  
- Chlorella vulgaris  

The program retrieves sequences and calculates relationships.

### Outputs displayed:

- Sequence length for each organism  

Pairwise similarity:

- Organism 1 vs Organism 2  
- Organism 1 vs Organism 3  
- Organism 2 vs Organism 3  

Distance Matrix:

Calculated from similarity values.

Phylogenetic Tree:

A simple text-based phylogenetic tree showing evolutionary relationships between organisms.

---

# ✨ Features

## Core Features

### Feature 1 — Single Sequence Analysis

- Fetch sequence data from NCBI
- Display biological record information
- Calculate nucleotide counts
- Compute GC and TA content
- Generate complement sequences
- Translate DNA into protein
- Detect ORFs
- Run BLAST analysis
- Calculate E-value score

---

### Feature 2 — Sequence Comparison

- Compare two biological sequences
- Calculate similarity percentage
- Display GC and TA comparison
- Perform BLAST comparison
- Generate biological interpretation
- Display comparison using Bar Chart visualization

---

### Feature 3 — Phylogenetic Tree

- Retrieve three sequences
- Calculate similarity matrix
- Generate distance matrix
- Build simple phylogenetic tree

---

## Future Features (Roadmap)

- Add graphical user interface (GUI)
- Store results securely
- Support multiple sequence alignment
- Add advanced phylogenetic algorithms
- Integrate blockchain-based result tracking

---

# 🛠️ Technology Stack

Backend:

- Python  
- Biopython  
- NCBI Entrez API  
- Matplotlib  

Data Source:

- NCBI Database  

Visualization:

- Matplotlib Bar Charts  

---

# 🏗️ Architecture

User Input  
↓  
NCBI Data Retrieval  
↓  
Sequence Analysis  
↓  
Result Processing  
↓  
Visualization (Bar Chart / Tree)  
↓  
Output Display  

This workflow ensures clear data flow from sequence retrieval to result generation.

---

# 📋 Prerequisites

Before running the tool:

Install:

- Python  
- Biopython  
- Matplotlib  

---

# 🚀 Installation

Install required libraries:

```bash
pip install biopython matplotlib
# 📌 Example Usage

Example 1 — Single Sequence Analysis

User Input:

1  
rbcL Zea mays  

Program Output:

- DNA sequence retrieved from NCBI database
- Record information displayed (ID, organism, accession, length)
- Nucleotide counts calculated (A, T, G, C)
- GC content and TA content computed
- Complement, reverse, and reverse complement generated
- Protein translation preview displayed
- Top k-mers detected
- ORFs identified
- BLAST E-value calculated
- E-value score generated


---

Example 2 — Sequence Comparison

User Input:

2  
rbcL Ulva lactuca  
rbcL Sargassum latifolium  

Program Output:

- Sequence 1 biological properties displayed
- Sequence 2 biological properties displayed
- GC content comparison calculated
- TA content comparison calculated
- Protein preview comparison displayed
- Similarity percentage calculated
- BLAST E-values calculated
- E-value scores generated
- Biological similarity interpretation shown
- Bar Chart visualization generated comparing:
  - GC content
  - TA content
  - Similarity percentage
  - E-value scores


---

Example 3 — Phylogenetic Tree

User Input:

3  
rbcL  
Ulva lactuca  
Sargassum latifolium  
Chlorella vulgaris  

Program Output:

- Sequences retrieved for three organisms
- Sequence lengths displayed
- Pairwise similarity calculated
- Distance matrix generated
- Phylogenetic tree displayed
- Evolutionary relationships visualized


---

# ⚡ Conflux Integration

BioPyLogic supports planned integration with the Conflux blockchain to enable secure storage of biological analysis results.

Instead of losing results after program execution, outputs can be stored permanently in structured format.

Planned Workflow:

User runs analysis  
↓  
Results generated  
↓  
Results converted into JSON format  
↓  
JSON stored securely on Conflux blockchain  
↓  
Results become permanent and verifiable  


Example JSON Output:

{
 "analysis_type": "sequence_comparison",
 "gene": "rbcL",
 "organisms": ["Ulva lactuca", "Sargassum latifolium"],
 "similarity": 87.4,
 "gc_content_seq1": 48.2,
 "gc_content_seq2": 45.7,
 "evalue_score_seq1": 30,
 "evalue_score_seq2": 28
}


Benefits of Conflux Integration:

- Secure storage of biological results
- Transparent and verifiable data records
- Prevention of data loss
- Reproducible bioinformatics workflows
- Future-ready blockchain-enabled analysis


---

# 📜 License

This project is licensed under the MIT License.

You are free to use, modify, and distribute this project for educational and research purposes.

---

## 🎥 Demo Videos

Intro Video:
[Watch Intro Video](https://drive.google.com/file/d/145U2ZzSdX52rfDiuNMBDPFsvEPouHFxa/view?usp=sharing)

Demo Video:
[Watch Demo Video](https://drive.google.com/file/d/18e7QX_SuFQ5HfH9qBLQ_v9AJr3utlF0U/view?usp=sharing)
