# Gitfolder_finalProject_XAI
Final_project_XAI_jesper_de_Hart

--how to run
    Recommended: run on google collab for gpu usage for training BERT model
    change runtime type to gpu if possible


-- for the data::

put data from kaggle page in project folder to run. or if on collab upload the csv file

the csv file of data is too large to commit to github, link to kaggle page can be found here:
https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification/data



Required packages and compatible versions: 


    alibi==0.9.6 
    numba==0.60.0 llvmlite==0.43.0 --user 
    pandas==2.2.2
    tqdm==4.67.1
    scikit-learn==1.6.1
    torch (automatic) if not 2.6.0
    tensorflow==2.18.0
    alibi==0.9.6 

    numpy(gets installed automatically)


install intstructions:
    kernel/session has to be reset multiple times after running installs since some of the package require kernel restart.
    install and restart kernel untill all imports work.