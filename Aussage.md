Zustandslos, können nur wahr oder falsch sein, müssen überprüfbar sein. Meist **Konditional**, also an Bedingungen geknüpft.

Zu einer Aussage $A$ gibt es immer dessen **Gegenausage** $\bar{A}$, auch $\lnot A$ geschreiben, welche man durch negieren erhält. 

**Tautologien** sind Aussagen, welche immer wahr sind und werden als Werkzug für [[Beweise|Beweise]] eingesetzt. 

# Verknüpfungen
- **Konjunktion** entspricht $\land$. *Das $\land$ kann weggelassen werden.*
- **Disjunktion** entspricht $\lor$.
- **Negation** entspricht der Gegenaussage.

Bei der **kanonische Normalform** werden alle Aussagen als Konjunktionen geschrieben und mit Disjunktionen verbunden oder umgekehrt. 

Zum Vereinfachen nutzt man aus, dass $A \lor \bar{A}$ immer wahr ist und klammert die restlichen Aussagen aus, wenn diese identisch sind. Es ist auch möglich, durch ein **Karnaugh-Veitch-Diagramm** zu vereinfachen.

Verknüpft eine Konjunktion nur mehr Aussagen als eine andere, so sind die Verknüpfiungen gleich.
$$
x_{1}\land x_{2}\land x_{3}=x_{1}\land x_{2}\land x_{3}\land x_{4}\land x_{5}
$$

## Äquivalenz
$$
A \iff B := (A \implies B) \land (B \implies A)
$$
Immer dann wahr, wenn $A$ und $B$ den gleichen Wert haben.

Das Gegenteil dazu ist die **Antivalenz**, welche XOR entspricht.
$$
(A \land \overline{B}) \lor (\overline{A} \land B)
$$

## Implikation
$\implies$ ist nur ein Operator, der besagt, dass, nur wenn die erste Aussage zutrifft, auch die zweite Aussage zutrifft. Das Zeichen alleine bedeutet jedoch keine Kausalität. Wenn die erste Aussage nicht zutrifft, kann nicht  auf die zweite Aussage gefolgert werden.

| $A$ | $B$ | $A \implies B$ |
| --- | --- | --- | 
Wahr | Wahr | Wahr 
Wahr | Falsch | Falsch
Falsch | Wahr | Wahr
Falsch | Falsch | Wahr 

$A \land (A \implies B)$ stellt erst eine **Kausalität** dar, da nun $A$ wahr sein muss, damit auch die Gesamtaussage zutrifft.

# Interpretation

Eine **aussagenlogische Signatur** $\sum=\{ A, B, C \}$ beschreibt eine [[Menge|Menge]] von mindestens eine atomare Aussage. Die **Formelmenge** $For0_{\sum}$ enthält alle mögliche Verknüpfungen der Aussagen von $\sum$.

Werden die Aussagewerte der atomaren Aussagen jetzt angenommen, handelt es sich um eine Interpretation, mit der eine Verknüpfung ausgewertet werden kann.
$$
I = \{ A \rightarrow 1, B \rightarrow 1 \}, val_{I}(A\land B)=\top
$$

Die [[Menge|Menge]] an allen Interpretationen über $\sum$ ist dann $I_{\sum}$.

Ein **Modell** ist eine Interpretation, bei welche die Gesamtaussage wahr ist. Die Menge aller Modelle einer Formel ist dann $Mod(A)=\left\{  I \in I_{\sum} |I(A)=\top  \right\}$.