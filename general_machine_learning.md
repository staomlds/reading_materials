
## Books

*Understanding by Machine Learning: From Theory to Algorithms* by Shai Shalev-Shwarz and Shai Ben-David, 2014

chapter reviews. 
### Chapter 2. 
Notations: 
* $S=(X, y)$ denotes training data.
* hypothesis = classifier = predictor 
* $L_{D,f}h$ measures true error of $h$. $D$ is distribution of $X$. $f$ labeling function. ERM $L_S(h)$.

Contents:
* Finite hypothesis class $H$
* The Realizability Assumption (exists $h*$ so that $L_S(h^{*})=0$)
### Chapter 3 
Contents:
* Probably approximately correct (PAC) for a hypothesis
* Agnostic PAC with $L_{D}(h')$ for all $h'$ in $H$.
* Sample complexity for finite class is $\frac{\log{|H|/\delta}}{\epsilon}$
* The PAC learnability of a hypothesis class depends on VC dimension (not just finiteness).


