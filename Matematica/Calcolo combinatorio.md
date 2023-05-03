Il  calcolo combinatorio si occupa di trovare i modi possibili in cui si possono ordinare gli elementi di un insieme.
Per il calcolo combinatorio servono due tipi di operazioni: **il fattoriale e il coefficiente binomiale**.

### Fattoriale e coefficiente binomiale
Il fattoriale (che si indica con il punto esclamativo) è il prodotto di un numero per tutti i suoi numeri inferiori fino a uno. Quindi:
$$
n! = n \cdot (n-1) \cdot (n-2) \cdots 2 \cdot 1
$$
Il coefficiente binomiale di due numeri è il rapporto tra il fattoriale del primo per il prodotto del fattoriale del secondo e il fattoriale della differenza del primo e del secondo. Quindi:
$$
\binom{n}{m}=\frac{n!}{m!\cdot(n-m)!}
$$


## Raggruppamenti
Tutti i sottoinsiemi possibili dall'insieme $A$, definiti **insieme delle parti dell'insieme $A$**. Per esempio, dato un insieme $\{a,b,c\}$ i raggruppamenti sono:
- $a,b,c$
- $ab$ - $ac$ - $bc$
- $a$ - $b$ - $c$
L'insieme delle parti si definisce $P(A)$.

## Permutazioni
Sono i diversi modi per ordinare gli elementi $n$ di un insieme con $k$ posti a disposizioni, con $k=n$. Per esempio, le permutazioni di *CIAO* sono:

| -    | -    | -    | -    | -    |  -   |
| ---- | ---- | ---- | ---- | ---- |:----:|
| CIAO | CIOA | CAIO | CAOI | COIA | COAI |
| ICAO | ICOA | IACO | IAOC | IOCA | IOAC |
| ACIO | ACOI | AICO | AIOC | AOCI | AOIC |
| OCIA | OCAI | OICA | OIAC | OACI | OAIC |

Le permutazioni totali sono pari a:
$$
P_{n}=n!
$$
### Con ripetizioni
Se si considerano le **ripetizioni** degli elementi allora il totale diventa il fattoriale di $n$ diviso per il prodotto del fattoriale delle ripetizioni degli elementi. Per esempio, nella parola *MAMMA* la M si ripete 3 volte e la A 2 volte. Quindi il totale sarà
$$
P'_{n}=
\frac{n!}{r_{M}!\cdot r_{A}!}=
\frac{5!}{3!\cdot 2!}=
\frac{5 \cdot 4 \cdot 3!}{3!\cdot2!}=
\frac{5\cdot4}{2}=
5\cdot2=
10
$$


## Disposizioni
Trovano i possibili ordini con $n$ elementi e $k$ posti, con $k<n$, dove l'ordine fa la differenza. Per esempio, con l'insieme $\{a,b,c\}$ le disposizioni, dove $k=2$, possibili sono:
- $ab$
- $ac$
- $ba$
- $bc$
- $ca$
- $cb$

E disposizioni come $ab$ e $ba$ **non sono uguali**.
Per calcolare il numero di possibili disposizioni totali si usa la formula:
$$
D_{n,k}= \frac{n!}{(n-k)!}
$$
Per semplificare conviene fermarsi al fattoriale fino a $(n-k)!$, cosi da semplificare con il denominatore. Per esempio con $n=50$ e $k=3$:
$$
\frac{50!}{(50-3)!} = \frac{50!}{47!} = \frac{50*49*48*47!}{47!} = 50*49*48 = 117600
$$
### Con ripetizioni
Se si considerano le **ripetizioni** diventa molto più semplice. La formula diventa:
$$
D'_{n,k}=n^{k}
$$


## Combinazioni
Anche qui $k<n$, ma l'ordine qui non fa differenza. Per esempio, con l'insieme $\{a,b,c\}$ le combinazioni possibili, dove $k=2$, possibili sono:
- $ab$
- $ac$
- $bc$
E combinazioni come $ab$ e $ba$ **sono uguali**.
Si calcolano le possibili combinazioni con il *coefficiente binomiale* di $n$ su $k$: 
$$
C_{n,k}=\binom{n}{k}
$$

### Con ripetizioni
Se si considerano le **ripetizioni** la formula diventa:
$$
C'_{n,k}=\frac{(n-k-1)!}{k!\cdot(n-k)!}
$$
