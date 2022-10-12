# Cancer Risk Exploration

## Deliverable
- RestAPI
```bash
curl --location --request POST 'https://gender-classifier-n7asbfuu5a-as.a.run.app/api' --header 'Content-Type: application/json' --data-raw '{"Sex":"F","Age":"37.10","Smoking":"former","BMI":28.80,"Heart rate data used":0.0,"MET (activity level)":50.08}'
```

## Usage
## installation (assumed in a [conda] virtual env)
```bash
pip install -r requirements.txt
```

## Model Playground
- [ML](code/disease_explorative_study.ipynb)


## Launch app locally using Gunicorn
```bash
gunicorn -w 4 app:app -b localhost:8000
```