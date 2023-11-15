# Definition
Eine Menge ist eine Zusammenfassung von endlich oder unendlich vielen Elementen. Eine Menge wird durch zwei geschweifte Klammern dargestellt. Die Elemente einer Menge werden mit Kommas getrennt zwischen diese Klammern geschrieben.
$$\{1, 2, 3\}$$
Für eine Menge kann auch ein Platzhalter definiert werden. Für diesen werden gewöhnlich Großbuchstaben verwendet.
$$M := \{1, 2, 3\}$$
Anstelle alle Elemente einer Menge aufzulisten, kann eine Menge auch Anhand einer Eigenschaft definiert werden.
$$M := \{x | x \text{ hat Eigenschaft}\}$$
## Die Leere-Menge
ist eine Menge ohne Elemente. Sie wird durch zwei leere geschweifte Klammern $\{\}$ oder einen durchgestrichenen Kreis $\emptyset$ dargestellt.
# Mengenoperatoren
## Gleiche Menge
Eine Menge A ist gleich einer anderen Menge B wenn alle Elemente von A auch in B sind und alle Elemente von B auch in A sind.
$$A = B$$
## Die Teilmenge
einer Menge A ist eine Menge B von welcher alle Elemente auch in A enthalten sind.
$$B \subseteq A$$
Es gilt:
- Jede Menge ist eine Teilmenge von sich selbst.
- Eine Teilmenge jeder Menge ist die [[#Die Leere-Menge|Leere-Menge]].
## Die Schnittmenge
oder Durchschnittsmenge von zwei Mengen A und B enthält alle Elemente, die sowohl in A als auch B enthalten sind.
$$A \cap B := \{x: x \in A \land x \in B\}$$
Falls $A \cap B = \emptyset$ gilt, werden die beiden Mengen als disjunkt bezeichnet.
Die Schnittmenge kann auch aus mehr als zwei Mengen gebildet werden.
$$A_1 \cap A_2 \cap ... A_n = \overset{n}{\underset{i = 1}{\bigcap}} A_i$$
## Die Vereinigungsmenge
von zwei Mengen A und B umfasst alle Elemente, die zu A oder B gehören.
$$A \cup B := \{x: x \in A \lor x \in B\}$$
Die Vereinigungsmenge kann auch aus mehr als zwei Mengen gebildet werden.
$$A_1 \cup  A_2 \cup ... \cup A_n = \overset{n}{\underset{i = 1}{\bigcup}} A_i$$
## Die Differenzmenge
zweier Mengen A und B enthält diejenigen Elemente von A, die nicht zur Menge B gehören.
$$A \setminus B := \{x: x \in A \land x \notin B\}$$
## Die Komplementmenge
einer Menge A bezüglich einer beliebigen Obermenge X besteht aus allen Elementen vom X, welche nicht in der Menge A enthalten sind.
$$\overline{A} := \{x: x \in X \land x \notin A\}$$
Alternative Definition mit [[#Die Differenzmenge|Differenzmenge]]:
$$\overline{A} := X \setminus A$$
Anstelle von $\overline{A}$ kann auch die Bezeichnung $A^{c}$ verwendet werden.
## Die Symetrische Differenz
von zwei Mengen A und B besteht aus allen Elementen, welche zu genau einer der beiden Mengen gehören.
$$A \bigtriangleup B := (A \cup B) \setminus (A \cap B)$$
## Die Produktmenge
von zwei Mengen A und B ist die Menge aller (geordneten (ToDo: hier Definition verlinken)) Paare aller Elemente aus A und B.
$$A \times B := \{(a; b): a \in A, b \in B\}$$
Die Produktmenge kann auch für mehr als zwei Mengen gebildet werden. Dabei entsteht die Menge aller geordneten Tupel der Länge n.
$$A_1 \times A_2 \times ... \times A_n = (a_1; a_2; ... ; a_n: a_1 \in A_1, a_2 \in A_2; ... ; a_n \in A_n)$$
Wird die Produktmenge aus $n$ gleichen Mengen gebildet lässt sich auch $A^n$ schreiben.
### Beispiel
Es existieren die beiden Mengen $A := \{0, 1\}$ und $B := \{2\}$. Im folgenden wird die Produktmenge aus A unb B gebildet.
$$A \times B = \{(0; 2), (1; 2)\}$$
Zu beachten ist dabei, das dass erste Element eines Paares immer aus A und das zweite Element eines Paares immer aus B stammt.
## Die Potenzmenge
ist die Menge aller Teilmengen einer Menge $A := \{a, b\}$.
$$P(A) = \{\emptyset, \{a\}, \{b\}, \{a, b\}\}$$
Hat die Menge A genau n Elemente, so enthält $P(A)$ genau $2^n$ Elemente (Mengen) oder $P(A)$ enthält $2^{|A|}$ Elemente oder $|P(A)| = 2^{|A|}$.
# Rechenregeln für Mengen
## Assoziativgesetze
$$(A \cap B) \cap C = A \cap (B \cap C)$$
$$(A \cup B) \cup C = A \cup (B \cup C)$$
## Kommutativgesetze
$$A \cap B = B \cap A$$
$$A \cup B = B \cup A$$
## Distributivgesetze
$$A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$$
$$A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$$
## Idempotenzgesetze
$$A \cap A = A$$
$$A \cup A = A$$
## Absorptionsgesetze
$$A \cap (B \cup A) = A$$
$$A \cup (B \cap A) = A$$
## Schneiden mit Leerer Menge
$$A \cap \emptyset = \emptyset$$
$$A \cup \emptyset = A$$
## Schneiden mit Obermenge
Hierfür gilt: $A \subset M$
$$A \cap M = A$$
$$A \cup M = M$$
## Komplementgesetze
$$A \cap \overline{A} = \emptyset$$
Hierfür gilt: $\overline{A} = \{x: x \notin M\}$
$$A \cup M = M$$
## Gesetze von de Morgan
$$\overline{A \cap B} = \overline{A} \cup \overline{B}$$
$$\overline{A \cup B} = \overline{A} \cap \overline{B}$$
$$\overline{ \overset{n}{ \underset{i = 1}{\bigcap} } A_{i} } = \overset{n}{ \underset{i = 1}{\bigcap} } \overline{ A_{i} }$$
$$\overline{ \overset{n}{ \underset{i = 1}{\bigcup} } A_{i} } = \overset{n}{ \underset{i = 1}{\bigcup} } \overline{ A_{i} }$$