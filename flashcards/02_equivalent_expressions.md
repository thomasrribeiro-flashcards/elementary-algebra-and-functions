+++
order = 2
subject = "mathematics"
authoring_provider = "openai"
authoring_model = "gpt-5.6-sol"
authoring_reasoning_effort = "high"
authoring_run_id = "request-22"
curriculum_provider = "openai"
curriculum_model = "gpt-5.6-sol"
curriculum_reasoning_effort = "high"
curriculum_run_id = "request-11"
tags = ["elementary-algebra", "equivalent-expressions", "operation-properties", "distributive-property"]
prerequisites = ["chapter:01_variables_and_expressions"]
provides = [
  "equivalent-expression",
  "properties-of-operations",
  "distributive-property",
  "like-terms",
  "expression-simplification",
]
+++

# Equivalent expressions

## F01 — First meaning of equivalence

<!-- card-id: card-685e9eb3-4194-486a-aefb-bd6d0e64ce76 -->
Q: Two expressions are called **equivalent expressions** when they have the same value for every variable value for which both can be evaluated. If \(x=4\), what value do the equivalent expressions \(x+3\) and \(3+x\) both have?
A: **\(7\).** Substitution gives \(4+3=7\) and \(3+4=7\), as equivalence requires.

## F02 — Defining equivalent expressions

<!-- card-id: card-36d50647-5a99-44e6-9371-6d41dedaad0f -->
Q: What condition makes two algebraic expressions **equivalent**?
A: **They have the same value for every variable value for which both can be evaluated.** The expressions may look different while still naming the same quantity.

## F03 — A numerical check that rejects equivalence

<!-- card-id: card-b3397e18-9b40-40df-bb67-8a820b1f7545 -->
Q: Each row substitutes the shown value of \(x\) into both expressions. Which row shows that \(x+2\) and \(2x\) are not equivalent?

| \(x\) | Value of \(x+2\) | Value of \(2x\) |
|---:|---:|---:|
| \(1\) | \(3\) | \(2\) |
| \(2\) | \(4\) | \(4\) |

A: **The row with \(x=1\).** Equivalent expressions must agree for every value, so one differing row is enough to reject equivalence; the match at \(x=2\) does not undo it.

## F04 — Commutative property

<!-- card-id: card-4d68ec24-cf64-4ac6-b338-68b33a9abea3 -->
Q: A **property of operations** is a rule that permits a rewrite without changing the value. The **commutative property of addition or multiplication** permits changing the order of the items being added or multiplied. How can \(x+4\) be rewritten using this property?
A: **\(4+x\).** Only the order changes, so \(x+4\) and \(4+x\) are equivalent.

## F05 — Associative property

<!-- card-id: card-7ab9815b-4b20-4b88-bed1-598215ad829e -->
Q: The **associative property of addition or multiplication** permits changing the grouping without changing the order. How can \((x+2)+3\) be regrouped using this property?
A: **\(x+(2+3)\).** The items being added remain in the order \(x,2,3\); only the grouping changes.

## F06 — Order versus grouping

<!-- card-id: card-5e14e799-24e7-49e0-aeda-d3e8f7c9e9ab -->
Q: What is the decisive difference between the commutative and associative properties?
A: **The commutative property changes order; the associative property changes grouping.** Both preserve the expression's value.

## F07 — Additive identity

<!-- card-id: card-27474886-a643-4765-bcfb-b9d9aa9925ad -->
Q: The **additive identity property** says that adding \(0\) leaves a number unchanged. What expression is equivalent to \(x+0\)?
A: **\(x\).** Adding the identity number \(0\) does not change the value represented by \(x\).

## F08 — Multiplicative identity

<!-- card-id: card-829b43d4-1f47-4e1a-a030-7c79f52994d7 -->
Q: The **multiplicative identity property** says that multiplying by \(1\) leaves a number unchanged. What expression is equivalent to \(1x\)?
A: **\(x\).** Multiplying the value represented by \(x\) by \(1\) does not change it.

## F09 — First distributive rewrite

<!-- card-id: card-83a05607-1c46-4109-a210-dbffb7c88d7d -->
Q: The **distributive property** rewrites multiplication by an addition in parentheses: the outside factor multiplies each item being added inside. What equivalent expression results from \(3(x+2)\)?
A: **\(3x+6\).** Multiply both \(x\) and \(2\) by \(3\): \(3(x+2)=3x+3\times2=3x+6\).

## F10 — Naming distribution

<!-- card-id: card-07e17375-db38-4a45-9bd9-effe0a74eae4 -->
C: The property that rewrites \(3(x+2)\) as \(3x+6\) is the [distributive property].

## F11 — Analyzed distribution problem

<!-- card-id: card-cb8745ec-eddd-4dbf-a5ad-789762847af2 -->
P: Rewrite \(4(x+3)\) as an equivalent expression without parentheses.
S:
**IDENTIFY**

This is an expression rewrite using the distributive property.

**PLAN**

Multiply \(4\) by each item being added inside the parentheses, then complete the whole-number multiplication.

**EXECUTE**

**The equivalent expression is \(4x+12\).** Distributing gives \(4\times x+4\times3=4x+12\).

**EVALUATE**

At \(x=2\), the original expression is \(4(2+3)=20\), and the rewritten expression is \(4\times2+12=20\).

## F12 — Diagnosing incomplete distribution

<!-- card-id: card-c502e226-9bdc-4636-bf6b-cac2d913e26d -->
Q: A learner rewrites \(5(x+2)\) as \(5x+2\). What is the error, and what is the correct equivalent expression?
A: **The factor \(5\) was not multiplied by every item being added; the correct expression is \(5x+10\).** Distribution applies \(5\) to both \(x\) and \(2\).

## F13 — First like terms

<!-- card-id: card-2a7dc448-0a6e-4708-a71c-7b268859c561 -->
Q: Terms such as \(2x\) and \(5x\) that contain the same variable are called **like terms**, even when their coefficients differ. Which pair consists of like terms: \(2x\) and \(5x\), or \(2x\) and \(5\)?
A: **\(2x\) and \(5x\).** Both terms contain the same variable \(x\); \(5\) is a constant term.

## F14 — Repeated copies and a coefficient

<!-- card-id: card-e4bd5c1a-7e5f-40bc-abab-0fd8535a4a72 -->
Q: What equivalent expression combines \(x+x+x+x\) into one term, and why?
A: **\(4x\).** The sum contains four copies of the same value \(x\), so the coefficient is \(4\).

## F15 — Like-term completion problem

<!-- card-id: card-601f4e8d-1316-45d8-93f0-acbadf5be6a7 -->
P: Combine the like terms in \(2x+4x\).
S:
**IDENTIFY**

The two terms are like terms because both contain \(x\).

**PLAN**

Add the coefficients while keeping the variable.

**EXECUTE**

**The equivalent expression is \(6x\).** Two copies of \(x\) plus four copies of \(x\) make six copies of \(x\).

**EVALUATE**

At \(x=3\), the original expression has value \(2\times3+4\times3=18\), and \(6x\) has value \(6\times3=18\).

## F16 — Unlike terms do not combine

<!-- card-id: card-cd48e270-1330-4157-9abb-00ee0e542a57 -->
Q: A learner rewrites \(2x+3\) as \(5x\). Why is this rewrite invalid?
A: **\(2x\) and \(3\) are not like terms.** The first term contains the variable \(x\), while \(3\) is a constant term, so their coefficients cannot be combined into \(5x\).

## F17 — Combining constant terms

<!-- card-id: card-e5a14b40-3a27-406b-9e1c-e446ed4699ae -->
Q: Constant terms are like terms with each other. What equivalent expression results when the constant terms in \(4x+2+5\) are combined?
A: **\(4x+7\).** The constant terms combine as \(2+5=7\), while the term \(4x\) remains unchanged.

## F18 — Faded collection problem

<!-- card-id: card-a22228c3-10fa-42c4-a736-586b70f4f615 -->
P: Rewrite \(4x+2+3x+5\) by combining all like terms.
S:
**IDENTIFY**

The expression contains two variable terms and two constant terms.

**PLAN**

Use the operation properties to place like terms together, then combine each group.

**EXECUTE**

**The equivalent expression is \(7x+7\).** The variable terms give \(4x+3x=7x\), and the constants give \(2+5=7\).

**EVALUATE**

At \(x=2\), the original value is \(8+2+6+5=21\), and the rewritten value is \(14+7=21\).

## F19 — Meaning of simplification

<!-- card-id: card-107a445a-01ed-4d13-93ec-7475879de701 -->
Q: To **simplify an expression** means to rewrite it equivalently with steps such as using the distributive property and combining like terms completed where possible. Under this meaning, which form is simplified: \(2(x+3)+x\) or \(3x+6\)?
A: **\(3x+6\).** In the other form, the distributive property can be used and then \(2x\) can be combined with \(x\).

## F20 — Independent simplification problem

<!-- card-id: card-15d87299-687d-45e0-a62c-35f2bdaae165 -->
P: Simplify \(3(x+2)+2x+1\).
S:
**IDENTIFY**

The expression requires the distributive property followed by combining like terms.

**PLAN**

Remove the parentheses with the distributive property, then combine the variable terms and the constant terms.

**EXECUTE**

**The simplified expression is \(5x+7\).** Distribution gives \(3x+6+2x+1\); combining like terms gives \(5x+7\).

**EVALUATE**

At \(x=2\), the original value is \(3(2+2)+2\times2+1=17\), and the simplified value is \(5\times2+7=17\).

## F21 — Structural equivalence discrimination

<!-- card-id: card-f5d6e338-8d43-4ac9-b80d-5cffe00369d1 -->
Q: Which expression is equivalent to \(2(x+4)+3x+0\): \(5x+8\) or \(5x+4\)? What rewrite decides?
A: **\(5x+8\).** The distributive property gives \(2x+8+3x+0\); combining the like variable terms and using the additive identity gives \(5x+8\).

## F22 — Mixed equivalence problem

<!-- card-id: card-93de3a20-4e69-496a-9d23-1a9d03e65034 -->
P: Determine whether \(3(x+2)+1x\) and \(4x+5\) are equivalent expressions.
S:
**IDENTIFY**

This is an equivalence decision between two algebraic expressions.

**PLAN**

Rewrite the first expression using the distributive property and like terms, then use one substituted value as a check.

**EXECUTE**

**The expressions are not equivalent.** The first simplifies to \(3x+6+1x=4x+6\), which differs from \(4x+5\).

**EVALUATE**

At \(x=1\), the first expression has value \(3(1+2)+1\times1=10\), while \(4x+5\) has value \(9\); the unequal values confirm the decision.
