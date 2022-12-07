Naive Definition von **Cantor**. Mithilfe von einem **Venn-Diagram** lassen sich Mengen und deren Beziehungen als überlappende Flächen darstellen.

# Arten
- Explizite Aufzählung 
$$
\{ Liste\ aller\ Werte\}
$$
- Deskriptive Form, also beschreibend 
$$
\{ x \in\text{Wertebereich}\ |\  \text{Bedingung} \}
$$
$$
\{ \text{Funktion}\ |\ \text{Wertebreich} \} \iff \{ \text{Wertebreich} | \exists_{anderer\ Wertebereich}x=Funktion\}
$$
$$
X: \text{Menge},\ A(x)\ \text{Aussageform:}\ B=\{ x \in X | A(x)\} \subseteq X
$$

# Teilmenge
Jede Menge ist ihre eigene Teilmenge. Wenn zwei Mengen Teilmengen zueinander sind, sind sie identisch.
$$
X \subseteq Y \land Y \subseteq X \iff X = Y
$$

**Echte Teilmengen**, wenn die Mengen  nicht gleich sein können.
$$
X \subset Y :\iff (x \in Y \iff x \in Y) \land (\exists _{y \in Y} y \notin X)
$$

**Intervalle** sind Teilmengen von $\mathbb{R}$.

Die Menge aller Teilmengen einer Menge ist die **Potenzmenge**.
$$
2^{M} = \{ M' | M' \subseteq M \}
$$
Für die **Mächtigkeit**, also die Anzahl an Teilmengen einer Menge, gilt $2^{\text{Anzahl an Elementen in der Menge}}$.

# Leere Menge
$$
\emptyset = \{  \}
$$

Teilmenger aller Mengen. Alle [[Aussage | Ausssagen]] über die Elemente sind wahr. Teilmenge aller Mengen.

# Operationen
Können durch Operatoren von [[Aussage]] dargestellt werden.

- Vereinigungsmenge $M_{1} \cup M_{2}$, entspricht dem logischen ODER von [[Aussage|Aussagen]].
- Schnittmenge $M_{1} \cap M_{2}$, entspricht dem logischen UND von [[Aussage|Aussagen]].
- Differenz $M_{1} \setminus M_{2}$, in $M_{1}$ aber nicht in $M_{2}$.
- Symetirsche Differen $M_{1} \triangle M_{2}$, nicht gleichzeitig in $M_{1}$ und $M_{2}$, aber mindestens in einer der Mengen.
- [[Komplement | Komplement]]  $\overline{M_{1}}$, auch $M^{C}$, nicht in $M_{1}$, also $\{ x \in X |\  \overline{x \in M} \}$
- **Kartesisches Produktmenge**, jede mögliche Kombination als geordnete Tupel.
  $$
 M_{1} \times M_{2} \times  \dots \times M_{n}:= \{ [m_{1}, m_{2}, \dots, m_{3}]\ |\ m_{1} \in M_{1} \land m_{2} \in M_{2} \land \dots \land m_{n} \in M_{n} \}
 $$
 ![[Kartesisches Prdukt.excalidraw|200]]
 $M^{n} = M \times \dots \times M$ ist die Menge der n-Tupel über M. 

# Relationen
Die Teilmengen von kartesischen Produkte. Eine Relation ist homogen, falls diese gleich der Ausgangsmenge ist. Gibt es nur zwei Ausgangsmengen aus denen das kartesische Produkt gebildet worden ist, sind die Relationen davon binär. 