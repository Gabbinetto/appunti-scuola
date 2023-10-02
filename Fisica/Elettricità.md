Un atomo è elettrizzato **se il numero di elettroni varia**. Precisamente acquista carica positiva se perde elettroni e acquista carica negativa se guadagna elettroni. Questo perché gli elettroni hanno *carica negativa* e i protoni hanno *carica positiva*.

Ci sono tre tipi di elettrizzazione:
- **Strofinio**: Strofinando due corpi si possono scambiare elettroni, quindi le cariche saranno <u>opposte</u>.
- **Contatto**: Lo scambio avviene semplicemente per contatto, ma solo se almeno uno dei corpi non è neutro. Le cariche risultanti saranno <u>uguali</u>.
- **Induzione**: Per semplice avvicinamento, senza contatto. Gli atomi si polarizzano, e gli elettroni/protoni si avvicinano alla carica esterna.
  Senza una messa a terra il corpo rimane, in realtà, neutro. Se c'è, invece, le particelle 
  sub-atomiche non attratte si allontanano da quelle attratte e si distribuiscono a terra; così la carica cambia e le cariche risultanti saranno <u>opposte</u>.
  ![[MessaATerra.excalidraw]]

## La forza di attrazione o repulsione (Coulomb)
La forza di attrazione/repulsione, chiamata **forza di Coulomb**, ha modulo e direzione uguale per le due cariche, ma verso opposto.

![[ForzaDiRepulsione.excalidraw|width:100%]]

L'intensità si calcola con la **legge di Coulomb**:
$$
\large
\bbox[yellow]{
|\overrightarrow{F_{C}}| =
\frac{Q_{1} \cdot Q_{2}}{d^{2}} \cdot K_{0} 
}
$$

Dove:
- $Q_{1}$ e $Q_{2}$ sono le cariche, misurate in *Coulomb* (**C**)
- $d$ è la distanza fra le cariche
- $K_{0}$ è la *costante di proporzionalità nel vuoto*, che è: $\large K_{0} = 8.987 \frac{N \cdot m^{2}}{C^{2}}$ 
	- Più precisamente, è calcolata tramite $\large \frac{1}{4\pi\varepsilon_{0}}$

### La costante di proporzionalità e la costante dielettrica
$K$ è un fattore di proporzionalità, dove nel vuoto assume il valore di *$\large 8.99 \cdot 10^{9} \frac{N \cdot m^{2}}{C^{2}}$*.
$$\large
K = \frac{1}{4\pi\varepsilon}
$$
Dove $\varepsilon$ è assoluta o relativa, a seconda del contesto.

$\large\varepsilon$ è la costante dielettrica e dipende dal materiale del mezzo. Nel vuoto è *$\large 8.854 \cdot 10^{-12} \frac{C^{2}}{N \cdot m^{2}}$*.
In un mezzo la costante dielettrica è
$$\large
\varepsilon_{m} = \varepsilon_{0} \cdot \varepsilon_{r}
$$
Dove $\large \varepsilon_{r}$, detta *relativa*, dipende dal mezzo di trasmissione e sono valori tabulati.


## Il campo elettrico
Ogni carica ha la proprietà e capacità di agire su altre cariche. Lo spazio dove questo avviene è definito **campo elettrico** di una carica. La carica del campo elettrico è definita *carica generatrice*.

Il vettore campo elettrico $\large\vec{E}$  in un punto $P$ è uguale al rapporto tra la forza $\large \vec{F}$ che agisce su una carica $q$ in $P$, definita *carica esploratrice* (O *di prova*) perché è la carica che subisce la forza dalla *carica generatrice* (Quella che genera il campo elettrico), e la carica stessa.
$$
\underbrace{\vec{E}}_{N/C} = \frac{\vec{F}}{q}
$$
Applicando la legge di Coulomb:

$$
\large
\bbox[yellow]{
\vec{E} = K_{0} \cdot \frac{Q \cdot q}{d^{2} \cdot q} = \frac{K_{0}\cdot Q}{d^{2}}
}
$$
Dove $\large Q$ è la *carica generatrice*. Quindi si nota come in realtà la carica esploratrice non influisce sul campo elettrico, e ci serve solo a misurarlo.

Il vettore del campo elettrico ha sempre verso *esterno* quando la carica è *positiva*, e *interno* quando è *negativa*.
![[CampoElettrico.excalidraw|width:100%]]



### Il campo elettrico con distribuzioni particolari
#### Sfera
In una sfera la formula del campo elettrico può essere scritta come:
$$
\large
E=\frac{|Q|}{4\pi \varepsilon_{0}d^{2}}
$$
Se il campo si calcola all'interno la formula è:
$$\large
E = \frac{|Q|}{4\pi \varepsilon_{0}R^{3}}\cdot r
$$
Dove $R$ è il raggio della sfera e $r$ è la distanza dalla carica.
#### Piano infinito di carica
In un piano infinito di carica l'unità di misura è $\large N \cdot \frac{m^{2}}{C}$ e si calcola:
$$
\large
E = \frac{|\sigma|}{2\varepsilon_{0}}
$$
$\large \sigma$ è la **densità superficiale di carica**, quindi quanta carica in Coulomb c'è per metro quadro ($\large\frac{C}{m^{2}}$). Si calcola:
$$\large
\sigma = \frac{\Delta Q}{\Delta S}
$$

#### Filo rettilineo infinito di carica
In una superficie rettilinea, come un filo o simili:
$$
\large
E = \frac{|\lambda|}{2\pi \varepsilon_{0}r}
$$
Dove $\lambda$ è la **densità lineare di carica** ed è definita come il rapporto tra la differenza di carica e di lunghezza in un tratto di linea, assumendo che la carica sia distribuita equamente:
$$\large
\lambda = \frac{\Delta Q}{\Delta l}
$$

## Il flusso
Il flusso del campo elettrico è il *prodotto scalare* tra il vettore campo elettrico e il *vettore superficie*, ovvero un vettore perpendicolare alla superficie, con modulo pari all'area della superficie.
$$

\overbrace{\Phi_{S}}^{\textnormal{Flusso}}(\vec{E}) =
\vec{E} \cdot \vec{S}
$$
Ovvero:
$$
\large
\Phi_{S}(\vec{E}) = \vec{E} \cdot \vec{S} \cdot \cos(\alpha)
$$
Può essere anche espresso in un altro modo, considerando la singola velocità della carica:
$$
\large
\Phi_{S}(\vec{E}) = \vec{v} \cdot \vec{S} \cdot \cos(\alpha)
$$
Quindi il flusso è massimo se i vettori sono **paralleli** (Perché $\large \cos(0) = 1$). Ovviamente il valore non può essere negativo, quindi tutti i casi negativi non sono considerati, e non possono esistere.

Questo è il flusso considerato su una superficie piana. Se la superficie non è piana il vettore superficie *non può esistere*. Questo perché il vettore superficie è sempre perpendicolare alla superficie, ma se questa è curva ciò non può accadere. 

Quindi, per ovviare al problema, si considera la superficie $\large \Omega$ suddivisa in $\large n$ *micro-superfici* tanto piccole da essere considerabili piane. 
Poi si sommano i tanti micro-campi calcolati con le superfici:
$$
\large
\Phi_{\Omega}(\vec{E}) = \vec{E}_{1} \cdot \vec{S}_{1} + \vec{E}_{2} \cdot \vec{S}_{2} + \dots + \vec{E}_{n} \cdot \vec{S}_{n}
$$
Sostituendo con l'*operatore di sommatoria*:
$$
\large
\Phi_{\Omega}(\vec{E}) =
\sum_{i=0}^{n} \vec{E}_{i} \cdot \vec{S}_{i}
$$
Essendo la somma delle tante piccole superfici, la formula si può scrivere anche come il prodotto del campo elettrico e la **superficie totale**:
$$
\large
\Phi_{\Omega}(\vec{E}) = \vec{E} \cdot \Delta S
$$
### Teorema di Gauss
Secondo il teorema di Gauss, il flusso del campo elettrico di una **superficie chiusa** è pari al rapporto tra *carica totale entro la superficie* e la *costate dielettrica del vuoto*:
$$\large
\Phi_{\Omega}(\vec{E}) = \frac{Q_{\text{tot}}}{\varepsilon_{0}}
$$

# Potenziale elettrico

