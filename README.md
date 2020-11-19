# recomandation-system-python


Recomandation based on Similaritecosinus fonction <br>

<h2> libraries</h2> <br>
import mysql.conne <br>
import nltk <br>
import numpy as np <br>
from scipy import spatial <br>
 

<h3>Similaritecosinus :</h3>Calcule du similarité  <br>

<h3>EnglishStemmer :<h3> Garder les mots unique (nom = adjective = meme sens !! ) <br>

<h3>stopwords :</h3> [".",";","!",",",":"] : enlever la  ponctuation <br>

<h3>mysql connector :</h3> To connect to data base  <br>

Nb : ici la recommandation est basé sur le contenue , j'ai choisi l'attribut description [6] <br>

<h3>Resultat final :<h3> pour chaque livre Book les tops livre similaire selon son contenu  <br>
                 une base de donneé contient {idbook}, '{idfirst}', '{idsecond}', '{idthird}'  <br>
                 
<h2>outil :<//h2> <br>
Spyder(Anaconda 3) , Xampp

