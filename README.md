# Smartness_WordCloud
Keyword Mining from Definitions Related to Smartness from Scholarly Articles 

This github page contains both dataset (demo.xlsx) and Juypter notebook script that helps prepare wordclouds
of keywords corresponding to smartness from scholarly literature across multiple topics/domains. 

This page is an accompaniment to our review article titled "Conceptualizing Smartness of Cyber-Physical Systems"

Dataset has two columns : (1) Definitions and (2) Domains
There are 17 sub-domains/topics within e.g. city, building, governance, tourism, etc.  
Detailed methodology of collecting this dataset is described in our research article. 

Goal: To automatically mine keywords that represent these topics and produce wordcloud for each topics

Note: 
1. For the purpose of visualization we broadly categorized the dataset into 5 topics namely : city, built-envir, tourism, governance and others. 
2. Built-envir is composed of topics related to buildings and learning environment such as schools, universities, campus etc. 
3. All other topics in the demo.xlsx such as technology, solutions, port, growth, work, regulation, health etc. that have fewer mentions in the literature are grouped under "others". 

Disclaimer: Python Script in Juypter notebook is not developed by me from scratch, rather compiled from open-source material for the purpose of this analysis. The script is commented and made self-readable
