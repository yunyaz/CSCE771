Dataset:
The dataset is available on https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge
On the above website it shows that the current version of dataset is 6 GB. However, it is a archive zip folder. The actual size of the dataset is 27 GB. The download time is less than 10 minutes.
If you would like to execute the program, rename the downloaded dataset as 'data' and put it along with the program named 'CSCE771_code.ipynb' in the same root folder.
The Dataset contains around 200,000 scholarly articles. Since my laptap can not handle this big dataset for later topic modeling step. I only used 50,000 articles (the first 25% of the dataset)
Loading this amount of dataset would take around 30 minutes.
Data processing would take around 25 minutes.
Vectorization would take around 20 minutes.
Topic modeling would take around 20 minutes.


Input:
Widgets have been created to type in the search content, which can be keywords, phrases, sentences, or paragraphs.

Two queries that are included in the report:
Implementation of diagnostics and products to improve clinical processes
What has been published about medical care?

More sample queries:
What antiviral drugs have been tested against coronaviruses?
What drugs are effective and what are ineffective?
There are many types of vaccines (inactivated vaccines, modified live virus vaccines, subunit vaccines, DNA vaccines, mRNA vaccines, genetically engineered vaccines, etc.). What types of vaccines have been developed and evaluated against different coronaviruses?
What has been the conclusion on the effectiveness of the vaccine candidates?
What are the origins of coronaviruses? How have the coronaviruses been transmitted (cross-species or not)?


Output:
The documents that are related to the search content will be returned. They will be ranked by the score of similarity. If url is provided in the dataset, click the document will direct to the full document. The number of returned documents is limited to 10, but it can be changed in the program.
The full screenshots for the output of the above sample queries will be included in the current Github folder. 
