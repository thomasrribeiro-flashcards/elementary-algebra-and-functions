# Chapter 02 cold-start audit — Equivalent expressions

Audit date: 2026-08-24
Mode: build, bounded to flashcards/02_equivalent_expressions.md
Edge mode: explicit
Target prerequisite: chapter:01_variables_and_expressions
External deck prerequisite: mathematics/number-sense-and-arithmetic
Assumed tools: none

cold_start_status: pass
unresolved_dependencies: 0

## Learner contract and chapter-boundary ledger

Only the CLI-resolved edge closure is treated as mastered. The external staged
files expose validator-resolved capability summaries rather than card bodies, so
this audit does not infer vocabulary or procedures beyond those capabilities.

| Inbound concept or representation | Confirmed source | Chapter 02 use | Status |
|---|---|---|---|
| Variable, algebraic expression, term, coefficient, constant term | Chapter 01 F01–F10 | Parse all symbolic expressions and classify like or unlike terms | pass |
| Substitution and expression evaluation | Chapter 01 F11–F14 | Numerical equivalence checks | pass |
| Two-column value table | Chapter 01 F18 | Basis for the explicitly bridged three-column table on F03 | pass |
| Juxtaposition such as \(4x\) meaning multiplication | Chapter 01 F08 and F20 | Coefficients, distribution, and like-term checks | pass |
| Whole-number addition, subtraction, multiplication, and division | External capability summaries, Chapters 02–03 | Complete coefficient and constant calculations | pass |
| Arithmetic expressions, operation order, and parentheses | External capability summary, Chapter 04 | Read grouped expressions before distribution | pass |
| Signed numbers and signed addition/subtraction | External capability summary, Chapter 05 | Available but not required by the authored fronts | pass |
| Fractions, decimals, ratios, percents, measurement, and reasonableness | External capability summaries, Chapters 06–10 | Available but intentionally unused because they add no Chapter 02 retrieval value | pass |

Signed multiplication is not declared by the staged external summaries. Every
factor, coefficient, and substituted value in this chapter is therefore a
nonnegative whole number. No equation solving, function notation, coordinates,
graphs, exponents on variables, factoring, or later-chapter representation is
used.

## Chapter design ledger

| Design area | Planned decision | Actual result |
|---|---|---|
| Retrieval targets and card forms | Equivalence, operation properties, distribution, like terms, simplification, and diagnosis through 16 basic cards; one property-name cloze only after meaning; 5 problems | Exact match: 16 Q:/A:, 1 C:, 5 P:/S: |
| Problem progression | Analyzed distribution → like-term completion → faded collection → independent simplification → mixed equivalence decision | Exact match: F11 → F15 → F18 → F20 → F22 |
| Authentic representations | Symbolic expressions and an accessible numerical-check table | Exact match; F03 is the table translation and all other fronts are symbolic/verbal |
| Area-model figure | Omit because area and rectangle-measure grammar are not inbound | Omitted |
| Variable-tile or array figure | Omit because it requires new visual grammar without a distinct retrieval target | Omitted |
| Expression-tree figure | Omit because it duplicates established parentheses and operation order | Omitted |

Cards and examples are original. Scope and claims were checked against the
[Common Core Expressions & Equations standards](https://www.thecorestandards.org/Math/Content/EE/),
the [Common Core properties table](https://www.thecorestandards.org/Math/Content/mathematics-glossary/Table-3/),
and the UK Department for Education
[key stage 3 mathematics guidance](https://assets.publishing.service.gov.uk/media/621629ac8fa8f5490d52ee78/KS3_NonStatutory_Guidance_Sept_2021_FINAL_NCETM.pdf).
Authority, terms, source roles, and access dates are recorded in README.md.

## Concept-dependency ledger

| New concept, symbol, or representation | First scheduled explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|
| Equivalent expressions | F01 defines agreement for every variable value and asks for a shared substituted value | F02 retrieves the condition; F03 rejects a pair from a differing row | F04 onward and F21–F22 | pass |
| Three-column expression-value table | F03 explains that each row substitutes one \(x\)-value into both expressions | F03 identifies the decisive differing row | No later dependency; structural properties replace exhaustive checking | pass |
| Property of operations; commutative property | F04 defines value-preserving property use and order change | F04 rewrites \(x+4\) | F06, F18, F20–F22 | pass |
| Associative property | F05 explains grouping change without order change | F05 regroups one sum; F06 contrasts it with commutativity | F18, F20–F22 | pass |
| Additive identity | F07 defines the role of \(0\) | F07 rewrites \(x+0\) | F21 | pass |
| Multiplicative identity | F08 defines the role of \(1\) | F08 rewrites \(1x\) | F22 | pass |
| Distributive property | F09 explains multiplication of every item inside the addition | F09 performs the first supported rewrite; F10 retrieves the name | F11–F12, F19–F22 | pass |
| Like terms with a shared variable | F13 defines the chapter-bounded criterion | F13 selects the valid pair; F14 connects repeated addition with a coefficient | F15–F16, F18–F22 | pass |
| Constants as like terms | F17 explains that constant terms are like one another | F17 combines two constants | F18, F20 | pass |
| Simplifying an expression | F19 defines an equivalence-preserving finished form | F19 discriminates the simplified form | F20–F22 | pass |

## Front-by-front cold-start scan

The scan was performed on the ordered Q:, C:, and P: fronts only. For each row,
dependencies were recorded before the corresponding answer or solution was
checked.

| Front | Dependencies needed to parse and attempt | Source or bridge available before attempt | Finding |
|---|---|---|---|
| F01 | Variable, substitution, addition; new equivalence relation | Chapter 01; equivalence is defined on this front | pass |
| F02 | Algebraic expression, variable; equivalent | Chapter 01; F01 | pass |
| F03 | Substitution, \(2x\), table reading; equivalence | Chapter 01 F08, F11–F12, F18; this front explains the added result column; F01–F02 | pass |
| F04 | Addition and variable notation; property and commutativity | Inbound arithmetic/Chapter 01; both new terms are minimally explained on this front | pass |
| F05 | Parentheses and operation order; associativity | External arithmetic structure; the new property is explained on this front | pass |
| F06 | Commutative and associative properties | F04–F05 | pass |
| F07 | Addition, zero, equivalence; additive identity | Inbound arithmetic; F01–F02; identity is explained on this front | pass |
| F08 | Multiplication notation, one, equivalence; multiplicative identity | Chapter 01 F08; inbound arithmetic; F01–F02; identity is explained on this front | pass |
| F09 | Multiplication, addition, parentheses; distribution | Inbound arithmetic and Chapter 01; the distributive rule is explained on this front | pass |
| F10 | The distributive transformation and its name | F09 | pass |
| F11 | Equivalent-expression rewrite, parentheses, distribution | F01–F02 and F09–F10 | pass |
| F12 | Distribution and error diagnosis | F09–F11 | pass |
| F13 | Term, variable, coefficient, constant; like terms | Chapter 01 F07–F10; like terms are explained on this front | pass |
| F14 | Equivalent expression, coefficient, repeated addition | F01–F02; Chapter 01 F08; inbound addition/multiplication; F13 | pass |
| F15 | Like terms and coefficients | F13–F14 | pass |
| F16 | Like versus constant terms | F13–F15; Chapter 01 F09 | pass |
| F17 | Constant terms and like-term extension | Chapter 01 F09; the constant-term case is explained on this front | pass |
| F18 | Both categories of like terms; operation properties | F13–F17; F04–F08 | pass |
| F19 | Distribution, like terms; new simplification goal | F09–F18; simplification is explained on this front | pass |
| F20 | Simplification procedure | F19 plus F09–F18 | pass |
| F21 | Distribution, combining like terms, additive identity, equivalence | F01–F20 | pass |
| F22 | Equivalence decision, distribution, like terms, multiplicative identity, substitution check | F01–F21 and Chapter 01 substitution/evaluation | pass |

Answer/solution review found no new term or procedure later assumed without an
earlier supported establishment. Every S: begins immediately with IDENTIFY,
retains IDENTIFY → PLAN → EXECUTE → EVALUATE, places the direct result first in
EXECUTE, and uses substitution as a genuine EVALUATE check.

## Separate first-use scan (U11 and D8)

| First use on a scheduled front | Classification | Check |
|---|---|---|
| Equivalent expressions on F01 | Minimally self-bridged from inbound variable values and evaluation | pass |
| Three-column numerical-check table on F03 | Extension of Chapter 01 F18, with every column's role stated | pass |
| Property of operations and commutative property on F04 | Minimally self-bridged using inbound addition and multiplication | pass |
| Associative property and grouping change on F05 | Minimally self-bridged using inbound operations, parentheses, and operation order | pass |
| Additive and multiplicative identity properties on F07–F08 | Each explained before its bounded retrieval | pass |
| Distributive property on F09 | Explained and used in a supported rewrite before name recall or application | pass |
| Symbolic distributive pattern on F10 | Uses only the concrete pattern already retrieved on F09; no new variable-product notation | pass |
| Like terms on F13 | Explained using established term, variable, and coefficient language | pass |
| Constant terms as like terms on F17 | Explained before combined-variable-and-constant application | pass |
| Simplify an expression on F19 | Explained after distribution and both like-term cases are retrieved | pass |

No figure, alt text, distractor, supplied premise, or ordinary word with a new
technical meaning crosses the established frontier. The rejected area,
variable-tile, exponent, factoring, equation-solving, and function examples
remain outside the chapter.

## Inventory reconciliation and validation evidence

- Planned versus actual card types: exact match — 16 basic, 1 cloze, 5 problem.
- Planned versus actual problem sequence: exact match — F11, F15, F18, F20, F22.
- Planned versus actual figures: exact match — 0, with all three opportunities
  intentionally omitted above.
- flashcards deck stabilize . --check: pass; no missing stable IDs.
- flashcards deck validate .: 42 cards across Chapters 01–02; 32 basic,
  1 cloze, 9 problem; 0 parser warnings, KaTeX errors, image errors, identity
  errors, markup errors, cloze lints, or frontmatter lints.
- The standalone validator reports one collection-path prerequisite error because
  it searches for the external deck outside this isolated workspace. The staged
  closure and .flashcards/prerequisites/graph.json resolve the declared edge;
  this environment limitation does not create a learner dependency.
