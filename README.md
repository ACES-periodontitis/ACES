# Computation of the new classification of periodontitis according to the European Federation of Periodontology (EFP) based on epidemiological datasets.

Classifications in medicine and dentistry are necessary for practitioners to correctly diagnose and subsequently treat their patients, as well as for scientists to study the prevalence and etiopathogenesis of diseases, their prognosis, course and therapy. Over the past 30 years, the **classification of periodontitis** has been repeatedly modified to bring it in line with new scientific findings. In 2017, a [new framework for the classification of periodontitis](https://www.efp.org/publications-education/new-classification/overview/) was developed. It was agreed to further characterize periodontitis within the framework of a multi-dimensional *staging and grading* matrix. Here, staging - the stage of the disease - is dependent on the severity of the diagnosis and also the complexity of its treatment, while grading - the degree of the disease - provides additional information regarding disease progression and risks. Refer to the document [Periodontitis: clinical decision tree for staging and grading](https://www.efp.org/fileadmin/uploads/efp/Documents/Campaigns/New_Classification/Guidance_Notes/report-02b.pdf) for detailed information. 

The aim of the project is to develop algorithms based on epidemiological data, which allows the characterization of "periodontitis" at the patient level based on the multi-dimensional "staging and grading" matrix. These algorithms will be made available to the scientific community. 


## Publication


### [**ACES: A new framework for the application of the 2018 periodontal status classification scheme to epidemiological survey data**](https://onlinelibrary.wiley.com/doi/10.1111/jcpe.13965)

Please cite as `Holtfreter, B., Kuhr, K., Borof, K.,Tonetti, M. S., Sanz, M., Kornman, K., Jepsen, S., Aarabi, G.,Völzke, H., Kocher, T., Krois, J., & Papapanou, P. N. (2024). ACES: A new framework for the application of the 2018 periodontal status classification scheme to epidemiologicalsurvey data. Journal of Clinical Periodontology, 1–10. https://doi.org/10.1111/jcpe.13965`

#### Aim
To propose a framework for consistently applying the 2018 periodontal status classification scheme to epidemiological surveys (Application of the 2018 periodontal status Classification to Epidemiological Survey data, ACES).

#### Proposed Framework
We specified data requirements and workflows for either completed or planned epidemiological surveys, utilizing commonly collected measures of periodontal status (clinical attachment levels [CAL], probing depths, bleeding on probing), as well as additional necessary variables for the implementation of the 2018 periodontal status classification (tooth loss due to periodontitis and complexity factors). Following detailed instructions and flowcharts, survey participants are classified as having periodontal health, gingivitis or periodontitis. Rates of edentulism must also be reported. In cases of periodontitis, instructions on how to compute the stage and extent are provided. Assessment of grade can be derived from CAL measurements (or from radiographic alveolar bone loss data) in relation to root length and the participant's age.

#### Conclusions
ACES is a framework to be used in epidemiological studies of periodontal status that (i) have been completed, and in which stage and grade according to the 2018 classification are inferred retroactively, or (ii) are being planned. Consistent use of the proposed comprehensive approach will facilitate the comparability of periodontitis prevalence estimates across studies.


## Contact

* ZZMK - Birte Holtfreter (birte.holtfreter@uni-greifswald.de)
* IDZ - Kathrin Kuhr (K.Kuhr@idz.institute)
* UKE -  Katrin Borof (k.borof@uke.de)
* ODDH2 - Joachim Krois (joachim.krois@gmail.de)

***

## Repository structure

This repository has the following structure:

    pkk
    ├── .git                    # Git internals, don't mess around here.
    ├── .gitignore              # Specifies files and folders that should be ignored by git.
    ├── datasets                # Find the datasets here 
    ├── README.md               # README for using this project.    
    ├── Python                  # Find the Python implementation of the algorithm here.
    │   └── ...                 # ...
    │   ├── data                # data folder
    │   │   ├── interim         # temporary files
    │   │   └── processed       # processed files that may be used elsewhere
    │   ├── src                 # Source code
    │   │   ├── __init__.py     # Makes src a Python module
    │   │   └── notebook_env.py # A file with basic settings when working with Jupyter notebooks.
    │   ├── requirements.yml    # The requirements file for reproducing the analysis environment. 
    │   └── README.md           # A README for the Python code repository.
    ├── R                       # Find the R implementation of the algorithm here.
    │   ├── ...                 # ...
    │   ├── data                # data folder
    │   │   ├── interim         # temporary files
    │   │   └── processed       # processed files that may be used elsewhere
    │   ├── src                 # Source code
    │   └── README.md           # A README for the R code repository.
    ├── SPSS                    # Find the SPSS implementation of the algorithm here.
    │   ├── ...                 # ...
    │   ├── data                # data folder
    │   │   ├── interim         # temporary files
    │   │   └── processed       # processed files that may be used elsewhere
    │   ├── src                 # Source code
    │   └── README.md           # A README for the SPSS code repository.
    ├── STATA                   # Find the STATA implementation of the algorithm here.
    │   ├── ...                 # ...
    │   ├── data                # data folder
    │   │   ├── interim         # temporary files
    │   │   └── processed       # processed files that may be used elsewhere
    │   ├── src                 # Source code
    │   └── README.md           # A README for the STATA code repository.
    
    




