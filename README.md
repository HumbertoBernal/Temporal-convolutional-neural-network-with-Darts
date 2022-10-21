
# Temporal convolutional neural network

This is a replica and update of the code from the [blog](https://unit8.com/resources/temporal-convolutional-networks-and-forecasting/) by Francesco Lässig.


# Instructions

## How to run the project

1. Install the dependencies:
```python
pip install requirements.txt
```

2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather).

3. Run the main.py file.
```python
python main.py
```

## How to load / save your model

To save your model use:
```python
model.save(path)
```
To load your model use:
```python
from darts.models import TCNModel

model = TCNModel()
model.load(path)
```

Resources:

https://unit8.com/resources/temporal-convolutional-networks-and-forecasting/
https://arxiv.org/pdf/1803.01271.pdf
https://unit8co.github.io/darts/
https://github.com/unit8co/darts/blob/develop-bak/examples/06-TCN-examples.ipynb