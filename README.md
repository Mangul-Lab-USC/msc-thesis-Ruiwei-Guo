[Acknowledgements]

First and foremost, I would like to greatly acknowledge the help and support of my supervisor, Dr. Serghei Mangul, who has offered me valuable suggestions in academic studies and provided me with valuable guidance in every stage of the writing of this thesis. Also, I shall extend my gratitude to my teamates and friends in Serghei's lab, thanks for their help, kindness and time spent together. Without Dr. Serghei’s enlightening instruction, and my teamates' help, I would not have completed my thesis.

[Background information]

Modern data-driven research increasingly depends on quantitative analysis and researchers have increasingly recognized the need and benefits of sharing research products (i.e. raw data, the metadata accompanying the raw data, and the code of the analysis). To promote transparency and reproducibility in biomedical research, it is not only necessary to publish a full description of the study design, methodology, results, and interpretation, but it is also critical to make all research products publicly available, shareable, repurposable and properly documented.

Currently, the conduct of sharing research products relies heavily on individual researchers, and the regulations of data sharing are enforced by these individuals and research institutions in a variety of ways. However, a rising body of evidence in recent years reveals reproducibility issues across many scientific disciplines, i.e. published results frequently contain studies that cannot be duplicated due to a lack of documentation, code, data or metadata.

This study analyzed 480 publications across eight journals from 2016 to 2021 to quantify code and data availability of the publications and assess the completeness of the metadata reported in publications and online repositories across 127 studies over 18,559 samples across six therapeutic fields.This research aims to analyze the availability of research products and help to build a transparent, reproducible data-driven environment in biomedical research.

[How to use the files]

There are three chapters in my thesis, which are Availability of data accompanying scientific publication, Availability of code accompanying scientific publication and Metadata availability and analysis. Each of the three directories contains 3 subdirectories: code, results, figures and a README. The code for chapter 1 can be found in «code» subdirectory of «Chapter 1» directory in the file named "chapter 1-data availability". The code for chapter 2 can be found in «code» subdirectory of «Chapter 2» directory in the file named "chapter 2-code availability". The code for chapter 3 can be found in «code» subdirectory of «Chapter 3» directory in the file named "chapter 3-metadata". The data for chapter 1 and 2 can be found in «results» subdirectory of «Chapter 1» directory in the file named "Data_CDAP_Jan22-Main_copy1". The data for chapter 3 can be found in «results» subdirectory of «Chapter 3» directory the file named "Metadata_Summary_Table".

[Directory Structure]

msc-thesis-Ruiwei-Guo
├─── Chapter 1
│   ├── code 
│   │   ├── chapter1_data_availability.ipynb
│   │   └── README.md
│   ├── results
│   │   ├── Data_CDAP_Jan22-Main_copy1.csv
│   │   └── README.md
│   └── figures
│       └── README.md
├─── Chapter 2
│   ├── code 
│   │   ├── chapter2_code_availability.ipynb
│   │   └── README.md
│   ├── results
│   │   ├── Data_CDAP_Jan22-Main_copy1.csv
│   │   └── README.md
│   └── figures
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
│       └── README.md
└── README.md

[Datasets]
After downloading the entire open-access corpus of publications from the PubMed Central (PMC), only the directories named after the following eight journals: Nature Biotechnology, Genome Medicine, Nature Methods, Genome Biology, Bioinformatics, BMC Bioinformatics, Nucleic Acid Research, and Nature Genetics were kept.  These publications were published ranging from the year 2016 to 2021 including the commercial use and non-commercial use subsets. 12,603 publications were selected for the analysis each having a unique PMC 
identification number (PMC ID) stored in XML file. The original files were then processed with Python script utilizing the package ElementTree to systematically extract publication metadata. Since the XML files and scripts are not available, resulting CSV files can be found in "results" subdirectories of Chapter 1, Chapter 2 and Chapter 3 directories, respectively. Detailed description of each file is present in README file within "results" folder.

[Contact]
Please do not hesitate to contact us (grigore.boldirev@gmail.com, mangul@usc.edu) if you have any comments, suggestions, or clarification requests regarding the study or if you would like to contribute to this resource. If you encounter bugs or have further questions or requests, you can raise an issue at the issue page.
