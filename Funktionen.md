# Definition
Eine Funktion auch Abbildung genannt ist eine Teilmenge $f$ der [[Mengenlehre#Die Produktmenge|Produktmenge]] einer Definitionsmenge $D$ mit einer Wertemenge $B$. Die Wertemenge lässt sich einschränken, auf alle Paare für welche gilt, dass für jedes Element der Definitionsmenge genau ein Element der Wertemenge existiert.
$$f \subseteq D \times B | \forall x \in D: \exists! y \in B: (x, y) \in f$$
## Schreibweisen
- Einer Funktion
$$y = f(x)$$
$$x \rightarrow y$$
$$(x, y) \in f$$
- Der Abbildung der Definitionsmenge auf die Wertemenge
$$f \subseteq D \times B$$
$$f: D \rightarrow B$$
- Der Bildmenge der Funktion
$$f(D) := \{f(x) \in B | x \in D\}$$
## Eigenschaften
### Injektiv
Eine Funktion liefert nur dann das selbe Ergebnis, wenn auch die Eingangswerte gleich sind.
$$\forall x, y \in D: f(x) = f(y) \Longrightarrow x = y$$
Umgekehrt gilt, dass eine injektive Funktion für unterschiedliche Eingangswerte nicht das selbe Ergebnis liefern kann.
$$\forall x, y \in D: x \neq y \Longrightarrow f(x) \neq f(y)$$
### Surjektiv
Eine Funktion heißt surjektiv, wenn für jedes Element der Ergebnismenge ein Eingangswert der Definitionsmenge existiert.
$$\forall y \in B: \exists x \in D: b = f(x)$$
### Bijektiv
Funktion heißt bijektiv wenn diese injektiv und surjektiv ist.
## Urbildmenge
ToDo: Genauer anschauen