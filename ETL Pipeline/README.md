The Python Notebook in this folder demonstrates an ETL Pipeline.  

**Source:**  
Source data for this pipeline comes from of a .txt file. Thus, in terms of the extract part of the pipeline, .txt from our local system is used.

**Transform:**  
PySpark is used to carry out the transformations on the data extracted from the .txt file.

**Load:**  
The transformed data is loaded in the PostgreSQL instance created in the AWS Cloud.
