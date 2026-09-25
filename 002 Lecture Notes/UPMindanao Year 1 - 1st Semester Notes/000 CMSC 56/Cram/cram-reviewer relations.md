# 20-Minute Cram Reviewer: Discrete Mathematics (Relations, Digraphs, and Hasse Diagrams)

## Related notes

- [[2026-09-06 Week 1 Sets|Sets lecture note]]
- [[2026-09-14 Week 4 Relations|Relations lecture note]]
- [[cmsc56-100-practice-problems|100-problem practice bank]]

---

## 1. Cartesian Product & Basic Binary Relations

### Ordered Pairs and Tuples
* An **ordered $n$-tuple** $(a_1, a_2, \dots, a_n)$ is an ordered collection with $a_1$ as first element, $a_2$ as second, and $a_n$ as $n$-th element [2].
* A **2-tuple** is called an **ordered pair** $(a, b)$ [2]. Two ordered pairs $(a, b)$ and $(c, d)$ are equal if and only if $a = c$ and $b = d$ [2].

### Cartesian Product
* The **Cartesian product** $A \times B$ ("A cross B") is the set of all ordered pairs $(a, b)$ where $a \in A$ and $b \in B$ [2, 3]:
  $$A \times B = \{(a, b) \mid a \in A \text{ and } b \in B\}$$
* $A \times A$ is commonly written as $A^2$ [3].
* **Properties**:
  * In general, $A \times B \neq B \times A$ [3].
  * Total number of pairs: $n(A \times B) = n(A) \cdot n(B)$ [3].

### Binary Relation Definition
* A **binary relation** $R$ from $A$ to $B$ is a subset of $A \times B$ ($R \subseteq A \times B$) [3].
* Notation: $aRb$ or $xRy$ indicates $(x, y) \in R$ [3, 4].
* **Domain of $R$**: The set of all first elements in the ordered pairs of $R$ ($\subseteq A$) [4].
* **Range of $R$**: The set of all second elements in the ordered pairs of $R$ ($\subseteq B$) [4].
* **Relations on a Single Set $A$**: A relation $R \subseteq A \times A$ [3, 5].
* **Universal & Empty Relations**: For any set $A$, $\emptyset \subseteq R \subseteq A \times A$, where $\emptyset$ is the empty relation and $A \times A$ is the universal relation [5].

---

## 2. Operations on Relations

### Inverse Relation ($R^{-1}$)
* Given $R \subseteq A \times B$, the **inverse relation** $R^{-1} \subseteq B \times A$ reverses all ordered pairs [6]:
  $$R^{-1} = \{(b, a) \mid (a, b) \in R\}$$
* **Key Properties**:
  * $(R^{-1})^{-1} = R$ [6].
  * $\text{Domain}(R^{-1}) = \text{Range}(R)$ and $\text{Range}(R^{-1}) = \text{Domain}(R)$ [6].

### Composition of Relations ($R \circ S$)
* Given $R \subseteq A \times B$ and $S \subseteq B \times C$, the **composition** $R \circ S \subseteq A \times C$ is [7]:
  $$R \circ S = \{(a, c) \mid \exists b \in B \text{ such that } (a, b) \in R \text{ and } (b, c) \in S\}$$
* That is, $a(R \circ S)c$ whenever an intermediate element $b \in B$ connects $aRb$ and $bSc$ [7].

---

## 3. The Six Core Relation Properties

A relation $R$ on a set $A$ may possess the following properties:

| Property          | Formal Definition                                                   | Description / Meaning                                          |
| :---------------- | :------------------------------------------------------------------ | :------------------------------------------------------------- |
| **Reflexive**     | $\forall x \in A, xRx$ [7, 10, 13]                                  | Every element is related to itself [7, 10].                    |
| **Irreflexive**   | $\forall x \in A, (x, x) \notin R$ [8, 10, 14]                      | No element is related to itself [8, 10, 14].                   |
| **Symmetric**     | $\forall x, y \in A, xRy \implies yRx$ [8, 10, 13]                  | If $x$ is related to $y$, then $y$ is related to $x$ [8, 10].  |
| **Asymmetric**    | $\forall x, y \in A, (x, y) \in R \implies (y, x) \notin R$ [8, 10] | If $x$ is related to $y$, $y$ is never related to $x$ [8, 10]. |
| **Antisymmetric** | $\forall x, y \in A, (xRy \land yRx) \implies x = y$ [9, 10, 13]    | Two distinct elements cannot be mutually related [9, 10].      |
| **Transitive**    | $\forall x, y, z \in A, (xRy \land yRz) \implies xRz$ [9, 10, 13]   | If $xRy$ and $yRz$, then $xRz$ [9, 10].                        |

### Important Distinctions
* **Symmetric vs. Antisymmetric**: They are **not** exact opposites [11]. A relation can be both symmetric and antisymmetric, or neither [11].
* **Asymmetric vs. Antisymmetric**: Every asymmetric relation is antisymmetric [9]. However, if an antisymmetric relation contains a self-loop $(a, a)$, it cannot be asymmetric [9].

---

## 4. Classifications of Relations

### Equivalence Relation
* A relation $R$ on set $S$ is an **equivalence relation** if and only if it is **reflexive, symmetric, and transitive** [17, 18].
* **Partitions and Cells**: A partition of set $S$ subdivides $S$ into mutually disjoint, non-empty subsets called **cells** [17, 18]. An equivalence relation on $S$ induces a partition of $S$ into equivalence classes [17, 18].

### Order Relations
* **Strict Order**: Irreflexive, asymmetric, and transitive (e.g., $<$ or $>$ on numbers) [19].
* **Partial Order (Poset)**: Reflexive, antisymmetric, and transitive (e.g., $\le$, $\ge$, or $\subseteq$) [19, 20]. The pair $(A, R)$ is called a **partially ordered set** or **poset** [19].
* **Total Order (Linear Order)**: A partial order where **every** pair of elements $a, b \in A$ is comparable (either $aRb$ or $bRa$) [21, 22]. Example: $\le$ on integers [22].

---

## 5. Directed Graphs (Digraphs) & Hasse Diagrams

### Digraphs
* A relation $R$ on $A$ is modeled as a directed graph $G = (V, E)$ where $V = A$ (vertices/nodes) and $E = R$ (directed edges/arrows) [15].
* **Visualizing Properties**:
  * **Reflexive**: A self-loop exists at every node [16].
  * **Symmetric**: Every directed edge between distinct nodes has a matching return edge [16].
  * **Antisymmetric**: No two distinct nodes have edges pointing both ways [16].

### Hasse Diagrams
A Hasse diagram is a simplified visual representation of a poset $(A, R)$ constructed using four rules [23]:
1. **Undirected Edges**: All edges are drawn as simple lines without arrowheads [23].
2. **Upward Orientation**: If $xRy$ and $x \neq y$, $x$ is placed lower than $y$ in the diagram [23].
3. **No Self-Loops**: Reflexive loops $(x, x)$ are omitted [23].
4. **No Redundant Transitive Edges**: If $xRy$ and $yRz$, the transitive edge $(x, z)$ is omitted [23].
