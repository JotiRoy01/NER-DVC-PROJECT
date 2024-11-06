# /d/Develops/NLP_PROJECT/NER-DVC-PROJECT
### To run bash shell
```bash
bash init_setup.sh
```
```bash
> override
>> append
```
### Run first Stage
```bash
python src/NER_data_ingestion/data_ingestion.py
```
### Initialize The dvc
```bash
dvc init
```
### Create Necessary File
```bash
mkdir docs
touch docs/index.md
mkdir docs/img
mkdir docs/javascripts
touch docs/javascripts/mathjax.js
touch docs/img/.gitkeep
touch docs/Data_injection.md
```
### Run mkdocs server
```bash
mkdocs serve
```
