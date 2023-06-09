Il  calcolo combinatorio si occupa di trovare i modi possibili in cui si possono ordinare gli elementi di un insieme.
Per il calcolo combinatorio servono due tipi di operazioni: **il fattoriale e il coefficiente binomiale**.

### Fattoriale e coefficiente binomiale
Il fattoriale (che si indica con il punto esclamativo) è il prodotto di un numero per tutti i suoi numeri inferiori fino a uno. Quindi:
$$
\large
n! = n \cdot (n-1) \cdot (n-2) \cdots 2 \cdot 1
$$
Il coefficiente binomiale di due numeri è il rapporto tra il fattoriale del primo per il prodotto del fattoriale del secondo e il fattoriale della differenza del primo e del secondo. Quindi:
$$
\large
\binom{n}{m}=\frac{n!}{m!\cdot(n-m)!}
$$


## Raggruppamenti
Tutti i sottoinsiemi possibili dall'insieme $A$, definiti **insieme delle parti dell'insieme $A$**. Per esempio, dato un insieme $\{a,b,c\}$ i raggruppamenti sono:
- $a$ - $b$ - $c$
- $ab$ - $ac$ - $bc$
- $a$ - $b$ - $c$
L'insieme delle parti si definisce $P(A)$.

## Permutazioni
Sono i diversi modi per ordinare gli elementi $n$ di un insieme con $k$ posti a disposizioni, con $k=n$. Quindi le diverse sequenze ordinate possibili con $n$ elementi. Per esempio, le permutazioni di *CIAO* sono:

| -    | -    | -    | -    | -    |  -   |
| ---- | ---- | ---- | ---- | ---- |:----:|
| CIAO | CIOA | CAIO | CAOI | COIA | COAI |
| ICAO | ICOA | IACO | IAOC | IOCA | IOAC |
| ACIO | ACOI | AICO | AIOC | AOCI | AOIC |
| OCIA | OCAI | OICA | OIAC | OACI | OAIC |

Le permutazioni totali sono pari a:
$$
\large
P_{n}=n!
$$
### Con ripetizioni
Se si considerano le **ripetizioni** degli elementi allora il totale diventa il fattoriale di $n$ diviso per il prodotto del fattoriale delle ripetizioni degli elementi. Per esempio, nella parola *MAMMA* la M si ripete 3 volte e la A 2 volte. Quindi il totale sarà
$$
\large
P'_{n}=
\frac{n!}{r_{M}!\cdot r_{A}!}=
\frac{5!}{3!\cdot 2!}=
\frac{5 \cdot 4 \cdot 3!}{3!\cdot2!}=
\frac{5\cdot4}{2}=
5\cdot2=
10
$$
Infatti, in un insieme senza ripetizioni come *CIAO*, anche qui possiamo dividere per le ripetizioni degli elementi, ma essendo le ripetizioni pari a 1 il denominatore si rimuove:
$$
\large
P'_{\text{CIAO}} = \frac{4!}{r_{C}\cdot r_{I} \cdot r_{A} \cdot r_{O}} =
\frac{4!}{1\cdot1\cdot1\cdot1} = 4! = P_{\text{CIAO}}
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
\large
D_{n,k}= \frac{n!}{(n-k)!}
$$
Per semplificare conviene fermarsi al fattoriale fino a $(n-k)!$, cosi da semplificare con il denominatore. Per esempio con $n=50$ e $k=3$:
$$
\large
\frac{50!}{(50-3)!} = \frac{50!}{47!} = \frac{50*49*48*47!}{47!} = 50*49*48 = 117600
$$
> Le permutazioni, infatti, possono essere pensate come caso particolare di disposizioni, dove $k=n$, infatti con questi due valori uguali: $\large D_{n,n}=\frac{n!}{(n-n)!}=\frac{n!}{1}=n!=P_{n}$.
### Con ripetizioni
Se si considerano le **ripetizioni** diventa molto più semplice. La formula diventa:
$$
\large
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
\large
C_{n,k}=\binom{n}{k}
$$

### Con ripetizioni
Se si considerano le **ripetizioni** la formula diventa:
$$
\large
C'_{n,k} = \binom{n+k-1}{k} = \frac{(n+k-1)!}{k! \cdot (n-1)!}
$$
