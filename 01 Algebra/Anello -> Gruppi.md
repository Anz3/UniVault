($\mathbb{Z},+. \cdot$)
- ($Z,+$) Gruppo **Abeliano** (+ è comm.)
- è **associativa** (ab)c=a(bc)$\forall a,b,c\in Z$
- **Distributiva** di $\\cdot$ Rispetto alla +. a(b+c)=(ab)+(ac) (b+c)a=ba+ca   $\forall a,b,c,\in Z$
- $\exists 1 \in Z $ neutra rispetto a  $a \cdot 1=a$   $1  \cdot a=a $  $\forall a \in Z$

>[!info] Anello
>Un anello è un insieme con due operazione binarie (A,+,$\cdot$) **Tale che:**
>- (A,+) Gruppo abelliano
>	+ è ass,  $\exists$  Elemento $O_{a},\forall a \in A  $\exists$  -a$ T.C. $(-a)+a=O_{A}$ ,$ a+b=b+a \forall{a},b\inA$
>- $\cdot$ è associativa $(a\cdot b)c = a(bc)\forall a,b,\in a$
>- $(A,+.\cdot)$ Anello è commutativo se $\cdot$ è commutativa
>- $(A,+,\cdot)$ anello è unitario se $\exists$ 

#### Esempi:
![[Pasted image 20241217115326.png]]
![[Pasted image 20241217114949.png]]

>[!info] Corpo
>Un anello $(A,+,\cdot)$ unitario è detto **corpo** se ogni $a \in A-$ {o} è inverso rispetto A $\cdot$ cioè $\exists a^{-1} \forall a\in A-$ {o}.
>Se inoltre $\cdot$ è comm lo chiamiamo **campo**

#### Esempi:
![[Pasted image 20241217120230.png]]
$(A,+,\cdot)$ Anello
$a\cdot O_{A}=O_{A}$ <- (a buon senso ci aspettiamo questo)
come si comporta un elemento speciale rispetto alla moltiplicazione?
discende dagli assiomi 
$a(O_{A}+O_{A}=a \cdot O_{A})$
$a \cdot(O_{A}+a \cdot O_{A} )$
$t=a \cdot O_{A}$
$t=t+t$
$t-t=t+t-t$



$(a+ib)$ $(a+ib)$  0a

--- 
# Appunti di Matematica: Anelli e Corpi chatgpittato

## $(\mathbb{Z},+,\cdot)$

- **$(\mathbb{Z},+)$ è un gruppo Abeliano:**
  - $+$ è commutativa.
  - $+$ è associativa: $(a+b)+c = a+(b+c) \quad \forall a,b,c \in \mathbb{Z}$.
  - Esiste un elemento neutro rispetto a $+$: $0 \in \mathbb{Z}$ tale che $a+0=a$.
  - Ogni elemento ha un opposto rispetto a $+$: $\forall a \in \mathbb{Z}, \exists -a$ tale che $a+(-a)=0$.

- **$\cdot$ è associativa:**
  - $(a\cdot b)\cdot c = a\cdot(b\cdot c) \quad \forall a,b,c \in \mathbb{Z}$.

- **Distributiva di $\cdot$ rispetto a $+$:**
  - $a(b+c)=ab+ac$
  - $(b+c)a=ba+ca \quad \forall a,b,c \in \mathbb{Z}$.

- **Elemento neutro rispetto a $\cdot$:**
  - Esiste $1 \in \mathbb{Z}$ tale che $a \cdot 1 = a$ e $1 \cdot a = a \quad \forall a \in \mathbb{Z}$.

---

## Definizione di Anello

Un anello è un insieme $(A,+,\cdot)$ con due operazioni binarie tale che:

- **$(A,+)$ è un gruppo Abeliano:**
  - $+$ è associativa.
  - Esiste un elemento neutro $O_A \in A$ tale che $a + O_A = a$.
  - Ogni elemento ha un opposto: $\forall a \in A, \exists -a$ tale che $a + (-a) = O_A$.
  - $+$ è commutativa: $a+b = b+a \quad \forall a,b \in A$.

- **$\cdot$ è associativa:**
  - $(a\cdot b)c = a(bc) \quad \forall a,b,c \in A$.

- **Ulteriori proprietà:**
  - L'anello è commutativo se $\cdot$ è commutativa.
  - L'anello è unitario se esiste un elemento neutro rispetto a $\cdot$.

---

## Definizione di Corpo

Un anello unitario $(A,+,\cdot)$ è detto **corpo** se ogni elemento diverso da $O_A$ ha un inverso rispetto a $\cdot$, cioè:

- $\forall a \in A - \{O_A\}, \exists a^{-1}$ tale che $a\cdot a^{-1} = 1$.

Se inoltre $\cdot$ è commutativa, il corpo è detto **campo**.

---

## Esempio Importante

Proprietà speciale dell'elemento neutro $O_A$ rispetto alla moltiplicazione:

\[
 a \cdot O_A = O_A \quad \text{(per buon senso e dagli assiomi)}
\]

Dimostrazione:

\[
 a \cdot (O_A + O_A) = a \cdot O_A
\]

\[
 a \cdot O_A + a \cdot O_A = a \cdot O_A
\]

Pongo $t = a \cdot O_A$:

\[
 t = t + t
\]

\[
 t - t = t + t - t
\]

Quindi $t = O_A$, quindi $a \cdot O_A = O_A$.

---

### Nota sui Numeri Complessi

Se consideriamo $(a+ib)(a+ib)$, possiamo sviluppare ulteriori proprietà considerando l'insieme dei numeri complessi.
