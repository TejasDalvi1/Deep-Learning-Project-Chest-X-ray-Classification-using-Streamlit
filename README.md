===============================================================================
# Deep-Learning-Project-Chest-X-ray-Classification
===============================================================================
## Tech stack:
        (1)Python
        (2)Pytorch
        (3)AWS
        (4)BentoML
-------------------------------------------------------------------------------
## Workflow (of updating files)

- constants
- config_enity
- artifact_entity
- components
- pipeline
- main
-------------------------------------------------------------------------------

## Steps to run:

### (1) Create Environment
```bash
conda create -n x_ray python=3.8 -y
```
```bash
conda activate x_ray
```

### (2) Install "requirements.txt"
```bash
pip install -r requirements_dev.txt
```

### (3) setup AWS CLI
```bash
link: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

```
```bash
aws configure
```
```bash
AWS_ACCESS_KEY_ID=***

AWS_SECRET_ACCESS_KEY= ***

AWS_REGION = us-east-1
```

### (4) Run "main.py"
```bash
python main.py
```
-------------------------------------------------------------------------------