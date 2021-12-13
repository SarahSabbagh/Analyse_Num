# Tp3 Intégration Numérique
- [Introduction](#Introduction)
- [Méthode :](#Méthode) <br/>
-[réctangles ](#réctangles ) <br/>
-[point_milieu](#point_milieu) <br/>
-[trapèzes](#trapèzes)<br/>
-[Simpson ](#Simpson)
## Introduction :
Supposons qu'on veuille intégrer une fonction f(x) sur un intervalle [a,b]. Puisque
l'intégrale est la limite de sommes de Riemann, l'idée la plus évidente pour approximer
numériquement le résultat qu'on cherche est de calculer des sommes de Riemann en
espérant qu'elles s'approcheront de manière désirée de la réponse exacte à condition de
prendre les sous-intervalles suffisamment petits.
Découpons donc l'intervalle [a, b] en n sous-intervalles [x<sub>i-1</sub>,x<sub>i</sub>] de largeur : <br/>
<img src="https://render.githubusercontent.com/render/math?math=d(x)=\displaystyle\frac{(b-a)}{n}">
## Méthode :
#### -réctangles :
Le principe de cette technique est illustré dans la figure (3.1)
L’expression de l’intégrale devient :<br/>
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle I=\frac{h}{2}\sum_{i=1}^{n} f(x_{i%2B1} + x_i)f(x_i)">
On considère le point milieu de chaque sous intervalle pour augmenter la précision.
L’expression de l’intégrale devient dans ce cas :
<img src="https://render.githubusercontent.com/render/math?math=\displaystyle I=\frac{h}{2}\sum_{i=1}^{n} f(\frac{x_{i%2B1} + x_i}{x_i})">

#### -point_milieu :
#### -trapèzes :
#### -Simpson :
