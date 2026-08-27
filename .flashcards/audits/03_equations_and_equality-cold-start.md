# Chapter 3 cold-start audit — Equations and equality

- Audit date: 2026-08-26
- Mode: build, bounded chapter authoring
- Target: `flashcards/03_equations_and_equality.md`
- Learner: foundational novice in algebra who has completed the declared
  arithmetic prerequisite deck
- Resolved local closure: `01_variables_and_expressions`
- Resolved external closure: `mathematics/number-sense-and-arithmetic`
- Assumed tools: none
- Edge mode: explicit
- Unavailable as inbound knowledge: Chapter 2 and every later local chapter

## Chapter-boundary dependency ledger

| Boundary item | Source or disposition | Status |
|---|---|---|
| Equation as a statement that two quantities have the same value | Chapter 1 F05–F06 | inbound |
| Variable and value | Chapter 1 F01–F02 | inbound |
| Juxtaposition such as `5x` meaning multiplication; coefficient | Chapter 1 F08–F10 | inbound |
| Substitution and expression evaluation | Chapter 1 F11–F14 | inbound |
| Verbal-expression translation | Chapter 1 F15–F19 | inbound |
| Whole-number addition, subtraction, multiplication, and division | External validator-resolved capabilities | inbound |
| Inverse-operation checks | External validator-resolved capability | inbound |
| Signed addition and subtraction | External validator-resolved capabilities | inbound |
| Fraction and decimal operations | External validator-resolved capabilities | inbound |
| Equivalent-expression and named operation-property vocabulary | Chapter 2 is not in the resolved closure | excluded |
| Signed multiplication | Not explicitly provided by the bounded external summaries | excluded |
| Multi-step equations, variables on both sides, formula rearrangement, identity and contradiction cases | Chapter 4 | deferred |
| Inequalities, coordinates, relations, graphs, and functions | Chapters 5–8 | deferred |

No inbound edge was added. The authored chapter uses only the declared Chapter
1 edge and the existing external deck prerequisite.

## Pre-authoring chapter design ledger

| Design dimension | Frozen plan |
|---|---|
| Retrieval targets | Meaning of solution; substitution check; solving/checking discrimination; equality-preserving moves; inverse-operation choice; one-step execution; verbal/context translation; error diagnosis |
| Card forms | 11 bounded `Q:/A:` decisions, 0 clozes, 7 `P:/S:` problems |
| Problem progression | F07 analyzed addition; F09 completion with subtraction; F11 faded multiplication; F13 independent division; F14 signed-result transfer; F16 contextual translation and solve; F18 mixed decimal-coefficient transfer |
| Authentic representations | Verbal statements, symbolic equations, whole-number and signed-number calculations, a context, and a decimal coefficient |
| Figure opportunity: balance scale | Intentionally omitted. It duplicates the same-value/same-operation decision and introduces a physical diagram grammar without a distinct retrieval target. |
| Figure opportunity: operation-flow diagram | Intentionally omitted. It would preselect the inverse operation that the learner should retrieve. |
| Figure opportunity: before/after equation diagram | Intentionally omitted. The symbolic equation transformations are the authentic representation and are clearer directly in the solution. |
| Boundary | No simplification, properties vocabulary from Chapter 2, variables on both sides, multi-step work, inequalities, coordinates, or functions |

## Completed concept-dependency ledger

| New concept, notation, or representation | First explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|
| Solution of an equation | F01 defines it as a value that makes the equation true through a substituted example. | F01 explains why `5` is a solution; F02 rejects `4`. | F03 and all problems | pass |
| Solving versus checking | F03 defines both actions using already established substitution. | F03 selects checking by substitution. | Every IPEE EVALUATE stage | pass |
| Equality-preserving move | F04 defines the same-operation-on-both-sides rule and bounds it to allowed, undoable arithmetic moves. | F04 retrieves the rule; F05 diagnoses a one-sided violation. | F06–F18 | pass |
| One-step equation | F06 defines it as requiring one equality-preserving inverse-operation move. | F06 selects subtraction for `x + 4 = 11`. | F07–F18 | pass |
| Addition equation procedure | F06 supplies the method choice. | F07 analyzes and executes it. | F14, F16 | pass |
| Subtraction equation procedure | F08 connects subtraction with its inbound inverse operation. | F08 selects addition; F09 executes it. | F18 discrimination | pass |
| Multiplication equation procedure and valid division move | F10 connects `5x` with inbound multiplication and asks for the inverse move. | F10 selects division; F11 executes and checks it. | F17–F18 | pass |
| Division equation procedure and valid multiplication move | F12 asks for the inverse move using inbound division. | F12 selects multiplication; F13 executes and checks it. | F17 discrimination | pass |
| Negative solution | Signed subtraction is inbound; F14 applies it only after addition equations are established. | F14 solves and checks `x + 7 = 3`. | None required | pass |
| Verbal statement translated to an equation | F15 extends inbound expression translation with the inbound equals-sign assertion. | F15 produces `n + 5 = 12`. | F16 context | pass |
| Contextual equation | The packet/counter grammar was already scheduled in Chapter 1 F17. | F16 writes, solves, and checks the equation. | None required | pass |
| Decimal-coefficient multiplication equation | Decimal operations and coefficient notation are inbound; multiplication equations are established at F10–F11. | F18 chooses, executes, and checks the inverse move. | None; closing transfer | pass |

## Fronts-only cold-start scan

Each row was recorded from the scheduled front before its answer or solution was
checked. Headings and prose outside scheduled blocks were not counted as
instruction.

| Front | Dependencies needed to parse and attempt | Source available before this front | Answer/solution check after dependency record | Status |
|---|---|---|---|---|
| F01 | equation, variable, substitution, addition; new `solution` | Chapter 1 plus inbound arithmetic; `solution` is minimally defined on this front | Correctly identifies truth after substitution | pass |
| F02 | substitution and solution meaning | Chapter 1; F01 | Correctly rejects `4` because `4 + 3` differs from `8` | pass |
| F03 | solution and substitution; new solving/checking distinction | F01–F02; both actions are defined on this front | Correctly selects checking by substitution | pass |
| F04 | equation as same-value statement and arithmetic operations; new equality-preserving move | Chapter 1 and arithmetic closure; the move is defined on this front | Correctly requires the same allowed, undoable operation with the same number on both sides | pass |
| F05 | equality-preserving move and subtraction | F04; arithmetic closure | Correctly diagnoses the one-sided change and repairs both sides | pass |
| F06 | solving, equality-preserving move, inverse operations; new one-step equation | F03–F05; inverse-operation check is inbound; one-step is defined on this front | Correctly selects subtracting `4` from both sides | pass |
| F07 | one-step addition equation and selected inverse move | F06 | Complete analyzed solve; substitution genuinely checks the original equation | pass |
| F08 | equality-preserving move, subtraction, inverse operations | F04–F07 and arithmetic closure | Correctly selects adding `6` to both sides | pass |
| F09 | subtraction equation procedure | F08; the established move is supplied on this completion front | Complete completion-stage solve; substitution checks `15 - 6 = 9` | pass |
| F10 | `5x` multiplication notation, equality preservation, inverse operations | Chapter 1 F08; F04–F09; whole-number division inbound | Correctly chooses division by the nonzero coefficient | pass |
| F11 | multiplication equation procedure | F10 | Complete faded solve; multiplication substitution checks the result | pass |
| F12 | variable division notation, equality preservation, inverse operations | Variable and division are inbound; F04–F11 | Correctly chooses multiplication by `4` on both sides | pass |
| F13 | division equation procedure | F12 | Complete independent solve; division substitution checks the result | pass |
| F14 | addition equation procedure and signed subtraction | F06–F07; signed subtraction inbound | Correctly obtains and checks `-4` without requiring signed multiplication | pass |
| F15 | variable, verbal-expression translation, equation assertion | Chapter 1 F05–F06 and F15–F19 | Correctly translates the statement to `n + 5 = 12` | pass |
| F16 | packet/counter context, verbal equation, addition procedure | Chapter 1 F17; F07 and F15 | Complete contextual solve; substitution matches the stated total | pass |
| F17 | multiplication notation and all inverse-operation choices | Chapter 1 F08; F06–F13 | Correctly diagnoses subtraction as the wrong inverse and supplies division | pass |
| F18 | decimal multiplication, coefficient notation, multiplication equation procedure | External decimal operations; Chapter 1 F08; F10–F11 | Complete mixed solve; `0.5 × 6 = 3` checks the result | pass |

## Separate first-use scan

This scan is separate from the answer and style review. It covers every
domain-bearing first use on a scheduled front, including notation and context.

| First use | Location | Classification | Evidence |
|---|---|---|---|
| Equation, equals sign, variable, substitution | F01 | inbound | Chapter 1 F01–F06 and F11 |
| Solution | F01 | minimally self-bridged | Defined before the supported inference on F01 |
| Checking and solving | F03 | minimally self-bridged | Both actions are defined on F03 using established words and substitution |
| Equality-preserving move | F04 | minimally self-bridged | Defined as keeping both sides at the same value; rule retrieved there |
| Applying one operation to both sides | F04 | supported arithmetic bridge | Four operations and inverse-operation checks are inbound |
| One-step equation | F06 | minimally self-bridged | Defined on F06 before method selection |
| `5x` as multiplication | F10 | inbound and redundantly bridged | Chapter 1 F08; F10 also states the reading |
| Variable division notation `x ÷ 4` | F12 | composition of inbound representations | Variable plus arithmetic division; no fraction-bar convention is imported |
| Negative solution value | F14 | inbound arithmetic used after method establishment | Signed addition/subtraction are external capabilities |
| Verbal equation | F15 | supported extension | Expression translation and equation assertion are both inbound |
| Packet/counter context | F16 | inbound context grammar | Chapter 1 F17 uses the same context |
| Decimal coefficient `0.5x` | F18 | inbound composition | Decimal operations plus Chapter 1 coefficient notation |

No first use depends on Chapter 2 or a later chapter. No answer-only term is
silently reused on a later front without an earlier supported establishment.

## IPEE and markup audit

- Seven `P:/S:` cards are present: F07, F09, F11, F13, F14, F16, and F18.
- Every `S:` begins immediately with `IDENTIFY`.
- Every problem retains `IDENTIFY → PLAN → EXECUTE → EVALUATE` in order.
- Every direct result is the first sentence inside `EXECUTE`.
- Every `EVALUATE` substitutes the result into the original equation or stated
  context; none uses a bare assertion of correctness.
- No `A:` or `S:` begins with a bare number and period.
- Every scheduled block has a unique stable `card-id`.
- The application parser reports 0 parser, KaTeX, image, identity, markup,
  cloze, and frontmatter errors for the bounded two-file workspace.

## Planned-versus-actual reconciliation

| Inventory | Planned | Actual | Reconciliation |
|---|---:|---:|---|
| Basic cards | 11 | 11 | exact |
| Cloze cards | 0 | 0 | exact; no target benefits from exact deletion |
| Problem cards | 7 | 7 | exact; all seven planned progression stages are present |
| Figures | 0 | 0 | exact; all three opportunities were intentionally omitted before authoring |

The actual problem order exactly matches the planned analyzed → completion →
faded → independent symbolic → signed → contextual → mixed progression.

## Validation note

`flashcards deck stabilize . --check` reports no missing stable IDs. The parser,
KaTeX, identity, markup, card counts, and generation provenance validate. The
ordinary prerequisite validator reports one environment-only error because it
looks for the external arithmetic deck at its normal sibling path; this isolated
workspace instead supplies the immutable staged closure and
`.flashcards/prerequisites/graph.json`. That graph resolves Chapter 3 to Chapter
1 plus `mathematics/number-sense-and-arithmetic`, with no missing or proposed
inbound edge.

cold_start_status: pass
unresolved_dependencies: 0
