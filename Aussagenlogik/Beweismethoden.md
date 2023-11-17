# Direkter Beweis
Beweis mittels [[Aussagenlogik#Implikation|Implikation]]. Um eine Aussage $B$ zu beweisen wird von einer bereits bewiesenen Aussage $A$ ausgegangen. Aus dieser Aussage $A$ wird die Aussage $B$ gefolgert. Ist somit $A$ richtig, was die Annahme ist und $A \Rightarrow B$ richtig. Dann ist $B$ bewiesen.
## Beispiel
### Aussage
Wenn $k$ eine gerade Zahl ist, ist auch $k^2$ eine gerade Zahl. Das bedeuet aus $A$ folgt $B$ also $A \Rightarrow B$ mit $A$ als $k$ ist eine gerade Zahl und $B$ als $k^2$ ist eine gerade Zahl.
### Annahme
Eine gerade Zahl ist eine durch zwei teilbare, natürliche Zahl $\frac{k}{2} = n$ für $n \in \mathbb{N}$ daraus folgt $k = 2n$.
### Beweis
Direkter Beweis $A \Rightarrow B$.
$$ \begin{multline}
\text{k ist eine gerade zahl } \newline
\Rightarrow k = 2n \newline
\Rightarrow k^{2} = (2n)^{2} \newline
\Rightarrow k^{2} = 4n^{2} \newline
\Rightarrow k^{2} = 2 * (2n^{2}) \newline
\text{$k^2$ ist eine gerade Zahl}
\end{multline} $$
# Indirekter Beweis
Beweis mittels [[Aussagenlogik#Implikation|Implikation]]. Anstelle $B$ aus $A$ zu folgern, kann auch nicht $A$ aus nicht $B$ gefolgert werden $\neg B \Rightarrow \neg A$.
## Beispiel
### Aussage
Wenn $k^2$ eine gerade Zahl ist, ist auch $k$ eine gerade Zahl. Das bedeutet aus $A$ folgt $B$ also $A \Rightarrow B$ mit $A$ als $k^2$ ist eine gerade Zahl und $B$ als $k$ ist eine gerade Zahl.
### Annahme
Eine ungerade Zahl ist eine gerade Zahl plus Eins. $k = 2n + 1$ für $n \in \mathbb{N}_{0}$.
### Beweis
Indirekter Beweis: $\neg B \Rightarrow \neg A$
$$ \begin{multline}
\text{$k$ ist eine ungerade Zahl} \newline
\Rightarrow k = 2n + 1 \newline
\Rightarrow k^{2} = (2n + 1)^{2} \newline
\Rightarrow k^{2} = 4n^{2} + 4n + 1 \newline
\text{$k^2$ ist eine ungerade Zahl}
\end{multline} $$
Da $4n^{2}$ und $4n$ eine gerade Zahl ist und zwei gerade Zahlen plus eins eine ungerade Zahl ergibt. Ist $\neg B \Rightarrow \neg A$ richtig. Somit ist auch $A \Rightarrow B$ richtig und $B$ bewiesen.
# Wiederspruchsbeweis
Um eine Aussage $B$ zu beweisen, kann ausgehend von einer richtigen Aussage $A$, unter Annnahme das die Aussage $B$ falsch ist, ein Wiederspruch hergeleitet werden. Dieser Wiederspruch zeigt somit das die Annahme $A$ richtig und $B$ falsch nicht zutreffen kann. Somit kann $B$ nicht falsch sein. Es ist also bewiesen das $B$ richtig sein muss.
## Beispiel
### Aussage
Die Wurzel aus zwei ist keine rationale Zahl.
### Annahme
Es gibt eine rationale Zahl $r = \frac{p}{q} = \sqrt{2}$. Da Wurzel zwei größer Null ist, sind $p, q \in \mathbb{N}$.
### Beweis
Die Annahme lässt sich wie folgt umschreiben.
$$\left( \frac{p}{q} \right)^{2} = 2$$
Sind $p, q$ gerade Zahlen, können diese so lange miteinander gekürzt werden, bis entweder im Zähler oder im Nenner eine gerade Zahl steht. (Sind nicht beides gerade Zahlen, steht entweder im Nenner oder im Zähler eine ungerade Zahl). Somit, wenn die Annahme wahr ist, existiert ein Fall für welchen $p, q$ nicht gerade sind.
$$ \begin {multline}
\left( \frac{p}{q} \right)^{2} = 2 \newline
\Rightarrow \frac{p^2}{q^2} = 2 \newline
\Rightarrow p^{2} = 2q^{2}
\end {multline} $$
Da $q$ eine natürliche Zahl ist und somit $q^2$ eine natürliche Zahl ist, ist  $p^2$ eine gerade Zahl. Daraus folgt dass auch $p$ eine gerade Zahl ist. Somit lässt sich $p$ durch $2n$ mit $n \in \mathbb{N}$ ersetzen.
$$ \begin {multline}
(2n)^{2} = 2q^{2} \newline
\Rightarrow 4n^{2} = 2q^{2} \newline
\Rightarrow 2n^{2} = q^{2}
\end {multline} $$
Da $n$ eine natürliche Zahl ist, ist $2n^2$ eine gerade Zahl. Somit ist $q^2$ ebenfalls eine gerade Zahl. Daraus folgt dass auch $q$ eine gerade Zahl ist. Hier findet sich nun ein Wiederspruch, da von einem Fall, bei welchem $p$ oder $q$ eine ungerade Zahl ist ausgegangen wurde. Somit ist die Annahme falsch und die Aussage richtig.