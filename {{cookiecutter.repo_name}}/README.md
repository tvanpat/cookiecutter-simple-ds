# {{cookiecutter.repo_name}}

{{cookiecutter.description}}

Project Organization
------------

    ├── work                                <- Location where all work will occur in project.
    │   ├── data                                <- Location of data used in project.
    │   │
    │   ├── models                              <- Trained and serialized models, model predictions, or model summaries.
    │   │   ├── current                         <- Current model produced by this project.
    │   │   ├── imputation                      <- Models used to impute missing values in training data.
    │   │
    │   ├── modules                             <- Project specific modules.
    │   │
    │   ├── tests                               <- modules used for testing.
    │   │
    │   ├── {{cookiecutter.repo_name}}.ipynb    <- Jupyter notebook used for this project.
    │   │
    │   ├── requirements.txt                    <- The requirements file for reproducing the analysis environment, e.g.
    │                                              generated with `pip freeze > requirements.txt`. Used if user prefers
    │                                              virtual environments to run program as opposed to docker environments.
    │
    ├── .dockerignore                       <- Types of files not to include in a Docker build.
    │
    ├── .gitignore                          <- Types of files to exclude from git.
    │
    ├── docker_requirements.txt             <- Project specific python modules used for this project excluding 
    │                                          those used in the jupyter/scipy-notebook image.
    │
    ├── Dockerfile                          <- Dockerfile to build the Jupyter notebook environment, based on the 
    │                                          jupyter/scipy-notebook image.
    │
    ├── Dockerfile.tst                      <- Dockerfile used to run unit tests based in Pytest.
    │
    ├── README.md                           <- The top-level README for developers using this project.
    │
