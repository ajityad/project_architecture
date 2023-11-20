## THIS FILE HELPS YOU TO PROVIDE DETAILS ABOUT STEPWISE ENVIRONMENT CREATION OF THE PROJECT
### STEP 1 : To create environment for the project
```
                conda create -p env python=3.8 
```
### STEP 2 : To create requirements.txt file
```
 create requirements.txt file and write down the names of all required liabraries and packages in the file
 To install the packages write the below code in terminal
                pip install -r requirements.txt
 
```
### STEP 3 : To create .gitignore file
```
If you want to transfer your project through github and want to restrict some files for transferring through github
that files you can mention in the .gitignore file.
example: we want to restrict to transfer environment of the project via github, then simply mention the name of the environment folder in .gitignore file
```

### STEP 4 : To create setup.py file
```
If you want to convert your project into packages, this will done with the help of setup.py file
```

### STEP 5 : Create src and notebook folder 
```
create src folder which is entry point of the programme 
In source folder create logger.py,exception.py,utils.py files
Also, create notebook folder for EDA and FE notebooks.
```
### STEP 5 : Create components and pipeline  folder in src folder
```
create srccomponents and pipeline folder src folder 
In component folder create data_ingestion.py, data_transformation.py,model_trainer.py
In pipeline folder create prediction_pipeline.py, training_pipeline.py,model_trainer.py
```