<h1>Projet Orgue</h1>
<h2>Présentation</h2>

<div>
 <p>Nous avons comme devoir de réaliser un projet aux sein de notre apprentissage d'électroniciens en 3ème années.<br>
  Nous avons donc décidé de réaliser un orgue electronique. Il devra pouvoir jouer les notes de Do à Do en actionnant des interupteurs.</p>
</div>

<h2> </h2>

<p>Nous avons décidé d'utiliser un oscillateur "555" pour la création des différentes fréquences. Puis de modifier le signal carré de sortie en signal sinusoïdal. 
Et pour finir de l'apliquer à un haut parleur.</p>
<p>Voici l'entoèreté des fréquence que nous devons réaliser. (en [Hz]) </p>
<table>
 <tr>
  <th>DO</th>
  <th>RE</th>
  <th>MI</th>
  <th>FA</th>
  <th>SOL</th>
  <th>LA</th>
  <th>SI</th>
  <th>DO</th>
 </tr>
 <tr>
  <td>262</td>
  <td>294</td>
  <td>330</td>
  <td>349</td>
  <td>392</td>
  <td>440</td>
  <td>494</td>
  <td>523</td>
 </tr>
</table>

<h2>Schéma</h2>
<img src='https://raw.githubusercontent.com/Montandon-Varoda/Orgue/main/1_Documentation/shema1.PNG'/>

<h2>Formule</h2>

Ra = 10 KΩ </br>

C = 100 nF </br>

<img src='https://raw.githubusercontent.com/Montandon-Varoda/Orgue/main/1_Documentation/Tex2Img_1613136798.jpg'/>

<img src='https://raw.githubusercontent.com/Montandon-Varoda/Orgue/main/1_Documentation/Tex2Img_1613136442.jpg'/>

Voici la valeur théorique de Rb [Ω] en fonction de la fréquence f [Hz]

<table>
 <tr>
  <th>DO</th>
  <th>RE</th>
  <th>MI</th>
  <th>FA</th>
  <th>SOL</th>
  <th>LA</th>
  <th>SI</th>
  <th>DO</th>
 </tr>
 <tr>
  <td>262</td>
  <td>294</td>
  <td>330</td>
  <td>349</td>
  <td>392</td>
  <td>440</td>
  <td>494</td>
  <td>523</td>
</tr>
<tr>
  <td>22481</td>
  <td>19489</td>
  <td>16818</td>
  <td>15630</td>
  <td>13367</td>
  <td>11363</td>
  <td>9574</td>
  <td>8767</td>
 </tr>

</table>


<h2> </h2>
<p align="center"> <br> <a href="https://github.com/Montandon-Varoda/"><img src="https://img.shields.io/badge/My-GitHub-red.svg" alt="version"/></a> <i> Maxime Montandon </i></p>
<p align="center"> <br> <a href="https://github.com/Forestierr/"><img src="https://img.shields.io/badge/My-GitHub-red.svg" alt="version"/></a> <i> Robin Forestier </i></p>
