# Web Scraping
S&amp;P 100 Wiki and 10-K SEC EDGARS forms of Apple and Intel
## Introduction

This notebook contains the python code to complete a coding assignment given by *Prof. John Gallemore*. The assignment mainly testes out the coding skill of the candidate with regard to web scrapping.

**Task 1: Description**\
In this python package *requests* has been used to retrieve a table of S&P 100 companies from their wikipedia page. After retreiving the table, the company name columns is fuzzy matched with set of company names from from local gvkeys.csv file by using python *fuzzywuzzy* package.

**Task 2:Description**\
In this task, 10-K Forms of Intel and Apple for the fiscal years of 2014 to 2018 have been retrieved from SEC EDGAR website. The the next step, Risk Section portion of the 10-K form is analyzed to get the following information

1. The number of words in *Risk Section*
2. The number of times the word "competition" repeats in the *Risk Section*.
3. Exports the text of *Risk Section* to txt file
4. Python package *nltk* is used to remove all the stopwords
5. Notes occurence of the word *patents* and its variation such as patenting, patents, etc. It notes each repetition as word preceding, occurence found and word following.

