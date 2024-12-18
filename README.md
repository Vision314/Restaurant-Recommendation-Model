## Set up

All necessary packages can be found in `requirements.txt`. To install necessary packages run `pip install -r requirements.txt` in the terminal.

## Download Data

1. Navigate to [dataset](https://www.kaggle.com/datasets/mrmorj/restaurant-recommendation-challenge) on kaggle and download zip file.
2. Create folder in project named `data` and move files there.

_Note: All preprocessing data is saved to `data` folder to avoid git pushing issues._

## Preprocess Data

You will need to preprocess the data to train the model.
Run the following notebooks to obtain the datasets:

- antoski/preprocessing.ipynb (lg_train_full)
- milad_analysis.ipynb (sm_train_full)

You must process datasets before adding new features. To obtain new features run notebook:

- antoski/feature_eng.ipynb

## Initial Model Evaluations

- Kernel Approximation: `Kernal_Model.ipynb`
- SGD Classifier: `training_SGD.ipynb`
- KNeighborsClassifier: `Milad_Training.ipynb`
- HistGradBoostingClassifier: `hist_grad.ipynb`

## Final Models Evaluation

- `final_evaluations.ipynb`
