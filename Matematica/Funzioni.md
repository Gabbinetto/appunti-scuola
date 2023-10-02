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
## Punto di accumulazione
Un punto $\large x_{0}$ è punto di accumulazione di una data funzione $\large f(x)$ quando nel suo [intorno](Matematica/Intervalli)
$\large I$ vi è almeno un punto appartenente al dominio $\large D$ della funzione.
$$\large
x_{0} \text{ è accumulazione per } D
\Leftrightarrow
\forall \delta > 0 \:\: \exists \: I_{x_{0}} = \:
]x_{0}-\delta, x_{0}+\delta[\: / I_{x_{0}} \cap D \neq \varnothing
$$
Ovviamente un punto appartenente al dominio sarà un punto di accumulazione. È utile sapere se un punto <u>non</u> appartenente al dominio sia un punto di accumulazione, per studiare l'andamento della funzione quando si avvicina a quel punto.

Esiste un caso in cui un punto appartenente al dominio non sia un punto di accumulazione, per esempio:
$$\large
D: \forall x \in \: ]-\infty, -1[ \:\: \cup \: \{2\} 
$$
Qui il 2 è ***isolato*** rispetto al resto del dominio, e qualunque punto *intorno* al 2 non appartiene al dominio, quindi non è punto di accumulazione.

## Il limite
Tramite l'**operatore di limite** si può dedurre l'andamento di una funzione ai suoi, appunto, limiti del dominio, come un punto di accumulazione. 

$$\large
\lim_{x \to x_{0}} f(x) = l
$$
La definizione di limite è:
$$\large
\forall \varepsilon > 0 \: \exists\delta > 0 / \forall x \in \: \underbrace{]x_{0}-\delta, x_{0} + \delta[}_{I_{x_{0}}} \Rightarrow |f(x)-l| < \varepsilon
$$

Dove $\large \delta$ e $\large \varepsilon$ sono l'ampiezza degli intorni di $\large x_{0}$ e $\large l$. L'andamento della funzione si trova nella zona infinitesima individuata dagli intorni di $\large x_{0}$ e $\large l$.

### Calcolo del limite
Calcolare il limite è molto semplice. Calcolare $\large \lim_{x \to x_{0}}f(x)$ è come calcolare $\large f(x_{0})$. La difficoltà sta nell'interpretarlo.
Per esempio:
$$\large
f(x) = \frac{x^{2}-3}{x-1}
$$
$$\large
\lim_{x \to 1} \frac{x^{2}-3}{x-1} = \frac{1-3}{1-1} = -\frac{2}{0}
$$
Normalmente $\large -\frac{2}{0}$ è un'operazione impossibile, ma nell'operazione di limite **un denominatore uguale a zero risulta in infinito($\large \infty$)**. Quindi la retta a $\large x=1$ è *asintoto verticale della funzione*:
$$\large
\lim_{x \to 1}f(x) = -\infty
$$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x)=(x^(2)-3)/(x-1)
```
> La crescenza o decrescenza della curva è deducibile dalla positività

A differenza della forma $\large \frac{n}{0}$, che assume un valore nel limite, la forma $\large \frac{0}{0}$ rimane indeterminata, e si chiama proprio *forma indeterminata*. Per risolverle, normalmente, si scompone la funzione. Per esempio:
$$\large
\lim_{x \to 0} \frac{x^{2}+x}{x} = \frac{0}{0}
$$
Scomponendo:
$$\large
\lim_{x \to 0} \frac{x^{2}+x}{x} = \lim_{x \to 0} \frac{x(x+1)}{x} = \lim_{x \to 0} x+1
$$
$$\large
\lim_{x \to 0} x+1 = 0+1 = 1
$$
### Verifica del limite
Verificare il limite vuol dire verificare che $\large |f(x)-l| < \varepsilon$. Questo perché bisogna verificare che ci sia sempre un valore minore di $\large \varepsilon$, che è un valore **infinitesimale**.

È diverso se il limite tende all'infinito. Il limite tende all'infinito quando:
- $\large \lim_{x \to x_{0}} = \frac{n}{0}$
- $\large \lim_{x \to x_{0}} = \frac{0}{n}$

In questi casi la definizione cambia:
$$\large
\forall \varepsilon > 0 \: \exists\delta > 0 / \forall x \in \: \underbrace{]x_{0}-\delta, x_{0} + \delta[}_{I_{x_{0}}} \Rightarrow |f(x)| > \varepsilon
$$
Quindi, in questo caso, la verifica da fare è che $f(x)$ sia maggiore di $\large\varepsilon$, che stavolta sarà un **numero grandissimo**, invece che infinitesimale. Questo perché stavolta, visto che la funzione tende all'infinito,  bisogna verificare che ci sia un valore nella funzione sempre più grande di qualsiasi numero, sia esso $7$ o $20.000.000$.