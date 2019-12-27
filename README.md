# tripletx
# Download Stanford CoreNLP :
https://stanfordnlp.github.io/CoreNLP/download.html

# Initialize CoreNLP Server :

java -mx4g -cp "*" edu.stanford.nlp.pipeline.StanfordCoreNLPServer -preload tokenize,ssplit,pos,lemma,ner,parse,depparse -status_port 9000 -port 9000 -timeout 15000 & 
