Zustandslos, können nur wahr oder falsch sein, müssen überprüfbar sein. Meist **Konditional**, also an Bedingungen geknüpft.

Zu einer Aussage $A$ gibt es immer dessen **Gegenausage** $\bar{A}$, auch $\lnot A$ geschreiben, welche man durch negieren erhält. 

**Tautologien** sind Aussagen, welche immer wahr sind und werden als Werkzug für [[Beweise|Beweise]] eingesetzt. 

# Verknüpfungen

- **Konjunktion** entspricht dem logischen UND.
- **Disjunktion** entspricht dem logischen ODER.
- **Negation** entpricht der Gegenaussage.

Bei der **kanonische Normalform** werden alle Aussagen als Konjunktionen geschrieben und mit Disjunktionen verbunden oder umgekehrt. Zum vereinfachen nutzt man aus, dass $A \lor \bar{A}$ immer wahr ist und klammert die restlichen Aussagen aus. Es ist auch möglich durch ein **Karnaugh-Veitch-Diagramm** zu vereinfachen.

## Äquivalenz
$$
A \iff B := (A \implies B) \land (B \implies A)
$$
Immer dann wahr, wenn $A$ und $B$ den gleichen Wert haben.

Das Gegenteil dazu ist die **Antivalenz**, welche XOR entpricht.
$$
(A \land \overline{B}) \lor (\overline{A} \land B)
$$

## Implikation
$\implies$ ist nur ein Operator, der besagt, dass nur wenn die erste Aussage zutrifft, auch die zweite Aussage zutrifft. Das Zeichen alleine bedeutet jedoch keine Kausalität. Wenn die erste Aussage nicht zutrifft, kann nicht  auf die zweite Aussage gefolgert werden.

| $A$ | $B$ | $A \implies B$ |
| --- | --- | --- | 
Wahr | Wahr | Wahr 
Wahr | Falsch | Falsch
Falsch | Wahr | Wahr
Falsch | Falsch | Wahr 

$A \land (A \implies B)$ stellt erst eine **Kausalität** dar, da nun $A$ wahr sein muss damit auch die Gesammtaussage zurifft.
