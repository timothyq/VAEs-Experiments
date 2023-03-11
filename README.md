# Experiments on VAEs

### Project Structures
- `data/`: This directory contains the training, validation, and test CSV files.
    - `train.csv`: The training data.
    - `validation.csv`: The validation data.
    - `test.csv`: The test data.
- `models/`: This directory contains the model definition, loss function, and metrics.
    - `__init__.py`: An empty file indicating this directory can be imported as a Python package.
    - `model.py`: The PyTorch model definition.
    - `loss.py`: The custom loss function.
    - `metrics.py`: The custom metrics.
- `notebooks/`: This directory contains the Jupyter notebooks used for data exploration and model training.
    - `explore_data.ipynb`: A Jupyter notebook for exploring the data.
    - `train_model.ipynb`: A Jupyter notebook for training the model.
- `trainers/`: This directory contains the trainer classes for training the model.
    - `__init__.py`: An empty file indicating this directory can be imported as a Python package.
    - `base_trainer.py`: The base trainer class.
    - `model_trainer.py`: The trainer class used for training the PyTorch model.
- `utils/`: This directory contains utility functions and classes.
    - `__init__.py`: An empty file indicating this directory can be imported as a Python package.
    - `dataset.py`: The custom dataset class.
    - `config.py`: The configuration file.
- `tests/`: This directory contains the test files.
    - `__init__.py`: An empty file indicating this directory can be imported as a Python package.
    - `test_model.py`: The test file for the model.
    - `test_trainer.py`: The test file for the trainer.
- `config.yaml`: The configuration file in YAML format.
- `main.py`: The main script to run the training and testing.
- `README.md`: This file.
