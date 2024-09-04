Text mining project README


The main folder of the project ‘TM&S_Baghrous_Iarocci_Ferrari’ contains the report and the original datasets (‘wikihowAll.csv’ and ‘wikihowSep.csv’), as well as 3 sub-folders: ‘Preprocessing’, ‘Text Summarization’ and ‘Topic Modeling’. Each sub-folder contains the respective task’s code (as .ipynb files) and results.


If one wants to replicate the project’s results from scratch, ‘Preprocessing.ipynb’ should be run first, then ‘Summarization.ipynb’ and ‘Topic Modeling.ipynb’ with no particular order. If one wants to replicate just the results of topic modeling or summarization, one does not need to run ‘Preprocessing.ipynb’ and can run instead ‘Summarization.ipynb’ and ‘Topic Modeling.ipynb’ directly.


In order to correctly set up the notebooks’ environment, it is necessary to mount drive and set the working directory to the main project folder ‘TM&S_Baghrous_Iarocci_Ferrari’. This can be done by changing the path specified in the os.chdir() that can be found at the beginning of each notebook after the libraries and packages installation and import.