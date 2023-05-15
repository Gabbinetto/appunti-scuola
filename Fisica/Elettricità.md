\Un atomo è elettrizzato **se il numero di elettroni varia**. Precisamente acquista carica positiva se perde elettroni e acquista carica negativa se guadagna elettroni. Questo perché gli elettroni hanno *carica negativa* e i protoni hanno *carica positiva*.

Ci sono tre tipi di elettrizzazione:
- **Strofinio**: Strofinando due corpi si possono scambiare elettroni, quindi le cariche saranno diverse
- **Contatto**: Lo scambio avviene semplicemente per contatto, ma solo se almeno uno dei corpi non è neutro. Le cariche risultanti saranno uguali.
- **Induzione**: Per semplice avvicinamento, senza contatto. Gli atomi si polarizzano, e gli elettroni/protoni si avvicinano alla carica esterna.
  Senza una messa a terra il corpo rimane, in realtà, neutro. Se c'è, invece, le particelle 
  sub-atomiche non attratte si allontanano da quelle attratte e si distribuiscono a terra; così la carica cambia e le cariche risultanti saranno opposte.
  ![[MessaATerra.excalidraw]]

## La forza di attrazione o repulsione
La forza di attrazione/repulsione, chiamata **forza di Coulomb**, ha modulo e direzione uguale per le due cariche, ma verso opposto.

![[ForzaDiRepulsione.excalidraw|width:100%]]

L'intensità si calcola con la **legge di Coulomb**:
$$
\large
|\overrightarrow{F_{C}}| =
\frac{Q_{1} \cdot Q_{2}}{d^{2}} \cdot K_{m} 
$$

Dove:
- $Q_{1}$ e $Q_{2}$ sono le cariche, misurate in *Coulomb* (**C**)
- $d$ è la distanza fra le cariche
- $K_{m}$ è la *costante elettrica*, che convenzionalmente: $\large K_{m} = 8.987 N \cdot \frac{m^{2}}{C^{2}}$ 
	- Più precisamente, è calcolata tramite $\large \frac{\mu_{0}}{2\pi}$ 
	- La costante nel vuoto si chiama $K_{0}$ e assume il valore di $8.854 \cdot 10^{-12}$

## Il campo elettrico

Il vettore campo elettrico $\large\vec{E}$  in un punto $P$ è uguale al rapporto tra la forza $\large \vec{F}$ che agisce su una carica $q$ in $P$ e la carica stessa.
$$
\large
\underbrace{\vec{E}}_{N/C} = \frac{\vec{F}}{q}
$$
### Il flusso
Il flusso del campo elettrico è il *prodotto scalare* tra il vettore campo elettrico e il *vettore superficie*, ovvero un vettore perpendicolare alla superficie, con modulo pari all'area della superficie.
$$
\large

\overbrace{\Phi_{S}}^{\textnormal{Flusso}}(\vec{E}) =
\vec{E} \cdot \vec{S}
$$
Ovvero:
$$
\large
\Phi_{S}(\vec{E}) = E \cdot S \cdot \cos(\alpha)
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
Essendo la somma delle tante piccole superfici,