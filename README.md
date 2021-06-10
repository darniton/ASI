# ASI
Attention-Based Spatial Interpolation for House Price Prediction

## Data

* Data: a numpy saved file (.npz) containing:
  * data['dist_eucli']
  * data['dist_geo']
  * data['idx_eucli']
  * data['idx_geo']
  * data['X_train']
  * data['X_test']
  * data['y_train']
  * data['y_test']

## Installation
To install as a module:
```
$ git clone https://github.com/darniton/ASI
$ cd ASI
$ pip install -r requirements.txt
```

## Replicating experiments
To replicate the experimental results:

* ./notebook: One notebook for each dataset
    