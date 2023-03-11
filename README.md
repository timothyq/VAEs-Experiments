# Experiments on VAEs

### Project Structures
my_project/
├── data/
│   ├── train.csv
│   ├── validation.csv
│   ├── test.csv
│   └── *datasrc/
├── models/
│   ├── __init__.py
│   ├── model.py
│   ├── loss.py
│   └── metrics.py
├── notebooks/
│   ├── explore_data.ipynb
│   └── train_model.ipynb
├── trainers/
│   ├── __init__.py
│   ├── base_trainer.py
│   └── model_trainer.py
├── utils/
│   ├── __init__.py
│   ├── dataset.py
│   └── config.py
├── tests/
│   ├── __init__.py
│   ├── test_model.py
│   └── test_trainer.py
├── config.yaml
├── main.py
└── README.md
