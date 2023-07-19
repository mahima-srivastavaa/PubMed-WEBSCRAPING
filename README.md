# PubMed-WEBSCRAPING
PubMed is online literature Database for biomedical literature from various scientific journals. It is a service provided by the National Library of Medicine (NLM) at the U.S. National Institutes of Health (NIH).

PubMed is a valuable resource for researchers, healthcare professionals, and anyone interested in exploring the latest developments in medical research. It allows users to search for and access a wide range of peer-reviewed publications, including research papers, clinical trials, and reviews, covering various areas of biomedicine, such as genetics, immunology, pharmacology, and many others.

## 📌Problem Statement
The problem at hand is to extract relevant articles on Alzheimer's disease from PubMed. Alzheimer's disease is a complex and debilitating neurodegenerative disease that affects millions of people worldwide. As research into Alzheimer's disease is a rapidly evolving field, it is essential to have access to up-to-date and accurate information.

the extracted information will have

name of the article

authors of the article

citation

pubmedID (a unique identifier alloted to every article on PubMed)

link to the article

## A break down of the code ⚒
Download web pages via requests library and convert it into a BeautifulSoup object
Use BeautifulSoup to parse information
Create functions to get the necessary tags and write information gathered to a csv



Scraped PubMed Articles on Alzheimer’s Disease using BeautifulSoup4 and Requests
Built functions like pubmed_url(), get_pubmed_url() , getting_info(), scrapping_pubmed(), get_csv(), Parser() -The
Scraped data has 2200 rows x 6 columns
link
