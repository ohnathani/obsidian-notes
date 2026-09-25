
# CMSC 56: Set Theory 30-Question Focused Practice Exam

## Related notes

- [[2026-09-06 Week 1 Sets|Sets lecture note]]
- [[Obsidian Notes/002 Lecture Notes/UPMindanao Year 1 - 1st Semester Notes/000 CMSC 56/Practice Problems/cmsc56-50-practice-problems|50-problem practice bank]]
- [[cmsc56-50-item-quiz|50-item practice quiz]]
- [[cmsc56-100-practice-problems|100-problem practice bank]]

---
## Part I: The Practice Problems

### Section A: Set Foundations and Representations (Problems 1–6)

1. **The Definition of a Set:** According to Georg Cantor's standard mathematical formulation, what is the definition of a set, and what are its components called?

2. **Membership Notation:** Let $S$ be a set. Write down the formal mathematical notation for:
   * I) An object $x$ being a member of $S$.
   * II) An object $y$ not being a member of $S$. 

3. **Roster Method Distinctness Rule:** A student writes the set of letters in the word `"DATA"` in roster form as $A = \{D, A, T, A\}$. 
   * Is this representation correct under the rules of the roster method? 
   * If not, state the rule that was violated, write down the corrected roster form, and state its cardinality $|A|$.

4. **Converting to Set-Builder Notation:** Convert the following infinite set from roster form to formal set-builder (rule) notation:
   $$S = \{3, 6, 9, 12, 15, \dots\}$$

5. **Limitations of the Rule Method:** The lecture notes mention that "There are sets which could not be described using the rule method." Explain under what conditions the rule (set-builder) method can be successfully applied to describe a set.

6. **The Logical Equivalence of Set Equality:** Your lecture notes state that two sets $A$ and $B$ are equal ($A = B$) if and only if:
   $$A \subseteq B \land B \subseteq A$$
   What is the name of this logical equivalence principle used in formal set-theoretic proofs?

---

### Section B: Set Classifications, Subsets, and Power Sets (Problems 7–14)

7. **The Empty Set Notation:** Define an empty (null or void) set, and write down both symbols used to represent it in your course slides.

8. **Set Classification - Case I:** Classify the set $W = \{0, 1, 2, 3, \dots, 1000000\}$ according to the three criteria in your slide exercise:
   * I) Is it written in Roster or Rule method?
   * II) Is it finite or infinite?
   * III) Is it a subset or not a subset of the set of integers ($\mathbb{Z}$)?

9. **Set Classification - Case II:** Classify the set $D = \{d \mid d \text{ is a letter in the English alphabet}\}$ according to the same three criteria:
   * I) Is it written in Roster or Rule method?
   * II) Is it finite or infinite?
   * III) Is it a subset or not a subset of the set of integers ($\mathbb{Z}$)?

10. **Set Classification - Case III:** Classify the set $N = \{n \mid n \text{ is a real number}\}$ according to the same three criteria:
    * I) Is it written in Roster or Rule method?
    * II) Is it finite or infinite?
    * III) Is it a subset or not a subset of the set of integers ($\mathbb{Z}$)?

11. **Equivalent Sets and Bijections:** If there exists a one-to-one correspondence (bijection) between two sets $A$ and $B$, what term is used to describe their relation, and what notation is written?

12. **Subsets vs. Element Membership:** Let $X = \{1, \{2\}\}$. State whether each of the following statements is **true** or **false** and justify your reasoning mathematically:
    * I) $\{2\} \in X$
    * II) $\{2\} \subseteq X$
    * III) $2 \in X$

13. **Proper Subset Criteria:** If $A$ is a subset of $B$ and there is at least one element of $B$ which is not an element of $A$, what is the relationship between $A$ and $B$ called, and how is it written?

14. **Power Set Cardinality and Listing:** Define a power set $\mathcal{P}(A)$ (or $P^A$). If $A = \{\emptyset, a\}$, list all elements of $\mathcal{P}(A)$ explicitly and state its cardinality $|\mathcal{P}(A)|$.

---

### Section C: Basic Set Operations and Cartesian Products (Problems 15–23)

15. **Complement Identity Simplifications:** Using the basic properties of set complements under a universal set $U$, simplify the following expressions:
    * I) $(A^c)^c$
    * II) $U^c$
    * III) $\emptyset^c$

16. **Set Difference Definition:** Define set difference $B - A$ in words, and state what informal english phrase is commonly used to describe this operation.

17. **Universal Operations with Difference:** For any set $A$ inside a universal set $U$, simplify the following operations:
    * I) $U - A$
    * II) $A - \emptyset$
    * III) $A - A$

18. **Basic Union and Intersection:** Let $A = \{a, b, c, d\}$ and $B = \{c, d, e\}$. Find:
    * I) $A \cup B$
    * II) $A \cap B$

19. **Disjoint Sets:** What does it mean mathematically if two sets $A$ and $B$ are disjoint? Write down the exact defining set equation.

20. **The Cartesian Product:** Define the Cartesian product $A \times B$ in formal set-builder notation using ordered pairs.

21. **Cartesian Product Equality Conditions:** Under what specific mathematical conditions will the Cartesian products $A \times B$ and $B \times A$ be equal?

22. **Calculating Cartesian Products:** Let $A = \{1, 2\}$ and $B = \{x, y\}$. List all elements of:
    * I) $A \times B$
    * II) $B \times A$

23. **Product Cardinality Theorem:** If $|A| = 4$ and $|B| = 3$, what is the cardinality of the Cartesian product $|A \times B|$?

---

### Section D: Laws of Sets, Venn Diagrams, and Partitions (Problems 24–30)

24. **De Morgan's Laws:** State both of De Morgan's Laws using set theory notation.

25. **Absorption Laws:** State the two algebraic set identities that comprise the Absorption Laws.

26. **Idempotent and Domination Laws:** Write down:
    * I) The Idempotent Laws for both union and intersection.
    * II) The Domination (Null) Laws for both union and intersection.

27. **Venn Diagram Representation:** In a standard Venn diagram:
    * I) How is the universal set $U$ represented?
    * II) How are the subsets of $U$ represented?

28. **Methods of Proving Set Equality:** Your lecture slides list five distinct methods to prove or disprove a theorem on sets. List all **five methods**.

29. **Set Partition Criteria:** A collection of nonempty sets $\{A_1, A_2, \dots, A_n\}$ is a partition of set $A$ if and only if they satisfy two core conditions. State these two conditions in mathematical notation.

30. **Partition Proof Exercise:** Prove whether the set of even integers $E = \{2k \mid k \in \mathbb{Z}\}$ and the set of odd integers $O = \{2k + 1 \mid k \in \mathbb{Z}\}$ form a valid partition of the set of integers $\mathbb{Z}$.

---

## Part II: Complete Step-by-Step Solutions

### Solutions for Section A (Problems 1–6)

1. **Set Definition:**
   * **Answer:** A set is an **unordered collection of well-defined objects**. The objects that belong to a set are called its **elements**.
   * **Grounding:** Slide 3: *"A set is a collection of well-defined objects."* Slide 4: *"Objects that belong to a set are called elements of that particular set."*

2. **Membership Notation:**
   * **Answer:** 
     * I) $x \in S$
     * II) $y \notin S$ (or $y \notin S$)
   * **Grounding:** Slide 4: *"Notation for element: $\in$. Notation for not an element: $\notin$."*

3. **Roster Method Distinctness Rule:**
   * **Answer:** **No, this representation is incorrect.** 
   * **Rule Violated:** The roster method requires that **all elements must be distinct**. The letter 'A' is written twice in $\{D, A, T, A\}$, which violates this rule.
   * **Corrected Roster Form:** $A = \{D, A, T\}$ (or any permutation since order does not matter).
   * **Cardinality:** $|A| = 3$.
   * **Grounding:** Slide 5: *"In the roster method, the elements are enumerated, separated by commas and enclosed by braces. Important note: The elements must be distinct!"*

4. **Converting to Set-Builder Notation:**
   * **Answer:** $S = \{x \in \mathbb{Z}^+ \mid x \text{ is a multiple of } 3\}$ (or $\{x \in \mathbb{N} \mid x > 0 \land 3 \mid x\}$).
   * **Grounding:** Slide 5: *"In the rule method, the elements are not listed individually. Instead, membership in the set is defined by stating a descriptive phrase that gives the common property..."*

5. **Limitations of the Rule Method:**
   * **Answer:** The rule method can be used **as long as there is a property that will describe each element of the set**. If no such common, characterizing property exists among the collection of objects, the rule method cannot be used.
   * **Grounding:** Slide 6: *"Note: There are sets which could not be described using the rule method. Remember: The rule method can be used as long as there is a property that will describe each element of the set."*

6. **Logical Equivalence of Set Equality:**
   * **Answer:** **The Principle of Double Inclusion** (or Mutual Inclusion).
   * **Grounding:** Slide 8: *"Observe that $A = B$ if and only if $A$ is a subset of $B$ and $B$ is a subset of $A$."*

---

### Solutions for Section B (Problems 7–14)

7. **Empty Set:**
   * **Answer:** An empty set is a set **having no elements**. It is denoted by **$\emptyset$** or **$\{\}$**.
   * **Grounding:** Slide 6: *"Sets having no elements are called empty or null sets. An empty set is denoted by $\emptyset$ or $\{\}$."*

8. **Set Classification - Case I ($W$):**
   * **Answer:** 
     * I) **Roster method** (elements are listed explicitly).
     * II) **Finite** (the elements can be completely listed; cardinality is $1000001$).
     * III) **Subset** of $\mathbb{Z}$ (yes, $W \subseteq \mathbb{Z}$ because every element in $W$ is an integer).
   * **Grounding:** Slide 9 (Exercise 1) & Slide 10 (Answer to Exercise 1): *"Roster, finite, yes"*.

9. **Set Classification - Case II ($D$):**
   * **Answer:** 
     * I) **Rule method** (membership is defined by a descriptive property).
     * II) **Finite** (there are exactly 26 letters in the English alphabet, so a complete list is possible).
     * III) **Not a subset** of $\mathbb{Z}$ (no, $D \not\subseteq \mathbb{Z}$ because English letters are not integers).
   * **Grounding:** Slide 9 (Exercise 3) & Slide 10 (Answer to Exercise 3): *"- Rule, finite, no"*.

10. **Set Classification - Case III ($N$):**
    * **Answer:** 
      * I) **Rule method** (membership is defined by a property).
      * II) **Infinite** (it is impossible to write down a complete list of all real numbers).
      * III) **Not a subset** of $\mathbb{Z}$ (no, $N \not\subseteq \mathbb{Z}$ because real numbers like $\pi$ or $0.5$ are not integers).
    * **Grounding:** Slide 9 (Exercise 4) & Slide 10 (Answer to Exercise 4): *"- Rule, infinite, no"*.

11. **Equivalent Sets:**
    * **Answer:** **Equivalent sets**, written as **$A \approx B$**.
    * **Grounding:** Slide 7: *"Sets $A$ and $B$ are equivalent sets if and only if there exists a one-to-one correspondence between sets $A$ and $B$. If $A$ and $B$ are equivalent, we write $A \approx B$."*

12. **Subsets vs. Element Membership ($X = \{1, \{2\}\}$):**
    * **Answer:**
      * I) **True.** The object $\{2\}$ is enclosed in the outer braces and separated by a comma, meaning it is a direct element of $X$.
      * II) **False.** For $\{2\} \subseteq X$ to be true, the element inside the subset (the number $2$) must be a member of $X$. However, $2 \notin X$ (it only exists nested inside the element $\{2\}$).
      * III) **False.** The number $2$ is not a direct, top-level element of $X$; only $1$ and $\{2\}$ are.
    * **Grounding:** Slide 7: Definition of a subset requires: *"Set $A$ is a subset of $B$ if and only if each element of $A$ is a member of $B$."*

13. **Proper Subset:**
    * **Answer:** **Proper subset**, written as **$A \subset B$**.
    * **Grounding:** Slide 8: *"If $A$ is a subset of $B$ and there is at least one element of $B$ which is not an element of $A$, then $A$ is a proper subset of $B$. If $A$ is a proper subset of $B$, we write $A \subset B$."*

14. **Power Set Cardinality and Listing ($A = \{\emptyset, a\}$):**
    * **Answer:** The power set is the set of all subsets of $A$. 
      * Subsets of $A$: $\emptyset$, $\{\emptyset\}$, $\{a\}$, $\{\emptyset, a\}$.
      * **Power Set:** $\mathcal{P}(A) = \{\emptyset, \{\emptyset\}, \{a\}, \{\emptyset, a\}\}$.
      * **Cardinality:** $|\mathcal{P}(A)| = 2^n = 2^2 = 4$.
    * **Grounding:** Slide 8: *"The set whose elements are the subsets of a set $A$ is called the power set of $A$ denoted by $P^A$ or $\mathcal{P}(A)$."*

---

### Solutions for Section C (Problems 15–23)

15. **Complement Identity Simplifications:**
    * **Answer:** 
      * I) $(A^c)^c = A$ (Double Complement/Involution Law)
      * II) $U^c = \emptyset$ (0/1 Complement Law)
      * III) $\emptyset^c = U$ (0/1 Complement Law)
    * **Grounding:** Slide 12: *"Some properties of the complement: $\emptyset^c = U$, $U^c = \emptyset$, $(A^c)^c = A$."*

16. **Set Difference:**
    * **Answer:** The set of elements in $B$ which are not elements of $A$. It is informally called **"$B$ but not $A$"**.
    * **Grounding:** Slide 12: *"The set difference of $B$ and $A$, also called 'B but not A', is the set of elements in $B$ which are not elements of $A$."*

17. **Universal Operations with Difference:**
    * **Answer:** 
      * I) $U - A = A^c$
      * II) $A - \emptyset = A$
      * III) $A - A = \emptyset$
    * **Grounding:** Slide 13: *"Some properties of the set difference: $U - A = A^c$, $A - \emptyset = A$, $A - A = \emptyset$."*

18. **Basic Union and Intersection:**
    * **Answer:** 
      * I) $A \cup B = \{a, b, c, d, e\}$ (all elements in either $A$, $B$, or both).
      * II) $A \cap B = \{c, d\}$ (elements common to both sets).
    * **Grounding:** Slide 13: Union definition: *"elements in $A$ or in $B$."* Slide 14: Intersection definition: *"elements that are common to both $A$ and $B$."*

19. **Disjoint Sets:**
    * **Answer:** Two sets $A$ and $B$ are disjoint if they share no common elements, meaning:
      $$A \cap B = \emptyset$$
    * **Grounding:** Slide 14: *"Two sets $A$ and $B$ are disjoint if: $A \cap B = \emptyset$."*

20. **The Cartesian Product:**
    * **Answer:** $A \times B = \{(a, b) \mid a \in A \land b \in B\}$
    * **Grounding:** Slide 10: *"The Cartesian product of $A$ and $B$, denoted by $A \times B$ is the set of all ordered pairs $(a, b)$ where $a \in A$ and $b \in B$."*

21. **Cartesian Product Equality Conditions:**
    * **Answer:** $A \times B = B \times A$ if and only if **$A = \emptyset$**, **$B = \emptyset$**, or **$A = B$**.
    * **Grounding:** Slide 11: *"NOTE: The Cartesian Products $A \times B$ and $B \times A$ are not equal, unless $A = \emptyset$ or $B = \emptyset$ or $A = B$."*

22. **Calculating Cartesian Products ($A = \{1, 2\}, B = \{x, y\}$):**
    * **Answer:** 
      * I) $A \times B = \{(1, x), (1, y), (2, x), (2, y)\}$
      * II) $B \times A = \{(x, 1), (x, 2), (y, 1), (y, 2)\}$
    * **Grounding:** Slide 10: Definition of $A \times B$ as ordered pairs.

23. **Product Cardinality Theorem:**
    * **Answer:** $|A \times B| = |A| \cdot |B| = 4 \cdot 3 = \mathbf{12}$.
    * **Grounding:** Slide 11 (Exercise): Verified by the general Cartesian product cardinality theorem.

---

### Solutions for Section D (Problems 24–30)

24. **De Morgan's Laws:**
    * **Answer:** 
      1. $(A \cup B)^c = A^c \cap B^c$
      2. $(A \cap B)^c = A^c \cup B^c$
    * **Grounding:** Slide 15: De Morgan's Law properties.

25. **Absorption Laws:**
    * **Answer:**
      1. $A \cup (A \cap B) = A$
      2. $A \cap (A \cup B) = A$
    * **Grounding:** Slide 17: Absorption Law properties.

26. **Idempotent and Domination Laws:**
    * **Answer:**
      * I) **Idempotent Laws:** 
        * $A \cup A = A$
        * $A \cap A = A$
      * II) **Domination Laws:**
        * $A \cup U = U$
        * $A \cap \emptyset = \emptyset$
    * **Grounding:** Slide 16 & Slide 17.

27. **Venn Diagram Representation:**
    * **Answer:** 
      * I) Universal set $U$ is represented by the **interior of a rectangle**.
      * II) Subsets of $U$ are represented by **any closed plane figures** (e.g., circles, triangles, or squares).
    * **Grounding:** Slide 18: *"The universal set is represented by the interior of a rectangle. The subsets of U is represented by any closed plane figures like circle, triangle, or square"*.

28. **Methods of Proving Set Equality:**
    * **Answer:** 
      1. Proof using previously proven theorems.
      2. Proof using the Indirect Method / Contradiction.
      3. Proof using Venn Diagrams.
      4. Proof using Set-membership Tables.
      5. Disproof by Counterexample.
    * **Grounding:** Slide 18 & Slide 19: *"There are many ways to prove a theorem on sets..."*

29. **Set Partition Criteria:**
    * **Answer:** A collection of nonempty sets $\{A_1, A_2, \dots, A_n\}$ is a partition of $A$ if and only if:
      1. $A = A_1 \cup A_2 \cup \dots \cup A_n$
      2. $A_1, A_2, \dots, A_n$ are mutually disjoint ($A_i \cap A_j = \emptyset$ for all $i \neq j$).
    * **Grounding:** Slide 23: Partition of a Set slide.

30. **Partition Proof Exercise:**
    * **Answer:** **Yes, they form a valid partition of $\mathbb{Z}$.**
    * **Proof:**
      1. **Union Condition:** Every integer $z \in \mathbb{Z}$ is of the form $2k$ (even) or $2k + 1$ (odd) for some $k \in \mathbb{Z}$. Thus, the union of even and odd integers equals the entire set of integers: $E \cup O = \mathbb{Z}$.
      2. **Disjoint Condition:** No integer can be both even and odd simultaneously. If there were an integer $x \in E \cap O$, then $x = 2k_1$ and $x = 2k_2 + 1$ for integers $k_1, k_2$. This implies $2k_1 = 2k_2 + 1 \implies 2(k_1 - k_2) = 1 \implies k_1 - k_2 = 0.5$, which is a contradiction since the difference of two integers must be an integer. Thus, $E \cap O = \emptyset$.
      Since both conditions are satisfied and neither set is empty, they form a valid partition of $\mathbb{Z}$.
    * **Grounding:** Slide 24: *"Exercise: The set of even and odd integers"*.
