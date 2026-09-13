# CMSC 56: 50-Item Set Theory Practice Quiz & Answer Key

This 50-item practice quiz is structured around the 8 core fundamental questions of set theory from **CMSC 56 Week 1 (1.-SETS.pdf)**. Work through the questions to test your knowledge, then review the complete step-by-step Answer Key and explanations at the end of the document.

---

## Part I: The 50 Practice Quiz Questions

### Section 1: Set vs. Non-Set (Questions 1–6)
*Target Question 1: Differentiate a set from a non-set. Give at least two examples of each.*

1. **Definition of a Set:** Which of the following best defines a mathematical set? [2]
   - A) A list of numbers ordered from least to greatest.
   - B) A collection of well-defined objects.
   - C) A group of items that share identical physical attributes.
   - D) An arbitrary sequence of symbols enclosed in parentheses.

2. **Well-Defined Criterion:** What does it mean for a collection of objects to be "well-defined"? [2]
   - A) The elements must be written in alphabetical order.
   - B) There is a clear, objective rule determining whether any given object belongs or does not belong to the collection.
   - C) The collection must contain a finite number of items.
   - D) Every object in the collection must be a real number.

3. **Identifying Sets vs. Non-Sets (Example Analysis I):** Consider the following two collections:
   - Collection X: The collection of all vowels in the English alphabet.
   - Collection Y: The collection of all good movies released in 2023.
   Which statement correctly classifies Collections X and Y? [2]
   - A) Both X and Y are sets.
   - B) Both X and Y are non-sets.
   - C) X is a set because membership is objective; Y is a non-set because "good" is subjective.
   - D) X is a non-set because letters are not numbers; Y is a set.

4. **Identifying Sets vs. Non-Sets (Example Analysis II):** Consider the following two collections:
   - Collection P: The collection of all prime numbers less than 20.
   - Collection Q: The collection of all difficult math problems.
   Which statement is true? [2]
   - A) P is a set ($\\{2, 3, 5, 7, 11, 13, 17, 19\\}$) and Q is a non-set because difficulty is subjective.
   - B) Q is a set and P is a non-set.
   - C) Both P and Q are well-defined sets.
   - D) Neither P nor Q is a valid set.

5. **Element Membership Notation:** If object $x$ belongs to set $A$, we write $x \in A$. If object $y$ does not belong to set $A$, how is this expressed? [2]
   - A) $y \subset A$
   - B) $y \notin A$
   - C) $y \neq A$
   - D) $y \cap A$

6. **Distinguishing Non-Sets in Computer Science:** Why are subjective phrases (e.g., "fast algorithms", "popular websites") non-sets in computer science data structures? [2]
   - A) Because computer databases cannot store text string values.
   - B) Because without an objective predicate, membership cannot be evaluated deterministically by an algorithm.
   - C) Because non-sets always contain infinite elements.
   - D) Because set operations like union cannot be defined on non-numerical sets.

---

### Section 2: Describing Sets (Questions 7–12)
*Target Question 2: What are the two major ways to describe sets?*

7. **Major Description Methods:** What are the two major methods used to describe a set? [3]
   - A) Matrix Method and Graphical Method
   - B) Roster (List) Method and Rule (Set-Builder) Method
   - C) Decimal Form and Fractional Form
   - D) Primary Method and Secondary Method

8. **Roster Method Mechanics:** In the roster method, how are set elements displayed? [3]
   - A) Enumerated, separated by commas, and enclosed in braces $\{\}$.
   - B) Listed in a single vertical column without punctuation.
   - C) Written inside brackets $[ ]$ with mathematical plus signs.
   - D) Stated as an English sentence without symbols.

9. **The Roster Method Distinctness Rule:** A student writes the set of letters in the word `"DATABASE"` in roster form as $S = \{D, A, T, A, B, A, S, E\}$. Why is this representation incorrect? [3]
   - A) Capital letters are not allowed in roster form.
   - B) In the roster method, all listed elements must be distinct (no duplicates).
   - C) The elements must be sorted in alphabetical order.
   - D) Words with more than 5 letters cannot be converted to roster form.

10. **Rule (Set-Builder) Method Mechanics:** How does the rule method define set membership? [3]
    - A) By explicitly listing every single element individually.
    - B) By stating a descriptive phrase or predicate that gives the common property satisfied by all elements.
    - C) By displaying a geometric circle containing dots.
    - D) By assigning a numerical index to each element.

11. **Converting Roster to Rule Form:** What is the correct rule method description for $V = \{a, e, i, o, u\}$? [3]
    - A) $V = \{x \mid x \text{ is a letter in the English alphabet}\}$
    - B) $V = \{x \mid x \text{ is a vowel in the English alphabet}\}$
    - C) $V = \{x \mid x \text{ is a consonant in the English alphabet}\}$
    - D) $V = \{x \in \mathbb{Z} \mid x \le 5\}$

12. **Limitations of the Rule Method:** According to lecture notes, can *every* possible set be described using the rule method? [3]
    - A) Yes, all sets without exception can be written in rule form.
    - B) No, there are sets that cannot be described using the rule method because no common descriptive property exists for their arbitrary elements.
    - C) Only finite sets can be written in rule form.
    - D) Rule form is only applicable to sets of numbers.

---

### Section 3: Types of Sets (Questions 13–20)
*Target Question 3: Can you name different types of sets?*

13. **Empty (Null) Set:** What is an empty set, and what are its standard notations? [4]
    - A) A set containing the number $0$; denoted by $\{0\}$.
    - B) A set having no elements; denoted by $\emptyset$ or $\{\}$.
    - C) A set with infinite elements; denoted by $\infty$.
    - D) A set containing an empty string; denoted by $\{\""\}$.

14. **Finite vs. Infinite Sets:** What distinguishes a finite set from an infinite set? [4, 5]
    - A) A set is finite if it contains positive numbers; infinite if it contains negative numbers.
    - B) A set is finite if it is possible to write down a complete list of all its elements; otherwise, it is infinite.
    - C) A set is finite if its cardinality is greater than 1,000.
    - D) Finite sets use roster form; infinite sets use Venn diagrams.

15. **Equal Sets vs. Equivalent Sets:** What is the precise distinction between equal sets ($A = B$) and equivalent sets ($A \approx B$)? [5, 6]
    - A) Equal sets have the same cardinality; equivalent sets have the same elements.
    - B) Equal sets have the exact same elements ($A \subseteq B \land B \subseteq A$); equivalent sets have a one-to-one correspondence ($|A| = |B|$).
    - C) Equal sets apply to numbers; equivalent sets apply to text strings.
    - D) There is no distinction; the terms are synonymous.

16. **Subsets ($\subset$ vs $\subseteq$):** Given $A = \{1, 2\}$ and $B = \{1, 2, 3\}$, which statement is true? [5, 6]
    - A) $A \subseteq B$ and $A \subset B$ (A is both a subset and a proper subset of B).
    - B) $A \subseteq B$ but $A \not\subset B$.
    - C) $B \subseteq A$.
    - D) $A = B$.

17. **Universal Set ($U$):** What is the universal set $U$? [6]
    - A) The set of all real and complex numbers in mathematics.
    - B) A fixed set that contains all objects under discussion in a given context.
    - C) The set of all subsets of $A$.
    - D) An infinite set that contains every imaginable object in the universe.

18. **Power Set $\mathcal{P}(A)$:** What is the power set of a set $A$? [6]
    - A) The product of all elements in $A$.
    - B) The set whose elements are all the subsets of set $A$.
    - C) The set of all elements not in $A$.
    - D) The union of set $A$ with the universal set $U$.

19. **Cartesian Product $A \times B$:** How is the Cartesian product $A \times B$ defined? [7]
    - A) The set of all sums $a + b$ where $a \in A$ and $b \in B$.
    - B) The set of all ordered pairs $(a, b)$ where $a \in A$ and $b \in B$.
    - C) The set of elements common to both $A$ and $B$.
    - D) The set of all subsets of $A \cup B$.

20. **Disjoint Sets:** Two sets $A$ and $B$ are classified as disjoint if and only if: [9]
    - A) $A \cup B = U$
    - B) $A \cap B = \emptyset$
    - C) $|A| = |B|$
    - D) $A \subseteq B$

---

### Section 4: Cardinality of a Set (Questions 21–26)
*Target Question 4: What is the cardinality of a set?*

21. **Definition of Cardinality:** What does the cardinality of a finite set $A$, denoted $|A|$, represent? [5]
    - A) The sum of all numerical elements in $A$.
    - B) The number of elements contained in the set $A$.
    - C) The number of operations performed on $A$.
    - D) The largest number in set $A$.

22. **Cardinality of the Empty Set:** What is the cardinality of the empty set $|\emptyset|$? [4, 5]
    - A) $0$
    - B) $1$
    - C) Undefined
    - D) $-1$

23. **Cardinality of Singleton & Nested Sets:** Find the cardinality $|S|$ for $S = \{\emptyset, \{1, 2\}, 3\}$. [5]
    - A) $1$
    - B) $2$
    - C) $3$
    - D) $4$

24. **Power Set Cardinality Formula:** If a set $A$ has cardinality $|A| = n$, what is the cardinality of its power set $|\mathcal{P}(A)|$? [6]
    - A) $n^2$
    - B) $2n$
    - C) $2^n$
    - D) $n!$

25. **Power Set Cardinality Calculation:** If set $M = \{a, b, c, d\}$, what is $|\mathcal{P}(M)|$? [6]
    - A) $4$
    - B) $8$
    - C) $16$
    - D) $32$

26. **Cartesian Product Cardinality Rule:** If $|A| = m$ and $|B| = n$, what is $|A \times B|$? [7, 8]
    - A) $m + n$
    - B) $m \cdot n$
    - C) $m^n$
    - D) $2^{m+n}$

---

### Section 5: Operations on Sets (Questions 27–33)
*Target Question 5: Name at least 4 operations on sets.*

27. **Set Union ($A \cup B$):** The set union $A \cup B$ is formally defined as: [9]
    - A) $\{x \mid x \in A \land x \in B\}$
    - B) $\{x \mid x \in A \lor x \in B\}$
    - C) $\{x \mid x \in A \land x \notin B\}$
    - D) $\{x \mid x \notin A \land x \notin B\}$

28. **Set Intersection ($A \cap B$):** The set intersection $A \cap B$ is formally defined as: [9]
    - A) $\{x \mid x \in A \lor x \in B\}$
    - B) $\{x \mid x \in A \land x \in B\}$
    - C) $\{x \mid x \in U \land x \notin A\}$
    - D) $\{(a, b) \mid a \in A, b \in B\}$

29. **Set Absolute Complement ($A'$ or $A^c$):** What is the absolute complement of set $A$? [8]
    - A) The set of elements in the universal set $U$ that are not in $A$ ($U - A$).
    - B) The set of elements in $A$ that are not in $U$.
    - C) The power set of $A$.
    - D) The empty set $\emptyset$.

30. **Set Difference ($B - A$):** The set difference $B - A$, also called "$B$ but not $A$", is defined as: [8]
    - A) $\{x \mid x \in A \land x \notin B\}$
    - B) $\{x \mid x \in B \land x \notin A\}$
    - C) $\{x \mid x \in B \lor x \in A\}$
    - D) $\{x \mid x \in U \land x \in B\}$

31. **Symmetric Difference ($A \oplus B$ or $A \Delta B$):** What does the symmetric difference $A \oplus B$ represent? [14]
    - A) Elements common to both $A$ and $B$ ($A \cap B$).
    - B) Elements in $A$ or in $B$, but not in both ($(A \cup B) - (A \cap B)$).
    - C) All elements in the universal set $U$.
    - D) The Cartesian product $A \times B$.

32. **Calculating Operations I:** Let $A = \{1, 2, 3, 4\}$ and $B = \{3, 4, 5, 6\}$. What is $A - B$? [8]
    - A) $\{1, 2\}$
    - B) $\{5, 6\}$
    - C) $\{3, 4\}$
    - D) $\{1, 2, 3, 4, 5, 6\}$

33. **Calculating Operations II:** For $A = \{1, 2, 3, 4\}$ and $B = \{3, 4, 5, 6\}$, what is $A \oplus B$? [14]
    - A) $\{3, 4\}$
    - B) $\{1, 2, 5, 6\}$
    - C) $\{1, 2, 3, 4, 5, 6\}$
    - D) $\emptyset$

---

### Section 6: Laws Involving Set Operations (Questions 34–41)
*Target Question 6: Give at least 8 laws involving set operations.*

34. **De Morgan's Laws:** Which of the following equations correctly states one of De Morgan's Laws? [10]
    - A) $(A \cup B)^c = A^c \cap B^c$
    - B) $(A \cup B)^c = A^c \cup B^c$
    - C) $(A \cap B)^c = A \cap B^c$
    - D) $A \cup (B \cap C) = (A \cup B) \cap C$

35. **Distributive Laws:** Which equation represents the Distributive Law for set intersection over union? [10]
    - A) $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$
    - B) $A \cap (B \cup C) = (A \cup B) \cap (A \cup C)$
    - C) $A \cup (B \cup C) = (A \cup B) \cup C$
    - D) $A \cap (B \cap C) = (A \cap B) \cap C$

36. **Absorption Laws:** Which equation represents an Absorption Law in set algebra? [10]
    - A) $A \cup (A \cap B) = A$
    - B) $A \cup A^c = U$
    - C) $A \cap \emptyset = \emptyset$
    - D) $(A^c)^c = A$

37. **Idempotent Laws:** What do the Idempotent Laws state for union and intersection? [10]
    - A) $A \cup \emptyset = A$ and $A \cap U = A$
    - B) $A \cup A = A$ and $A \cap A = A$
    - C) $A \cup A^c = U$ and $A \cap A^c = \emptyset$
    - D) $A \cup U = U$ and $A \cap \emptyset = \emptyset$

38. **Identity Laws:** What are the Identity Laws for set union and intersection? [10]
    - A) $A \cup \emptyset = A$ and $A \cap U = A$
    - B) $A \cup U = U$ and $A \cap \emptyset = \emptyset$
    - C) $A \cup A = A$ and $A \cap A = A$
    - D) $(A^c)^c = A$

39. **Domination (Null) Laws:** What do the Domination Laws state? [10]
    - A) $A \cup U = U$ and $A \cap \emptyset = \emptyset$
    - B) $A \cup \emptyset = A$ and $A \cap U = A$
    - C) $A \cup A^c = U$ and $A \cap A^c = \emptyset$
    - D) $A \cap B = B \cap A$

40. **Inverse (Complement) Laws:** What are the Inverse Laws in set algebra? [10]
    - A) $A \cup A^c = U$ and $A \cap A^c = \emptyset$
    - B) $(A^c)^c = A$
    - C) $\emptyset^c = U$ and $U^c = \emptyset$
    - D) $A - B = A \cap B^c$

41. **Involution (Double Complement) Law:** What does the Involution Law state? [10]
    - A) $(A^c)^c = A$
    - B) $A \cup A^c = U$
    - C) $A \cap A^c = \emptyset$
    - D) $A \cup B = B \cup A$

---

### Section 7: Venn Diagrams and Importance (Questions 42–45)
*Target Question 7: What is a Venn diagram? What is its importance?*

42. **Definition of a Venn Diagram:** What is a Venn diagram? [11]
    - A) A 3D graph used to plot linear equations.
    - B) A pictorial representation of sets where the universal set is represented by a rectangle and its subsets by closed plane figures.
    - C) A tabular matrix recording truth values of 1s and 0s.
    - D) A flowchart showing algorithmic step execution.

43. **Venn Diagram Graphical Components:** In standard Venn diagrams, how are $U$ and its subsets visually represented? [11]
    - A) $U$ is a circle; subsets are rectangles.
    - B) $U$ is the interior of a rectangle; subsets are closed plane figures like circles, triangles, or squares.
    - C) $U$ is an open line segment; subsets are points.
    - D) $U$ is a sphere; subsets are cubes.

44. **Importance of Venn Diagrams I (Problem Solving):** Why are Venn diagrams important in discrete mathematics and real-world applications? [2, 11]
    - A) They eliminate the need to learn algebra.
    - B) They provide a clear visual tool to organize overlapping data, solve multi-set cardinal counting problems, and visualize set operations.
    - C) They automatically calculate infinite series values.
    - D) They replace formal mathematical logic proofs.

45. **Importance of Venn Diagrams II (Proof Method):** How are Venn diagrams used as a formal proof method for set equalities? [11, 12]
    - A) By counting the total number of circles drawn.
    - B) By illustrating both sides of a set statement using Venn diagrams and verifying if both yield identical shaded drawings.
    - C) By converting set operations into decimal numbers.
    - D) By measuring the surface area of the drawn rectangle.

---

### Section 8: Partitions of a Set (Questions 46–50)
*Target Question 8: What is a partition?*

46. **Definition of a Set Partition:** What is a partition of a set $A$? [14]
    - A) A collection of subsets that all share at least one common element.
    - B) A grouping of the set's elements into non-empty subsets such that every element of $A$ is included in one and only one subset.
    - C) The division of a set's cardinality by $2$.
    - D) The power set $\mathcal{P}(A)$ excluding the empty set.

47. **Two Mathematical Conditions for Partitions:** A collection of nonempty sets $\{A_1, A_2, \dots, A_n\}$ is a partition of $A$ if and only if: [14]
    - A) $A_1 \cap A_2 \cap \dots \cap A_n = A$ and subsets are equal.
    - B) $A = A_1 \cup A_2 \cup \dots \cup A_n$ and the subsets are mutually disjoint ($A_i \cap A_j = \emptyset$ for $i \neq j$).
    - C) $|A_1| = |A_2| = \dots = |A_n|$.
    - D) Each subset $A_i$ is a singleton set.

48. **Evaluating Partitions I:** Let $A = \{1, 2, 3, 4, 5, 6\}$. Is $P_1 = \{\{1, 3, 5\}, \{2, 4\}, \{6\}\}$ a valid partition of $A$? [14]
    - A) Yes, because all subsets are non-empty, their union equals $A$, and they are mutually disjoint.
    - B) No, because the subsets have different cardinalities.
    - C) No, because $6$ is in a set by itself.
    - D) No, because it does not contain the empty set.

49. **Evaluating Partitions II:** Let $A = \{1, 2, 3, 4, 5, 6\}$. Why is $P_2 = \{\{1, 2, 3\}, \{3, 4, 5\}, \{6\}\}$ NOT a valid partition of $A$? [14]
    - A) Because the union does not equal $A$.
    - B) Because the subsets are not mutually disjoint (the element $3$ belongs to two subsets).
    - C) Because it contains an even number of subsets.
    - D) Because $A$ is a finite set.

50. **Classic Partition Example:** Do the set of even integers $E$ and the set of odd integers $O$ form a valid partition of the set of integers $\mathbb{Z}$? [15]
    - A) No, because zero is neither even nor odd.
    - B) Yes, because every integer is either even or odd ($E \cup O = \mathbb{Z}$) and no integer is both ($E \cap O = \emptyset$).
    - C) No, because integers are infinite.
    - D) Yes, but only for positive integers.

---

## Part II: Complete Answer Key & Step-by-Step Explanations

### Section 1 Answers
1. **B) A collection of well-defined objects.** [2]  
   *Explanation:* By definition, a set is a collection of well-defined objects [2].
2. **B) There is a clear, objective rule determining whether any given object belongs or does not belong to the collection.** [2]  
   *Explanation:* "Well-defined" means membership is non-ambiguous and deterministic [2].
3. **C) X is a set because membership is objective; Y is a non-set because "good" is subjective.** [2]  
   *Explanation:* Vowels are objectively defined ($a, e, i, o, u$), whereas "good movies" depends on personal opinion [2].
4. **A) P is a set ($\\{2, 3, 5, 7, 11, 13, 17, 19\\}$) and Q is a non-set because difficulty is subjective.** [2]  
   *Explanation:* Prime numbers less than 20 form a strict, objective set; difficulty varies per person [2].
5. **B) $y \notin A$** [2]  
   *Explanation:* The symbol $\in$ denotes element membership, and $\notin$ denotes not an element [2].
6. **B) Because without an objective predicate, membership cannot be evaluated deterministically by an algorithm.** [2]  
   *Explanation:* Computer logic requires exact boolean predicates to decide membership [2].

### Section 2 Answers
7. **B) Roster (List) Method and Rule (Set-Builder) Method** [3]  
   *Explanation:* The two major methods to describe a set are the Roster Method and the Rule Method [3].
8. **A) Enumerated, separated by commas, and enclosed by braces $\{\}$.** [3]  
   *Explanation:* In the roster method, elements are enumerated, separated by commas, and enclosed by braces [3].
9. **B) In the roster method, all listed elements must be distinct (no duplicates).** [3]  
   *Explanation:* An essential rule of the roster method is that listed elements must be distinct! Duplicate letters must be removed, yielding $S = \{D, A, T, B, S, E\}$ [3].
10. **B) By stating a descriptive phrase or predicate that gives the common property satisfied by all elements.** [3]  
    *Explanation:* In the rule method, elements are defined by a descriptive phrase giving their common property [3].
11. **B) $V = \{x \mid x \text{ is a vowel in the English alphabet}\}$** [3]  
    *Explanation:* This rule accurately describes the common property of the elements in $V$ [3].
12. **B) No, there are sets that cannot be described using the rule method because no common descriptive property exists for their arbitrary elements.** [3]  
    *Explanation:* The lecture notes explicitly state: "Note: There are sets which could not be described using the rule method." [3]

### Section 3 Answers
13. **B) A set having no elements; denoted by $\emptyset$ or $\{\}$.** [4]  
    *Explanation:* Sets having no elements are called empty or null sets, denoted by $\emptyset$ or $\{\}$ [4].
14. **B) A set is finite if it is possible to write down a complete list of all its elements; otherwise, it is infinite.** [4, 5]  
    *Explanation:* Classification by size defines a finite set as one where a complete list of elements can be written down [4, 5].
15. **B) Equal sets have the exact same elements ($A \subseteq B \land B \subseteq A$); equivalent sets have a one-to-one correspondence ($|A| = |B|$).** [5, 6]  
    *Explanation:* Equal sets require identical elements ($A=B$), while equivalent sets require a 1-to-1 correspondence ($A \approx B$) [5, 6].
16. **A) $A \subseteq B$ and $A \subset B$** [5, 6]  
    *Explanation:* Every element of $A$ is in $B$ ($A \subseteq B$), and $B$ contains an extra element $3$ not in $A$, making $A$ a proper subset ($A \subset B$) [5, 6].
17. **B) A fixed set that contains all objects under discussion in a given context.** [6]  
    *Explanation:* A universal set $U$ is a fixed set containing all sets under discussion [6].
18. **B) The set whose elements are all the subsets of set $A$.** [6]  
    *Explanation:* The power set $P^A$ or $\mathcal{P}(A)$ is the set whose elements are all subsets of $A$ [6].
19. **B) The set of all ordered pairs $(a, b)$ where $a \in A$ and $b \in B$.** [7]  
    *Explanation:* $A \times B = \{(a, b) \mid a \in A \land b \in B\}$ [7].
20. **B) $A \cap B = \emptyset$** [9]  
    *Explanation:* Two sets are disjoint if their intersection is empty ($A \cap B = \emptyset$) [9].

### Section 4 Answers
21. **B) The number of elements contained in the set $A$.** [5]  
    *Explanation:* Cardinality $|A|$ is the number of elements of a finite set $A$ [5].
22. **A) $0$** [4, 5]  
    *Explanation:* An empty set has no elements, so its cardinality is 0 [4, 5].
23. **C) $3$** [5]  
    *Explanation:* $S$ contains three distinct elements: the element $\emptyset$, the set element $\{1, 2\}$, and the number 3 [5].
24. **C) $2^n$** [6]  
    *Explanation:* The number of subsets of a set with $n$ elements is $2^n$ [6].
25. **C) $16$** [6]  
    *Explanation:* $|M| = 4$, so $|\mathcal{P}(M)| = 2^4 = 16$ [6].
26. **B) $m \cdot n$** [7, 8]  
    *Explanation:* The cardinality of a Cartesian product is $|A \times B| = |A| \cdot |B| = m \cdot n$ [7, 8].

### Section 5 Answers
27. **B) $\{x \mid x \in A \lor x \in B\}$** [9]  
    *Explanation:* Union is the set of elements in $A$ OR in $B$ [9].
28. **B) $\{x \mid x \in A \land x \in B\}$** [9]  
    *Explanation:* Intersection is the set of elements common to BOTH $A$ and $B$ [9].
29. **A) The set of elements in the universal set $U$ that are not in $A$ ($U - A$).** [8]  
    *Explanation:* $A'$ or $A^c$ contains elements in $U$ that are NOT in $A$ [8].
30. **B) $\{x \mid x \in B \land x \notin A\}$** [8]  
    *Explanation:* Set difference $B - A$ ("$B$ but not $A$") contains elements in $B$ not in $A$ [8].
31. **B) Elements in $A$ or in $B$, but not in both ($(A \cup B) - (A \cap B)$).** [14]  
    *Explanation:* Symmetric difference $A \oplus B$ is the set of elements in exactly one of the sets [14].
32. **A) $\{1, 2\}$** [8]  
    *Explanation:* Elements in $A$ ($\{1, 2, 3, 4\}$) that are not in $B$ ($\{3, 4, 5, 6\}$) are $\{1, 2\}$ [8].
33. **B) $\{1, 2, 5, 6\}$** [14]  
    *Explanation:* $(A \cup B) - (A \cap B) = \{1, 2, 3, 4, 5, 6\} - \{3, 4\} = \{1, 2, 5, 6\}$ [14].

### Section 6 Answers
34. **A) $(A \cup B)^c = A^c \cap B^c$** [10]  
    *Explanation:* De Morgan's Laws state $(A \cup B)^c = A^c \cap B^c$ and $(A \cap B)^c = A^c \cup B^c$ [10].
35. **A) $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$** [10]  
    *Explanation:* Distributive Law distributes $\cap$ over $\cup$ [10].
36. **A) $A \cup (A \cap B) = A$** [10]  
    *Explanation:* Absorption Laws state $A \cup (A \cap B) = A$ and $A \cap (A \cup B) = A$ [10].
37. **B) $A \cup A = A$ and $A \cap A = A$** [10]  
    *Explanation:* Idempotent Laws state $A \cup A = A$ and $A \cap A = A$ [10].
38. **A) $A \cup \emptyset = A$ and $A \cap U = A$** [10]  
    *Explanation:* Identity Laws state $A \cup \emptyset = A$ and $A \cap U = A$ [10].
39. **A) $A \cup U = U$ and $A \cap \emptyset = \emptyset$** [10]  
    *Explanation:* Domination Laws state $A \cup U = U$ and $A \cap \emptyset = \emptyset$ [10].
40. **A) $A \cup A^c = U$ and $A \cap A^c = \emptyset$** [10]  
    *Explanation:* Inverse Laws state $A \cup A^c = U$ and $A \cap A^c = \emptyset$ [10].
41. **A) $(A^c)^c = A$** [10]  
    *Explanation:* Involution (Double Complement) states $(A^c)^c = A$ [10].

### Section 7 Answers
42. **B) A pictorial representation of sets where the universal set is represented by a rectangle and its subsets by closed plane figures.** [11]  
    *Explanation:* A pictorial representation of sets is called a Venn diagram [11].
43. **B) $U$ is the interior of a rectangle; subsets are closed plane figures like circles, triangles, or squares.** [11]  
    *Explanation:* $U$ is represented by a rectangle, and subsets by closed plane figures [11].
44. **B) They provide a clear visual tool to organize overlapping data, solve multi-set cardinal counting problems, and visualize set operations.** [2, 11]  
    *Explanation:* Venn diagrams apply set operation properties to real-life problems [2, 11].
45. **B) By illustrating both sides of a set statement using Venn diagrams and verifying if both yield identical shaded drawings.** [11, 12]  
    *Explanation:* Proof using Venn diagrams illustrates both sides to see if drawings match [11, 12].

### Section 8 Answers
46. **B) A grouping of the set's elements into non-empty subsets such that every element of $A$ is included in one and only one subset.** [14]  
    *Explanation:* A partition groups a set's elements into non-empty subsets where every element is included in exactly one subset [14].
47. **B) $A = A_1 \cup A_2 \cup \dots \cup A_n$ and the subsets are mutually disjoint ($A_i \cap A_j = \emptyset$ for $i \neq j$).** [14]  
    *Explanation:* Partition criteria require union equality ($A = \bigcup A_i$) and mutual disjointness [14].
48. **A) Yes, because all subsets are non-empty, their union equals $A$, and they are mutually disjoint.** [14]  
    *Explanation:* All three subsets are non-empty, disjoint, and their union is $\{1, 2, 3, 4, 5, 6\} = A$ [14].
49. **B) Because the subsets are not mutually disjoint (the element $3$ belongs to two subsets).** [14]  
    *Explanation:* $\{1, 2, 3\} \cap \{3, 4, 5\} = \{3\} \neq \emptyset$, violating mutual disjointness [14].
50. **B) Yes, because every integer is either even or odd ($E \cup O = \mathbb{Z}$) and no integer is both ($E \cap O = \emptyset$).** [15]  
    *Explanation:* Even and odd integers partition $\mathbb{Z}$ because their union is $\mathbb{Z}$ and they share no common elements [15].
