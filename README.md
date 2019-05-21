# AutoML_AutoSklearn
Testing some Auto-ML libraries for fun

In these notebooks, I am testing the [Auto-Sklearn](https://www.automl.org/automl/auto-sklearn/) auto-ML library, which is in turn based on scikit-learn. It uses Bayesian optimization and information from prior data sets to find the best possible model amongst the various classification models available in sklearn, and then output an ensemble prediction based on the best performing models. 

Examples studied so far: 
The Titanic data set from Kaggle: Can auto-sklearn get a competitive score on the leader board? 
So far auto-sklearn gives a competitive score, but not the best score possible. 

Note that these notebooks were run on MacOS, which isn't supported by auto-sklearn. To get it to run, I had to update several libraries manually, and to add gcc to my Anaconda installation. To figure out which libraries to update manually, I basically ran the pip install a first time and then debugged the error messages to find which libraries needed to be updated. 
