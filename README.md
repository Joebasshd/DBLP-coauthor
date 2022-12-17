# DBLP-coauthor

This notebook is intended to suggest a method to mine a set of coauthor relationships from the mammoth DBLP dataset which can be found on https://dblp.uni-trier.de/xml/

The aim is to answer the question 'Which authors collaborate with each other the most?'

I did not use the original dataset, as I couldn't successfully parse the xml file to user-friendly json or csv. So I used a chunk of the dataset from https://data.world/pulkit-jain/dblp-acm/workspace/file?filename=DBLP2.csv
I used Association Rule for Data Mining and the algorithm used is Apriori algorithm.
