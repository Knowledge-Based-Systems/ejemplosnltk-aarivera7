# EjemplosNLTK
## Ejemplo 1

###### import nltk<br>
###### import re<br>
  
<p># Se descarga una base de datos de texto en español</p>

###### nltk.download('cess_esp')<br>
###### corpus = nltk.corpus.cess_esp.sents()<br>
###### print(corpus)<br>

###### flatten = [w for l in corpus for w in l] 
###### print(flatten[:20])
