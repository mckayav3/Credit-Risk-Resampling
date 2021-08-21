# Module_12_Challenge: Credit Risk Resampling



This application uses resampling to create a model that can determine the creditworthiness of borrowers.

---

## Technologies


This was run on a pc using Windows 10

This project leverages python 3.8.8 with the following packages:


* [pandas](https://pandas.pydata.org/docs) - For manipulating the DataFrame.

* [Jupyter Lab](https://jupyterlab.readthedocs.io.en/stable) - For code and visualizations.

* [numpy](https://numpy.org/install/) - For scientific computing with python.

* [pathlib](https://docs.python.org/3/library/pathlib.html) - For location through the directory and file path.

* [balance_accuracy_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.balanced_accuracy_score.html) - For computing the balanced accuracy.

* [confusion_matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html) - For computing the confusion matrix to evaluate the accuracy of a classification.

* [classification_report_imbalanced](http://glemaitre.github.io/imbalanced-learn/generated/imblearn.metrics.classification_report_imbalanced.html) - For building a classification report based on metrics used with an imbalanced dataset.

---

## Installation Guide

In gitbash after you have activated your dev environment, install the following:

*Jupyter Lab

    `pip install jupyter lab`
    
![install juypter lab](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/install_jupyterlab.JPG)

*Imbalance-learn

    `conda install -c conda-forge imbalanced-learn`
    
![install imbalanced-learn](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/install_imbalanced_learn.JPG)

![list imbalanced-learn](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/list_imbalanced.JPG)

*Pydotplus

    `conda install -c conda-forge pydotplus`
    
![install pydotplus](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/install_pydotplus.JPG)

![list pydotplus](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/list_pydotplus.JPG)

---

## Examples

The images below show the different types of charts and graphs that should be a result from running the code in the Credit Risk Resampling application. By reviewing the charts and graphs below will allow us to choose which model best fits our needs to determine a borrower’s creditworthiness.


![lending dataframe](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/lending_df.JPG)


![X and y variables](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/y_X_variables.JPG)

![y value counts](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/y_value_count.JPG)

![model test predictions](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/model_test_predict.JPG)

![y resampled value counts](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/y_resampled_value_count.JPG)

![model resampled predictoins](https://github.com/mckayav3/Module_12_Challenge/blob/main/Credit%20Risk%20Classification/images/model_resampled_predict.JPG)


---

## Contributors

Andrew McKay

Email: andrew.v.mckay@gmail.com

---