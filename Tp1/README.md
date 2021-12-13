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
On a : a<sub>n+1</sub> − b<sub>n+1</sub> =<img src="https://render.githubusercontent.com/render/math?math=m=\frac{1}{2}">(a<sub>n</sub> − b<sub>n</sub>), 
soit par récurrence a<sub>n</sub> − b<sub>n</sub> =1 <frac>2<sup>n</sup></frac>(a<sub>0</sub> − b<sub>0</sub>)
Il en résulte que cette méthode est toujours convergente puisque a<sub>n</sub> − b<sub>n</sub> tend vers 0 quand
n tend vers l'infini. On peut choisir le temps d'arrêt N pour que : <br/>
> 1 <frac>2<sup>n</sup></frac> (a<sub>0</sub> − b<sub>0</sub>) < ε = précision choisie.
## La méthode de point fixe :
## La méthode de Newton :
