Besitzt zwei die **Nennwerte**, also Zustände.

Negative Zahlen dargestellt durch [[Komplement|Zweierkomplement]], wobei man das erste Bit als negative Zahl dessen Wertigkeit ansehen kann, worauf die anderen Bits drauf addiert werden.

# Konversion 
- **Dezimal**, zuerst in Binär umwandeln wenn andere Zahlensysteme verwenden soll
![[Binäre Dezimal Konversion.excalidraw | 1000]]

- **Hexadezimal**, 4 Bits sind eine Hexadezimalstelle
- **Octal**, 3 Bits sind eine Octalstelle

# Mathematische Operatoren
Analog zum Dezimalsystem.
- Für die **Addition** ist es einfacher mehrere Zahlen hintereinander zu addieren, anstatt alle auf einmal.
- **Subtration** wird in der Regel nicht auf die tradizionelle Art gemacht, sondern in dem man mit der [[Komplement | Komplimentärzahl]] addiert.
- Bei der **Multiplikation** kann bei $n$ Bitstellen kann das Produkt maximal $2n$ Bitstellen haben. Für negative Werte zuersten den Beträge multiplizeren und am Ende das Vorzeichen bestimmen.
- Wenn bei der **Division** eines Integers keine weitere Bitstelle vorhanden ist, endet diese. 

Vorzeichen ausklammern soweit es geht und dass die erste Zahl positiv ist, vereinfacht es.


# Overflow
Lässt sich daran feststellen, dass der letzte und vorletzte Übertrag nicht identisch sind. Kann nicht auftreten, wenn man eine positive Zahl von einer positiven Zahl abzieht. 