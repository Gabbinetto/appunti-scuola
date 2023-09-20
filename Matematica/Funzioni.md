Una funzione è **la relazione tra due insiemi** che associa un elemento del secondo ad ogni elemento del primo. Quando il legame è dettato da una formula matematica la funzione è **algebrica**.

Una funzione di due insiemi $A \rightarrow B$ si indica tramite:
$$
\large
y = f(x)
$$
L'insieme $A$ è il *dominio* ed è l'insieme di tutti i valori della variabile *indipendente* $\large x$.
L'insieme $B$ è il *codominio* ed è l'insieme di tutti i valori della variabile *dipendente* $\large y$, chiamata così perché il suo valore dipende dal valore della variabile indipendente.
$$
\large
\underbrace{D}_{\text{Dominio}} \rightarrow \underbrace{C_{D}}_{\text{Codominio}}
$$

Per esempio, prendendo una funzione esponenziale:
$$
\large
f: y = 2^x
$$
Il dominio è $\large\mathbb{R}$, perché la $\large x$ può assumere qualsiasi valore, mentre il codominio è $\large\mathbb{R}^+$ perché la $\large y$ assumerà sempre valore positivo. Quindi:
$$
\large
f: \mathbb{R} \rightarrow \mathbb{R}^+
$$

Una funzione può essere invertita, dove il dominio diventa il codominio e viceversa. Un esempio di funzione inversa è:
$$
\large
y = x + 3
\leftrightarrow
x = y - 3
$$

Se nell'espressione di una funzione compaiono le funzioni goniometriche, il logaritmo o l'esponenziale la funzione è definita **trascendente**, altrimenti è **algebrica**. In entrambi i casi la funzione può essere *intera* o *fratta*.

## Suriettività, iniettività e biettività
Una funzione è definita **iniettiva** quando a valori diversi della $\large x$ corrispondono valori diversi della $\large y$:
$$
\large
\forall x_{1} \neq x_{2} \in D \Rightarrow f(x_{1)} \neq f(x_{2})
$$
Una funzione è definita **suriettiva** quando ad ogni valore di $\large y$ corrisponde un valore o più di $\large x$:
$$
\large
\forall y \in C_{D} \Rightarrow \exists x \in D / f(x) = y
$$
Una funzione è definita **biettiva** quando è sia *iniettiva* che *suriettiva*. Quando una funzione è biettiva, può essere **invertita**.

## Calcolare il dominio

Il dominio dipende dal tipo di equazione della funzione, e quindi, dall'**operazione**. Il dominio coincide con la condizione di esistenza.
- Nel caso in cui l'equazione sia elementare o esponenziale, il dominio è $\large\mathbb{R}$
- Se l'equazione è fratta, il dominio include qualsiasi numero affinché il denominatore non sia 0
- Se la variabile indipendente è un radicando di una radice con indice pari, il dominio è $\large\mathbb{R}^+$, altrimenti è $\large\mathbb{R}$
- Se l'equazione è logaritmica, l'argomento dell'operazione dev'essere maggiore di 0.

Se le operazioni si sovrappongono, il dominio equivale al risultato del *sistema* fra le condizioni di esistenza delle diverse operazioni.

Le coordinate di un punto non potranno mai avere valori esterni al dominio o codominio.

## Intersezione con gli assi

Un'altra informazione utile nello studio di una funzione sono i punti in cui la funzione si interseca con gli assi. Per calcolarli bisogna fare il sistema tra la funzione e l'equazione di un asse:

$$
\large
\begin{cases}
y = f(x) \\
x = 0
\end{cases}
$$
$$
\large
\begin{cases}
y = f(x) \\
y = 0
\end{cases}
$$
## Positività della funzione

Vuol dire stabilire dove la variabile dipendente assume valore positivo e negativo. Per scoprirlo basta porre la funzione come maggiore di 0:
$$
\large
f(x) > 0
$$

## Simmetria

Calcolare la simmetria di una funzione come primo passo è utile perché ci permette di scoprire due punti sul grafico calcolandone solo uno.
La simmetria dipende dalla *parità o disparità* di una funzione.

Una funzione è **pari** quando simmetrica rispetto all'asse delle *ordinate*.
La parità si verifica così:
$$
\large
f(x) = f(-x)
$$
Quindi è simmetrica sull'asse delle ordinate.

La parabola è un esempio di funzione simmetrica dove $f(x) = f(-x)$:
$$
\large
y = 2x^{2}= 2(-x)^{2}
$$
$\large x^2$ e $\large(-x)^{2}$ sono uguali, quindi la funzione è simmetrica.

Una funzione è **dispari** quando i suoi valori sono simmetrici rispetto all'*origine*.
La disparità si verifica così:
$$
\large
f(-x) = -f(x)
$$
Per esempio:
$$
\large
f(x) = x^{3}
$$
$$
\large
f(-x) = -x^3
$$
$$
\large
-f(x) = (-x)^{3} = -x^3
$$
$$
\large
-f(x) = f(-x)
$$

## Monotonia
Una funzione è **monotòna** quando i valori di $\large y$ sono *crescenti* o *decrescenti*:
$$\large
\forall x_{1} < x_{2} \Rightarrow y_{1} < y_{2}
\cup
\forall x_{1} <  x_{2} \Rightarrow y_{1} > y_{2}
$$
