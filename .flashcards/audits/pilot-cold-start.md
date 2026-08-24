# Pilot cold-start audit — Chapter 1

Audit date: 2026-08-24  
Target: `flashcards/01_variables_and_expressions.md`  
Mode: novice-first pilot, explicit chapter edges

cold_start_status: pass
unresolved_dependencies: 0

## Frozen learner contract

The learner has completed the validator-resolved
`mathematics/number-sense-and-arithmetic` deck and has no confirmed algebra or
tool knowledge. The allowed inbound frontier is limited to the capabilities
declared in `.flashcards/prerequisites/graph.json`: quantities and whole
numbers; arithmetic operations and inverse-operation checks; arithmetic
expressions and operation order; whole-number powers; signed numbers with
signed addition and subtraction; fraction and decimal operations; ratios,
rates, proportions, and percents; and measurement, units, and quantitative
reasonableness. The staged external files contain capability summaries rather
than card bodies, so no additional terminology is inferred. There is no local
chapter prerequisite and no assumed tool.

Signed multiplication, negative substitution, function terminology and
notation, coordinates, graphs, slope, properties of operations, equivalent
expressions, equation solving, inequalities, and later polynomial or nonlinear
language are outside the pilot frontier.

## Audit method

The chapter was scanned in scheduled order using fronts only: each `Q:` or
complete `P:` setup was extracted while every `A:` and `S:` body was suppressed.
Dependencies were recorded below before answer bodies were reviewed. Answers
were then checked separately for terms that a later front might silently assume.
Headings and prose outside scheduled blocks were not counted as instruction.

## Front-by-front dependency scan

| Front | Retrieval decision | Dependencies needed to parse and attempt | Allowed source or establishment | Status |
|---|---|---|---|---|
| F01 | Read the number represented by `x`. | Number recognition; a letter standing for a number; variable. | Number recognition is inbound. The front explains “stands for,” gives `x = 4` in words, and names variable before asking only for the represented number. | pass |
| F02 | State what a variable is. | Variable; number. | Variable was explained and retrieved in F01; number is inbound. | pass |
| F03 | Classify `3 + x` as algebraic. | Arithmetic expression, operation sign, variable; algebraic expression. | Arithmetic expression is inbound; variable is established by F01–F02; the front explains how an algebraic expression extends the inbound idea before classification. | pass |
| F04 | Interpret the calculation in `3 + x`. | Algebraic expression, variable, addition. | Expression is retrieved in F03; variable in F01–F02; addition is inbound. | pass |
| F05 | Select the equation. | Quantity, value, expression; equals sign and equation. | Quantity is inbound; expression is established by F03–F04; the front defines equation and explains the equals-sign assertion before selection. | pass |
| F06 | Discriminate expression from equation. | Expression, equation, quantity, equals sign. | Expression is established by F03–F04 and equation by F05. | pass |
| F07 | Identify terms in `x + 7`. | Expression, addition/subtraction; term. | Expression is established; operations are inbound; the front explains the simple sum-of-terms reading before identification. | pass |
| F08 | Identify a coefficient. | Variable, multiplication; adjacency notation `4x`; coefficient. | Variable is established and multiplication is inbound; the front explicitly equates `4x` with `4 × x` and defines coefficient before retrieval. | pass |
| F09 | Identify the constant term. | Terms, variable; constant term. | Terms are retrieved in F07 and variable earlier; the front defines a constant term before identification. | pass |
| F10 | Correct coefficient/term confusion. | Coefficient, term, adjacency notation. | Term is established by F07 and coefficient/adjacency by F08; no new distractor concept is required. | pass |
| F11 | Substitute into `x + 5` without evaluating. | Substitution, variable, equation notation, arithmetic expression. | Variable and equation are established; arithmetic expression is inbound; the front defines substitution before asking for the resulting arithmetic expression. | pass |
| F12 | Evaluate after substitution. | Evaluate/value, substitution, addition. | Substitution is retrieved in F11; addition is inbound; the front defines evaluate before calculation. | pass |
| F13 | Execute analyzed substitution/evaluation. | Evaluation, substitution, `2x` multiplication, coefficient notation, operation order. | Evaluation and substitution are established by F11–F12; adjacency by F08; multiplication and operation order are inbound. | pass |
| F14 | Execute a faded substitution/evaluation. | Same dependencies as F13. | All were established before F13 and retrieved through F13's worked sequence. | pass |
| F15 | Translate “add 6” into an expression. | Variable, algebraic expression, addition, verbal-to-symbolic recording. | Variable/expression are established and addition is inbound; the front states what `n` represents and asks one bounded translation. | pass |
| F16 | Translate multiplication followed by addition. | Variable, expression, multiplication, addition, adjacency notation. | All symbols and operations are established by F01–F08 and inbound arithmetic; F15 supplies the first supported translation. | pass |
| F17 | Translate and evaluate a packet context. | Whole-number equal groups, addition, variable, equation notation, expression translation, substitution, evaluation. | Equal-groups multiplication and addition are inbound; every algebraic dependency is established and retrieved by F01–F16. Packet and counter language is ordinary and fully quantified on the front. | pass |
| F18 | Complete a two-column value table. | Column/row reading, variable, expression, substitution, evaluation. | The front explains exactly what each column records; all algebraic operations were established earlier. The sample and target rows use no function terminology. | pass |
| F19 | Preserve subtraction order in translation. | Variable, expression translation, subtraction order. | Translation is established by F15–F17; subtraction and its order are inbound. | pass |
| F20 | Diagnose lost multiplication during substitution. | Substitution, adjacency notation, multiplication, addition. | Substitution is established by F11–F14; `3x` notation by F08 and reused repeatedly; operations are inbound. | pass |

## Separate first-use scan

| First use | Front | Establishment test | Result |
|---|---|---|---|
| Variable and a letter representing a number | F01 | Defined in established number language and immediately used for a bounded inference. | pass |
| Algebraic expression | F03 | Built explicitly from inbound arithmetic expression plus the established variable. | pass |
| Equation and equals-sign assertion | F05 | Defined on the scheduled front before selection; no solving is implied. | pass |
| Term | F07 | Introduced only for the simple top-level sum shown, avoiding an overgeneralization about nested grouping. | pass |
| Adjacent coefficient notation and coefficient | F08 | `4x = 4 × x` is stated before the coefficient is identified. | pass |
| Constant term | F09 | Defined using established term and variable concepts before identification. | pass |
| Substitution | F11 | Defined before the replacement decision; `x = 3` relies only on established equation notation. | pass |
| Evaluate/expression value | F12 | Defined after substitution was retrieved and before the calculation. | pass |
| Verbal-to-symbolic translation | F15 | Begins with one operation and an explicitly assigned variable, then varies in F16–F17. | pass |
| Context-to-expression translation | F17 | Every quantity is given; repeated groups are inbound; no formula or future model vocabulary appears. | pass |
| Two-column value table | F18 | Column meanings are explained directly on the scheduled problem front without using input/output or function language. | pass |
| Subtraction-order wording | F19 | Uses inbound subtraction after translation has been retrieved in three earlier contexts. | pass |

No front, distractor, example, table label, or supplied premise imports a concept
from a later chapter. The first-use scan found no dependence on headings, prose,
figures, or answer-only explanations.

## Answer and solution scan

- Every basic answer places the direct answer first and remains a concise repair.
- No answer-only term is required by a later front. The table check refers to the
  “given value of `n`,” not the later function term “input.”
- All four problem solutions begin immediately with `IDENTIFY`, retain the full
  ordered `IDENTIFY → PLAN → EXECUTE → EVALUATE` sequence, and place the direct
  result as the first sentence inside `EXECUTE`.
- Each `EVALUATE` stage performs a real inverse-operation check.
- No `A:` or `S:` body begins with a bare number-and-period sequence.

## Figure and representation audit

The chapter uses verbal, symbolic, numerical, contextual, and tabular
representations. Four plausible visual opportunities were considered before
authoring and intentionally omitted:

1. An expression tree would duplicate inbound operation structure for the
   chapter's simple one- and two-term expressions.
2. An annotated coefficient/constant diagram would reveal the labels being
   retrieved.
3. A packet or counter illustration would duplicate inbound equal-groups
   arithmetic rather than add a new visual decision.
4. The two-column relationship is more directly and accessibly represented by
   the scheduled Markdown table than by an SVG restatement.

No technical figure is needed, so the actual figure inventory of zero matches
the design ledger.

## Planned-versus-actual inventory

| Inventory | Planned | Actual | Reconciliation |
|---|---:|---:|---|
| Basic cards | 16 | 16 | Exact match; each card tests a distinct explanation, discrimination, translation, or diagnosis. |
| Cloze cards | 0 | 0 | Exact match; no compact deletion was preferable to reasoning with newly established notation. |
| Problem cards | 4 | 4 | Exact analyzed → faded → independent contextual → tabular progression; every solution retains IPEE. |
| Figures | 0 | 0 | Exact match after four explicit omit decisions. |

## Validation note

`flashcards deck validate .` parses all 20 cards with zero parser, KaTeX, image,
identity, markup, cloze, and frontmatter errors. It reports one prerequisite
lookup error because the isolated validator searches for the external deck at a
non-staged sibling path. The authoritative staged graph resolves
`mathematics/number-sense-and-arithmetic`, and its checksum-recorded closure is
present under `.flashcards/prerequisites/`; this environmental lookup error does
not leave a semantic chapter dependency unexplained.
