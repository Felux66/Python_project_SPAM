# Python_project_SPAM

#Content of this repository 

 - A PowerPoint explaining the ins and outs of the problem, my thoughts on the asked question, the different variables you created, how the problem fits in the context of the study.
 - A code in python (Jupyter Notebook format):
   - Data-visualization (use matplotlib, seaborn, bokeh ...): show the link between the variables and the target.
   - Modeling: use the scikit-learn library to try several algorithms, change the hyper parameters, do a grid search, compare the results of your models using graphics.
 - Transformation of the model into an API of your choice (flask).

# Dataset and Project

  The problem here is to classify email whether they are spam or not. We base our analysis on frequence of different features such as the frequence of words or the frequence of character. We are going to use scikit-learn and differents models provided by this module. We are going to compare this different models in order to find out the one which fits the best our dataset.
  
  # API
  
  We used the flask api to transform our model into an API. We you launch our appli, you have to inform the frequence of different features we ask and the api answer you if your email is a spam or not.
