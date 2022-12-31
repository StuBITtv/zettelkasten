[[Transistoren|Bipolare Transistoren]] mit mehreren Ausgängen können genutzt werden, um mehrere Eingänge in einem Bauteil zusammenzufassen. Sind alle Ausgänge auf einem hohen Potenzial, ist diese im [[Transistoren#Inverser Betrieb|inversen Betrieb]], ansonsten im Regulären.

# TTL-Glieder
Erzeugen logische Verknüpfungen durch das Zusammenschalten von mehreren [[Transistoren#Bipolare Transistoren|bipolare Transistoren]]. 

Eine **Gegentakt-Ausgangsstufe** sorgt dafür, dass kein Spannungsabfall am Ausgang entsteht,, genauso wie, dass die Eingangspannung zur Masse abfließen an. Dies erreicht man mit den zwei Transistoren $T_{3}$ und $T_{4}$, wovon immer einer gesperrt ist, während der andere offen ist.

![[TTL-Glied.png|NAND-Glied]]

# ECL-Glieder
Bestehen aus einem **Differenzverstärker**. Dieser besteht aus zwei Transistoren. Die Basis von einem Transistor liegt dabei an einer konstanten Spannung, sodass die kein Strom mehr fließen kann, wenn an der Basis des anderem eine höhere Spannung anliegt. Das hat zu Folge, dass $y_{1}$ und $y_{2}$ negierte Signale zueinander sind.

![[Differenzenverstärker.png]]

Es lassen sich mehrere Transistoren parallel schalten am Eingang, um ein OR-Glied zu erhalten. Mittels einer **Emitterentstufe** bringt man das Ausgangssignal wieder auf den genauen Signalpegel, indem der Inputpegel hinzu oder weggeschaltet wird.

![[ECL-Glied.png]]