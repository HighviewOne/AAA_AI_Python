# AAA AI & Python Course

Coursework and project for the AAA AI with Data Science / Python course.

## Project: Wine Quality Prediction

An end-to-end machine learning project that predicts red wine quality using physicochemical properties.

- **Models:** Random Forest Regressor (MAE: 0.52) and Classifier (F1: 0.68, ROC AUC: 0.75)
- **App:** Interactive Streamlit interface for real-time predictions
- **Dataset:** UCI Wine Quality Dataset (1,599 red wine samples, 11 features)

See [project/](project/) for the full notebook, trained models, and Streamlit app.

## Lectures

| Notebook | Topic |
|----------|-------|
| [01-python-basics](lectures/01-python-basics.ipynb) | Python fundamentals, Pandas, data cleaning |
| [02-predictive-models](lectures/02-predictive-models.ipynb) | Regression models with scikit-learn |
| [03-dogs-vs-cats-cnn](lectures/03-dogs-vs-cats-cnn.ipynb) | CNN image classification with TensorFlow |

## Repo Structure

```
├── lectures/                          # Lecture notebooks and data
│   ├── 01-python-basics.ipynb
│   ├── 02-predictive-models.ipynb
│   ├── 03-dogs-vs-cats-cnn.ipynb
│   └── *.csv                          # Data files for exercises
├── project/                           # Wine Quality Prediction project
│   ├── wine_quality_prediction.ipynb  # Full EDA and modeling notebook
│   ├── wine_quality_streamlit.py      # Interactive Streamlit app
│   ├── wine.csv                       # Dataset
│   ├── *.pkl                          # Trained models and scaler
│   └── assignment.pdf                 # Project requirements
```

## Author

Michael - [@HighviewOne](https://github.com/HighviewOne)
