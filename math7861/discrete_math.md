Discrete Mathematics

[TOC]

# The Logic of Compound Statement

## Logical Equivalences


|  |  |  |
| --- | --- | --- |
| Commutative laws | $p \wedge q \equiv q \wedge p$ | $p \vee q \equiv q \vee p$ |
| Associative laws | $(p \wedge q) \wedge r \equiv p \wedge (q \wedge r)$ | $(p \vee q) \vee r \equiv p \vee (q \vee r)$ |
| Distributive laws | $p \wedge (q \vee r) \equiv (p \wedge q) \vee (p \wedge r)$ | $p \vee (q \wedge r) \equiv (p \vee q) \wedge (p \vee r)$ |
| Identity law | $p \wedge t \equiv p$ | $p \vee c \equiv p$ |
| Negation law | $p \vee \neg p \equiv t$ | $p \wedge \neg p \equiv c$ |
| Double negation law | $\neg(\neg p)\equiv p$ |  |
| Idempotent laws | $p \wedge p \equiv p$ | $p \vee p \equiv p$ |
| Universal bound law | $p \vee t \equiv t$ | $p \wedge c \equiv c$ |
| De MOrgan's laws | $\neg (p \wedge q) \equiv \neg p \vee \neg q$ | $\neg (p \vee q) \equiv \neg p \wedge \neg q$ |
| Absorption laws | $p \vee (p \wedge q) \equiv p$ | $p \wedge (p \vee q) \equiv p$ |
| Negations of **t** and **c** | $\neg t \equiv c$ | $\neg c \equiv t$ |
| Exclusive Or | $p \oplus q \equiv (p \vee q) \wedge \neg (p \wedge q)$ | $(p \oplus q) \wedge r \equiv (p \wedge r) \oplus (q \wedge r)$ |

## Conditional Statements

>If p and q 

| $p$ | $q$ | $p \to q$ |
| --- | --- | --- |
| T | T | T |
| T | F | F |
| F | T | T |
| F | F | T |

$p \to q \equiv \neg p \vee q \equiv \neg q \to \neg p$

The **converse** of $p \to q$ is $q \to p$
The **inverse** of $p \to q$ is $\neg p \to \neg q$
The **contrapositive** of $p \to q$ is $\neg q \to \neg p$

>If p and q are statements, 
>p **only if** q means "if not q then not p ($\neg q \to \neg p$)", 
>or, equivalently, "if p then q ($p \to q$)"

>If r and s are statements:
>r is a **sufficient condition** for s, means: "if r then s ($r \to s$)"
>r is a **neccessary condition** for s, means: "if not r then not s ($\neg r \to \neg s$)", also means: "if s then r ($s \to r$)"
>r is a necessary and sufficient condition for s, means: "r if, and only if, s ($r \leftrightarrow s$)"
