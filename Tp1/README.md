f une fonction continue et strictement monotone . Soit a < b on suppose que f(a)*f(b)<0 donc d’après le théorème des valeurs intermédiaire f admit une unique racine ⍺ ∈ [a ;b]
L’objectif de ce TP : est de rechercher une valeur approchée de ⍺ avec une erreur de l’ordre ε. On se dispose de 3 méthodes :

* La méthode de la dichotomie 
 Soit f : [a0, b0] → R continue et telle que f (a0) f (b0) ≤ 0.
      | Pour n = 0, 1, 2, ..., N, faire
      | m :=(an+bn)/2
      | Si f (an) f (m) ≤ 0, an+1 := an, bn+1 := m
      | Sinon an+1 := m, bn+1 := bn.

On a : an+1 − bn+1 =1/2(an − bn), soit par récurrence an − bn =1/$n^2$ (a0 − b0). Il en résulte que cette méthode est toujours convergente puisque an − bn tend vers 0 quand n tend vers l'infini. On peut choisir le temps d'arrêt N pour que :
1/2N (a0 − b0) < ε = précision choisie.
* La méthode de point fixe
* La méthode de Newton
