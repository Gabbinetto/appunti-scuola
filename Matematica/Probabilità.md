Se prendiamo un dado, quali sono le probabilità che esca un numero pari?
Per saperlo calcoliamo il rapporto tra **i casi favorevoli**, quindi i casi che noi cerchiamo, e **i casi possibili**, quindi tutti i possibili risultati sono:
$$
p(E) = \frac{f}{u}
$$
Dove $p(E)$ è la probabilità dell'evento $E$, $f$ sono i *casi favorevoli* e $u$ sono i *casi possibili*.

Quindi, con il dado i *casi favorevoli* sono 3 (2, 4, 6) e i *casi possibili* sono 6 (1, 2, 3, 4, 5, 6):
$$
\frac{f}{u} =
\frac{3}{6} =
\frac{1}{2}
$$
$p(E)$ risulterà sempre un valore tra 0 e 1, dove:
- Se è 0 è *impossibile*
- Se è 1 è *certo*
  
> Moltiplicando $p(E)$ per 100 si ha la probabilità in percentuale.

Per avere la probabilità che l'evento **non accada** si sottrae la probabilità a $1$:
$$
p(\overline{E}) = 1-p(E)
$$
Dove $p(\overline{E})$ è l'**evento contrario**.


## Eventi indipendenti
Un evento indipendente è tale perché il **suo verificarsi non è condizionato o motivato da altri eventi**.
Un esempio è il lancio del dado sopracitato. La probabilità che esca un numero pari non è influenzato dai lanci precedenti o successivi.

Gli la probabilità che due eventi indipendenti $E$ ed $F$ accadano insieme
(*Evento intersezione* $E \cap F$) è data dal prodotto delle due probabilità:
$$
\mathbb{P}(E \cap F) = \mathbb{P}(E) \cdot \mathbb{P}(F)
$$ 
