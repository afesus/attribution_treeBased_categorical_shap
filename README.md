# attribution_treeBased_categorical_shap
Download attribution_project.zip, and unzip it. This is only an empty folder structure, containing no data.
Place it in a chosen location on your computer. 
In the subfolder 'data' place your dataset in a form of a pickle file data.pkl, containing:

a dataframe 'data', with all categorical explanation variables, 
a numerical outcome variable, an a variable 'm_var', 
stating how on how many single datapoints each row is based.
All categorical variables (columns) should be of type category.

No further setup needed for the folder structure and the input.

Run the Python Notebooks in sequence based on the number their name starts with. 

In each of the notebooks the cells at the beginning, up to the first empty cells can be adjusted, based on the path of the project folder and the structure of the data/experiment.
