## The snail

Un escargot doit parcourir 100 mètres sur une route.

Il parcourt un mètre chaque jour.

Ca ne lui prendra que quelques mois.

##--##

## sauf que

Un type sadique tire chaque nuit sur la route.

(élastique)

Il la rallonge de 100 mètre chaque nuit.

Avec l'escargot dessus.

##--##

## du coup

Au second matin l'escargot a parcouru 2 mètres sur 200 au lieu de 1 mètre sur 100.

Au troisième matin l'escargot a parcouru 4,5 mètres sur 300 au lieu de 3 mètre sur 200.

Au dixième matin il aura parcouru 28 mètres sur 1000 (à une vache près).

##--##

## mais alors

Arrivera-t-il jamais au bout ? Quizz !

<div class="fragment">
<ul>
<li class="fragment"> Oui, la semaine d'après</li>
<li class="fragment"> Oui, dans 7 ans, 11 mois et 13 jours</li>
<li class="fragment"> Oui, en fusion avec le bout de la route au moment du big crunch</li>
<li class="fragment"> Oui, s'il vit 41350 milliards de milliards de milliards de milliards d'années</li>
<li class="fragment"> Non, il n'y aura plus beaucoup de protons à ce moment-là, donc pas de route.</li>
<li class="fragment"> Non, juste non</li>
</div>

##--##

### J'avais dit pas de démo mais…

| jour | % parcouru                          |
| ---- | ----------------------------------- |
| 0    | 0/100                               |
| 1    | 1/100 : 1%                          |
| 2    | 1/100+ 1/200 : 1+1/2 %              |
| 3    | 1/100 + 1/200 + 1/300 : 1+1/2+1/3 % |
| …    |                                     |
| n    | sum(i=1..n, 1/i) / 100              |

<!-- .element style="font-size: 70%"-->

gamma = lim(sum(i=1..n, 1/i) - ln(n)) = ❤️

<!-- .element style="font-size: 70%"-->

on veut le % parcouru > 100 : (gamma + ln(n))/100 > 1

<!-- .element style="font-size: 70%"-->

c-à-d n > exp(100 - gamma) ~= e(100)

<!-- .element style="font-size: 70%"-->
