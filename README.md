# this is my end to end project

# first initialize the git

```
git init
```

```
git add abc.txt
git add .
```
```
git commit -m "this is my first commit"
```

```

git pull

```

```
bash your_file_name.sh
```

```
python setup.py install
```

# another way you can mention -e . in your requirement file and you can run

```
pip install -r requirements.txt
```


## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### local cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kishanverma4444/mlflow.mlflow \
MLFLOW_TRACKING_USERNAME=kishanverma4444 \
MLFLOW_TRACKING_PASSWORD=b389441d4e88752fad565cba12d8634fdb9987da \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kishanverma4444/mlflow.mlflow \

export MLFLOW_TRACKING_USERNAME=kishanverma4444 \

export MLFLOW_TRACKING_PASSWORD=b389441d4e88752fad565cba12d8634fdb9987da \

```


### DVC cmd
- dvc init
- dvc repro
- dvc dag

