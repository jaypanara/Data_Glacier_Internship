# Week 6: File ingestion and schema validation

## Tasks:
1. Take any csv/text file of 2+ GB of your choice. --- (You can do this assignment on Google colab)

2. Read the file ( Present approach of reading the file )

3. Try different methods of file reading eg: Dask, Modin, Ray, pandas and present your findings in term of computational efficiency

4. Perform basic validation on data columns : eg: remove special character , white spaces from the col name

5. As you already know the schema hence create a YAML file and write the column name in YAML file. --define separator of read and write file, column name in YAML

6. Validate number of columns and column name of ingested file with YAML.

7. Write the file in pipe separated text file (|) in gz format.

8. Create a summary of the file:
   Total number of rows,
   Total number of columns
   File size
   
   
   Dataset:https://www.kaggle.com/datasets/hm-land-registry/uk-housing-prices-paid
