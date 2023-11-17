# Aufgabenstellung
Seinen $A_1$, $A_2$, $A_3$, $A_4$ beliebige (nicht leere) Mengen. Man beweise die Inklusion
$$ (A_{1} \times B_{1}) \cup (A_{2} \times B_{2}) \subseteq (A_{1} \cup A_2) \times (B_{1} \cup B_{2}) $$
und geben ein Beispiel an, für das $\subset$ anstelle von $\subseteq$ steht.
# Lösung
## Aussage
$L$ ist Teilmenge von $R$. Für $L := (A_{1} \times B_{1}) \cup (A_{2} \times B_{2})$ und $R := (A_{1} \cup A_2) \times (B_{1} \cup B_{2})$.
## Annahme
$L$ ist Teilmenge von sich selbst.
## Beweis
Direkter Beweis $L \Longrightarrow R$ Ausgehend von der Annahme $L \subseteq L$.
$$
(A_{1} \times B_{1}) \cup (A_{2} \times B_{2}) \subseteq (A_{1} \times B_{1}) \cup (A_{2} \times B_{2})
$$
Dafür existiert eine Menge $X_{1}$ die Menge aller geordneten Paare $(a_{1}, b_{1})$ mit $a_{1} \in A_{1}$ und $b_{1} \in B_{1}$. Sowie eine Menge $X_{2}$ die Menge aller geordneten Paare $(a_{2}, b_{2})$ mit $a_{2} \in A_{2}$ und $b_{2} \in B_{2}$.
$$
(A_{1} \times B_{1}) \cup (A_{2} \times B_{2}) \subseteq X_{1} \cup X_{2}
$$
Die Vereinigungsmenge von $X_{1} \cup X_{2}$ ist eine Menge $X_{12}$ aller geordneten Paare $(a, b)$ mit $a \in A_{1} \land a \in A_{2}$ und $b \in B_{1} \land b \in B_{2}$.
$$ (A_{1} \times B_{1}) \cup (A_{2} \times B_{2}) \subseteq X_{12} $$
Die Menge $X_{12}$ ist gleich dem Ausdruck $A \times B$ wobei $A$ die Vereinigungsmenge von $A_1$ und $A_2$. Sowie $B$ die Vereinigungsmenge von $B_1$ und $B_2$ ist. Also ist $X_{12}$ gleichwertig zu $(A_{1} \cup A_2) \times (B_{1} \cup B_{2})$.
$$ (A_{1} \times B_{1}) \cup (A_{2} \times B_{2}) \subseteq (A_{1} \cup A_2) \times (B_{1} \cup B_{2}) $$
Somit folgt die Aussage aus der Annahme und ist bewiesen.
Ein Fall, für welchen $\subset$ anstelle von $\subseteq$ gelten würde. Wäre wenn alle vier Mengen verschiedene beliebige Mengen wären, allerdings gilt dass $A_1$ weniger Elemente enthält als $A_2$.
$$ A_{1} = \{1\}, A_{2} = \{3, 4\}, B_{1} = \{a\}, B_{2} = \{b\} $$