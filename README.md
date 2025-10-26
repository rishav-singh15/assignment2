## Assignment 2: Advanced Genomic Analysis and Pattern Recognition

This repository contains the solution for **Assignment 2: Advanced Genomic Analysis and Pattern Recognition (CCA4)**, which builds upon basic DNA manipulation by implementing advanced tools for sequence composition analysis, pattern matching, and protein analysis.

---

## 1. Submission Details

| Detail | Value |
| :--- | :--- |
| **Total Marks** | [cite_start]100 Marks [cite: 63] |
| **Deadline** | [cite_start]28 October 2025 [cite: 81] |
| **Submission Format** | [cite_start]Python files (`.py`), Jupyter notebooks (`.ipynb`), and documentation [cite: 82] |
| **Code Base** | [cite_start]Python standard library and common packages (NumPy, Pandas for data analysis) [cite: 76] |

---

## 2. Implementation Overview

[cite_start]The solution addresses three main areas: GC content and advanced composition analysis, pattern matching for motif discovery, and comprehensive protein sequence analysis[cite: 85, 96, 107].

### [cite_start]Part A: GC Content and Sequence Analysis (30 marks) [cite: 85]

#### [cite_start]Question 1: GC Content Calculation (15 marks) [cite: 86]
Comprehensive GC analysis implementation:
* [cite_start]**Overall GC:** Calculation of the overall GC content percentage[cite: 87].
* [cite_start]**Sliding Windows:** Analysis of GC content using a sliding window approach[cite: 88].
* [cite_start]**GC Skew:** Generation of GC skew plots and related statistics[cite: 89].
* [cite_start]**Comparison:** Implemented a function to compare GC content across different species or sequences[cite: 90].

#### [cite_start]Question 2: Sequence Composition Analysis (15 marks) [cite: 91]
Advanced sequence composition tools developed:
* [cite_start]**Oligonucleotide Frequencies:** Calculation of dinucleotide and trinucleotide frequencies[cite: 92].
* [cite_start]**CpG Islands:** Identification of CpG islands within genomic sequences[cite: 93].
* [cite_start]**Codon Usage Bias:** Analysis of codon usage bias in protein-coding regions[cite: 94].
* [cite_start]**Classification:** Generation of composition-based sequence classification[cite: 95].

---

### [cite_start]Part B: Pattern Matching and Motif Discovery (40 marks) [cite: 96]

#### [cite_start]Question 3: Hamming Distance Implementation (15 marks) [cite: 97]
Sophisticated distance calculation algorithms:
* [cite_start]**Hamming Distance:** Implemented the Hamming distance metric for sequence comparison[cite: 98].
* [cite_start]**Length Handling:** Functionality to handle sequences of different lengths[cite: 99].
* [cite_start]**Distance Matrices:** Calculation of distance matrices for a set of multiple sequences[cite: 100].
* [cite_start]**Visualization Prep:** Used appropriate data structures to prepare for the visualization of distance relationships[cite: 101].

#### [cite_start]Question 4: Motif Finding Algorithms (25 marks) [cite: 102]
Advanced pattern recognition systems developed:
* [cite_start]**Exact Matching:** Implemented exact pattern matching algorithms[cite: 103].
* [cite_start]**Fuzzy Matching:** Created fuzzy matching functionality with support for a defined number of allowed mismatches[cite: 104].
* [cite_start]**Occurrence Finding:** Developed logic to find all occurrences of patterns in genomic sequences[cite: 105].
* [cite_start]**Conservation Analysis:** Algorithms to analyze motif conservation across multiple sequences[cite: 106].

---

### [cite_start]Part C: Protein Sequence Analysis (30 marks) [cite: 107]

#### [cite_start]Question 5: Reading Frame Analysis (15 marks) [cite: 108]
Comprehensive Open Reading Frame (ORF) detection system:
* [cite_start]**Six Frames:** Identification of all six reading frames in DNA sequences[cite: 109].
* [cite_start]**Start/Stop Codons:** Logic to find start and stop codons in each reading frame[cite: 110].
* [cite_start]**Sequence Extraction:** Extraction of potential protein sequences (candidate ORFs)[cite: 111].
* [cite_start]**Statistics:** Calculation of ORF statistics and length distributions[cite: 112].

#### [cite_start]Question 6: Protein Translation and Analysis (15 marks) [cite: 113]
Implementation of translation machinery and analysis tools:
* [cite_start]**Translation:** Conversion of DNA/RNA sequences to amino acid sequences[cite: 114].
* [cite_start]**Genetic Code:** Implementation handles the genetic code using dictionaries for mapping[cite: 115].
* [cite_start]**Longest ORFs:** Identification and translation of the longest ORFs found[cite: 116].
* [cite_start]**Amino Acid Analysis:** Analysis of amino acid composition and properties of translated sequences[cite: 117].

---

## 3. Evaluation and Quality Assurance

[cite_start]The implementation strictly adheres to the submission requirements and evaluation criteria[cite: 64, 70]:

* [cite_start]**Correctness (40%):** Algorithm implementation accuracy and output validity are ensured[cite: 71].
* [cite_start]**Efficiency (25%):** Code optimization and performance considerations were prioritized, with time and space complexity analysis included[cite: 68, 72].
* **Code Quality (20%):** The Python code is **well-commented**, **readable**, and follows the **PEP 8** standard. [cite_start]All functions and classes include **docstrings**[cite: 65, 66, 73].
* [cite_start]**Innovation (15%):** Creative solutions and additional features were implemented[cite: 74].
* [cite_start]**Version Control:** The entire codebase is managed on a **GitHub Repository** with proper commit history[cite: 69].

---

## 4. How to Run

1.  Clone the repository:
    ```bash
    git clone [Your Repository URL]
    ```
2.  Navigate to the directory:
    ```bash
    cd [repository-name]
    ```
3.  Ensure required packages are installed (if any beyond standard library):
    ```bash
    [cite_start]pip install numpy pandas  # As per allowed resources [cite: 76]
    ```
4.  [cite_start]The main code and analysis can be found in the provided Jupyter Notebook (`.ipynb`) and supporting Python files (`.py`)[cite: 82].
5.  [cite_start]Run the testing suite to verify all functionalities[cite: 67]:
    ```bash
    python -m unittest discover tests  # Example command, depending on test setup
    ```
