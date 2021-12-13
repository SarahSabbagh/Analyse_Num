f une fonction continue et strictement monotone . Soit a < b on suppose que f(a)*f(b)<0 donc d’après le théorème des valeurs intermédiaire f admit une unique racine ⍺ ∈ [a ;b]
L’objectif de ce TP : est de rechercher une valeur approchée de ⍺ avec une erreur de l’ordre ε. On se dispose de 3 méthodes :

* [La méthode de la dichotomie](#dichotomie) 
* [La méthode de point fixe](#fixe) 
* [La méthode de Newton](#Newton) 
## La méthode de la dichotomie : 
 Soit f :[a<sub>0</sub>,b<sub>0</sub>]→ R continue et telle que f(a<sub>0</sub>) f(b<sub>0</sub>)≤ 0  
 > Pour n = 0, 1, 2, ..., N, faire <br/>
 <img src="https://render.githubusercontent.com/render/math?math=m=\frac{(a_n%2Bb_n)}{2}"> <br/>
 Si f(a<sub>n</sub>) f(m) ≤ 0, a<sub>n+1</sub> = a<sub>n</sub>, b<sub>n+1</sub>= m <br/>
 Sinon a<sub>n+1</sub>= m, b<sub>n+1</sub>= b<sub>n</sub>. <br/>
On a :<img src="https://render.githubusercontent.com/render/math?math=a_n_%2B_1-b_n_%2B_1=\frac{1}{2^n}(a_n-b_n)">, <br/>
soit par récurrence <img src="https://render.githubusercontent.com/render/math?math=a_n-b_n=\frac{1}{2^n}(a_0-b_0)"><br/>
Il en résulte que cette méthode est toujours convergente puisque a<sub>n</sub> − b<sub>n</sub> tend vers 0 quand
n tend vers l'infini. On peut choisir le temps d'arrêt N pour que : <br/>
>  <img src="https://render.githubusercontent.com/render/math?math=\frac{1}{2^n}(a_0-b_0)"> < ε = précision choisie.
## La méthode de point fixe :
Soit, la droite d'équation :
Y = f(x<sub>n</sub>) + f(x<sub>n</sub>)(x − x<sub>n</sub>). <br/>
Son intersection avec l'axe des abscisses fournit une approximation de la solution x<sub>∞</sub>.<br/>
A nouveau, on renouvelle le procédé jusqu'à obtenir une approximation suffisante, d'où:<br/>
x<sub>0</sub> étant donné <br/>
Pour n = 0, 1, 2, ... <br/>
x<sub>n+1</sub> = x<sub>n</sub> −f(x<sub>n</sub>)/f′(x<sub>n</sub>).

## La méthode de Newton :
