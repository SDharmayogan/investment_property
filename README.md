# investment_property
Software Dependency:
 1. Python 3
 2. Jupyter notebook
 3. metapy
 4. pytoml
 5. numpy
 
 Tool Overview
 The program compares retreival and classification techniques to identify potential investment properties
 
 Classification
 The training data for classification is 30 files in the property folder. Investmetn properties are in the investment sub folder and ready to move-in properties are in the movein folder. The setup is managed using a toml files  - config.toml, file.toml, line.toml and gz.toml. The background model (stopwords) are provided in the stopwords.txt file
  The file property-full-corpus.txt provides a list of all training data
 
 Retreival
 The search terms are provided in investment-queries.txt
 The relevent files are provided in investment-qrels.txt
 The retreival files are the same as that used to train the classifiers above. 
 
