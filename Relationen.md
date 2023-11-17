# Definition
Als Relation wird eine Teilmenge des [[Mengenlehre#Die Produktmenge|kartesischen Produkts]] zweier beliebiger Mengen $A$ und $B$ bezeichnet. Für den Fall, dass gilt $A = B$ wird die Relation auch als Relation auf $A$ bezeichnet.
$$R \subseteq A \times B$$
# Eigenschaften von Relationen
Eine Relation $R$ auf $A$ kann folgende Eingeschaften aufweisen.
- Reflexiv, wenn für jedes Element der Menge $A$ eine Releation des Elements mit sich selbst existiert.
  $$\forall x \in A: xRx$$
- Symetrisch, wenn für jedes geordnete Paar zweier Elemente aus $A$ eine Relation $xRy$ sowie eine umgekehrte Variante $yRx$ dieser Relation existiert.
  $$\forall x, y \in A: xRy \in R \land yRx \in R$$
  Somit lässt sich sagen, dass bei einer symetrischen Relation auf $A$, Für jede Relation $xRy$ auch eine Relation $yRx$ existieren muss.
  $$\forall x, y \in A: xRy \Longrightarrow yRx$$
- Transitiv, wenn für jedes geordnete Paar aus drei beliebigen Elementen der Menge $A$ eine Relation besteht.
  $$\forall x, y, z \in A: xRy \land yRz \land xRz$$
  Somit lässt sich sagen, dass bei einer transitiven Relation auf die Menge $A$ für jede Relation von $x$ zu $y$ für welche auch eine Relation von $y$ zu $z$ existiert. Auch eine Relation von $x$ zu $z$ existieren muss.
  $$\forall x, y, z \in A: (xRy \land yRz) \Longrightarrow xRz$$
- Symetrisch, wenn
- Asymetrisch, wenn