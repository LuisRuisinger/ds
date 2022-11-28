## Vollständige Induktion
### Das Induktionsschema

>Beispiel: Eine Aussage A, die für alle $n\in\mathbb{N_0}$ gilt

##### Induktionsbasis:

>Zeige durch geeignetes Einsetzen, dass A für $n = 0$ gilt

##### Induktionsschritt:

> Sei $n\in\mathbb{N_0}$ beliebig fixiert

##### Induktionsannahme:

> A gilt für $n$

##### Induktionsbehauptung:

>  A gilt für $n+1$

##### Induktionsbeweis:

> Mathematische Umformungen um jeweils die `linke Seite` und die `rechte Seite` zu beweisen

>[!NOTE] Beispiel anhand der Gaußschen Summenformel
>Für $n\in\mathbb{N_0}$ gilt: $\sum^n_{k=0} a_k$
>
>Induktionsbasis:
>$n=0: \sum^0_{k=0}a_k=0$
>
>Induktionsschritt:
>Sei $n\in\mathbb{N_0}$ beliebig, aber fest fixiert
>
>Induktionsannahme:
>die Aussage gilt für $n:\sum^n_{k=0}a_k=a_0+...+a_k=\frac{n\cdot(n+1)}{2}$
>
>Induktionsbehauptung:
>die Aussage gilt auch für $n+1:\sum^{n+1}_{k=0}a_k=a_0+...+a_{k+1}=\frac{(n+1)\cdot(n+2)}{2}$
>
>Induktionsbeweis:
>$\sum^{n+1}_{k=0}a_k=\big(\sum^n_{k=0}a_k\big)+(n+1)=\frac{n\cdot(n+1)}{2}+(n+1)=\frac{n\cdot(n+1)}{2}+\frac{2\cdot(n+1)}{2}=\frac{n^2+3n+2}{2}=\frac{(n+1)(n+2)}{2}$

##### Rekursive Funktionen

Induktion kann auch auf rekursiven Funktionen angewendet werden:

- Rekursionsfolge statt iterativer Funktion
- es gibt ein oder mehrere Rekursionsbasen die die Basis formen








