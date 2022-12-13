Zwei Zahlen sind teilerfremd, wenn ihr gemeinsammer größter Teil $1$ ist. 

Ist Produkt ist teilbar durch $p$, gilt $p\mid a \cdot b \land ggT(p,a)=1\implies p\mid b$ und $p\mid a\cdot b \land p \in \mathbb{P}\implies p\mid a \lor p\mid b$. 

# Euklidischer Algorithmus
Finden den größten gemeinsammen Teiler $ggT(p_{0},p_{1})$, indem die größere Zahl durch die kleiner Geteilt wird. Entsteht dabei ein Rest, teilt man die kleinere Zahl durch diesen Rest. Der Algorithmus determinert, wenn der Rest $0$ ist.

Darstellung von Euklid ist $ggT(p,q) = tp + sq$.