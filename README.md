
##  How to use the files
There are three chapters in my thesis, which are Availability of data accompanying scientific publication, Availability of code accompanying scientific publication and Metadata availability and analysis. Each of the three directories contains 3 subdirectories: code, results, figures and a README. The code for chapter 1 can be found in «code» subdirectory of «Chapter 1» directory in the file named "chapter 1-data availability". The code for chapter 2 can be found in «code» subdirectory of «Chapter 2» directory in the file named "chapter 2-code availability". The code for chapter 3 can be found in «code» subdirectory of «Chapter 3» directory in the file named "chapter 3-metadata". The data for chapter 1 and 2 can be found in «results» subdirectory of «Chapter 1» directory in the file named "Data_CDAP_Jan22-Main_copy1". The data for chapter 3 can be found in «results» subdirectory of «Chapter 3» directory the file named "Metadata_Summary_Table".

##  Directory Structure

```
msc-thesis-Ruiwei-Guo
├─── Chapter 1
│   ├── code 
│   │   ├── chapter1_data_availability.ipynb
│   │   └── README.md
│   ├── results
│   │   ├── Data_CDAP_Jan22-Main_copy1.csv
│   │   └── README.md
│   └── figures
│       ├── Figure1.png
│       ├── Figure2.png
│       ├── Figure3.png
│       ├── Figure4.png
│       └── README.md
├─── Chapter 2
│   ├── code 
│   │   ├── chapter2_code_availability.ipynb
│   │   └── README.md
│   ├── results
│   │   ├── Data_CDAP_Jan22-Main_copy1.csv
│   │   └── README.md
│   └── figures
│       ├── Figure5.png
│       ├── Figure6.png
│       ├── Figure7.png
│       ├── Figure8.png
│       └── README.md
├─── Chapter 3 
│   ├── code 
│   │   ├── chapter3_metadata(2).ipynb
│   │   ├── pull_metadata.py
│   │   ├── get_xml_files.py
│   │   └── README.md
│   ├── results
│   │   ├── Metadata_Summary_Table.xlsx
│   │   └── README.md
│   └── figures
│       ├── Figure9.png
│       ├── Figure10.png
│       ├── Figure11.png
│       ├── Figure12.png
│       ├── Figure13_a.png
│       ├── Figure13_b.png
│       ├── Figure13_c.png
│       └── README.md
└── README.md

```            

##  Datasets
After downloading the entire open-access corpus of publications from the PubMed Central (PMC), only the directories named after the following eight journals: Nature Biotechnology, Genome Medicine, Nature Methods, Genome Biology, Bioinformatics, BMC Bioinformatics, Nucleic Acid Research, and Nature Genetics were kept.  These publications were published ranging from the year 2016 to 2021 including the commercial use and non-commercial use subsets. 12,603 publications were selected for the analysis each having a unique PMC 
identification number (PMC ID) stored in XML file. The original files were then processed with Python script utilizing the package ElementTree to systematically extract publication metadata. Since the XML files and scripts are not available, resulting CSV files can be found in "results" subdirectories of Chapter 1, Chapter 2 and Chapter 3 directories, respectively. Detailed description of each file is present in README file within "results" folder.

##  Contact
Please do not hesitate to contact us (ruiweigu@usc.edu, mangul@usc.edu) if you have any comments, suggestions, or clarification requests regarding the study or if you would like to contribute to this resource. If you encounter bugs or have further questions or requests, you can raise an issue at the issue page.
