# DREIFLUSS - Table Matching via Schema.org and DBpedia Labels

This repository contains the Jupyter notebook and code associated with our paper, "DREIFLUSS: A Minimalist Approach to Table Matching with Schema.org and DBpedia Labels."

The paper presents DREIFLUSS, a novel method for improving the performance of table matching tasks in the SemTab challenge using labels from Schema.org and DBpedia. We specifically focus on the Column Type Annotation (CTA) and Column Property Annotation (CPA) tasks.

## **Dataset**

- **Info**: The data used in this study are publicly available via the SemTab 2023 challenge. You can download the required datasets from the following link: SemTab 2023 Datasets 
- **CTA**: Links for download 
    - CTA tables [ref](https://data.dws.informatik.uni-mannheim.de/structureddata/sotab/Round2-SOTAB-CTA-Tables.zip)
        - Train Validate and Test files [ref](https://data.dws.informatik.uni-mannheim.de/structureddata/sotab/Round2-SOTAB-CTA-SCH-Datasets.zip)
- **CPA**: Links for download       
    - CPA tables [ref](https://data.dws.informatik.uni-mannheim.de/structureddata/sotab/Round2-SOTAB-CPA-Tables.zip)
        - Train Validate and Test files [ref](https://data.dws.informatik.uni-mannheim.de/structureddata/sotab/Round2-SOTAB-CPA-SCH-Datasets.zip)
**`Notebooks/`**: Containing all the required jupyter notebooks.         
- **`README.md`**: This file provides an overview of the repository and instructions for running the code.

## **Dependencies**

- Python libraries
    - pandas
    - gzip
    - matplotlib
    - json
    - scipy
    - sklearn

## **Usage**

1. Download all the jupyter notebook available in the **``Notebooks/`** folder.
2. Install the required dependencies and ensure access to the relevant APIs.
3. Downloand all the dataset mentioned above for CTA and CPA tasks.
4. Give proper path to the downloaded files in your jupyter notebooks
5. Run the jupyter notebooks