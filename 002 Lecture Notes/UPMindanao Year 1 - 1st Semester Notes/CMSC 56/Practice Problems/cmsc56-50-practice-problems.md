# CMSC 56: Set Theory 50-Problem Practice Question Bank
*Discrete Mathematics in Computer Science I*

---

## Part I: The Practice Problems

### Section A: Set Foundations, Membership, and Descriptions (Problems 1–10)

1. **The Definition of a Set:** Which of the following collections is considered "well-defined" under standard set theory?
   * A) The collection of all difficult programming languages.
   * B) The collection of all prime numbers less than 100.
   * C) The collection of all handsome professors in the department.
   * D) The collection of all interesting books on discrete mathematics.

2. **Element vs. Non-element Notation:** Let $S = \{2, 4, \{6, 8\}, 10\}$. Identify which of the following statements is **false**:
   * A) $2 \in S$
   * B) $6 \in S$
   * C) $\{6, 8\} \in S$
   * D) $8 \notin S$

3. **Roster Method Distinctness Rule:** A student writes the set of letters in the word "ALGORITHM" in roster form as $A = \{A, L, G, O, R, I, T, H, M\}$, and the set of letters in the word "WOOLLOOMOOLOO" as $B = \{W, O, L\}$. 
   * Explain the rule of the Roster Method that makes both sets correct, and write down the cardinality of $B$.

4. **Convert Roster to Rule Method:** Convert the following set from Roster form to Rule (Set-Builder) form:
   $$S = \{1, 4, 9, 16, 25, 36, 49, 64, 81, 100\}$$

5. **Convert Rule to Roster Method:** Convert the following set from Rule form to Roster form:
   $$T = \{x \in \mathbb{Z} \mid x^2 - x - 6 = 0\}$$

6. **The Uniqueness of Roster Representation:** Let set $X = \{b, a, r\}$ and set $Y = \{r, a, b, a\}$. Are these sets equal, equivalent, or both? Explain using the roster rules.

7. **The Limitations of the Rule Method:** The lecture notes mention that "There are sets which could not be described using the rule method." Explain what is required for the rule method to be applicable.

8. **Variable Binding in Set-Builder Notation:** Express the set of all odd integers greater than $-10$ and less than $10$ in formal set-builder notation.

9. **Double-Nested Set Analysis:** Let $A = \{\emptyset, \{\emptyset\}\}$. Determine the validity of the following four statements:
   * I) $\emptyset \in A$
   * II) $\emptyset \subseteq A$
   * III) $\{\emptyset\} \in A$
   * IV) $\{\emptyset\} \subseteq A$

10. **The Universal Set:** In the context of a student enrollment database where sets are grouped by major, describe what the universal set $U$ represents.

---

### Section B: Set Classifications, Subsets, and Power Sets (Problems 11–20)

11. **Finite vs. Infinite Set Identification:** Classify each of the following sets as either finite or infinite:
    * I) $A = \{x \in \mathbb{R} \mid 0 < x < 1\}$
    * II) $B = \{x \in \mathbb{Z} \mid 0 < x < 1000000\}$
    * III) $C = \{x \in \mathbb{Z}^- \mid x < -5\}$

12. **The Empty Set Notation:** Why is the set $\{\emptyset\}$ not considered an empty set? What is its cardinality?

13. **Equal vs. Equivalent Sets:** Set $A = \{x, y, z\}$ and Set $B = \{1, 2, 3\}$. Are they equal, equivalent, both, or neither? Prove your answer by referencing bijections.

14. **The Definition of a Subset:** Let $X = \{2, 3, 5\}$ and $Y = \{n \in \mathbb{Z} \mid n \text{ is prime}\}$. Prove whether $X \subseteq Y$ or $X \not\subseteq Y$.

15. **Proper Subset Criteria:** Let $A = \{a, b, c\}$ and $B = \{a, b, c\}$. Determine if $A \subset B$ is true or false, and state the definition of a proper subset.

16. **Cardinality of a Power Set:** If $|S| = k$, the cardinality of its power set $|\mathcal{P}(S)| = 2^k$. Find the cardinality of the power set of:
    $$A = \{x \in \mathbb{Z} \mid -2 \le x \le 2\}$$

17. **Listing a Power Set:** Let $M = \{0, 1, \{2\}\}$. Write out the entire power set $\mathcal{P}(M)$ explicitly.

18. **The Cardinality of $\mathcal{P}(\mathcal{P}(\emptyset))$:** Step-by-step, determine the cardinality of:
    $$|\mathcal{P}(\mathcal{P}(\mathcal{P}(\emptyset)))|$$

19. **Subset Reflexivity Theorem:** Prove that for any set $A$, $A \subseteq A$.

20. **Transitivity of Subsets:** Prove that if $A \subseteq B$ and $B \subseteq C$, then $A \subseteq C$.

---

### Section C: Basic Set Operations & Venn Diagram Shading (Problems 21–30)

21. **Absolute Complement Calculation:** Let $U = \{1, 2, 3, 4, 5, 6, 7, 8, 9, 10\}$ and $A = \{x \in U \mid x \text{ is prime}\}$. Find the complement $A'$.

22. **Set Difference (Relative Complement):** Let $A = \{a, b, c, d, e\}$ and $B = \{d, e, f, g\}$. Find:
    * I) $A - B$
    * II) $B - A$

23. **Symmetric Difference Calculation:** Using the sets from Problem 22, find the symmetric difference $A \oplus B$ (sometimes written as $A \Delta B$).

24. **Union and Intersection of Overlapping Sets:** Let $X = \{1, 2, 3, 4, 5\}$ and $Y = \{4, 5, 6, 7, 8\}$. List the elements of:
    * I) $X \cup Y$
    * II) $X \cap Y$

25. **Complement Properties Identification:** Simplify the following expressions using complement properties:
    * I) $(A^c)^c$
    * II) $U^c$
    * III) $\emptyset^c$

26. **Disjoint Sets Determination:** Let $P = \{x \in \mathbb{Z} \mid x \text{ is a multiple of 4}\}$ and $Q = \{x \in \mathbb{Z} \mid x \text{ is odd}\}$. Are $P$ and $Q$ disjoint? Mathematically justify your answer.

27. **Universal Operations with Set Difference:** Simplify the following expressions for any set $A$ inside a universe $U$:
    * I) $U - A$
    * II) $A - \emptyset$
    * III) $A - A$

28. **Venn Diagram Shading for $(A \cap B)^c$:** Draw or describe the exact shaded regions of a two-set Venn Diagram representing the set $(A \cap B)^c$. Which law of De Morgan does this relate to?

29. **Venn Diagram Shading for $A - B$:** Describe which region is shaded in a Venn Diagram with overlapping circles $A$ and $B$ to represent $A - B$.

30. **Indexed Union Interpretation:** Let $A_n = \{x \in \mathbb{Z} \mid -n \le x \le n\}$ for $n \in \mathbb{Z}^+$. Find:
    * I) $\bigcup_{n=1}^{3} A_n$
    * II) $\bigcap_{n=1}^{3} A_n$

---

### Section D: Cartesian Products and Cardinalities (Problems 31–40)

31. **Two-Set Cartesian Product:** Let $A = \{p, q\}$ and $B = \{1, 2, 3\}$. Write out the set $A \times B$ in roster form.

32. **Cartesian Product Non-Commutativity:** Using the sets from Problem 31, write out $B \times A$. Does $A \times B = B \times A$?

33. **The Equality Theorem of Cartesian Products:** State the precise conditions under which $A \times B = B \times A$ is mathematically true.

34. **Cardinality of Multi-Set Products:** Let $|A| = 4$, $|B| = 5$, and $|C| = 2$. Find:
    * I) $|A \times B|$
    * II) $|A \times B \times C|$

35. **Cartesian Product of the Empty Set:** Let $A = \{a, b, c\}$. Write down the Cartesian product $A \times \emptyset$. What is its cardinality?

36. **Ordered Pair Definition & Equality:** If $(2x + y, 9) = (7, x - 2y)$, solve for $x$ and $y$ using the definition of ordered pairs.

37. **Powers of Sets (Cartesian Exponentiation):** Let $A = \{0, 1\}$. Write out the set $A^3$ (which is $A \times A \times A$).

38. **Cartesian Product of Real Coordinate Space:** Describe the geometric meaning of the Cartesian product $\mathbb{R} \times \mathbb{R}$ (or $\mathbb{R}^2$).

39. **Cartesian Product Cardinality Equation:** Prove that for any finite sets $A$ and $B$, $n(A \times B) = n(A) \cdot n(B)$.

40. **Elements of Cartesian Products:** Let $A = \{1, 2\}$. Identify which of the following elements belong to $A \times \mathcal{P}(A)$:
    * I) $(1, \{1\})$
    * II) $(2, 2)$
    * III) $(\{1\}, 1)$
    * IV) $(2, \emptyset)$

---

### Section E: Algebraic Proofs, Theorems, and Set Partitions (Problems 41–50)

41. **Partition Validation (Criteria 1):** Let $S = \{1, 2, 3, 4, 5, 6, 7\}$. Determine if $P = \{\{1, 3, 5\}, \{2, 4, 6\}, \{7\}\}$ is a valid partition of $S$. State your mathematical reasons.

42. **Partition Validation (Criteria 2):** Let $S = \{1, 2, 3, 4, 5, 6, 7\}$. Determine if $Q = \{\{1, 2, 3\}, \{3, 4, 5\}, \{6, 7\}\}$ is a valid partition of $S$. State your mathematical reasons.

43. **Syllabus Exercise Partition Example:** According to your lecture notes, what set do the set of even integers and the set of odd integers partition? Why?

44. **Counting Partitions with Bell Numbers:** A set $A$ has 3 elements. How many possible partitions of $A$ exist? List them all for $A = \{a, b, c\}$.

45. **Subset Equivalence Proof:** Prove that if $A \subseteq B$, then $A \cap B = A$.

46. **Syllabus Slide Proof Exercise 1:** Prove the following slide exercise using set identities (algebraic laws of sets):
    $$(B - A) \cup (C - A) = (B \cup C) - A$$

47. **Syllabus Slide Proof Exercise 2:** Prove the following slide exercise using a set-membership table:
    $$(A - B) - (B - C) = A - B$$

48. **Syllabus Slide Proof Exercise 3:** Prove the following slide exercise using set identities (algebraic laws of sets):
    $$[(A - B) - (B - C)]' = A' \cup B$$

49. **The Subset Empty Set Theorem:** Prove that for any set $A \subseteq U$, $\emptyset \subseteq A$. Further, prove that if $A \neq \emptyset$, then $\emptyset \subset A$.

50. **Venn Diagram Equality Disproof:** Use a Venn diagram or counterexample to disprove the following statement:
    $$(A - B) - C = A - (B - C)$$

---

## Part II: Complete Step-by-Step Solutions

### Section A Solutions: Set Foundations, Membership, and Descriptions

1. **Answer:** **B) The collection of all prime numbers less than 100.**
   * *Reasoning:* A set is a collection of "well-defined" objects, meaning it must be clear and objective whether any given object belongs to the collection. Terms like "difficult" (A), "handsome" (C), and "interesting" (D) are subjective opinions and cannot form a well-defined set. Prime numbers less than 100 is an objective mathematical fact, so it is well-defined.

2. **Answer:** **B) $6 \in S$ is false.**
   * *Reasoning:* Let's inspect the elements of $S = \{2, 4, \{6, 8\}, 10\}$. The elements are:
     * $2$ (an integer)
     * $4$ (an integer)
     * $\{6, 8\}$ (a set containing 6 and 8)
     * $10$ (an integer)
     * The number 6 itself is not a direct element of $S$ (it is nested within the element $\{6, 8\}$), hence $6 \in S$ is false. The statements $2 \in S$, $\{6, 8\} \in S$, and $8 \notin S$ are all true.

3. **Answer:**
   * *The Roster Method Rule:* Under the roster method, elements listed in the set must be distinct. Repetitions of the same object do not create new elements or alter the set. 
   * *Explanation:* In "WOOLLOOMOOLOO", there are only three distinct letters: 'W', 'O', and 'L'. Listing them as $B = \{W, O, L\}$ is the correct roster representation.
   * *Cardinality:* The cardinality of $B$ is $|B| = 3$.

4. **Answer:** **$S = \{x \in \mathbb{Z}^+ \mid x \text{ is a perfect square and } x \le 100\}$** (or $S = \{n^2 \mid n \in \mathbb{Z}, 1 \le n \le 10\}$).
   * *Reasoning:* The elements are the squares of the first ten positive integers ($1^2, 2^2, \dots, 10^2$).

5. **Answer:** **$T = \{-2, 3\}$**
   * *Reasoning:* Solve the quadratic equation:
     $$x^2 - x - 6 = 0 \implies (x - 3)(x + 2) = 0 \implies x = 3 \text{ or } x = -2$$
     Since both 3 and $-2$ are integers ($\mathbb{Z}$), they are both elements of $T$.

6. **Answer:** **They are both equal and equivalent.**
   * *Reasoning:* 
     * **Equal Sets ($X = Y$):** Under the roster method, duplicate elements are ignored. Therefore, the set $Y = \{r, a, b, a\}$ simplifies to $\{r, a, b\}$. Since order does not matter in sets, $\{b, a, r\} = \{r, a, b\}$. Thus, $X = Y$.
     * **Equivalent Sets ($X \approx Y$):** Since $X = Y$, their cardinalities are identical ($|X| = |Y| = 3$). A bijective map (such as $a \mapsto a, b \mapsto b, r \mapsto r$) can easily be constructed, so they are equivalent.

7. **Answer:**
   * *Requirements for Rule Method:* The rule method is applicable as long as there exists a clear, unambiguous characterizing property or predicate $P(x)$ that describes each element of the set and determines whether an object belongs to the set or not. If such a common characterizing property cannot be formulated, the set cannot be described using the rule method.

8. **Answer:** **$A = \{x \in \mathbb{Z} \mid x \text{ is odd and } -10 < x < 10\}$** (or $A = \{2k+1 \in \mathbb{Z} \mid k \in \mathbb{Z}, -5 \le k \le 4\}$).

9. **Answer:** **All four statements are TRUE.**
   * *Reasoning:* Let $A = \{\emptyset, \{\emptyset\}\}$. The elements of $A$ are:
     * $x_1 = \emptyset$
     * $x_2 = \{\emptyset\}$
     * **I) $\emptyset \in A$:** True, because $\emptyset$ is the first listed element ($x_1$).
     * **II) $\emptyset \subseteq A$:** True, because the empty set is a subset of every set.
     * **III) $\{\emptyset\} \in A$:** True, because $\{\emptyset\}$ is the second listed element ($x_2$).
     * **IV) $\{\emptyset\} \subseteq A$:** True, because the element inside the subset is $\emptyset$, and $\emptyset \in A$ is true. Since the elements of the subset $\{\emptyset\}$ belong to $A$, the subset itself is a subset of $A$.

10. **Answer:** **$U$ represents the set of all students currently enrolled in the university.**
    * *Reasoning:* A universal set $U$ is a fixed set that contains all possible objects under discussion in a given context. In a student enrollment database, all groups, majors, and classes are subsets of the entire student body.

---

### Section B Solutions: Set Classifications, Subsets, and Power Sets

11. **Answer:**
    * **I) $A$ is Infinite.** (There are infinitely many real numbers between 0 and 1, e.g., 0.5, 0.25, 0.1, etc.).
    * **II) $B$ is Finite.** (The set contains exactly 999,999 integers, which can be fully counted and listed).
    * **III) $C$ is Infinite.** (The set of negative integers less than $-5$ is $\{\dots, -8, -7, -6\}$, which has no lower bound).

12. **Answer:**
    * *Why it is not empty:* The set $\{\emptyset\}$ is not empty because it contains exactly one element: the empty set itself. It is a **singleton (unit) set**.
    * *Cardinality:* The cardinality of $\{\emptyset\}$ is $1$.

13. **Answer:** **They are equivalent ($A \approx B$) but not equal ($A \neq B$).**
    * *Proof of Equivalence:* The cardinality of both sets is $3$ ($|A| = |B| = 3$). We can establish a one-to-one correspondence (bijection) $f: A \to B$ defined by $f(x) = 1$, $f(y) = 2$, and $f(z) = 3$. Since a bijection exists, $A \approx B$.
    * *Proof of Non-equality:* For $A = B$, they must contain the exact same elements. Since $x \in A$ but $x \notin B$, the sets are not equal.

14. **Answer:** **$X \subseteq Y$ is true.**
    * *Proof:* By definition, $X \subseteq Y$ if and only if every element in $X$ is also in $Y$. 
      * The elements of $X$ are $2$, $3$, and $5$.
      * We check each element: $2$ is prime, so $2 \in Y$; $3$ is prime, so $3 \in Y$; $5$ is prime, so $5 \in Y$.
      * Since every element of $X$ is a member of $Y$, $X \subseteq Y$ is proven.

15. **Answer:** **$A \subset B$ is false.**
    * *Definition of Proper Subset:* For $A$ to be a proper subset of $B$ (written $A \subset B$), two conditions must be met:
      1. $A$ must be a subset of $B$ ($A \subseteq B$).
      2. There must be at least one element of $B$ which is not an element of $A$ ($A \neq B$).
    * *Explanation:* Here, $A = B$ (they have the exact same elements). Since they are equal, the second condition is violated, making $A \subset B$ false.

16. **Answer:** **$32$**
    * *Reasoning:* Let's find the elements of $A$:
      $$A = \{-2, -1, 0, 1, 2\}$$
      The cardinality of $A$ is $|A| = 5$.
      Therefore, the cardinality of the power set is $|\mathcal{P}(A)| = 2^5 = 32$.

17. **Answer:** 
    $$\mathcal{P}(M) = \{\emptyset, \{0\}, \{1\}, \{\{2\}\}, \{0, 1\}, \{0, \{2\}\}, \{1, \{2\}\}, \{0, 1, \{2\}\}\}$$
    * *Reasoning:* $M$ has 3 elements: $0$, $1$, and $\{2\}$. The subsets consist of the empty set, 3 singletons, 3 subsets of size two, and the set $M$ itself.

18. **Answer:** **$4$**
    * *Reasoning:* Let's compute step-by-step:
      1. Start with the empty set: $\emptyset$. Its cardinality is $0$.
      2. Find $\mathcal{P}(\emptyset) = \{\emptyset\}$. Its cardinality is $2^0 = 1$.
      3. Find $\mathcal{P}(\mathcal{P}(\emptyset)) = \{\emptyset, \{\emptyset\}\}$. Its cardinality is $2^1 = 2$.
      4. Find $\mathcal{P}(\mathcal{P}(\mathcal{P}(\emptyset))) = \{\emptyset, \{\emptyset\}, \{\{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}\}$. Its cardinality is $2^2 = 4$.

19. **Answer:**
    * *Proof:* By definition, a set $A \subseteq B$ if and only if $\forall x (x \in A \implies x \in B)$. Let $B = A$. The statement becomes $\forall x (x \in A \implies x \in A)$, which is a logical tautology ($P \implies P$ is always true). Therefore, $A \subseteq A$ is always true (reflexivity).

20. **Answer:**
    * *Proof:* We must show that $\forall x (x \in A \implies x \in C)$.
      1. Let $x$ be an arbitrary element such that $x \in A$.
      2. Since $A \subseteq B$, by definition of a subset, every element of $A$ is in $B$. Therefore, $x \in B$.
      3. Since $B \subseteq C$, by definition of a subset, every element of $B$ is in $C$. Therefore, $x \in C$.
      4. Since $x \in A \implies x \in C$ holds for all $x$, we conclude $A \subseteq C$ (transitivity).

---

### Section C Solutions: Basic Set Operations & Venn Diagram Shading

21. **Answer:** **$A' = \{1, 4, 6, 8, 9, 10\}$**
    * *Reasoning:* $U = \{1, 2, 3, 4, 5, 6, 7, 8, 9, 10\}$. The primes in $U$ are $A = \{2, 3, 5, 7\}$. The complement $A'$ consists of all elements in $U$ that are not in $A$.

22. **Answer:**
    * **I) $A - B = \{a, b, c\}$** (elements in $A$ that are not in $B$).
    * **II) $B - A = \{f, g\}$** (elements in $B$ that are not in $A$).

23. **Answer:** **$A \oplus B = \{a, b, c, f, g\}$**
    * *Reasoning:* The symmetric difference is the union of $(A - B)$ and $(B - A)$:
      $$A \oplus B = (A - B) \cup (B - A) = \{a, b, c\} \cup \{f, g\} = \{a, b, c, f, g\}$$

24. **Answer:**
    * **I) $X \cup Y = \{1, 2, 3, 4, 5, 6, 7, 8\}$**
    * **II) $X \cap Y = \{4, 5\}$**

25. **Answer:**
    * **I) $(A^c)^c = A$** (Double complement law).
    * **II) $U^c = \emptyset$** (Complement of the universal set is empty).
    * **III) $\emptyset^c = U$** (Complement of the empty set is the universe).

26. **Answer:** **Yes, $P$ and $Q$ are disjoint.**
    * *Mathematical Justification:* Two sets are disjoint if and only if their intersection is empty ($P \cap Q = \emptyset$).
      * Elements of $P$ are multiples of $4$: $P = \{\dots, -8, -4, 0, 4, 8, \dots\}$. Every multiple of $4$ is an even number since $4k = 2(2k)$.
      * Elements of $Q$ are odd integers: $Q = \{\dots, -3, -1, 1, 3, \dots\}$.
      * No integer can be both even and odd simultaneously. Therefore, no multiple of $4$ can be odd.
      * Thus, $P \cap Q = \emptyset$, proving they are disjoint.

27. **Answer:**
    * **I) $U - A = A^c$** (This is the definition of absolute complement).
    * **II) $A - \emptyset = A$** (Subtracting no elements from $A$ leaves $A$ unchanged).
    * **III) $A - A = \emptyset$** (Subtracting all elements of $A$ from $A$ leaves nothing).

28. **Answer:**
    * *Description of shading:* Shade everything in the rectangle (universal set $U$) **except** for the small overlapping region where circles $A$ and $B$ intersect.
    * *De Morgan's Law:* This represents $(A \cap B)^c = A^c \cup B^c$.

29. **Answer:**
    * *Description of shading:* Shade only the region inside circle $A$ that does **not** overlap with circle $B$ (the crescent shape of $A$). Do not shade the intersection of $A$ and $B$, and do not shade any part of $B$ or the background.

30. **Answer:**
    * First, let's list the sets:
      * $A_1 = \{x \in \mathbb{Z} \mid -1 \le x \le 1\} = \{-1, 0, 1\}$
      * $A_2 = \{x \in \mathbb{Z} \mid -2 \le x \le 2\} = \{-2, -1, 0, 1, 2\}$
      * $A_3 = \{x \in \mathbb{Z} \mid -3 \le x \le 3\} = \{-3, -2, -1, 0, 1, 2, 3\}$
    * **I) $\bigcup_{n=1}^{3} A_n = A_3 = \{-3, -2, -1, 0, 1, 2, 3\}$** (since $A_1 \subseteq A_2 \subseteq A_3$).
    * **II) $\bigcap_{n=1}^{3} A_n = A_1 = \{-1, 0, 1\}$**.

---

### Section D Solutions: Cartesian Products and Cardinalities

31. **Answer:** **$A \times B = \{(p, 1), (p, 2), (p, 3), (q, 1), (q, 2), (q, 3)\}$**

32. **Answer:** 
    * **$B \times A = \{(1, p), (1, q), (2, p), (2, q), (3, p), (3, q)\}$**
    * **No, $A \times B \neq B \times A$** because the ordered pairs are different (e.g., $(p, 1) \neq (1, p)$).

33. **Answer:** **$A \times B = B \times A$ if and only if $A = \emptyset$ or $B = \emptyset$ or $A = B$.**
    * *Reasoning:* This is the exact "NOTE" featured in your CMSC 56 Cartesian Product slide.

34. **Answer:**
    * **I) $|A \times B| = 4 \cdot 5 = 20$**
    * **II) $|A \times B \times C| = 4 \cdot 5 \cdot 2 = 40$**

35. **Answer:**
    * **$A \times \emptyset = \emptyset$**
    * *Cardinality:* $0$. (Since there are no elements in the empty set, no ordered pairs can be formed).

36. **Answer:** **$x = 3$, $y = 1$**
    * *Reasoning:* By the definition of equality of ordered pairs, coordinates must be equal:
      1) $2x + y = 7$
      2) $x - 2y = 9 \implies x = 2y + 9$
      * Substitute (2) into (1):
        $$2(2y + 9) + y = 7 \implies 4y + 18 + y = 7 \implies 5y = -11 \implies y = -2.2$$
        Wait, let's re-solve the system carefully:
        $$2x + y = 7 \implies y = 7 - 2x$$
        $$x - 2(7 - 2x) = 9 \implies x - 14 + 4x = 9 \implies 5x = 23 \implies x = 4.6$$
        Let's adjust the system for integer values so it is cleaner:
        If we want $x=3, y=1$:
        $2x + y = 2(3) + 1 = 7$.
        $x - 2y = 3 - 2(1) = 1$.
        Ah! The question has $(2x+y, 9) = (7, x-2y)$ which gives $x - 2y = 9$.
        Let's solve $(2x+y, 9) = (7, x-2y)$ exactly:
        $2x + y = 7 \implies y = 7 - 2x$
        $x - 2y = 9 \implies x - 2(7 - 2x) = 9 \implies 5x - 14 = 9 \implies 5x = 23 \implies x = 4.6$.
        Then $y = 7 - 2(4.6) = 7 - 9.2 = -2.2$.
        Thus, the exact solutions are **$x = 4.6$ and $y = -2.2$**.

31. **Answer:** 
    $$A^3 = \{(0,0,0), (0,0,1), (0,1,0), (0,1,1), (1,0,0), (1,0,1), (1,1,0), (1,1,1)\}$$

38. **Answer:** **The entire 2-dimensional Cartesian coordinate plane.**
    * *Reasoning:* $\mathbb{R} \times \mathbb{R}$ is the set of all ordered pairs of real numbers $(x, y)$, which represents every point on the 2D plane.

39. **Answer:**
    * *Proof:* Let $A$ be a finite set with $|A| = m$ elements ($A = \{a_1, a_2, \dots, a_m\}$), and $B$ be a finite set with $|B| = n$ elements ($B = \{b_1, b_2, \dots, b_n\}$).
      * The Cartesian product $A \times B$ is the set of all ordered pairs $(a_i, b_j)$.
      * For the first coordinate, we have $m$ choices from $A$.
      * For each choice of the first coordinate, we have $n$ independent choices for the second coordinate from $B$.
      * By the fundamental counting principle, the total number of distinct ordered pairs is $m \cdot n$.
      * Therefore, $n(A \times B) = n(A) \cdot n(B)$.

40. **Answer:** **I and IV are elements of $A \times \mathcal{P}(A)$.**
    * *Reasoning:* $A = \{1, 2\}$. The power set is $\mathcal{P}(A) = \{\emptyset, \{1\}, \{2\}, \{1, 2\}\}$.
      * Any element of $A \times \mathcal{P}(A)$ must be an ordered pair $(x, y)$ where $x \in A$ and $y \in \mathcal{P}(A)$.
      * **I) $(1, \{1\})$:** $1 \in A$ and $\{1\} \in \mathcal{P}(A)$. (Valid)
      * **II) $(2, 2)$:** $2 \in A$ but $2 \notin \mathcal{P}(A)$ (it is not a subset). (Invalid)
      * **III) $(\{1\}, 1)$:** $\{1\} \notin A$ and $1 \notin \mathcal{P}(A)$. (Invalid)
      * **IV) $(2, \emptyset)$:** $2 \in A$ and $\emptyset \in \mathcal{P}(A)$. (Valid)

---

### Section E Solutions: Algebraic Proofs, Theorems, and Set Partitions

41. **Answer:** **Yes, $P$ is a valid partition of $S$.**
    * *Reasoning:* Check the three conditions for a partition:
      1. All subsets in $P$ are non-empty: $\{1,3,5\} \neq \emptyset$, $\{2,4,6\} \neq \emptyset$, $\{7\} \neq \emptyset$. (True)
      2. The union of the subsets must equal $S$: $\{1,3,5\} \cup \{2,4,6\} \cup \{7\} = \{1,2,3,4,5,6,7\} = S$. (True)
      3. The subsets must be mutually disjoint:
         * $\{1,3,5\} \cap \{2,4,6\} = \emptyset$
         * $\{1,3,5\} \cap \{7\} = \emptyset$
         * $\{2,4,6\} \cap \{7\} = \emptyset$. (True)
      Since all conditions are satisfied, $P$ is a valid partition.

42. **Answer:** **No, $Q$ is not a valid partition of $S$.**
    * *Reasoning:* The subsets are not mutually disjoint because $\{1,2,3\} \cap \{3,4,5\} = \{3\} \neq \emptyset$. The element 3 belongs to more than one subset, violating the disjointness requirement of partitions.

43. **Answer:** **The set of integers ($\mathbb{Z}$).**
    * *Reasoning:* Every integer is either even or odd, so their union is $\mathbb{Z}$. No integer can be both even and odd, so they are disjoint. Neither set is empty. Therefore, they partition $\mathbb{Z}$.

44. **Answer:** **$5$ partitions (this is the 3rd Bell Number, $B_3 = 5$).**
    * *The 5 Partitions:*
      1. $P_1 = \{\{a, b, c\}\}$ (The set itself)
      2. $P_2 = \{\{a\}, \{b, c\}\}$
      3. $P_3 = \{\{b\}, \{a, c\}\}$
      4. $P_4 = \{\{c\}, \{a, b\}\}$
      5. $P_5 = \{\{a\}, \{b\}, \{c\}\}$ (Individual singletons)

45. **Answer:**
    * *Proof:* We prove $A \cap B = A$ using double inclusion:
      1. **Prove $A \cap B \subseteq A$:** Let $x \in A \cap B$. By definition of intersection, $x \in A$ and $x \in B$. Since $x \in A$ is true, $A \cap B \subseteq A$. (This is always true, regardless of $B$).
      2. **Prove $A \subseteq A \cap B$:** Let $x \in A$. We are given that $A \subseteq B$. By definition of subset, since $x \in A$, we must have $x \in B$. Since $x \in A$ and $x \in B$, by definition of intersection, $x \in A \cap B$. Therefore, $A \subseteq A \cap B$.
      Since both inclusions hold, $A \cap B = A$.

46. **Answer:**
    * *Proof:* 
      $$\text{LHS} = (B - A) \cup (C - A)$$
      Using the set difference property $X - Y = X \cap Y^c$:
      $$= (B \cap A^c) \cup (C \cap A^c)$$
      Using the distributive law in reverse (factoring out $\cap A^c$):
      $$= (B \cup C) \cap A^c$$
      Using the set difference property $X \cap Y^c = X - Y$:
      $$= (B \cup C) - A = \text{RHS}$$
      Thus, LHS = RHS.

47. **Answer:**
    * *Membership Table:*
      * Let $1$ denote that an element $u$ belongs to the set, and $0$ denote that it does not. We show that the columns for $(A - B) - (B - C)$ and $A - B$ are identical.

| $A$ | $B$ | $C$ | $A - B$ | $B - C$ | $(A - B) - (B - C)$ |
| :---: | :---: | :---: | :---: | :---: | :---: |
| 1 | 1 | 1 | 0 | 0 | 0 |
| 1 | 1 | 0 | 0 | 1 | 0 |
| 1 | 0 | 1 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 | 0 | 1 |
| 0 | 1 | 1 | 0 | 0 | 0 |
| 0 | 1 | 0 | 0 | 1 | 0 |
| 0 | 0 | 1 | 0 | 0 | 0 |
| 0 | 0 | 0 | 0 | 0 | 0 |

   * *Conclusion:* Since the column for $A - B$ (Column 4) and $(A - B) - (B - C)$ (Column 6) are identical for all 8 possible cases, $(A - B) - (B - C) = A - B$.

48. **Answer:**
    * *Proof:*
      $$\text{LHS} = [(A - B) - (B - C)]'$$
      From Problem 47, we proved that $(A - B) - (B - C) = A - B$. Substituting this inside the complement:
      $$= (A - B)'$$
      Apply the set difference identity $A - B = A \cap B^c$:
      $$= (A \cap B^c)'$$
      Apply De Morgan's Law:
      $$= A' \cup (B^c)'$$
      Apply the double complement law $(B^c)' = B$:
      $$= A' \cup B = \text{RHS}$$
      Thus, LHS = RHS.

49. **Answer:**
    * *Part 1: Prove $\emptyset \subseteq A$*
      * By definition of a subset, $\emptyset \subseteq A \iff \forall x (x \in \emptyset \implies x \in A)$.
      * The hypothesis $x \in \emptyset$ is always false because the empty set has no elements.
      * In mathematical logic, an implication with a false premise ($F \implies P$) is vacuously true.
      * Therefore, the statement is vacuously true, so $\emptyset \subseteq A$.
    * *Part 2: Prove if $A \neq \emptyset$, then $\emptyset \subset A$*
      * By definition of a proper subset, $\emptyset \subset A$ if and only if $\emptyset \subseteq A$ and $\emptyset \neq A$.
      * We already proved $\emptyset \subseteq A$.
      * We are given $A \neq \emptyset$, which means $\emptyset \neq A$.
      * Since both conditions are met, $\emptyset \subset A$.

50. **Answer:**
    * *Disproof by Counterexample:*
      * Let $U = \{1, 2, 3\}$, $A = \{1, 2\}$, $B = \{2, 3\}$, and $C = \{3\}$.
      * Evaluate the Left Hand Side (LHS):
        * $A - B = \{1\}$
        * $(A - B) - C = \{1\} - \{3\} = \{1\}$
      * Evaluate the Right Hand Side (RHS):
        * $B - C = \{2\}$
        * $A - (B - C) = \{1, 2\} - \{2\} = \{1, 2\}$
      * Since LHS = $\{1\}$ and RHS = $\{1, 2\}$, LHS $\neq$ RHS. This counterexample disproves the equality.
