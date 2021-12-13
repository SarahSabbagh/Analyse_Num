f une fonction continue et strictement monotone . Soit a < b on suppose que f(a)*f(b)<0 donc d’après le théorème des valeurs intermédiaire f admit une unique racine ⍺ ∈ [a ;b]
L’objectif de ce TP : est de rechercher une valeur approchée de ⍺ avec une erreur de l’ordre ε. On se dispose de 3 méthodes :

* [La méthode de la dichotomie](#dichotomie) 
* [La méthode de point fixe](#fixe) 
* [La méthode de Newton](#Newton) 
## La méthode de la dichotomie : 
 Soit f :[a<sub>0</sub>,b<sub>0</sub>]→ R continue et telle que f(a<sub>0</sub>) f(b<sub>0</sub>)≤ 0  
 > Pour n = 0, 1, 2, ..., N, faire <br/>
 <img src="https://render.githubusercontent.com/render/math?math=m=\frac{(a_n \+ \b_n)}{2}"> <br/>
 Si f(a<sub>n</sub>) f(m) ≤ 0, a<sub>n+1</sub> = a<sub>n</sub>, b<sub>n+1</sub>= m <br/>
 Sinon a<sub>n+1</sub>= m, b<sub>n+1</sub>= b<sub>n</sub>.
## La méthode de point fixe :
## La méthode de Newton :
