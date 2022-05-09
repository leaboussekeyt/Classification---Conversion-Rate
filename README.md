# Classification---Conversion-Rate
Supervised Learning Project to predict if a user will subscribe to the newsletter

## Objective 
Achieve the highest F1 score on the test dataset (the score being calculated by the teacher who has access to the target of the test dataset)

## Technology Used 

 ### From Scikit-Learn
<ul> Logistic Regression </ul>
<ul> Decision Tree & Random Forests</ul>
<ul> Boosting algorithms (AdaBoost, XGBoost) </ul>
<ul> Voting algorithms </ul>
<ul> Gaussian Naive Bayes</ul>
<ul> Grid Search with cross-validation</ul>
<ul> PCA </ul>

### Data visualization

<ul> Plotly </ul>
<ul> Seaborn</ul>

## Dataset
The dataset was provided by Jedha's bootcamp. It is also included in the folder 'Data'. It consists of both a test and train dataset - the former having no labels and used only to submit predictions for the challenge. 

For each individual, we have several informations on them (including their age, country, the number of pages they visited, etc), and whether they have subscribed or not (our target, in the column 'converted')


## Prerequisites
### Dependencies
The source code is written in Python 3

The python packages can be installed with pip : pip3 install -R requirements.txt



If using Jupyter notebook, plotly renderer needs to be changed in the code. Here, the renderer provided works on VSCode. 

## Usage

train.ipynb -  Project file with the EDA, all of the models tested with their F1 score. Output the best model saved down as 'final_model.sav' along with .csv file with the predictions.


