Zwei Zahlen sind **teilerfremd**, wenn ihr **gemeinsammer größter Teil** $\text{ggT(a, b)}=1$ ist. Dies trifft auf einen vollständig gekürzten Bruch zu.

Ist ein Produkt ist teilbar durch $p$, gilt $p\mid a \cdot b \land ggT(p,a)=1\implies p\mid b$ und $p\mid a\cdot b \land p \in \mathbb{P}\implies p\mid a \lor p\mid b$. 

Die Wurzel einer Primzahl ist keine rationale Zahl und damit teilerfremd.
$$
p \in \mathbb{P} \implies \sqrt{ p } \notin \mathbb{Q}
$$

Wenn zwei Zahlen kein Primfaktor gemeinsam haben, sind sie teilerfremd.

# Modulo
Zahlen sind gleich, wenn sie sich nur um vielfache von $p$ unterscheiden.
$$
a=b\bmod{p}
$$

*Notation in Kursen unterrichtet von J. Hellmich $b=_{p}a$.*

Damit gibt es immer nur $p$ verschiedene Zahlen in der [[Menge|Menge]] der **Äquivalenzklasse** $\mathbb{Z}_{p}:=\{ 0, 1, 2, \dots, p-1 \}$. Dies hat auch zu Folge, dass eine Zahl nach $p$ Stellen spätestens periodisch sein wird, falls sie dieses ist.

Da die Rechengesetzte gelten, kann man Modulo am Anfang, Zwischendruch oder am Ende anwenden, aber nie im Exponenten.

Die **Inverse** von modulo $p$ ist die Zahl $b$, welche man mit $a$ multiplizieren muss, damit das Produkt daraus modulo $p$ $1$ ergibt. ^d94a6f
$$
1=(a\cdot b)\bmod p
$$
Wird eindeutig, wenn die Inverse zwischen $0$ und $p$ liegen soll.

# Euklidischer Algorithmus
Darstellung von Euklid ist $ggT(p,q) = tp + sq$.

Finden den größten gemeinsammen Teiler $ggT(p_{0},p_{1})$, indem die größere Zahl durch die kleiner Geteilt wird. Entsteht dabei ein Rest, teilt man die kleinere Zahl durch diesen Rest. Der Algorithmus determinert, wenn der Rest $0$ ist.

Durch den **erweiterten euklidschen Algorthmus** erhält man die [[Teilbarkeit#^d94a6f|Inverse]]. Dafür stehlt man alle Schritte nach den Rest um und setzt den jeweils vorrigen Rest nacheinander ein.