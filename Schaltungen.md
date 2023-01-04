Bilden Verknüpfungen um den Wahrheitswert einer [[Aussage|Aussage]] zu bestimmen.

# TTL-Glieder
Erzeugen logische Verknüpfungen durch das Zusammenschalten von mehreren [[Transistoren#Bipolare Transistoren|bipolare Transistoren]]. 

[[Transistoren|Bipolare Transistoren]] mit mehreren Ausgängen können genutzt werden, um mehrere Eingänge in einem Bauteil zusammenzufassen. Sind alle Ausgänge auf einem hohen Potenzial, ist diese im [[Transistoren#Inverser Betrieb|inversen Betrieb]], ansonsten im Regulären.

Eine **Gegentakt-Ausgangsstufe** sorgt dafür, dass kein Spannungsabfall am Ausgang entsteht,, genauso wie, dass die Eingangspannung zur Masse abfließen an. Dies erreicht man mit den zwei Transistoren $T_{3}$ und $T_{4}$, wovon immer einer gesperrt ist, während der andere offen ist.

![[TTL-Glied.png|NAND-Glied]]

# ECL-Glieder
Bestehen aus einem **Differenzverstärker**. Dieser besteht aus zwei Transistoren. Die Basis von einem Transistor liegt dabei an einer konstanten Spannung, sodass die kein Strom mehr fließen kann, wenn an der Basis des anderem eine höhere Spannung anliegt. Das hat zu Folge, dass $y_{1}$ und $y_{2}$ negierte Signale zueinander sind.

![[Differenzenverstärker.png]]

Es lassen sich mehrere Transistoren parallel schalten am Eingang, um ein OR-Glied zu erhalten. Mittels einer **Emitterentstufe** bringt man das Ausgangssignal wieder auf den genauen Signalpegel, indem der Eingangspegel hinzu oder weggeschaltet wird.

![[ECL-Glied.png]]

# MOS-Glieder
Logik durch Parallelschaltung bzw. Reihenschaltung von MOSFETs. Können simpler sein als Schaltungen mit bipolaren Transistoren, da kein Strom über das Gate fließt.

![[MOS-Glied.png]]

Der Lastwiderstand kann durch einen weiteren MOSFET ersetzt werden. Sind ausschließlich selbstsperrende P-MOSFETs verwendet, handelt sich es um ein **PMOS-Verknüpfungsglied**, bei ausschließlich selbstsperrende N-MOSFETs um ein **NMOS-Verknüpfungsglied**, und wenn beide Arten vorkommen um ein **CMOS-Verknüpfungsglied**.