Ist atomar, hat einen Wahrheitswert, welcher entweder wahr oder falsch . Zu einer Aussage $A$ gibt es immer dessen Gegenausage, welche man durch negieren erhält.

| $A$ | $\lnot A$ oder $\bar A$|
| --- | --- |
Wahr | Falsch
Falsch | Wahr


# Kombinatoren
Aussage $A$ und Aussage $B$ sind unabhängig voneinander.

## Und
Wenn $\bar \land$ dann $\lor$

| $A$ | $B$ | $A \land B$ |
| --- | --- | --- |
Wahr | Wahr | Wahr
Wahr | Falsch | Falsch
Falsch | Wahr | Falsch
Falsch | Falsch | Falsch

## Oder
Wenn $\bar \lor$ dann $\land$

| $A$ | $B$ | $A \lor B$ |
| --- | --- | --- |
Wahr | Wahr | Wahr
Wahr | Falsch | Wahr
Falsch | Wahr | Wahr
Falsch | Falsch | Falsch


## Implikation
Stellt keine kausalität dar, impliziert ausschließlich ("Daraus muss folgen"). Wenn $A$ eine unwahre Aussage ist, impliziert es nichts für die Aussage $B$. Wenn $A$ eine wahre Aussage ist, kann es nur eine wahre Aussage implizieren. 

| $A$ | $B$ | $A \Rightarrow B$ | $A \land (A \Rightarrow B)$ | $A \land (A \Rightarrow B) \Rightarrow B$ "Tautologie" Direkter Beweis | $A \land (\bar B \Rightarrow \bar A) \Rightarrow B$ Indirekter Beweise |
| --- | --- | --- | --- | --- | --- |
Wahr | Wahr | Wahr | Wahr | Wahr
Wahr | Falsch | Falsch | Falsch | Wahr
Falsch | Wahr | Wahr | Falsch | Wahr
Falsch | Falsch | Wahr | Falsch | Wahr

## Äquivalenz
| $A$ | $B$ | $A \Leftrightarrow B$ | $(A \Leftrightarrow B) \Leftrightarrow ((A \Leftrightarrow B)) \land (B \Rightarrow A ))$ |
| --- | --- | --- | --- |
Wahr | Wahr | Wahr 
Wahr | Falsch | Falsch
Falsch | Wahr | Falsch
Falsch | Falsch | Wahr

## MORGANsche Regel
$$ A \land (B \lor C) \Leftrightarrow (A \land B) \lor (A \land C) $$