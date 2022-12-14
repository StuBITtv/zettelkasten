Zwei Zahlen sind **teilerfremd**, wenn ihr **gemeinsammer größter Teil** $\text{ggT(a, b)}=1$ ist. Dies trifft auf einen vollständig gekürzten Bruch zu.

Ist ein Produkt ist teilbar durch $p$, gilt $p\mid a \cdot b \land ggT(p,a)=1\implies p\mid b$ und $p\mid a\cdot b \land p \in \mathbb{P}\implies p\mid a \lor p\mid b$. 

Die Wurzel einer Primzahl ist keine rationale Zahl und damit teilerfremd.
$$
p \in \mathbb{P} \implies \sqrt{ p } \notin \mathbb{Q}
$$

# Euklidischer Algorithmus
Finden den größten gemeinsammen Teiler $ggT(p_{0},p_{1})$, indem die größere Zahl durch die kleiner Geteilt wird. Entsteht dabei ein Rest, teilt man die kleinere Zahl durch diesen Rest. Der Algorithmus determinert, wenn der Rest $0$ ist.

Darstellung von Euklid ist $ggT(p,q) = tp + sq$.

# Modulo
Zahlen sind gleich, wenn sie sich nur um vielfache von $p$ unterscheiden.
$$
a=b\bmod{p}
$$

*Notation in Kursen unterrichtet von J. Hellmich $b=_{p}a$.*

Damit gibt es immer nur $p$ verschiedene Zahlen in der [[Menge|Menge]] der **Äquivalenzklasse** $\mathbb{Z}_{p}:=\{ 0, 1, 2, \dots, p-1 \}$.

Da die Rechengesetzte gelten, kann man Modulo am Anfang, Zwischendruch oder am Ende anwenden.

Die **Inverse**, also die Umkehroperation von Modulo, ist eindeutig. Nach Eulkid muss es eine Zahl $t \in \mathbb{Z}$ und eine Zahl $s \in \mathbb{Z}$ geben, sodass $1=ta+sp=_{p}ta$ gilt. Daraüber lässt sich die Inverse bestimmen.