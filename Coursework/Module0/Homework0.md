<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

# Homework 0
Name: Hyun Suk (Max) Ryoo

Computing ID: hr2ee

## Q1
Given the following predicates and their meanings

1. $P(x,y) : x>y$
2. $Q(x,y) : x \leq y$
3. $R(x) : x-7 = 2$
4. $S(x) : x > 9$

If the universe of discourse is the real numbers, give the truth value (true or false) of each of the
following propositions:

1. $(\exists x) R(x)$  = **True**
2. $(\forall y)[\neg S(y)]$ = **False**
3. $(\forall x)(\exists y)P(x,y)$ = **True**
4. $(\exists y) (\forall x) Q(x,y)$ = **True**
5. $(\forall x) (\forall y)[P(x,y) \lor Q(x,y)]$ = **False**
6. $(\exists x) S(x) \land \neg (\forall x)R(x)$ = **True**
7. $(\exists y)(\forall x)[S(y) \land Q(x,y)]$ = **True**
8. $(\forall x)(\forall y)[{R(x) \land S(y)} \rightarrow Q(x,y)]$ = **False**

## Q2
Which of the following sentences has the logical form $(p \land q) \rightarrow r$

Option 3

1. If you don’t attend the wedding, then Sam will be angry with you
2. Matt is happy and so are Sam and Fae
3. **If it rains and it snows then flooding will result**
4. Students will play football or students will play soccer; but they will not attend classes
5. Gene is smart and strong, additionally he is a good swimmer

## Q3
Which of the following formulas represents the sentence, "If there are no fruit in the market then the farmers didn’t plant fruit trees or the farmers didn’t water the trees"

p means There are no fruit in the market

q means Farmers didn’t plant fruit trees

r means Farmers didn’t water the trees

Option 2

1. $\neg p \rightarrow q$
2. **$p \rightarrow q \lor r$**
3. $(p \rightarrow q) \lor \neg r$
4. $p \rightarrow q \lor \neg r$
5. $p \lor q \rightarrow \neg r$

## Q4
Show $[p \land (p \rightarrow q)] \rightarrow q$ is a tautology

| $p$ | $q$ |  $p \rightarrow q$ | $p \land (p \rightarrow q)$  | $[p \land (p \rightarrow q)] \rightarrow q$ |
|:---:|:---:|:---:|:---:|:---:|
| T  | T  | T  | T  | T |
| T  | F  | F  | F  | T |
| F  | T  | T  | F  | T |
| F  | F  | T  | F  | T |

Since the final column with all operations is true $[p \land (p \rightarrow q)] \rightarrow q$ is a tautology

## Q5
Argue that set A and set A’ (the compliment of A) are disjoint

The complement of set A is defined as the set resulting from removing the set A from the Universe U. Let's say that we
are looking at the example of the male sex and female sex of a class. Given the assumption that a class consists of male and
female students, let us say that set A denotes all the male students. The complement of set A (A') is all the females in the class. There can be no overlaps between the sets thus proves our point that the set A (males) and set A' (females) are disjoint.

## Q6
Which of the following is a one-to-one function?

Option 5

1. { (1,2), (2,3), (3,4), (4,5), (3,7), (2,2) }
2. x = 5
3. x=5, 10 < y < 25
4. { (1,2), (2,3), (3,4), (2,5), (3,7) }
5. **{ (1,2), (2,4), (3,6), (4,8) }**

## Q7
Let $U = {x : x \text{ is an integer and } 2 ≤ x ≤ 10}$

In each of the following cases, determine whether $A \subseteq B$ , $B \subseteq A$ , both or neither:

$$
\begin{aligned}
&(i) &A=\{x: x \text{ is odd}\} \ \ &B = \{x : x \text{ is a multiple of 3}\} \ \ &\text{Neither}\\
&(ii) &A=\{x: x \text{ is even}\} \ \ &B = \{x : x^2 \text{ is even}\} \ \ &A \subseteq B\\
&(iii) &A=\{x: x \text{ is even}\} \ \ &B = \{x : x \text{ is a power of 2}\} \ \ &\text{Neither}\\
&(iv) &A=\{x: 2x + 1 > 7\} \ \ &B = \{x : x^2 > 20\} \ \ &A \subseteq B\\
&(v) &A=\{x: \sqrt{x}\in \mathbb{Z} \} \ \ &B = \{x : x \text{ is a power of 2 or 3}\} \ \ &A \subseteq B\\
&(vi) &A=\{x: \sqrt{x}\leq 2 \} \ \ &B = \{x : x \text{ is a perfect square}\} \ \ &\text{Neither}\\
&(vii) &A=\{x: x^2 - 3x + 2 = 0 \} \ \ &B = \{x : x+7 \text{ is a perfect square}\} \ \ &B \subseteq A\\
\end{aligned}
$$

**Note** : $\mathbb{Z}$ denotes the set of all integers
