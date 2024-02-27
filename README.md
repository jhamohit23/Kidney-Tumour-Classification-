# Kidney-Tumour-Classification-

## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/jhamohit23/Kidney-Tumour-Classification-
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```






## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

- [MLflow tutorial](https://youtu.be/qdcHHrsXA48?si=bD5vDS60akNphkem)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/jhamohit232001/Kidney-Tumour-Classification-.mlflow \
MLFLOW_TRACKING_USERNAME=jhamohit232001 \
MLFLOW_TRACKING_PASSWORD=1da5e3e9b4a6602d94a0b15b93a8101b2a6ac422 \
python script.py

Run this to export as env variables:

```bash

export DAGSHUB_API_KEY=6b195ea4cf80eb5ca621689c210fa56561be81b4


export MLFLOW_TRACKING_URI=https://dagshub.com/jhamohit232001/Kidney-Tumour-Classification-.mlflow

export MLFLOW_TRACKING_USERNAME=jhamohit232001

export MLFLOW_TRACKING_PASSWORD=1da5e3e9b4a6602d94a0b15b93a8101b2a6ac422


```