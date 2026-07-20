# Pilot cold-start audit

cold_start_status: pass
unresolved_dependencies: 0

## Audit scope and learner contract

- Target: `flashcards/01_variables_and_expressions.md`, read in scheduled order.
- Learner: novice in algebra.
- Allowed inbound subject knowledge: only the complete staged
  `mathematics/quantitative-reasoning-and-arithmetic` deck resolved by
  `.flashcards/prerequisites/graph.json` in whole-deck mode.
- Allowed tools: none.
- Confirmed inbound capabilities actually used: quantities and whole-number
  arithmetic; equal groups and multiplication; arithmetic expressions and
  operation order; the equals sign; tables of paired quantities; estimation;
  inverse-operation checks; and the established IPEE problem labels.
- Not assumed: variables, algebraic expressions, equation terminology,
  juxtaposed multiplication, terms, coefficients, constants, substitution,
  expression evaluation, function notation, coordinates, slope, or signed
  multiplication.

The workspace-supplied graph is executable truth for this isolated run. A local
`flashcards deck prerequisites .` attempt could not re-resolve the staged external
deck because it searched for that deck outside the supplied closure; no additional
knowledge was inferred from the failed lookup. Re-running the same command against
a temporary in-workspace collection layout containing the exact staged deck copy
resolved Chapter 1 with no local closure, the arithmetic deck as its sole external
closure, no tools, and explicit edge mode.

## Audit method

For each scheduled block, the front was inspected first and its parse and attempt
dependencies were recorded before the answer or solution was checked. The answer
was then inspected for terminology that a later front might assume. Headings and
deck prose were not counted as instruction.

## Front-by-front findings

| Front | Retrieval target | Dependencies recorded from the front before answer inspection | Establishment available at first attempt | Answer/solution inspection and later effect | Finding |
|---:|---|---|---|---|---|
| 1 | Map a variable to a known count | Quantity, count, addition, numeral `5`; new term `variable` | Arithmetic Chapters 1–2; the front itself defines `variable`, assigns `n` to the bag count, and states the bag contains 5 | Confirms the mapping and adds no unexplained term | pass |
| 2 | Retrieve what a variable represents | Variable | Front 1 | Clarifies that a value may be given, unknown, or allowed to change; later fronts either restate what they need or rely on this established meaning | pass |
| 3 | Identify an algebraic expression | Variable, operation symbols, quantity, equals sign; new term `algebraic expression` | Variable from Front 1; arithmetic expression and equals sign from arithmetic Chapters 4 and 2; the front defines the new term before the choice | Confirms expression versus equality claim | pass |
| 4 | Identify an equation | Algebraic expression, equals sign; new term `equation` | Front 3 and arithmetic Chapter 2; the front defines `equation` before asking for identification | Confirms that both sides are expressions; equation solving is not assumed | pass |
| 5 | Interpret `4x` as multiplication | Variable, multiplication, replacement by a chosen value; new notation `4x` | Front 1 and arithmetic Chapter 3; the front explicitly states that `4x` means `4 times x` | Confirms replacement and makes juxtaposition available to later fronts | pass |
| 6 | Identify terms | Algebraic expression, addition, juxtaposed multiplication; new term `term` | Fronts 3 and 5 plus arithmetic addition; the front defines how terms are separated | Confirms the two parts and adds no hidden procedure | pass |
| 7 | Identify a coefficient | Term, factor, multiplication; new term `coefficient` | Fronts 5–6 and arithmetic Chapter 3; the front defines the coefficient | Confirms the numerical factor | pass |
| 8 | Identify a constant term | Term, variable value changing; new term `constant term` | Fronts 1–2 and 6; the front defines the term before asking for it | Confirms `7`; no future dependency is introduced | pass |
| 9 | Perform an analyzed substitution | Variable, expression, juxtaposed multiplication, operation order; new procedure `substitute` | Fronts 1, 3, and 5 plus arithmetic Chapter 4; the front demonstrates replacement before asking for the resulting value | Gives the complete arithmetic chain and establishes substitution for later retrieval | pass |
| 10 | Retrieve the evaluation procedure | Algebraic expression, variable occurrence, operations; new term `evaluate` | Fronts 3 and 9; the front defines evaluation before asking what to replace | Answer names the established operation-order check | pass |
| 11 | Complete a scaffolded evaluation | Evaluate, substitute, juxtaposed multiplication, subtraction, order of operations, IPEE labels, estimate | Fronts 5, 9, and 10; arithmetic Chapters 2–4; IPEE and estimation are inbound | Full identify-plan-execute-evaluate solution uses no new algebra term | pass |
| 12 | Keep one chosen value for repeated occurrences | Evaluation, variable, same symbol, addition | Fronts 1–2 and 9–10; the convention is also stated on this front before the why-question | Confirms both occurrences receive the same value | pass |
| 13 | Translate “more than” | Variable and addition; verbal-order convention is new | Arithmetic addition and Front 1; the front explains the phrase before asking for the expression | Confirms `n+7` | pass |
| 14 | Translate “less than” with correct order | Variable and subtraction; verbal-order convention is new | Arithmetic subtraction and Front 1; the front explicitly says what is subtracted from what | Contrasts `n-5` with `5-n` without assuming later equation ideas | pass |
| 15 | Translate “times” to juxtaposition | Variable and multiplication; verbal phrase is new | Arithmetic multiplication and Front 5; the front explains the phrase before asking for notation | Confirms `6m` | pass |
| 16 | Translate and evaluate an equal-groups context | Identical groups, loose items, variable, multiplication notation, expression, substitution, IPEE | Arithmetic Chapter 3 and Fronts 1, 3, 5, 9–10, 13, and 15 | Solution makes each method choice explicit and checks against the context | pass |
| 17 | Diagnose multiplication-versus-addition confusion | Coefficient notation, addition, evaluation at a chosen value, equality claim | Fronts 3, 5, 7, and 9–10 plus arithmetic operations | The numerical comparison directly refutes “always equal” without introducing proof vocabulary | pass |
| 18 | Transfer evaluation to a table | Table-row grammar, chosen variable value, expression, substitution, multiplication, addition | Arithmetic Chapter 8; the front states exactly what the table records; Fronts 1, 3, 5, and 9–10 | Solution substitutes, evaluates, and uses inverse operations to recover the row value | pass |

## Dependency ledger disposition

Every row in the pilot concept-dependency ledger in `CARD_README.md` resolves to
the declared arithmetic deck or to an earlier scheduled establishment point. No
front depends on a later chapter, unscheduled prose, an answer-only first
explanation, an undeclared tool, or an answer-revealing asset.

## Parser, identity, representation, and scope checks

- Scheduled inventory: 15 `Q:/A:` blocks, 0 `C:` blocks, and 3 `P:/S:` blocks.
- Every block has a unique repository-scoped `card-id`.
- All teaching bridges needed by the pilot are on scheduled fronts.
- The only table is inside Problem 18's scheduled front.
- No figure is required for the pilot's retrieval decisions; all three candidate
  figure opportunities are intentionally omitted in the chapter design ledger.
- No later chapter card or figure was authored.

## Gate decision

The pilot has no blocked or unexplained semantic dependency. Stop after validation
for human review; later chapters remain plans only.

## Validation results

- `flashcards deck stabilize . --check`: passed; 18 schedulable cards and no
  missing stable IDs.
- Direct `flashcards deck validate .`: parser, KaTeX, image, identity, cloze, and
  frontmatter checks all passed for 18 cards; the command exited nonzero only
  because the isolated path lookup ignored the supplied staged prerequisite deck.
- `flashcards deck validate` against a temporary in-workspace collection layout
  with the exact staged arithmetic deck: passed; 18 cards and a valid graph with
  one local chapter and one external deck.
- `git diff --check`: passed.
