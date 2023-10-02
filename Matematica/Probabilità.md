Se lanciamo un dado, quali sono le probabilità che esca un numero pari?
Per saperlo calcoliamo il rapporto tra **i casi favorevoli**, quindi i casi che noi cerchiamo, e **i casi possibili**, quindi tutti i possibili risultati sono:
$$
\large
p(E) = \frac{f}{u}
$$
Dove $p(E)$ è la probabilità dell'evento $E$, $f$ sono i *casi favorevoli* e $u$ sono i *casi possibili*.

Quindi, con il dado i *casi favorevoli* sono 3 (2, 4, 6) e i *casi possibili* sono 6 (1, 2, 3, 4, 5, 6):
$$
\large
\frac{f}{u} =
\frac{3}{6} =
\frac{1}{2}
$$
$p(E)$ risulterà sempre un valore tra 0 e 1, dove:
- Se è 0 è *impossibile*
- Se è 1 è *certo*
  
> Moltiplicando $p(E)$ per 100 si ottiene la probabilità in percentuale.

Per avere la probabilità che l'evento **non accada** si sottrae la probabilità a $1$:
$$
\large
p(\overline{E}) = 1-p(E)
$$
Dove $p(\overline{E})$ è l'**evento contrario**.

### Eventi compatibili e incompatibili
Due eventi sono *compatibili* quando possono verificarsi insieme, *incompatibili* quando ciò è impossibile.
Usando il dado come esempio, l'evento $E$ che il lancio risulti in un 2 e l'evento $F$ che il lancio risulti in un numero dispari sono **incompatibili**.

## Eventi indipendenti e dipendenti
Un evento indipendente è tale perché il **suo verificarsi non è condizionato o motivato da altri eventi**.
Un esempio è il lancio del dado sopracitato. La probabilità che esca un numero pari non è influenzato dai lanci precedenti o successivi.
Un evento dipendente invece, appunto, dipende dal verificarsi o meno di altri eventi.

### Evento intersezione $\bigcap$
Gli la probabilità che due eventi indipendenti $E$ ed $F$ accadano insieme
(*Evento intersezione* $E \cap F$) è data dal prodotto delle due probabilità:
$$
\large
p(E \cap F) = p(E) \cdot p(F)
$$
Invece, se sono dipendenti, il prodotto è tra *eventi condizionati* e *evento condizionante*:
$$
\large
p(E \cap F) = p(E/F)\cdot p(G)
$$
Dove $G$ è l'**evento condizionante**.


### Evento unione $\bigcup$
La probabilità che si verifichi uno dei due eventi $E$ ed $F$ *incompatibili* banalmente equivale a
$$
\large
p(E \cup F) = p(E) + p(F)
$$
Se sono *compatibili*, la probabilità è
$$
\large
p(E \cup F) = p(E) + p(F) - p(E \cap F)
$$
Questo perché, se gli eventi sono compatibili, l'evento verrebbe contato due volte. Spiegato con gli insiemi:
$$
\large
\begin{align*}
E = \{1, 2, 3\}  \\
F = \{2, 4, 5\} \\
E \cup F = \{1, \boldsymbol{2}, 3, \boldsymbol{2}, 4, 5\} \\
E \cap F = \{2\}\\
\end{align*}
$$
Il $2$ viene contato due volte. Quindi, sottraendo l'intersezione si ha l'insieme dove ogni elemento appare una volta.

## Teorema di Bernoulli
Si applica quando ci sono prove ripetute (Come un lancio ripetuto del dado o di una moneta).
Serve a individuare *due eventi complementari*, ovvero due eventi che danno l'**evento certo**. Quindi le loro possibilità sono, appunto, complementari.

Per esempio, se prendiamo la possibilità che dal lancio di un dado esca un numero pari, questa è $\large\frac{1}{2}$. La probabilità che esca, invece, un numero dispari è anch'essa $\large\frac{1}{2}$. Insieme sono complementari, quindi, matematicamente, lanciando due volte un dado avverranno sempre entrambi.

La **formula di Bernoulli** dice:
$$
\large
p(E) = \binom{n}{k} \cdot p^{k} \cdot q^{n-k}
$$
Dove $n$ è il numero di *prove ripetute*, $k$ è il numero di volte in cui *$E$ si verifica*, $p$ è la probabilità che $E$ si verifichi e $q$ è la probabilità che si verifichi *l'evento complementare*.

Per esempio, se lanciando 8 volte una moneta io voglio che esca testa 3 volte, l'evento $E$ che si verifichi ciò che voglio è:
$$\large
p(E) = \binom{8}{3} \cdot (\frac{1}{2})^{3} \cdot (\frac{1}{2})^{5}
$$
Dove $p$ e $q$ sono $\large\frac{1}{2}$ perché queste sono le possibilità che esca testa e che esca croce, $n$ è 8 perché sono 8 i lanci della moneta e $k$ è 3 perché voglio che testa esca 3 volte.

> Il teorema non vale se le probabilità cambiano ad ogni prova (Come pescare da un mazzo di carte, senza reinserire la carta pescata)
