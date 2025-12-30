# [🧬 Hemolytik 2.0 🩸](http://webs.iiitd.edu.in/raghava/hemolytik2/)

Welcome to the official data repository for **Hemolytik 2.0**, a comprehensive and manually curated database of experimentally validated hemolytic and non-hemolytic peptides. This resource is designed to support researchers in the rational design and development of safer, more effective therapeutic peptides. 👩‍🔬👨‍🔬

**🔬 About the Database**

Hemolytik 2.0 is an updated and significantly expanded version of the original Hemolytik database. Peptides are promising therapeutic agents, but their clinical use can be limited by hemotoxicity—the unintended destruction of red blood cells (RBCs). This database provides a centralized platform to explore the complex relationship between a peptide's sequence, structure, chemical modifications, and its hemolytic activity. The data have been meticulously collected from over 4,533 peer-reviewed publications and established peptide repositories, including APD3, CAMP-R4, UniProt, and DRAMP4.0.

![Hemolytik 2.0 Overview](images/HEM_logo.jpeg)

---
## ✨ Key Features
**Massive Dataset 📈**: Contains 13,215 curated entries for over 7,500 unique peptides.

**Rich Annotations 📝**: Each entry includes detailed information such as amino acid sequence, biological source, terminal modifications (amidation, acetylation, etc.), stereochemistry (L, D, or mixed amino acids), and structural classification (linear, cyclic, branched, etc.).

**Structural Information 🧬**: Provides predicted tertiary structures and SMILES (Simplified Molecular Input Line Entry System) notations for over 10,615 peptides, enabling deep structure-activity relationship studies.

**Functional Data 🎯**: Includes peptides with diverse biological functions, such as antimicrobial, antibacterial, antifungal, anticancer, and cell-penetrating activities.

**Focus on Modified Peptides 🧪**: A significant portion of the database is dedicated to chemically modified peptides, which are crucial for enhancing therapeutic performance. The database includes information on non-canonical amino acids that are often used to optimize peptide drug candidates.

---
![Hemolytik 2.0 Overview](images/figure2.jpg)
## 🔍 Overview

Hemolytik 2.0 provides experimentally verified peptide sequences along with detailed annotations such as:
- **Hemolytic activity status** (Hemolytic / Non-Hemolytic)
- **Physicochemical properties**
- **Source organism**
- **Functional nature** (e.g., Antimicrobial, Anticancer, Cytotoxic)
- **Chemical modifications** (C-terminal amidation, N-terminal acetylation, lipidation, etc.)
- **Structural and sequence information**
- **Reference literature (PubMed-linked)**

---

💻 How to Download
You can download the entire dataset by cloning this repository:

Bash
```
git clone https://github.com/your-username/hemolytik2.git
```
Alternatively, you can download the latest version of the dataset as a ZIP file directly from the "Releases" page. 🚀

## 📦 Extracting `all_structures.tar.zst`

The archive is compressed using **Zstandard (zstd)** for maximum compression efficiency.

### 🔹 Step 1: Decompress the `.zst` file
Bash
```
zstd -d all_structures.tar.zst
```
This will generate: all_structures.tar

### 🔹Step 2: Extract the .tar archive
Bash
```
tar -xvf all_structures.tar
```
This will extract the original folder: all structures/

---
## 🌐 Web Server

Access the live web application here:  
👉 **[https://webs.iiitd.edu.in/raghava/hemolytik2/](https://webs.iiitd.edu.in/raghava/hemolytik2/)**

- **🎯 Aim and Objective**
The primary goal of the Hemolytik 2.0 database is to support the scientific community in studying hemolytic peptides. By compiling scattered information on these molecules into a single, comprehensive resource, the platform aims to assist both bioinformaticians and experimental researchers in their work.

- **🔍 Search Options**
The database provides powerful search capabilities to help users find the exact information they need:

i) Basic Search: This feature allows you to perform a quick search across the database's major fields. You can search in any single field or across multiple fields simultaneously. It also gives you the flexibility to DISPLAY only the specific fields you are interested in, making the results clean and focused.

ii) Advanced Search: For more complex queries, the advanced search module lets you construct detailed searches using logical operators like AND, OR, and NOT. This enables you to combine multiple criteria to refine your results. You can perform searches on any or all fields and customize the display to show all available information or just a selection of fields.

- **📚 Browse**
The modules in this section allow you to explore the database in a categorized manner. You can browse through various hemolytic peptides and proteins based on specific properties and categories, making it easy to discover related entries and explore the data systematically.

- **🛠️ Tools**
Hemolytik 2.0 integrates several web-based tools to facilitate further analysis directly on the platform:

Sequence Similarity Search: Find peptides with similar sequences.

Peptide Mapping: Map specific peptides within larger protein sequences.

Structure Alignment: Compare the 3D structures of different peptides.

- **🔗 API (Application Programming Interface)**
For developers and bioinformaticians, the Hemolytik 2.0 data is programmatically accessible. You can use simple URLs (RESTful API) to fetch data, allowing for easy integration into your own programs and analysis pipelines.

- **📱 Mobile Compatible Website**
The Hemolytik 2.0 website is built on the Bootstrap framework, ensuring that it is fully responsive. The layout automatically adjusts to fit the screen size of any device, providing a seamless experience on desktops, tablets, and smartphones.

---

## 📦 Dataset Download

The complete curated dataset of **Hemolytik 2.0** is available for academic use.  
You can download it directly from this repository:

- [`Hemolytik2_complete_data.csv`](https://github.com/anandr88/Hemolytik-2.0/blob/main/Hemolytik2_complete_data.csv)
- [`Hemolytik2_fasta_sequences.fasta`](https://github.com/anandr88/Hemolytik-2.0/blob/main/Hemolytik2_fasta_sequences.fasta)
- [`Hemolytik2_MAP_format.fasta`](https://github.com/anandr88/Hemolytik-2.0/blob/main/Hemolytik2_MAP_format.fasta)

> 📘 **Note:** The dataset is intended for non-commercial, academic, and research purposes only.  
> Please cite the corresponding publication when using this resource.

---

## 📊 Key Statistics

| Category | Count |
|-----------|-------|
| Total Peptides | 13,215 |
| Hemolytic Peptides | 9,589 |
| Non-Hemolytic Peptides | 3,626 |
| Peptides with Non-Natural Amino Acids | 2,678 |
| Functional Categories | 30+ (Antimicrobial, Anticancer, Antifungal, etc.) |
| Source Categories | 20 (Human, Horse, Sheep, Mouse, etc.) |

---

## 🧠 Citation

If you use **Hemolytik 2.0** in your research, please cite:

 
> **Singh, A., Raj SA, K., Rathore, A. S., & Raghava, G. P. S. (2025). Hemolytik2: An Updated Database of Hemolytic Peptides and Proteins.**  
> [Manuscript under review / Journal name, Year].


## ⚙️ Repository Structure

```
.
├── Hemolytik2_complete_data.csv
├── Hemolytik2_fasta_sequences.fasta
├── Hemolytik2_chemical_modifications.csv
├── source/
│   ├── Human
│   ├── Horse
│   └── ...
├── peptide type/
│   ├── L
│   ├── D
│   ├── Linear
│   └── ...
├── function/
│   ├── Antimicrobial
│   ├── Antibacterial
│   ├── Antifungal
│   └── ...
├── structure/
│   ├── all_structures.tar.zst
└── README.md
```

## 📧 Contact & Authors
For any questions, suggestions, or collaborations, please contact the corresponding author:

**Prof. Gajendra P. S. Raghava**

Email: raghava@iiitd.ac.in

Website: http://webs.iiitd.edu.in/raghava/

The database was developed and is maintained by a dedicated team at the Indraprastha Institute of Information Technology, Delhi, India.

## 📄 License
This database is made available under the MIT License. You are free to use, share, and adapt the data for any purpose, excluding commercial use, as long as you provide appropriate attribution.

## 🙏 Acknowledgments
The development of Hemolytik 2.0 was supported by funding from the Department of Biotechnology (DBT), Government of India. We thank all the researchers whose work has contributed to the data compiled in this resource. 🎉
