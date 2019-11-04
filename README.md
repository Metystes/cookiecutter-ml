{{cookiecutter.project_name}}
====================


{{cookiecutter.project_short_description}}

**Start Date:** {{cookiecutter.start_date}}

**Release Date:** {{cookiecutter.realease_date}}


Description
-----

**More Detailed Description**
Lorem Ipsum


Files Structure
-----------------

```
.
    ├── AUTHORS.md
    ├── LICENSE
    ├── README.md
    ├── models  <- compiled model .pkl or HDFS or .pb format
    ├── config  <- any configuration files
    ├── data
    │   ├── interim <- data in intermediate processing stage
    │   ├── processed <- data after all preprocessing has been done
    │   └── raw <- original unmodified data acting as source of truth and provenance
    ├── docs  <- usage documentation or reference papers
    ├── notebooks <- jupyter notebooks for exploratory analysis and explanation
        └── {initials}_{number}_{title}.ipynb <- Names of the notebooks with initials of the person, number and short description
    ├── reports <- generated project artefacts eg. visualisations or tables
    │   └── figures
    └── src
        ├── data   <- Scripts to download or generate data 
        ├── featurs     <- Scripts to turn raw data into features for modeling
        ├── modeling    <- Scripts to train models and then use trained models to make
        ├── utils       <- Scripts with general funcs and classes useful in the process
        └── visualization  <- Scripts to create exploratory and results oriented visualizations
    ├── environment.yml . <- YAML file with libraries and library versions for recreating an environment using conda
```

