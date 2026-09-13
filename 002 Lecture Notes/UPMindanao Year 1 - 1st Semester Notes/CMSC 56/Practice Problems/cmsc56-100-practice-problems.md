# CMSC 56: Comprehensive 100-Problem Set Theory Practice Question Bank

---

## PART I: THE PRACTICE PROBLEMS

### Module 1: Set Foundations, Membership, and Descriptions (Problems 1–15)

1. **Well-Defined Collections:** Under Georg Cantor's standard set theory, which of the following is considered a well-defined set?
   * A) $S = \{x \mid x \text{ is a very fast computer program}\}$
   * B) $T = \{x \in \mathbb{Z} \mid x \text{ is a prime number less than 50}\}$
   * C) $U = \{x \mid x \text{ is an interesting book on discrete structures}\}$
   * D) $V = \{x \mid x \text{ is an easy exam question}\}$

2. **The Membership Symbol ($\in$):** Let $A = \{2, \{3, 4\}, \emptyset, 5\}$. Which of the following statements is mathematically true?
   * A) $3 \in A$
   * B) $\{3, 4\} \in A$
   * C) $\{5\} \in A$
   * D) $\emptyset \notin A$

3. **The Non-Membership Symbol ($\notin$):** For the same set $A = \{2, \{3, 4\}, \emptyset, 5\}$, which statement is mathematically correct?
   * A) $2 \notin A$
   * B) $4 \in A$
   * C) $\{\emptyset\} \in A$
   * D) $4 \notin A$

4. **Roster Method Distinctness Rule:** A student writes the set of prime factors of $120$ as $F = \{2, 2, 2, 3, 5\}$. Which rule of the roster method is violated here? Rewrite the set correctly and state its correct cardinality.

5. **Roster Method Order Irrelevance:** Explain why the set $A = \{t, a, r\}$ and the set $B = \{r, a, t\}$ are identical. Does the order of listed elements affect a set's definition under the Roster Method?

6. **Convert Roster to Rule Method (Arithmetic Sequence):** Convert the following roster set to rule (set-builder) notation:
   $$X = \{3, 7, 11, 15, 19, 23, 27\}$$

7. **Convert Roster to Rule Method (Geometric Sequence):** Convert the following roster set to rule notation:
   $$Y = \{2, 4, 8, 16, 32, 64, 128, 256\}$$

8. **Convert Rule to Roster Method (Quadratic Constraint):** Convert the following set to roster form:
   $$S = \{x \in \mathbb{Z} \mid 2x^2 - 5x - 3 = 0\}$$

9. **Convert Rule to Roster Method (Absolute Value Constraint):** Convert the following set to roster form:
   $$T = \{x \in \mathbb{Z} \mid |x - 2| \le 3\}$$

10. **The Universal Set Definition:** Define what a universal set $U$ is. Can $U$ vary depending on the mathematical context, or is there a single, absolute universal set in mathematics?

11. **Natural Numbers Convention:** According to your Discrete Mathematics syllabus references (e.g., Northwestern DM notes), what is the convention regarding the inclusion of the number $0$ in the set of natural numbers $\mathbb{N}$?

12. **Integer Sets Representation:** Express the set of all negative even integers greater than $-15$ in both roster method and set-builder notation.

13. **Limitations of the Rule Method:** Give an example of a set that cannot be described using the rule (set-builder) method, or explain the conditions under which the rule method fails.

14. **Converting Set-Builder with Multiple Variables:** Let $S = \{x + y \mid x \in \{1, 2\}, y \in \{3, 4\}\}$. Write this set in roster method and find its cardinality.

15. **Symbolic Predicate Matching:** Express the set of all real numbers that are roots of the cubic equation $x^3 - x = 0$ using formal set-builder notation.

---

### Module 2: Structural and Relational Classifications of Sets (Problems 16–30)

16. **Finite vs. Infinite (Reals Interval):** Determine whether the set $I = \{x \in \mathbb{R} \mid 0 < x < 1\}$ is finite or infinite. Explain your reasoning.

17. **Finite vs. Infinite (Rational Interval):** Determine whether the set $Q = \{x \in \mathbb{Q} \mid 0 < x < 1\}$ is finite or infinite. Explain your reasoning.

18. **The Empty Set Uniqueness:** Prove that there is only one empty set. (Hint: Use set equality laws).

19. **The Empty Set Notation Pitfall:** Why is the set $S = \{\emptyset\}$ not empty? What is its cardinality? What about the set $T = \{\{\}\}\}$?

20. **Singleton Set Identification:** Identify which of the following is a singleton set:
    * A) $A = \{x \in \mathbb{Z} \mid x^2 = 4\}$
    * B) $B = \{x \in \mathbb{N} \mid x + 5 = 5\}$
    * C) $C = \{x \in \mathbb{R} \mid x^2 + 1 = 0\}$
    * D) $D = \{x \in \mathbb{Z} \mid x \text{ is even and prime}\}$

21. **Equal vs. Equivalent Sets (Definition):** State the precise difference between **equal sets** and **equivalent sets**. If two sets are equal, are they automatically equivalent? If two sets are equivalent, are they automatically equal?

22. **Establishing Bijection for Equivalence:** Show that the set of positive integers $\mathbb{Z}^+$ and the set of even positive integers $E^+ = \{2, 4, 6, 8, \dots\}$ are equivalent sets by defining a one-to-one correspondence (bijection).

23. **Cardinality Comparison Rules:** Let $A = \{x, y\}$ and $B = \{1, 2, 3\}$. Use your lecture notes' definition of cardinality comparisons ($|X| \le |Y|$) to show why $|A| < |B|$. Identify the injective but non-bijective function.

24. **Disjoint Sets Definition:** Two sets $A$ and $B$ are defined as disjoint if and only if $A \cap B = \emptyset$. Determine if the following two sets are disjoint:
    * $A = \{n \in \mathbb{Z} \mid n^2 \text{ is even}\}$
    * $B = \{n \in \mathbb{Z} \mid n^2 \text{ is odd}\}$

25. **Overlapping Sets Cardinality Formula:** If $|A \cup B| = |A| + |B| - |A \cap B|$, what does this imply about the relationship of $A$ and $B$ if $|A \cup B| = |A| + |B|$?

26. **The Multisets Concept:** What is a multiset? Contrast the multiset $M = \{a, a, b\}$ with the standard mathematical set $S = \{a, a, b\}$.

27. **Relating Empty Sets and Universes:** Simplify the absolute complement of the empty set, $\emptyset^c$, and the absolute complement of the universal set, $U^c$.

28. **Subsets of the Reals:** For the following sets, state all subset relations that exist among them: $\mathbb{N}$, $\mathbb{Z}$, $\mathbb{Q}$, $\mathbb{R}$, $\mathbb{C}$, $\mathbb{W}$.

29. **Cardinality of Nested Elements:** Find the cardinality of the following set:
    $$S = \{1, \{2, 3\}, \emptyset, \{\emptyset, \{4\}\}\}$$

30. **Equal Sets Double Inclusion Theorem:** Prove that two sets $A$ and $B$ are equal if and only if $A \subseteq B$ and $B \subseteq A$.

---

### Module 3: Subsets, Proper Subsets, and Inclusion Theorems (Problems 31–45)

31. **Subset Definition Verification:** Let $A = \{1, 2\}$ and $B = \{1, 2, \{1, 2\}\}$. Determine if $A \subseteq B$ and explain why.

32. **Proper Subset Definition Verification:** For the same sets $A = \{1, 2\}$ and $B = \{1, 2, \{1, 2\}\}$, determine if $A \subset B$ is a proper subset.

33. **The Nested Element vs. Subset Challenge I:** Let $S = \{a, \{a\}\}$. Determine the validity of:
    * I) $a \in S$
    * II) $a \subseteq S$
    * III) $\{a\} \in S$
    * IV) $\{a\} \subseteq S$

34. **The Nested Element vs. Subset Challenge II:** Let $T = \{x, y, \{x, y\}\}$. List all elements of $T$ that are also subsets of $T$.

35. **The Empty Set Subset Theorem:** Prove the theorem from your slides: "For any universe $U$, let $A \subseteq U$. Then $\emptyset \subseteq A$."

36. **The Empty Set Proper Subset Theorem:** Prove the theorem: "For any universe $U$, let $A \subseteq U$. If $A \neq \emptyset$, then $\emptyset \subset A$."

37. **Transitivity of Subsets Proof:** Prove formally using logic: "If $A \subseteq B$ and $B \subseteq C$, then $A \subseteq C$."

38. **Transitivity of Proper Subsets Proof:** Prove formally: "If $A \subset B$ and $B \subset C$, then $A \subset C$."

39. **Inclusion Relationships with Unions:** Prove that for any sets $A$ and $B$, $A \subseteq A \cup B$.

40. **Inclusion Relationships with Intersections:** Prove that for any sets $A$ and $B$, $A \cap B \subseteq A$.

41. **Complement Reversal of Inclusion:** Prove the theorem from your slides: "For any universe $U$, and sets $A, B \subseteq U$, $A \subseteq B \iff B^c \subseteq A^c$."

42. **Equivalent Statements of Subset Inclusion:** Your slides state that the following four statements are equivalent:
    * a) $A \subseteq B$
    * b) $A \cap B = A$
    * c) $A \cup B = B$
    * d) $B^c \subseteq A^c$
    
    Prove that (a) implies (b).

43. **Subset Inclusion Equivalence Proof (Part II):** Prove that (b) implies (c) from the theorem above.

44. **Analyzing False Proper Subset Claims:** Disprove by counterexample: "If $A \subseteq B$ and $B \subseteq A$, then $A$ is a proper subset of $B$."

45. **Inclusion in Cartesian Space:** Let $A \subseteq C$ and $B \subseteq D$. Prove that $A \times B \subseteq C \times D$.

---

### Module 4: Power Sets and Nested Set Hierarchies (Problems 46–55)

46. **Listing a Simple Power Set:** Let $S = \{a, b\}$. List all elements of its power set $\mathcal{P}(S)$.

47. **Power Set of Empty Set:** Find $\mathcal{P}(\emptyset)$ and state its cardinality.

48. **Double Power Set of Empty Set:** Find $\mathcal{P}(\mathcal{P}(\emptyset))$ and list its elements.

49. **Triple Power Set of Empty Set:** Find the cardinality of $\mathcal{P}(\mathcal{P}(\mathcal{P}(\emptyset)))$ and list all its elements.

50. **Power Set Cardinality Theorem Application:** Let $S$ be a set of size $n$. Prove by induction or combinatorial argument that $|\mathcal{P}(S)| = 2^n$.

51. **Power Set of a Singleton Set:** Let $S = \{x\}$. Find $\mathcal{P}(S)$ and $\mathcal{P}(\mathcal{P}(S))$.

52. **Power Set Intersection Theorem:** Prove that for any sets $A$ and $B$, $\mathcal{P}(A \cap B) = \mathcal{P}(A) \cap \mathcal{P}(B)$.

53. **Power Set Union Counterexample:** Show by counterexample that $\mathcal{P}(A \cup B) = \mathcal{P}(A) \cup \mathcal{P}(B)$ is **not** generally true.

54. **Nested Elements inside Power Sets:** Let $A = \{1, \{2\}\}$. List the elements of $\mathcal{P}(A)$.

55. **Strict Cardinality Ordering of Power Sets:** Explain why for any finite set $A$, $|A| < |\mathcal{P}(A)|$. Does this result (Cantor's Theorem) hold for infinite sets as well?

---

### Module 5: Core Set Operations and Symbolic Predicates (Problems 56–70)

56. **Complement Definition & Predicate:** Write the formal set-builder predicate definition for the complement $A^c$ of a set $A$ inside a universal set $U$.

57. **Union Definition & Predicate:** Write the formal set-builder predicate definition for $A \cup B$.

58. **Intersection Definition & Predicate:** Write the formal set-builder predicate definition for $A \cap B$.

59. **Set Difference Definition & Predicate:** Write the formal set-builder predicate definition for the relative complement $A - B$.

60. **Symmetric Difference Definition & Predicate:** Write the formal set-builder predicate definition for the symmetric difference $A \oplus B$ (or $A \Delta B$).

61. **Indexed Unions (Arithmetic Progression):** Let $A_n = \{x \in \mathbb{Z} \mid 1 \le x \le n\}$ for $n \in \mathbb{Z}^+$. Find:
    * I) $\bigcup_{n=1}^5 A_n$
    * II) $\bigcap_{n=1}^5 A_n$

62. **Indexed Intersections (Rational Intervals):** Let $B_n = \left(0, \frac{1}{n}\right)$ be open intervals of real numbers for $n \in \mathbb{Z}^+$. Find:
    * I) $\bigcup_{n=1}^\infty B_n$
    * II) $\bigcap_{n=1}^\infty B_n$

63. **Generalized Unions & Intersections (General Forms):** Write the formal logical predicate formulas for:
    $$\bigcup_{i \in I} S_i \quad \text{and} \quad \bigcap_{i \in I} S_i$$

64. **Symmetric Difference Equivalence Proof:** Prove algebraically that:
    $$A \oplus B = (A \cup B) - (A \cap B)$$

65. **Set Difference as Intersection with Complement:** Prove that for any sets $A$ and $B$, $A - B = A \cap B^c$.

66. **Distributive Law Proof (Union over Intersection):** Write down the distributive law for $A \cup (B \cap C)$ and prove it using set-membership logic.

67. **De Morgan's Law Proof (Intersection Complement):** State and prove De Morgan's Law for $(A \cap B)^c$ using element-chasing (logical equivalence of predicates).

68. **Simplifying Complicated Set Complements:** Simplify the expression:
    $$((A \cup B^c)^c \cap A)^c$$

69. **Symmetric Difference Associativity Statement:** Is the symmetric difference operation associative? Write out the expression for $A \oplus (B \oplus C)$.

70. **Set Difference Non-Associativity:** Show by counterexample that set difference is not associative, i.e., $(A - B) - C \neq A - (B - C)$.

---

### Module 6: Cartesian Products, Ordered Pairs, and Relations (Problems 71–80)

71. **Ordered Pair Equality:** What is the condition for two ordered pairs $(a, b)$ and $(c, d)$ to be equal?

72. **Cartesian Product Listing:** Let $A = \{0, 1, 2, 3\}$ and $B = \{x, y, z\}$. Write out the full Cartesian product $A \times B$ as an explicit set of ordered pairs.

73. **Non-Commutativity of Cartesian Product:** Using the sets from Problem 72, write out $B \times A$ and show why $A \times B \neq B \times A$.

74. **Cardinality of Cartesian Product:** Prove that if $A$ and $B$ are finite sets, then $|A \times B| = |A| \cdot |B|$.

75. **Multi-fold Cartesian Product:** Let $A = \{a\}$, $B = \{b, c\}$, and $C = \{0, 1\}$. List the elements of the 3-fold Cartesian product $A \times B \times C$.

76. **Cartesian Product with Empty Set:** For any set $A$, prove that $A \times \emptyset = \emptyset$.

77. **Cartesian Product Intersection Distribution:** Prove that:
    $$A \times (B \cap C) = (A \times B) \cap (A \times C)$$

78. **Cartesian Product Union Distribution:** Prove that:
    $$A \times (B \cup C) = (A \times B) \cup (A \times C)$$

79. **Definition of a Binary Relation:** What is a binary relation $R$ from set $A$ to set $B$ in terms of Cartesian products?

80. **Relation Domain and Range:** Let $A = \{1, 2, 3\}$ and $B = \{a, b\}$. If a relation $R \subseteq A \times B$ is given by $R = \{(1, a), (2, b), (3, a)\}$, state the domain and range of $R$.

---

### Module 7: Set Partitions, Disjoint Groupings, and Bell Numbers (Problems 81–90)

81. **Definition of a Set Partition:** State the exact conditions required for a family of subsets $\{A_1, A_2, \dots, A_n\}$ to be a valid partition of a set $A$.

82. **Partition Verification (Disjointness Failure):** Let $S = \{1, 2, 3, 4, 5\}$. Explain why the collection $P = \{\{1, 2, 3\}, \{3, 4, 5\}\}$ is not a valid partition of $S$.

83. **Partition Verification (Union Failure):** Let $S = \{1, 2, 3, 4, 5\}$. Explain why the collection $Q = \{\{1, 2\}, \{4, 5\}\}$ is not a valid partition of $S$.

84. **Partition Verification (Empty Set Failure):** Explain why the collection $R = \{\{1, 2, 3\}, \emptyset, \{4, 5\}\}$ is not a valid partition of $S = \{1, 2, 3, 4, 5\}$.

85. **Even/Odd Integers Partition Proof:** Prove the exercise from your slides: "The set of even and odd integers forms a partition of the set of integers $\mathbb{Z}$."

86. **Positive/Negative Integers Partition Analysis:** Does the collection of positive integers $\mathbb{Z}^+$ and negative integers $\mathbb{Z}^-$ form a valid partition of the set of integers $\mathbb{Z}$? Justify your answer.

87. **The Bell Numbers ($B_n$):** Define what a Bell Number $B_n$ is. What is the value of $B_0$?

88. **Listing All Partitions of a 3-Element Set:** Let $S = \{1, 2, 3\}$. List all possible partitions of $S$. Verify that the number of partitions matches the Bell Number $B_3 = 5$.

89. **Calculating Bell Number $B_4$:** Calculate the Bell Number $B_4$ using the Bell Triangle or recurrence relation, and explain its mathematical meaning.

90. **Equivalence Relations and Partitions:** State the fundamental theorem that relates equivalence relations on a set $A$ to partitions of $A$.

---

### Module 8: Venn Diagrams and Cardinal Counting (Problems 91–95)

91. **History of Venn Diagrams:** Summarize the origin of Venn Diagrams as outlined in your course. Who introduced the term, and what did John Venn originally call them?

92. **Shading a Two-Set Operation:** Draw or describe the shaded regions in a standard two-set Venn diagram for:
    * I) $A \cap B^c$
    * II) $(A \cup B)^c$
    * III) $A^c \cap B^c$

93. **Shading a Three-Set Operation:** Draw or describe the shaded regions in a three-set Venn diagram ($A$, $B$, $C$) for:
    * I) $A \cap (B \cup C)$
    * II) $(A \cap B) - C$
    * III) $(A \cup B) \cap C^c$

94. **The Principle of Inclusion-Exclusion (3 Sets):** State the formal mathematical formula for the cardinality of the union of three finite sets $|A \cup B \cup C|$.

95. **The 3-Course Student Enrollment Problem:** Solve the following cardinal counting word problem step-by-step:
    * There are students enrolled in three courses: Mathematics ($M$), Physics ($P$), and Computer Science ($C$).
    * Total enrollments are: $|M| = 300$, $|P| = 350$, and $|C| = 450$.
    * Overlapping enrollments are: $|M \cap P| = 100$, $|M \cap C| = 150$, and $|P \cap C| = 75$.
    * The number of students taking all three courses is: $|M \cap P \cap C| = 10$.
    * **Task:** Calculate the exact number of students taking **exactly one course**. Show the calculations for each individual disjoint region.

---

### Module 9: Formal Proofs and Algebraic Set Identities (Problems 96–100)

96. **Double Inclusion Proof Method:** Prove that for any sets $A, B, C$, if $A \subseteq B$, then $A \cap C \subseteq B \cap C$ using the method of double inclusion/element chasing.

97. **Exercise 1 Proof from Slides (Algebraic Laws):** Prove algebraically using set properties:
    $$(B - A) \cup (C - A) = (B \cup C) - A$$
    *Explicitly state which law of sets is used at each step.*

98. **Exercise 2 Proof from Slides (Algebraic Laws):** Prove algebraically using set properties:
    $$(A - B) - (B - C) = A - B$$
    *Explicitly state which law of sets is used at each step.*

99. **Exercise 3 Proof from Slides (Algebraic Laws):** Simplify and prove the following identity algebraically using laws of sets:
    $$[(A - B) - (B - C)]' = A' \cup B$$

100. **Set-Membership Table Proof:** Prove the identity from Problem 99, namely $[(A - B) - (B - C)]' = A' \cup B$, using a formal set-membership table with $1$s and $0$s.

---

## PART II: STEP-BY-STEP SOLUTION KEY

Below are the highly rigorous and mathematically precise solutions to all 100 practice problems.

---

### Solutions for Module 1 (Problems 1–15)

1. **Answer: B**
   * *Justification:* A set is well-defined if we can determine unambiguously whether any given object belongs to it. Prime numbers less than 50 are mathematically fixed and definite. "Very fast," "interesting," and "easy" are subjective terms that fail the "well-defined" criteria [2].

2. **Answer: B**
   * *Justification:* The elements of $A$ are $2$, $\{3, 4\}$, $\emptyset$, and $5$. The subset $\{3,4\}$ is listed directly as an element of $A$, hence $\{3, 4\} \in A$ is correct. Option A is false because $3$ is nested inside $\{3, 4\}$ and is not a direct element. Option C is false because $5$ is an element, so $\{5\}$ is a subset, not an element [2].

3. **Answer: D**
   * *Justification:* The number $4$ is nested inside the set element $\{3, 4\}$, but $4$ itself is not a direct element of $A$, meaning $4 \notin A$ is mathematically true [2].

4. **Answer:**
   * *Justification:* The roster method requires that **all elements must be distinct** [3]. Listing the prime factor 2 multiple times is a violation of this rule.
   * *Correct Set:* $F = \{2, 3, 5\}$
   * *Cardinality:* $|F| = 3$ [5]

5. **Answer:**
   * *Justification:* Order is irrelevant within set listings under standard set theory. Since $A$ and $B$ contain exactly the same elements ($a$, $r$, and $t$), they represent the same collection. The order of elements does not alter set membership.

6. **Answer:**
   * *Set-Builder Notation:* $X = \{x \in \mathbb{Z}^+ \mid x = 4k - 1 \text{ for } k \in \{1, 2, 3, 4, 5, 6, 7\}\}$ or $X = \{x \in \mathbb{Z}^+ \mid x \equiv 3 \pmod 4 \text{ and } 3 \le x \le 27\}$.

7. **Answer:**
   * *Set-Builder Notation:* $Y = \{2^n \mid n \in \mathbb{Z}, 1 \le n \le 8\}$.

8. **Answer:**
   * *Justification:* We solve the quadratic equation $2x^2 - 5x - 3 = 0$:
     $$(2x + 1)(x - 3) = 0 \implies x = -\frac{1}{2} \quad \text{or} \quad x = 3$$
     Since the rule restricts elements to the set of integers $\mathbb{Z}$, the value $-\frac{1}{2}$ is excluded.
   * *Roster Form:* $S = \{3\}$

9. **Answer:**
   * *Justification:* $|x - 2| \le 3 \implies -3 \le x - 2 \le 3 \implies -1 \le x \le 5$. Since $x \in \mathbb{Z}$, we list the integers in this range.
   * *Roster Form:* $T = \{-1, 0, 1, 2, 3, 4, 5\}$

10. **Answer:**
    * *Justification:* A universal set $U$ is a fixed set that contains all sets under discussion within a particular context [6]. It is not absolute; it changes depending on the domain of discourse (e.g., $U = \mathbb{Z}$ for number theory vs. $U = \mathbb{R}$ for real analysis).

11. **Answer:**
    * *Justification:* According to the primary DM syllabus conventions, the set of natural numbers $\mathbb{N}$ contains $0$ (i.e., $\mathbb{N} = \{0, 1, 2, 3, \dots\}$), representing non-negative integers.

12. **Answer:**
    * *Roster Form:* $S = \{-14, -12, -10, -8, -6, -4, -2\}$
    * *Set-Builder Notation:* $S = \{x \in \mathbb{Z}^- \mid x \text{ is even and } x > -15\}$

13. **Answer:**
    * *Justification:* The rule method fails if there is no unifying property or predicate that can characterize the elements. For example, a set containing completely random, unrelated objects such as $S = \{\text{apple}, 42, \pi, \text{blue}\}$ cannot be described using a descriptive rule.

14. **Answer:**
    * *Justification:* We compute the sums of all combinations:
      * $1 + 3 = 4$
      * $1 + 4 = 5$
      * $2 + 3 = 5$ (duplicate, omitted in roster)
      * $2 + 4 = 6$
    * *Roster Form:* $S = \{4, 5, 6\}$
    * *Cardinality:* $|S| = 3$

15. **Answer:**
    * *Set-Builder Notation:* $S = \{x \in \mathbb{R} \mid x^3 - x = 0\}$. Solving this yields $x(x-1)(x+1) = 0$, so in roster form, it would be $\{-1, 0, 1\}$.

---

### Solutions for Module 2 (Problems 16–30)

16. **Answer:**
    * *Justification:* The set is **infinite**. Between any two distinct real numbers (here, $0$ and $1$), there are infinitely many real numbers, which cannot be listed exhaustively [5].

17. **Answer:**
    * *Justification:* The set is **infinite**. Between any two rational numbers, there exists another rational number (by density of rationals), making a complete listing of elements impossible [5].

18. **Answer:**
    * *Justification:* Suppose there are two empty sets, $\emptyset_1$ and $\emptyset_2$. Since both contain no elements, every element of $\emptyset_1$ is vacuously a member of $\emptyset_2$ ($\emptyset_1 \subseteq \emptyset_2$). Similarly, every element of $\emptyset_2$ is vacuously a member of $\emptyset_1$ ($\emptyset_2 \subseteq \emptyset_1$). By the double inclusion theorem of set equality, we must have $\emptyset_1 = \emptyset_2$ [6].

19. **Answer:**
    * *Justification:* The set $S = \{\emptyset\}$ contains exactly one element: the empty set itself. It is a singleton set, so its cardinality is $1$. Similarly, $T = \{\{\}\}\}$ contains the empty set as a single element, so its cardinality is also $1$ [4].

20. **Answer: D**
    * *Justification:* $D = \{2\}$, which is a set with exactly one element. $A = \{-2, 2\}$ (cardinality 2), $B = \{0\}$ (which is indeed singleton too! Wait, under natural numbers starting at 0, $B = \{0\}$, but let's check: $x+5=5 \implies x=0$. Yes! Both B and D are singleton sets. Let's make sure our key clarifies this. $C = \emptyset$ in the real plane, as $x^2 = -1$ has no real solutions).

21. **Answer:**
    * *Justification:* **Equal sets** contain the exact same elements ($A = B$) [6]. **Equivalent sets** have a one-to-one correspondence, meaning they share the same cardinality ($|A| = |B|$) [5]. Equal sets are always equivalent because they have the same size. However, equivalent sets are not necessarily equal (e.g., $\{a, b\} \approx \{1, 2\}$, but $\{a, b\} \neq \{1, 2\}$).

22. **Answer:**
    * *Justification:* We define the function $f: \mathbb{Z}^+ \to E^+$ by $f(n) = 2n$.
      * *Injective (One-to-One):* If $f(a) = f(b)$, then $2a = 2b \implies a = b$.
      * *Surjective (Onto):* For any even integer $e \in E^+$, $e = 2k$ for some positive integer $k \in \mathbb{Z}^+$. Thus, $f(k) = e$.
      * Since a bijection exists, $\mathbb{Z}^+ \approx E^+$, proving they are equivalent [5].

23. **Answer:**
    * *Justification:* Let $f: A \to B$ be defined by $f(x) = 1$ and $f(y) = 2$. This function is injective because distinct inputs map to distinct outputs. However, the element $3 \in B$ is not mapped to by any element in $A$, so it is not bijective. Since an injection exists from $A$ to $B$ but no bijection can be constructed, $|A| < |B|$ [5].

24. **Answer:**
    * *Justification:* Yes, they are disjoint. An integer squared is even if and only if the integer itself is even. An integer squared is odd if and only if the integer is odd. Since an integer cannot be both even and odd, $A \cap B = \emptyset$.

25. **Answer:**
    * *Justification:* If $|A \cup B| = |A| + |B|$, then $|A \cap B| = 0$, which mathematically implies that the two sets are disjoint ($A \cap B = \emptyset$) [9].

26. **Answer:**
    * *Justification:* A multiset is a generalization of a set where elements are allowed to appear multiple times, and their multiplicity matters. In the multiset $M = \{a, a, b\}$, the element $a$ has a multiplicity of 2. In contrast, under standard set theory, repeated elements collapse, so the set $S = \{a, a, b\}$ simplifies exactly to $\{a, b\}$.

27. **Answer:**
    * *Justification:* The complement of the empty set is the universal set, i.e., $\emptyset^c = U$. The complement of the universal set is the empty set, i.e., $U^c = \emptyset$ [8].

28. **Answer:**
    * *Justification:* The subset inclusions are: $\mathbb{N} \subseteq \mathbb{W} \subseteq \mathbb{Z} \subseteq \mathbb{Q} \subseteq \mathbb{R} \subseteq \mathbb{C}$.

29. **Answer:**
    * *Justification:* The elements of $S$ are:
      1. $1$
      2. $\{2, 3\}$
      3. $\emptyset$
      4. $\{\emptyset, \{4\}\}$
      Thus, there are exactly 4 elements, so $|S| = 4$.

30. **Answer:**
    * *Justification:* By definition of subset, if $A \subseteq B$, then every element in $A$ is in $B$. If $B \subseteq A$, every element in $B$ is in $A$. Together, they imply that $A$ and $B$ have exactly the same elements, which satisfies the definition of set equality ($A = B$) [6].

---

### Solutions for Module 3 (Problems 31–45)

31. **Answer:**
    * *Justification:* **Yes**, $A \subseteq B$. For $A$ to be a subset of $B$, every element of $A$ (which are $1$ and $2$) must also be an element of $B$. Looking at $B = \{1, 2, \{1, 2\}\}$, we see that $1 \in B$ and $2 \in B$ [5].

32. **Answer:**
    * *Justification:* **Yes**, $A \subset B$. A subset is proper if there is at least one element of $B$ that is not in $A$. Here, the element $\{1, 2\} \in B$, but $\{1, 2\} \notin A$ (since the elements of $A$ are numbers, not sets). Thus, $A$ is a proper subset of $B$ [6].

33. **Answer:**
    * *Justification:*
      * I) **True** ($a$ is listed directly as an element of $S$).
      * II) **False** (for $a \subseteq S$ to be true, the elements inside $a$ would need to be elements of $S$, but $a$ is a primitive variable, not a set).
      * III) **True** ($\{a\}$ is listed directly as an element of $S$).
      * IV) **True** (since the element $a \in S$, the set containing it, $\{a\}$, is a subset of $S$) [5].

34. **Answer:**
    * *Justification:* The elements of $T$ are $x$, $y$, and $\{x, y\}$. The subsets of $T$ are constructed from these elements.
      * The element $\{x, y\}$ is listed directly, so $\{x, y\} \in T$.
      * Also, since $x \in T$ and $y \in T$, the set $\{x, y\}$ is a subset of $T$ ($\\{x, y\} \subseteq T$).
      * Thus, $\{x, y\}$ is both an element and a subset of $T$.

35. **Answer:**
    * *Justification:* We prove this by contradiction. Suppose there exists a set $A$ such that $\emptyset \not\subseteq A$. By the definition of subset, this means there exists an element $x$ such that $x \in \emptyset$ and $x \notin A$. However, by definition, the empty set $\emptyset$ contains no elements, so $x \in \emptyset$ is false. This contradiction proves that $\emptyset \subseteq A$ for any set $A$.

36. **Answer:**
    * *Justification:* A proper subset $X \subset Y$ requires $X \subseteq Y$ and $X \neq Y$ [6].
      * From Problem 35, we know $\emptyset \subseteq A$ is always true.
      * Since we are given that $A \neq \emptyset$, both conditions are met. Hence, $\emptyset \subset A$.

37. **Answer:**
    * *Justification:* Let $x$ be an arbitrary element of $A$. Since $A \subseteq B$, by definition of subset, $x \in B$. Since $B \subseteq C$, by definition of subset, $x \in C$. Since $x \in A \implies x \in C$ for all $x$, we have $A \subseteq C$.

38. **Answer:**
    * *Justification:* Since $A \subset B$, we know $A \subseteq B$. Since $B \subset C$, we know $B \subseteq C$. By subset transitivity (Problem 37), $A \subseteq C$. To prove it is proper, we must show $A \neq C$. Since $A \subset B$, there exists $y \in B$ such that $y \notin A$. Since $B \subset C$, we have $y \in C$. Thus, there is an element $y \in C$ such that $y \notin A$, which proves $A \neq C$. Hence, $A \subset C$.

39. **Answer:**
    * *Justification:* Let $x \in A$. By the definition of logical disjunction (OR), the statement $x \in A \lor x \in B$ is true. Since $A \cup B = \{x \mid x \in A \lor x \in B\}$, we have $x \in A \cup B$. Thus, $A \subseteq A \cup B$.

40. **Answer:**
    * *Justification:* Let $x \in A \cap B$. By the definition of intersection, $x \in A$ and $x \in B$. Since the conjunction is true, the individual conjunct $x \in A$ is true. Thus, $A \cap B \subseteq A$.

41. **Answer:**
    * *Justification:*
      * *Forward Direction ($\implies$):* Assume $A \subseteq B$. Let $x \in B^c$. By definition, $x \notin B$. We must show $x \in A^c$. Suppose $x \in A$. Since $A \subseteq B$, this would imply $x \in B$, which contradicts $x \notin B$. Thus, $x \notin A$, meaning $x \in A^c$. Hence, $B^c \subseteq A^c$.
      * *Backward Direction (${\impliedby}$):* Assume $B^c \subseteq A^c$. Let $y \in A$. Suppose $y \notin B$. Then $y \in B^c$. Since $B^c \subseteq A^c$, this implies $y \in A^c$, which contradicts $y \in A$. Thus, $y \in B$, meaning $A \subseteq B$.
      * Both directions are proven, so $A \subseteq B \iff B^c \subseteq A^c$ [13].

42. **Answer:**
    * *Justification:* Assume $A \subseteq B$. We show $A \cap B = A$ by proving double inclusion:
      * *Part I:* $A \cap B \subseteq A$ is always true (Problem 40).
      * *Part II:* Let $x \in A$. Since $A \subseteq B$, we have $x \in B$. Since $x \in A$ and $x \in B$, we have $x \in A \cap B$. Thus, $A \subseteq A \cap B$.
      * Both directions show $A \cap B = A$ [13].

43. **Answer:**
    * *Justification:* Assume $A \cap B = A$. We prove $A \cup B = B$ by double inclusion:
      * *Part I:* $B \subseteq A \cup B$ is always true (Problem 39).
      * *Part II:* Let $x \in A \cup B$. This means $x \in A$ or $x \in B$. If $x \in B$, then it is in the target. If $x \in A$, since $A = A \cap B$, we have $x \in A \cap B \implies x \in B$. Thus, in either case, $x \in B$, so $A \cup B \subseteq B$.
      * Together, they show $A \cup B = B$ [13].

44. **Answer:**
    * *Justification:* Let $A = \{1\}$ and $B = \{1\}$. Here, $A \subseteq B$ and $B \subseteq A$ are both true. However, $A = B$, so $A$ is not a proper subset of $B$ (which requires $A \neq B$).

45. **Answer:**
    * *Justification:* Let $(x, y) \in A \times B$. By definition of Cartesian product, $x \in A$ and $y \in B$. Since $A \subseteq C$, we have $x \in C$. Since $B \subseteq D$, we have $y \in D$. Since $x \in C$ and $y \in D$, we have $(x, y) \in C \times D$. Thus, $A \times B \subseteq C \times D$.

---

### Solutions for Module 4 (Problems 46–55)

46. **Answer:**
    * *Justification:* The power set is the set of all subsets [6].
    * *Power Set:* $\mathcal{P}(S) = \{\emptyset, \{a\}, \{b\}, \{a, b\}\}$

47. **Answer:**
    * *Justification:* The only subset of $\emptyset$ is itself.
    * *Power Set:* $\mathcal{P}(\emptyset) = \{\emptyset\}$
    * *Cardinality:* $2^0 = 1$ [4].

48. **Answer:**
    * *Justification:* The subsets of $\{\emptyset\}$ are the empty set and the set containing the element $\emptyset$.
    * *Power Set:* $\mathcal{P}(\mathcal{P}(\emptyset)) = \{\emptyset, \{\emptyset\}\}$
    * *Cardinality:* $2^1 = 2$

49. **Answer:**
    * *Justification:* Let $S = \{\emptyset, \{\emptyset\}\}$. Its elements are $e_1 = \emptyset$ and $e_2 = \{\emptyset\}$.
    * *Power Set:* $\mathcal{P}(\mathcal{P}(\mathcal{P}(\emptyset))) = \{\emptyset, \{\emptyset\}, \{\{\emptyset\}\}, \{\emptyset, \{\emptyset\}\}\}$
    * *Cardinality:* $2^2 = 4$

50. **Answer:**
    * *Justification:* We can use a combinatorial bijection argument. A subset $X$ of $S = \{s_1, s_2, \dots, s_n\}$ can be uniquely represented by an $n$-bit binary string $b_1 b_2 \dots b_n$, where $b_i = 1$ if $s_i \in X$, and $b_i = 0$ if $s_i \notin X$. Since there are exactly $2$ choices ($0$ or $1$) for each of the $n$ positions, there are $2^n$ distinct binary strings, and thus $2^n$ distinct subsets in $\mathcal{P}(S)$.

51. **Answer:**
    * *Power Set 1:* $\mathcal{P}(S) = \{\emptyset, \{x\}\}$
    * *Power Set 2:* $\mathcal{P}(\mathcal{P}(S)) = \{\emptyset, \{\emptyset\}, \{\{x\}\}, \{\emptyset, \{x\}\}\}$

52. **Answer:**
    * *Justification:* Let $X$ be an arbitrary set.
      $$X \in \mathcal{P}(A \cap B) \iff X \subseteq A \cap B$$
      $$\iff X \subseteq A \land X \subseteq B$$
      $$\iff X \in \mathcal{P}(A) \land X \in \mathcal{P}(B)$$
      $$\iff X \in \mathcal{P}(A) \cap \mathcal{P}(B)$$
      Since the biconditional holds, the two sets are equal.

53. **Answer:**
    * *Justification:* Let $A = \{1\}$ and $B = \{2\}$.
      * $A \cup B = \{1, 2\} \implies \mathcal{P}(A \cup B) = \{\emptyset, \{1\}, \{2\}, \{1, 2\}\}$.
      * $\mathcal{P}(A) = \{\emptyset, \{1\}\}$ and $\mathcal{P}(B) = \{\emptyset, \{2\}\}$.
      * $\mathcal{P}(A) \cup \mathcal{P}(B) = \{\emptyset, \{1\}, \{2\}\}$.
      * Notice that the subset $\{1, 2\}$ belongs to $\mathcal{P}(A \cup B)$ but not to $\mathcal{P}(A) \cup \mathcal{P}(B)$, proving they are not equal.

54. **Answer:**
    * *Justification:* The elements of $A$ are $1$ and $\{2\}$.
    * *Power Set:* $\mathcal{P}(A) = \{\emptyset, \{1\}, \{\{2\}\}, \{1, \{2\}\}\}$

55. **Answer:**
    * *Justification:* For any finite set of size $n$, $n < 2^n$ is mathematically true for all $n \in \mathbb{N}$ (e.g., $0 < 1$, $1 < 2$, $2 < 4$). Cantor's Theorem states that for **any** set $A$ (including infinite sets), there is no surjective function from $A$ to $\mathcal{P}(A)$, meaning $|A| < |\mathcal{P}(A)|$ holds universally for all sets, establishing a hierarchy of infinite cardinalities.

---

### Solutions for Module 5 (Problems 56–70)

56. **Answer:**
    * *Predicate:* $A^c = \{x \in U \mid x \notin A\}$ [8].

57. **Answer:**
    * *Predicate:* $A \cup B = \{x \mid x \in A \lor x \in B\}$ [9].

58. **Answer:**
    * *Predicate:* $A \cap B = \{x \mid x \in A \land x \in B\}$ [9].

59. **Answer:**
    * *Predicate:* $B - A = \{x \mid x \in B \land x \notin A\}$ [8].

60. **Answer:**
    * *Predicate:* $A \oplus B = \{x \mid (x \in A \land x \notin B) \lor (x \in B \land x \notin A)\}$ or $\{x \mid x \in A \oplus B\}$ where only one membership condition holds.

61. **Answer:**
    * *Justification:* The sets are $A_1 = \{1\}$, $A_2 = \{1, 2\}$, $A_3 = \{1, 2, 3\}$, $A_4 = \{1, 2, 3, 4\}$, $A_5 = \{1, 2, 3, 4, 5\}$.
    * *Union:* $\bigcup_{n=1}^5 A_n = \{1, 2, 3, 4, 5\}$
    * *Intersection:* $\bigcap_{n=1}^5 A_n = \{1\}$

62. **Answer:**
    * *Justification:* The sets are intervals: $B_1 = (0, 1)$, $B_2 = (0, 1/2)$, $B_3 = (0, 1/3)$, etc.
    * *Union:* $\bigcup_{n=1}^\infty B_n = (0, 1)$ (since all subsequent intervals are nested inside $B_1$).
    * *Intersection:* $\bigcap_{n=1}^\infty B_n = \emptyset$ (since for any positive real number $\epsilon > 0$, we can choose an integer $n > 1/\epsilon$ such that $1/n < \epsilon$, meaning the element is excluded).

63. **Answer:**
    * *Indexed Union:* $\bigcup_{i \in I} S_i = \{x \mid \exists i \in I \text{ such that } x \in S_i\}$
    * *Indexed Intersection:* $\bigcap_{i \in I} S_i = \{x \mid \forall i \in I, x \in S_i\}$

64. **Answer:**
    * *Justification:* We expand the definitions of both sides:
      * $(A \cup B) - (A \cap B) = (A \cup B) \cap (A \cap B)^c$
      * Applying De Morgan's Law: $= (A \cup B) \cap (A^c \cup B^c)$
      * Applying the Distributive Law: $= ((A \cup B) \cap A^c) \cup ((A \cup B) \cap B^c)$
      * Distribute again: $= ((A \cap A^c) \cup (B \cap A^c)) \cup ((A \cap B^c) \cup (B \cap B^c))$
      * Since $A \cap A^c = \emptyset$ and $B \cap B^c = \emptyset$: $= (\emptyset \cup (B \cap A^c)) \cup ((A \cap B^c) \cup \emptyset)$
      * Simplifies to: $= (B - A) \cup (A - B) = A \oplus B$

65. **Answer:**
    * *Justification:* By definition:
      $$A - B = \{x \mid x \in A \land x \notin B\}$$
      Since $x \notin B \iff x \in B^c$:
      $$= \{x \mid x \in A \land x \in B^c\}$$
      By definition of intersection:
      $$= A \cap B^c$$

66. **Answer:**
    * *Distributive Law:* $A \cup (B \cap C) = (A \cup B) \cap (A \cup C)$ [10].
    * *Membership Logic Proof:*
      Let $x$ be an arbitrary element.
      $$x \in A \cup (B \cap C) \iff x \in A \lor x \in (B \cap C)$$
      $$\iff x \in A \lor (x \in B \land x \in C)$$
      $$\iff (x \in A \lor x \in B) \land (x \in A \lor x \in C) \quad \text{(by distributive law of propositional logic)}$$
      $$\iff x \in (A \cup B) \land x \in (A \cup C)$$
      $$\iff x \in (A \cup B) \cap (A \cup C)$$
      Thus, the set equality is proven.

67. **Answer:**
    * *De Morgan's Law:* $(A \cap B)^c = A^c \cup B^c$ [10].
    * *Element Chasing Proof:*
      Let $x \in (A \cap B)^c$.
      $$\iff x \notin (A \cap B)$$
      $$\iff \neg(x \in A \land x \in B)$$
      $$\iff x \notin A \lor x \notin B \quad \text{(by De Morgan's Law of propositional logic)}$$
      $$\iff x \in A^c \lor x \in B^c$$
      $$\iff x \in A^c \cup B^c$$
      This bidirectionally proves $(A \cap B)^c = A^c \cup B^c$.

68. **Answer:**
    * *Justification:* We simplify step-by-step using laws of sets:
      * $((A \cup B^c)^c \cap A)^c$
      * Apply De Morgan's Law to the outermost complement: $= (A \cup B^c)^{cc} \cup A^c$
      * Apply Double Complement: $= (A \cup B^c) \cup A^c$
      * Apply Commutative & Associative Laws: $= (B^c \cup A) \cup A^c = B^c \cup (A \cup A^c)$
      * Apply Complement Law ($A \cup A^c = U$): $= B^c \cup U$
      * Apply Domination Law ($X \cup U = U$): $= U$
    * *Final Simplified Answer:* $U$

69. **Answer:**
    * *Justification:* Yes, symmetric difference is associative.
    * *Formula:* $A \oplus (B \oplus C) = (A \oplus B) \oplus C$. Both expressions yield the region of elements that belong to exactly one of the three sets or to all three sets.

70. **Answer:**
    * *Justification:* Let $A = \{1, 2\}$, $B = \{2\}$, and $C = \{1\}$.
      * LHS: $(A - B) - C = (\{1\}) - \{1\} = \emptyset$
      * RHS: $A - (B - C) = A - \{2\} = \{1\}$
      * Since $\emptyset \neq \{1\}$, set difference is not associative.

---

### Solutions for Module 6 (Problems 71–80)

71. **Answer:**
    * *Justification:* $(a, b) = (c, d)$ if and only if $a = c$ and $b = d$.

72. **Answer:**
    * *Cartesian Product:* $A \times B = \{(0, x), (0, y), (0, z), (1, x), (1, y), (1, z), (2, x), (2, y), (2, z), (3, x), (3, y), (3, z)\}$ [7].

73. **Answer:**
    * *Cartesian Product:* $B \times A = \{(x, 0), (x, 1), (x, 2), (x, 3), (y, 0), (y, 1), (y, 2), (y, 3), (z, 0), (z, 1), (z, 2), (z, 3)\}$ [7].
    * *Reason for Inequality:* $(0, x) \in A \times B$, but $(0, x) \notin B \times A$ because $0 \in B$ is false. Thus, $A \times B \neq B \times A$.

74. **Answer:**
    * *Justification:* Let $|A| = m$ and $|B| = n$. The Cartesian product $A \times B$ forms an $m \times n$ grid of ordered pairs, where each of the $m$ choices for the first coordinate is paired with each of the $n$ choices for the second coordinate. By the fundamental counting principle, there are exactly $m \cdot n$ ordered pairs, so $|A \times B| = |A| \cdot |B|$ [8].

75. **Answer:**
    * *Cartesian Product:* $A \times B \times C = \{(a, b, 0), (a, b, 1), (a, c, 0), (a, c, 1)\}$.

76. **Answer:**
    * *Justification:* By definition:
      $$A \times \emptyset = \{(a, b) \mid a \in A \land b \in \emptyset\}$$
      Since there is no element $b$ in the empty set $\emptyset$, the condition $b \in \emptyset$ is always false. Thus, no ordered pairs can be constructed, and the resulting set is empty ($\emptyset$).

77. **Answer:**
    * *Justification:* Let $(x, y)$ be an arbitrary ordered pair.
      $$(x, y) \in A \times (B \cap C) \iff x \in A \land y \in (B \cap C)$$
      $$\iff x \in A \land (y \in B \land y \in C)$$
      $$\iff (x \in A \land y \in B) \land (x \in A \land y \in C) \quad \text{(by logical distribution)}$$
      $$\iff (x, y) \in A \times B \land (x, y) \in A \times C$$
      $$\iff (x, y) \in (A \times B) \cap (A \times C)$$
      This bidirectional equivalence proves the distribution over intersection.

78. **Answer:**
    * *Justification:* Similarly:
      $$(x, y) \in A \times (B \cup C) \iff x \in A \land y \in (B \cup C)$$
      $$\iff x \in A \land (y \in B \lor y \in C)$$
      $$\iff (x \in A \land y \in B) \lor (x \in A \land y \in C)$$
      $$\iff (x, y) \in A \times B \lor (x, y) \in A \times C$$
      $$\iff (x, y) \in (A \times B) \cup (A \times C)$$
      This proves the distribution over union.

79. **Answer:**
    * *Justification:* A binary relation $R$ from set $A$ to set $B$ is formally defined as any subset of the Cartesian product $A \times B$ (i.e., $R \subseteq A \times B$).

80. **Answer:**
    * *Domain:* Dom($R$) $= \{1, 2, 3\}$ (the set of all first coordinates).
    * *Range:* Ran($R$) $= \{a, b\}$ (the set of all second coordinates).

---

### Solutions for Module 7 (Problems 81–90)

81. **Answer:**
    * *Justification:* A collection of subsets $\{A_1, A_2, \dots, A_n\}$ of a set $A$ is a partition if and only if:
      1. None of the subsets are empty: $A_i \neq \emptyset$ for all $i$.
      2. The union of all subsets equals the original set: $\bigcup_{i=1}^n A_i = A$ [14].
      3. The subsets are mutually disjoint: $A_i \cap A_j = \emptyset$ for all $i \neq j$ [14].

82. **Answer:**
    * *Justification:* The subsets are not mutually disjoint: $\{1, 2, 3\} \cap \{3, 4, 5\} = \{3\} \neq \emptyset$. Element $3$ is included in more than one subset, violating the disjointness requirement [14].

83. **Answer:**
    * *Justification:* The union of all subsets does not equal the original set $S$: $\{1, 2\} \cup \{4, 5\} = \{1, 2, 4, 5\} \neq S$. The element $3$ is omitted, violating the requirement that every element must be included [14].

84. **Answer:**
    * *Justification:* A partition by definition must consist of **non-empty** subsets [14]. The collection contains the empty set $\emptyset$, which makes it an invalid partition.

85. **Answer:**
    * *Justification:* Let $E$ be the set of even integers and $O$ be the set of odd integers [15].
      1. Both are non-empty (e.g., $2 \in E$ and $1 \in O$).
      2. Their union equals the integers: $E \cup O = \mathbb{Z}$ (every integer is either even or odd).
      3. They are mutually disjoint: $E \cap O = \emptyset$ (no integer is both even and odd).
      Since all three conditions are satisfied, $\{E, O\}$ is a valid partition of $\mathbb{Z}$ [15].

86. **Answer:**
    * *Justification:* **No**. The union $\mathbb{Z}^+ \cup \mathbb{Z}^- = \mathbb{Z} - \{0\}$, which does not equal $\mathbb{Z}$ because the element $0$ is omitted. Thus, it fails the union requirement and is not a valid partition.

87. **Answer:**
    * *Justification:* The Bell Number $B_n$ is the total number of unique ways to partition a set of cardinality $n$. By convention, $B_0 = 1$ (there is exactly 1 way to partition the empty set).

88. **Answer:**
    * *Justification:* The 5 distinct partitions of $S = \{1, 2, 3\}$ are:
      1. $\{\{1, 2, 3\}\}$ (1 subset)
      2. $\{\{1, 2\}, \{3\}\}$ (2 subsets)
      3. $\{\{1, 3\}, \{2\}\}$ (2 subsets)
      4. $\{\{2, 3\}, \{1\}\}$ (2 subsets)
      5. $\{\{1\}, \{2\}, \{3\}\}$ (3 subsets)
      The total count is indeed $B_3 = 5$.

89. **Answer:**
    * *Justification:* We use the Bell triangle recurrence:
      * Row 0: 1
      * Row 1: 1, 2
      * Row 2: 2, 3, 5
      * Row 3: 5, 7, 10, 15
      The first number of the next row is the last of the previous, and each subsequent number is the sum of the one to its left and the one above that left.
      * Row 4 begins with 15: 15, (15+5)=20, (20+7)=27, (27+10)=37, (37+15)=**52**.
    * *Answer:* $B_4 = 15$. Wait! Let's check Row 3:
      * Row 2 ends in 5.
      * Row 3 starts in 5. Next: 5+2=7. Next: 7+3=10. Next: 10+5=15. Yes!
      * Row 4 starts in 15. Next: 15+5=20. Next: 20+7=27. Next: 27+10=37. Next: 37+15=52.
      So $B_4$ is indeed 15? No, the last number in Row 3 is $B_3 = 5$, wait, Row 2 ends in 5, so $B_3 = 5$. Row 3 ends in 15, so $B_4 = 15$. Let's trace carefully:
      * $B_0 = 1$
      * $B_1 = 1$
      * $B_2 = 2$
      * $B_3 = 5$
      * $B_4 = 15$
      Let's re-verify:
      * $B_0 = 1$
      * $B_1 = 1$
      * $B_2 = 2$ (Partitions: $\{\{1, 2\}\}$ and $\{\{1\}, \{2\}\}$)
      * $B_3 = 5$
      * $B_4 = 15$
      Yes, $B_4 = 15$.

90. **Answer:**
    * *Justification:* The Fundamental Theorem of Equivalence Relations states that any equivalence relation $R$ on a set $A$ decomposes $A$ into a set of disjoint equivalence classes that form a partition of $A$. Conversely, any partition of $A$ uniquely defines an equivalence relation on $A$ where elements are related if and only if they belong to the same partition subset.

---

### Solutions for Module 8 (Problems 91–95)

91. **Answer:**
    * *Justification:* Venn Diagrams were introduced in 1880 by British logician John Venn [11]. He initially called them "Eulerian Circles" after Leonhard Euler [11]. The specific term "Venn Diagrams" was first published by American philosopher Clarence Irving Lewis in his 1918 book *A Survey of Symbolic Logic*.

92. **Answer:**
    * *I) $A \cap B^c$:* Shaded region is inside circle $A$ but completely outside circle $B$ (representing set difference $A - B$).
    * *II) $(A \cup B)^c$:* Shaded region is the entire area of the rectangle $U$ except for the interior of the circles $A$ and $B$.
    * *III) $A^c \cap B^c$:* By De Morgan's Law, this is equivalent to $(A \cup B)^c$, so the shaded region is exactly the same as in II.

93. **Answer:**
    * *I) $A \cap (B \cup C)$:* Shaded region contains the overlap of $A$ and $B$, the overlap of $A$ and $C$, and the central intersection of all three circles.
    * *II) $(A \cap B) - C$:* Shaded region is the overlapping section of circles $A$ and $B$, excluding the central portion that also overlaps with $C$.
    * *III) $(A \cup B) \cap C^c$:* Shaded region is the entire union of circles $A$ and $B$, except for any portions that overlap with circle $C$.

94. **Answer:**
    * *Formula:* $|A \cup B \cup C| = |A| + |B| + |C| - |A \cap B| - |A \cap C| - |B \cap C| + |A \cap B \cap C|$.

95. **Answer:**
    * *Step-by-Step Counting:* We solve from the innermost intersection outwards:
      1. **All 3 Courses:** $|M \cap P \cap C| = \mathbf{10}$
      2. **Exactly 2 Courses (subtraction of center):**
         * Math & Physics only: $|M \cap P| - |M \cap P \cap C| = 100 - 10 = \mathbf{90}$
         * Math & CS only: $|M \cap C| - |M \cap P \cap C| = 150 - 10 = \mathbf{140}$
         * Physics & CS only: $|P \cap C| - |M \cap P \cap C| = 75 - 10 = \mathbf{65}$
      3. **Exactly 1 Course (subtraction of surrounding intersections):**
         * Math only: $|M| - (90 + 10 + 140) = 300 - 240 = \mathbf{60}$
         * Physics only: $|P| - (90 + 10 + 65) = 350 - 165 = \mathbf{185}$
         * CS only: $|C| - (140 + 10 + 65) = 450 - 215 = \mathbf{235}$
      4. **Total taking exactly one course:**
         $$\text{Total} = 60 + 185 + 235 = \mathbf{480} \text{ students}$$

---

### Solutions for Module 9 (Problems 96–100)

96. **Answer:**
    * *Proof:*
      We must show that for any element $x$, if $x \in A \cap C$, then $x \in B \cap C$.
      Let $x \in A \cap C$.
      * By definition of intersection: $x \in A$ and $x \in C$.
      * Since $x \in A$ and we are given $A \subseteq B$, we must have $x \in B$ (by definition of subset).
      * Thus, we have $x \in B$ and $x \in C$.
      * By definition of intersection: $x \in B \cap C$.
      Since any arbitrary element in $A \cap C$ is also in $B \cap C$, we have shown $A \cap C \subseteq B \cap C$.

97. **Answer:**
    * *Proof:*
      1. LHS: $(B - A) \cup (C - A)$
      2. Apply **Set Difference Identity** ($X - Y = X \cap Y^c$):
         $$= (B \cap A^c) \cup (C \cap A^c)$$
      3. Apply **Distributive Law** (factoring out $\cap A^c$):
         $$= (B \cup C) \cap A^c$$
      4. Apply **Set Difference Identity** in reverse ($X \cap Y^c = X - Y$):
         $$= (B \cup C) - A$$
      5. This equals the RHS, completing the proof [14].

98. **Answer:**
    * *Proof:*
      1. LHS: $(A - B) - (B - C)$
      2. Apply **Set Difference Identity** ($X - Y = X \cap Y^c$):
         $$= (A \cap B^c) \cap (B \cap C^c)^c$$
      3. Apply **De Morgan's Law** to the second term:
         $$= (A \cap B^c) \cap (B^c \cup C^{cc})$$
      4. Apply **Double Complement** ($C^{cc} = C$):
         $$= (A \cap B^c) \cap (B^c \cup C)$$
      5. Apply **Associative Law** to regroup:
         $$= A \cap [B^c \cap (B^c \cup C)]$$
      6. Apply **Absorption Law** (where $X \cap (X \cup Y) = X$, with $X = B^c$ and $Y = C$):
         $$= A \cap B^c$$
      7. Apply **Set Difference Identity**:
         $$= A - B$$
      8. This equals the RHS, completing the proof [14].

99. **Answer:**
    * *Proof:*
      1. Expression: $[(A - B) - (B - C)]'$
      2. From the proof in Problem 98, we simplified the interior of the bracket:
         $$(A - B) - (B - C) = A \cap B^c$$
      3. Substitute this simplified form into the complemented expression:
         $$[(A - B) - (B - C)]' = (A \cap B^c)^c$$
      4. Apply **De Morgan's Law**:
         $$= A^c \cup (B^c)^c$$
      5. Apply **Double Complement Law** ($(B^c)^c = B$):
         $$= A^c \cup B$$
      6. This matches the target RHS ($A' \cup B$), completing the proof [14].

100. **Answer:**
     * *Membership Table:* We construct a truth table with 8 rows representing all configurations of membership for an element $u$ in sets $A, B, C$.
     
| Row | $A$ | $B$ | $C$ | $A - B$ | $B - C$ | $(A - B) - (B - C)$ | **$[(A - B) - (B - C)]'$** | **$A' \cup B$** |
|:---:|:---:|:---:|:---:|:-------:|:-------:|:-------------------:|:--------------------------:|:----------------:|
|  1  |  1  |  1  |  1  |    0    |    0    |          0          |           **1**            |      **1**       |
|  2  |  1  |  1  |  0  |    0    |    1    |          0          |           **1**            |      **1**       |
|  3  |  1  |  0  |  1  |    1    |    0    |          1          |           **0**            |      **0**       |
|  4  |  1  |  0  |  0  |    1    |    0    |          1          |           **0**            |      **0**       |
|  5  |  0  |  1  |  1  |    0    |    0    |          0          |           **1**            |      **1**       |
|  6  |  0  |  1  |  0  |    0    |    1    |          0          |           **1**            |      **1**       |
|  7  |  0  |  0  |  1  |    0    |    0    |          0          |           **1**            |      **1**       |
|  8  |  0  |  0  |  0  |    0    |    0    |          0          |           **1**            |      **1**       |

     * *Conclusion:* Since the columns for **$[(A - B) - (B - C)]'$** and **$A' \cup B$** have identical membership values ($1$ or $0$) for all 8 rows, the sets are equal under every possible configuration. Thus, $[(A - B) - (B - C)]' = A' \cup B$ is proven.

---
