+++
order = 3
subject = "mathematics"
curriculum_provider = "openai"
curriculum_model = "gpt-5.6-sol"
curriculum_reasoning_effort = "high"
curriculum_run_id = "request-11"
authoring_provider = "openai"
authoring_model = "gpt-5.6-sol"
authoring_reasoning_effort = "high"
authoring_run_id = "request-24"
tags = ["elementary-algebra", "equations", "equality", "inverse-operations"]
prerequisites = ["chapter:01_variables_and_expressions"]
provides = [
  "equation-solution",
  "equality-properties",
  "one-step-equation",
  "equation-checking",
]
+++

# Equations and equality

## F01 — Meaning of a solution

<!-- card-id: card-6cce9ba5-856e-43bf-9c82-62f62a20826e -->
Q: A value that makes an equation true is called a **solution** of the equation. Substituting \(x=5\) into \(x+3=8\) gives \(5+3=8\). Why is \(5\) a solution?
A: **It makes the equation true.** After \(5\) replaces \(x\), both sides have the same value.

## F02 — Checking a possible solution

<!-- card-id: card-6254dc8c-e464-4555-8461-3b0ea9bab676 -->
Q: What does substitution show about \(4\) as a possible solution of \(x+3=8\)?
A: **\(4\) is not a solution.** Substitution gives \(4+3=7\), so the two sides do not have the same value.

## F03 — Solving versus checking

<!-- card-id: card-47182d80-0a17-4431-ae61-98c5caafe72e -->
Q: **Solving** an equation means finding a solution. **Checking** a proposed solution means substituting it and testing whether the equation is true. Which action confirms that \(5\) works in \(x+3=8\)?
A: **Checking by substitution.** Replace \(x\) with \(5\) and verify that \(5+3=8\).

## F04 — Preserving equality

<!-- card-id: card-d8e693b0-c07b-4c89-8941-0b84870ad216 -->
Q: An **equality-preserving move** keeps both sides of an equation at the same value. For the arithmetic moves used here, what must you do to both sides?
A: **Apply the same operation with the same number to both sides.** The move must be allowed and undoable; in particular, division by \(0\) is not allowed.

## F05 — Diagnosing a one-sided change

<!-- card-id: card-e91f3cdf-a8f3-45dc-8659-43da1148fd87 -->
Q: From \(x+3=8\), a learner subtracts \(3\) only from the left side and writes \(x=8\). Why is this not an equality-preserving move?
A: **Only one side was changed.** Subtracting \(3\) from both sides gives \(x=5\), while subtracting it from only one side breaks the stated equality.

## F06 — Recognizing a one-step equation

<!-- card-id: card-d63be470-964d-405e-b312-3b0d18344837 -->
Q: A **one-step equation** can be solved with one equality-preserving inverse-operation move. For \(x+4=11\), which move undoes the addition and leaves \(x\) alone?
A: **Subtract \(4\) from both sides.** Subtraction undoes the addition of \(4\) while changing both sides alike.

## F07 — Analyzed addition equation

<!-- card-id: card-2e700c15-38c1-46ea-a16f-143e7a4b0063 -->
P: Solve \(x+4=11\).
S:
**IDENTIFY**

This is a one-step addition equation: \(4\) is added to \(x\).

**PLAN**

Use the inverse operation by subtracting \(4\) from both sides. This preserves equality and leaves \(x\) alone.

**EXECUTE**

**The solution is \(x=7\).** Subtracting \(4\) from both sides gives \(x+4-4=11-4\), so \(x=7\).

**EVALUATE**

Substitution gives \(7+4=11\), so the original equation is true.

## F08 — Choosing the move for subtraction

<!-- card-id: card-59a3d884-27f7-4f08-985f-a784bbcc96e1 -->
Q: Which equality-preserving move leaves \(x\) alone in \(x-6=9\)?
A: **Add \(6\) to both sides.** Addition undoes the subtraction of \(6\).

## F09 — Completing a subtraction equation

<!-- card-id: card-30b0b49c-0ac1-4aa2-b0f4-ad15a27b4faf -->
P: The equality-preserving move is to add \(6\) to both sides of \(x-6=9\). Complete the solve.
S:
**IDENTIFY**

This is a one-step subtraction equation.

**PLAN**

Add \(6\) to both sides to undo the subtraction.

**EXECUTE**

**The solution is \(x=15\).** Adding \(6\) gives \(x-6+6=9+6\), so \(x=15\).

**EVALUATE**

Substitution gives \(15-6=9\), so the solution makes the original equation true.

## F10 — Choosing the move for multiplication

<!-- card-id: card-818ab10f-d132-40bc-976d-676713b7eaef -->
Q: In \(5x=35\), the expression \(5x\) means \(5\times x\). Which equality-preserving move undoes this multiplication and leaves \(x\) alone?
A: **Divide both sides by \(5\).** Because \(5\) is not zero, the division is allowed and gives \(x\) on the left.

## F11 — Faded multiplication equation

<!-- card-id: card-f3dbf69c-39f8-4080-8d37-8db41a1b2dd9 -->
P: Solve \(5x=35\).
S:
**IDENTIFY**

This is a one-step multiplication equation.

**PLAN**

Undo multiplication by dividing both sides by \(5\).

**EXECUTE**

**The solution is \(x=7\).** Dividing both sides gives \((5x)\div5=35\div5\), so \(x=7\).

**EVALUATE**

Substitution gives \(5\times7=35\), so the original equation is true.

## F12 — Choosing the move for division

<!-- card-id: card-3aa8e717-1910-4674-a9e1-8d99b771d73c -->
Q: In \(x\div4=6\), which equality-preserving move undoes the division and leaves \(x\) alone?
A: **Multiply both sides by \(4\).** Multiplication by the same nonzero number preserves equality and undoes division by \(4\).

## F13 — Independent division equation

<!-- card-id: card-dede3083-76ef-4774-b623-4a1868fa8907 -->
P: Solve \(x\div4=6\).
S:
**IDENTIFY**

This is a one-step division equation.

**PLAN**

Use the inverse of division while preserving equality.

**EXECUTE**

**The solution is \(x=24\).** Multiplying both sides by \(4\) gives \(x=6\times4=24\).

**EVALUATE**

Substitution gives \(24\div4=6\), so the original equation is true.

## F14 — A negative solution

<!-- card-id: card-1bde2169-97c4-4af9-b26b-b4f2d5a7fa16 -->
P: Solve \(x+7=3\).
S:
**IDENTIFY**

This is a one-step addition equation whose solution may be a signed number.

**PLAN**

Subtract \(7\) from both sides.

**EXECUTE**

**The solution is \(x=-4\).** Subtracting \(7\) gives \(x=3-7=-4\).

**EVALUATE**

Substitution gives \(-4+7=3\), so the original equation is true.

## F15 — Translating words into an equation

<!-- card-id: card-8e2d44ff-2bd7-4919-9b07-4ff41aa80263 -->
Q: Let \(n\) stand for a number. Which equation records “add \(5\) to the number; the result is \(12\)”?
A: **\(n+5=12\).** The expression \(n+5\) records the calculation, and the equals sign states that its value is \(12\).

## F16 — Contextual one-step equation

<!-- card-id: card-5732657b-36f0-438a-9219-a154ca8a11a5 -->
P: A packet contains \(b\) counters. With \(5\) extra counters, there are \(12\) counters in total. Write and solve an equation for \(b\).
S:
**IDENTIFY**

The packet amount represented by \(b\), plus \(5\), equals the stated total of \(12\).

**PLAN**

Represent the statement with an addition equation, then use the inverse operation on both sides.

**EXECUTE**

**The packet contains \(7\) counters, so \(b=7\).** The equation is \(b+5=12\); subtracting \(5\) from both sides gives \(b=7\).

**EVALUATE**

Substitution gives \(7+5=12\), matching the stated total.

## F17 — Diagnosing the wrong inverse operation

<!-- card-id: card-7c4386d5-5783-45ea-9427-83e858133aa1 -->
Q: To solve \(3x=18\), a learner subtracts \(3\) from both sides. What is the method error?
A: **Subtraction does not undo the multiplication in \(3x\).** Divide both sides by \(3\); this leaves \(x=6\).

## F18 — Mixed decimal-coefficient equation

<!-- card-id: card-9b408c4a-856c-4c26-b624-34d35a844a07 -->
P: Solve \(0.5x=3\).
S:
**IDENTIFY**

This is a one-step multiplication equation with a decimal coefficient.

**PLAN**

Choose the inverse of multiplication and apply it to both sides.

**EXECUTE**

**The solution is \(x=6\).** Dividing both sides by \(0.5\) gives \(x=3\div0.5=6\).

**EVALUATE**

Substitution gives \(0.5\times6=3\), so the original equation is true.
