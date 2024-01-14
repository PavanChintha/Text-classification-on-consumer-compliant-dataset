Kaiburr Assesment - Task 5 (Data Science)
Name : Chintha Pavan
Roll No : CB.EN.U4CSE20312

# Text-classification-on-consumer-compliant-dataset

Data Source:

1. https://catalog.data.gov/dataset/consumer-complaint-database


The data consists of 18 columns, of which we will focus on 2:

1. The text of a consumer complaint
1. The product against which this complain is registered.

There are **18** kinds of products of a financial nature, such as debt collection or consumer loans, in the full dataset.

Close to one million rows of data are available (903983).
We will curtail this to 1000 rows for the sake of faster compute.

The length of the text per complaint is variable, which is a common situation in NLP tasks.

>
>**TASK:** We will create a multi-class classification model and try to predict which product a given complaint refers to
>

>
>**GENERAL APPROACH**
>
> 1. Convert the complaint text into its numerical representation using TF-IDF scores.
> 1. Convert the product classes into numbers using label encoding.
> 1. Create a conventional machine learning model to complete the task. Since this is an introduction to NLP and we have chosen to work with truncated data, deep learning methods are not discussed.


If you are working on your local machine on a jupyter environment,
 -    You will need to download the data - links shared above
 -    Please create a virtual environment and make sure it is active.
      This is a standard 'best-practice'. Run the next two lines to ensure the correct environment is activated.


      
import os


os.environ['CONDA_DEFAULT_ENV']
