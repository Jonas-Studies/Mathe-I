# Definition
Mathematische Inhalte werden mit Aussagen ausgedrückt. Eine Aussage ist richtig (r) oder falsch (f). Alternative Bezeichnungen wären Theorem, Satz oder Lemma.
# Verknüpfungen von Aussagen
## Negation
Die Negation einer Aussage $A$ ist genau dann richtig, wenn $A$ falsch ist.
$$\neg A$$
### Wahrheitstabelle
| $A$ | $\neg A$ |
| - | - |
| r | f |
| r | f |
## Konjunktion
Die Konjunktion von zwei Aussagen $A$ und $B$ ist genau dann richtig, wenn sowohl $A$ als auch $B$ richtig sind.
$$A \land B$$
### Wahrheitstabelle
| $A$ | $B$ | $A \land B$ |
| - | - | - |
| r | r | r |
| r | f | f |
| f | r | f |
| f | f | f |
## Disjunktion
Die Disjunktion von zwei Aussagen $A$ und $B$ ist genau dann richtig, wenn mindestens eine der beiden Aussagen richtig ist.
$$A \lor B$$
### Wahrheitstabelle
| $A$ | $B$ | $A \lor B$ |
| - | - | - |
| r | r | r |
| r | f | r |
| f | r | r |
| f | f | f |
## Implikation
Die Implikation von zwei Aussagen $A$ und $B$ ist nur dann falsch, wenn $A$ richtig und $B$ falsch ist.
$$A \Longrightarrow B$$
Alternative Definition als [[#Disjunktion]]
$$A \Longleftrightarrow B = (\neg A) \lor B$$
### Wahrheitstabelle
| $A$ | $B$ | $A \Longrightarrow B$ |
| - | - | - |
| r | r | r |
| r | f | f |
| f | r | r |
| f | f | r |
## Äquivalenz
Die Äquivalenz von zwei Aussagen $A$ und $B$ ist nur dann richtig, wenn $A$ gleich $B$ ist.
$$A \Longleftrightarrow B$$
### Wahrheitstabelle
| $A$ | $B$ | $A \Longleftrightarrow B$ |
| - | - | - |
| r | r | r |
| r | f | f |
| f | r | f |
| f | f | r |
# Rechenregeln für die Verknüpfungen von Aussagen
## Assoziativgesetze
$$(A \land B) \land C \Longleftrightarrow A \land (B \land C)$$
$$(A \lor B) \lor C \Longleftrightarrow A \lor (B \lor C)$$
## Kommutativgesetze
$$A \land B \Longleftrightarrow B \land A$$
$$A \lor B \Longleftrightarrow B \lor A$$
## Distributivgesetze
$$A \land (B \lor C) \Longleftrightarrow (A \land B) \lor (A \land C)$$
$$A \lor (B \land C) \Longleftrightarrow (A \lor B) \land (A \lor C)$$
## Idemptotenzgesetze
$$A \land A \Longleftrightarrow A$$
$$A \lor A \Longleftrightarrow A$$
## Absorbtionsgesetze
$$A \land (B \lor A) \Longleftrightarrow A$$
$$A \lor (B \land A) \Longleftrightarrow A$$
## Gesetze von de Morgan
$$\neg(A \land B) \Longleftrightarrow \neg A \lor \neg B$$
$$\neg(A \lor B) \Longleftrightarrow \neg A \land \neg B$$