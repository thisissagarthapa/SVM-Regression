# Support Vector Machine for Student Performance Prediction

## Overview

This project implements a Support Vector Machine (SVM) regression model to predict the number of students passing based on the number of study hours. The dataset contains two columns: `study_hours` and `students_passing`. The model is trained and evaluated using a linear kernel, achieving high accuracy on both training and test datasets.

## Dataset

The dataset used in this project is `school_data.csv`, which includes the following columns:

- `study_hours`: Number of hours studied by the students.
- `students_passing`: Number of students passing based on study hours.

### Sample Data

| study_hours | students_passing |
|-------------|------------------|
| 1           | 15               |
| 2           | 30               |
| 3           | 45               |
| 4           | 62               |
| 5           | 77               |

## Dependencies

The following libraries are required to run this project:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `mlxtend`
- `scikit-learn`

You can install the dependencies using pip:

```bash
pip install numpy pandas matplotlib seaborn mlxtend scikit-learn
