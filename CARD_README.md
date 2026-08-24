# Elementary Algebra And Functions card blueprint

This file records retrieval decisions specific to this deck. The universal card
standard, authoring playbook, mathematics guide, and subject roadmap remain the
canonical general guidance.

## Learner model

- Level: foundational novice in algebra.
- Confirmed mathematical prerequisites: the complete
  `mathematics/number-sense-and-arithmetic` deck.
- Confirmed tools: none.
- Capabilities this deck should produce: translate among verbal, symbolic,
  numerical, tabular, and graphical representations; select, execute, and check
  elementary algebraic methods; interpret functions and model parameters; and
  distinguish linear, quadratic, rational, exponential, and logarithmic
  structure.
- Important exclusions: formal proof, geometry theory, calculator-dependent
  graphing, advanced radical and rational-function analysis, trigonometry,
  complex numbers, sequences, conic sections, and long multi-step applications
  better practiced outside SRS.

Unconfirmed algebra knowledge is not mastered. Chapter 1 is the novice-first
pilot; every later chapter remains behind the pilot approval gate.

## Curriculum and prerequisite graph

The full arithmetic deck is a hard deck prerequisite. Chapter 1 adds no local
chapter edge. The remaining scaffold declares only the chapter edges needed to
resolve its capabilities; file order alone never grants inbound knowledge. The
14-chapter plan stays within the subject's course-size band and extends the
original 12-chapter estimate so rational and logarithmic functions required by
the subject roadmap are not hidden inside one overloaded nonlinear chapter.

Rejected boundary choices:

- Coordinate notation, function notation, slope, domain, and range are not used
  to make the symbolic-language pilot appear more advanced.
- Signed multiplication is not assumed from the prerequisite's signed-addition
  chapter, so the pilot evaluates expressions only at nonnegative values.
- Geometry formulas and quadratic examples are reserved for chapters whose
  dependency chains establish them. Elementary square roots enter only with
  quadratic solving; radical-function analysis remains a precalculus handoff.
- Rational expressions and functions are reserved for Chapter 13, after factoring
  and domain language. Exponential and logarithmic functions are reserved for
  Chapter 14, after exponent properties and function representations.

## Concept-dependency ledger — pilot

Allowed inbound knowledge is limited to the validator-resolved capabilities of
`mathematics/number-sense-and-arithmetic`: quantities and whole numbers; the four
arithmetic operations; inverse-operation checks; arithmetic expressions and
operation order; whole-number powers; signed numbers and signed addition and
subtraction; fraction and decimal operations; ratios, rates, proportions, and
percents; and measurement, units, and quantitative reasonableness. The external
card bodies are not present in this isolated run, so no vocabulary beyond those
declared capabilities is inferred. In particular, signed multiplication is not
assumed.

The pilot sequence below freezes the concept frontier before card authoring.
Front labels refer to the intended first-learning order in Chapter 1.

| New concept, notation, or representation | First scheduled explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|
| A letter standing for a number; **variable** | F01 explains that a letter can stand for a concrete number and names it a variable. | F01 retrieves the represented number; F02 retrieves the meaning of variable. | F03 onward | pass |
| **Algebraic expression** | F03 contrasts inbound arithmetic expressions with an expression that contains a variable. | F03 classifies `3 + x`; F04 interprets what it instructs the reader to do. | F06 onward | pass |
| **Equation** and equals-sign assertion | F05 defines an equation as a statement that uses an equals sign to say two quantities have the same value. | F05 selects the equation; F06 discriminates equation from expression. | F11 onward | pass |
| **Term** | F07 explains the simple top-level sum-of-terms reading without generalizing through nested grouping. | F07 identifies the terms of `x + 7`. | F09–F10 and later translations | pass |
| Juxtaposition `4x` meaning `4 × x`; **coefficient** | F08 states the notation and defines the number multiplying a variable as its coefficient. | F08 identifies the coefficient of `4x`. | F10, F13–F14, F16–F17, F20 | pass |
| **Constant term** | F09 defines it as a term with no variable. | F09 identifies the constant term of `4x + 7`. | F10, F13–F14, F16–F17 | pass |
| **Substitution** | F11 defines substitution as replacing a variable with its given number. | F11 produces an arithmetic expression after substitution. | F12–F14, F17–F18, F20 | pass |
| **Expression evaluation** and expression value | F12 explains that evaluating means calculating the expression's number after substitution. | F12 evaluates a one-operation expression. | F13–F14, F17–F18 | pass |
| Verbal-to-symbolic translation | F15 self-bridges “add 6 to a number”; F16 extends to multiplication followed by addition. | F15 and F16 each retrieve one expression. | F17 and F19 | pass |
| Context-to-expression translation | F17 states every contextual quantity and asks for one complete translation-and-evaluation task. | F17 | Closing discrimination | pass |
| Two-column value table | F18 explains on its front what each column records. | F18 completes one missing value by substitution and evaluation. | Later function tables are intentionally deferred to Chapter 7. | pass |
| Subtraction-order wording | F19 uses inbound subtraction to contrast `8 - n` with `n - 8`. | F19 | Later equation and function contexts | pass |

Function notation, coordinates, graphs, slope, domain, range, negative
substitution, properties of operations, equivalent expressions, equation
solving, inequalities, exponents on variables, and quadratic contexts remain
outside the pilot frontier. Tempting examples using formulas, geometry, signed
multiplication, or later function language are intentionally rejected.

## Retrieval portfolio

The course prioritizes operational definitions, structural interpretation,
translation among authentic representations, method selection, error diagnosis,
and short checked execution. Likely interference pairs are handled only after both
members are established: expression/equation, coefficient/exponent,
additive/multiplicative comparison, solution/value, relation/function,
rate/intercept, linear/quadratic/rational/exponential change, and
exponent/logarithm.

## Chapter design ledger

All rows are plans only. Their cards and figures remain unauthored behind the
pilot gate. Form choices are candidate roles, not quotas.

| Chapter | Purpose and learner capability | Retrieval targets and planned forms | Problem or application progression | Representations and figure opportunities | Boundary or handoff |
|---|---|---|---|---|---|
| 1. Variables and expressions | Read algebra as meaningful notation and evaluate a represented quantity. | Planned: 16 bounded `Q:/A:` decisions for variable meaning, expression/equation discrimination, structural vocabulary, substitution, evaluation, translation, and diagnosis; 4 `P:/S:` transfer tasks; 0 clozes because none of the new notation is both established and best learned as an exact deletion. | P13 analyzed substitution/evaluation → P14 faded calculation → P17 independent contextual translation/evaluation → P18 tabular transfer; all retain complete IPEE stages. | Verbal, symbolic, numerical, contextual, and tabular forms. **Figures intentionally omitted:** an expression tree duplicates inbound operation structure for these simple expressions; an annotated coefficient/constant diagram would reveal the requested labels; a context-object drawing duplicates inbound equal-groups arithmetic; the authentic two-column table is clearer as accessible Markdown. | Function notation, coordinates, slope, properties/equivalence, equation solving, and negative substitution remain downstream. |
| 2. Equivalent expressions | Rewrite an expression without changing the quantity it represents. | Operation properties, distribution, like terms, equivalence, and error diagnosis; primarily basic reasoning cards, with property-name clozes only after meaning is established. | Analyzed distribution → like-term completion → independent simplification → mixed equivalent/non-equivalent discrimination. | Symbolic forms and numerical-check tables. Candidate area model for distribution and expression tree for structure, each included only if it tests translation rather than geometry. | Equation solving is deferred; this chapter changes form, not the value sought. |
| 3. Equations and equality | Interpret and solve one-step equations while preserving equality. | Solution meaning, equality-preserving moves, inverse-operation choice, and substitution checks; basic reasoning plus IPEE problems, no planned cloze. | Analyzed balance move → completion → independent one-step equations → mixed operation choice and error diagnosis. | Symbolic, verbal, and balance representations. Candidate balance-scale figures earn inclusion only for equality-preserving transformations. | Multi-step simplification and variables on both sides belong to Chapter 4. |
| 4. Multi-step equations and formulas | Combine simplification and inverse operations to isolate a quantity and rearrange formulas. | Multi-step linear equations, variables on both sides, formula rearrangement, identity/contradiction cases; basic method-choice cards and IPEE problems, no planned cloze. | Fully analyzed equation → faded plan → independent formula rearrangement → mixed one/none/all-solution cases. | Symbolic equations and contextual formulas. Candidate operation-flow diagram only if it supports reversal-method selection. | Formal proof is excluded; quadratic and rational equations wait for their structures. |
| 5. Inequalities and solution sets | Solve and represent one-variable constraints rather than single-value equalities. | Inequality meaning, boundary inclusion, negative reversal, checking, number-line graphs, and interval notation; basic figure interpretation and problems; compact symbol clozes only after visual meaning is stable. | Analyzed one-step inequality → boundary/graph completion → independent solve/check → mixed equation/inequality selection. | Symbolic, interval, and number-line forms. Separate open/closed-boundary and negative-reversal figures have distinct retrieval roles. | Systems of inequalities and optimization are outside this deck. |
| 6. Coordinate plane and relations | Treat ordered pairs as solutions and translate tables or equations into plotted relations. | Axes, origin, ordered-pair order, scale, relation, and solution membership; figure-reading and translation basics plus plotting problems, no planned cloze. | Guided plotting → read a point and scale → independent table-to-plot → mixed equation/graph membership check. | Tables, ordered pairs, and coordinate graphs. Point reading, scale diagnosis, and equation-solution membership need separate figure opportunities. | Function tests and function notation wait for Chapter 7. |
| 7. Functions across representations | Decide when each allowed input has exactly one output and move among function representations. | Function/non-function discrimination, input/output, domain/range, notation, evaluation, and representation translation; basic reasoning and IPEE translation, with notation clozes only after conceptual establishment. | Mapping analysis → table completion → notation evaluation → mixed verbal/table/graph/formula discrimination. | Verbal rules, mappings, tables, graphs, and formulas. Mapping and vertical-line-test figures support distinct decisions; table-restatement figures are omitted. | Transformation families and inverse-function theory are reserved for precalculus. |
| 8. Proportional and linear functions | Generalize inbound proportional reasoning to linear functions with constant rate and possible nonzero initial value. | Proportional versus non-proportional linear structure, rate of change, initial value, parameters, and model interpretation; basic comparisons and modeling problems, no planned cloze. | Analyze an inbound proportional table → infer rate → build an independent linear model → mixed linear/nonlinear discrimination. | Tables, graphs, equations, and contexts. Proportional/non-proportional graph comparison and rate triangles are separate figure opportunities. | Detailed line forms follow in Chapter 9; statistics-style regression is excluded. |
| 9. Equations of lines | Construct and interpret a line from points, rates, tables, graphs, or contexts. | Slope, intercepts, slope-intercept, point-slope, and standard forms; basic parameter interpretation, possible form-name clozes after meaning, and method-selection problems. | Analyzed line construction → missing-parameter completion → independent equation → mixed representation/form choice. | Coordinate graphs, tables, and equations. Slope and intercept figures are separate when the visual decisions differ. | Parallel/perpendicular geometry is a neighboring geometry/precalculus topic except where needed to read slopes. |
| 10. Systems of linear equations | Interpret a shared solution and choose graphing, substitution, or elimination appropriately. | System solution, method cues, no/one/many solutions, and checks; basic graph interpretation and IPEE method-selection problems, no planned cloze. | Analyzed intersection → substitution completion → independent elimination → mixed method and solution-case selection. | Paired equations and overlaid graphs. Intersection, parallel, and coincident configurations are distinct visual targets. | Larger systems and matrix methods belong to linear algebra. |
| 11. Exponents and polynomial expressions | Extend arithmetic powers and expression laws to algebraic exponent and polynomial structure. | Exponent properties with conditions; monomial/polynomial vocabulary; degree; addition, subtraction, and multiplication; basic explanations, a few compact law clozes after derivation, and operation problems. | Numeric pattern analysis → supported law use → polynomial-operation completion → independent mixed simplification. | Symbolic expressions, factor/product structure, and coefficient tables. Area/product figures are candidates for polynomial multiplication; growth graphs wait for Chapter 14. | Factoring, roots, and polynomial functions are deferred to Chapter 12; negative/fractional exponents are precalculus depth. |
| 12. Factoring and quadratic functions | Connect products, factors, zeros, solution methods, and parabolic graphs. | Common-factor and trinomial factoring; zero-product property; square roots; completing the square; quadratic formula; discriminant-level solution cases; quadratic features. Basic structure/method cards, possible formula cloze only after derivation, and IPEE problems. | Product-area analysis → factoring completion → independent zero-product solve → method selection among factoring, square roots, completing the square, and formula → graph/equation transfer. | Symbolic forms, tables, product/area models, and parabolic graphs. Factor-area, zero/intercept, vertex, and model-comparison figures each require separate review. | Complex roots and radical-function analysis are excluded; richer polynomial behavior belongs to precalculus. |
| 13. Rational expressions and functions | Treat quotients of polynomials as expressions with excluded inputs and connect algebraic restrictions to graph behavior. | Denominator restrictions, simplification, elementary operations, extraneous-solution checks, reciprocal/inverse-variation models, zeros, holes, and vertical asymptotes; basic diagnosis and IPEE problems, no formula cloze planned. | Analyze a numeric rational analogy → restriction/simplification completion → independent simple rational equation → mixed symbolic/graph/domain discrimination. | Symbolic expressions, domain statements, tables, and reciprocal-type graphs. Hole-versus-intercept and asymptote figures have distinct visual roles. | Polynomial long division, oblique asymptotes, and full rational-function analysis are deferred to precalculus. |
| 14. Exponential and logarithmic functions | Model repeated multiplicative change and interpret logarithms as inverse exponent questions. | Exponential growth/decay, initial value and factor, percent change, exact tables/graphs, logarithm meaning, inverse operation, and elementary exact equations; basic contrasts, limited notation clozes after meaning, and modeling problems. | Analyze repeated multiplication → identify growth/decay parameters → build and compare exact models → solve supported exponential/logarithmic equations → mixed linear/quadratic/exponential discrimination. | Verbal, symbolic, tabular, and graph forms. Linear-versus-exponential, growth-versus-decay, and exponential/logarithmic inverse graph pairs are separate figure opportunities. | Calculator-dependent approximation, change of base, inverse-function theory, and advanced transformations belong to precalculus. |

## Initial-learning path

The pilot must begin with a scheduled front that defines a variable and gives it
a concrete numerical meaning. Every later new term must likewise be established
on a scheduled front before less-supported retrieval or application.

## Figure policy and pilot decision

Figures will be authored in TikZ and compiled to accessible SVG when visual
inspection is itself the retrieval target. The pilot agent must record each
include/omit decision before publication.

Chapter 1 has no figure whose removal would change the retrieval decision. Its
structural and translation targets are authentically symbolic, verbal,
contextual, and tabular; the four plausible visual opportunities are therefore
intentionally omitted for the reasons recorded in the Chapter 1 design row.

## Planned-versus-actual reconciliation

| Chapter | Planned card types | Actual card types | Planned problems | Actual problems | Planned figures | Actual figures | Reconciliation |
|---|---|---|---|---|---|---|---|
| 1 | 16 basic, 0 cloze, 4 problem | 16 basic, 0 cloze, 4 problem | Analyzed → faded → independent contextual → tabular transfer; 4 problems | 4 problems with complete IPEE stages | 0; four opportunities intentionally omitted | 0 | Exact match. Parser counts and the front-by-front reconciliation are recorded in `.flashcards/audits/pilot-cold-start.md`. |
| 2–14 | Planned in the chapter design ledger | 0 | Planned only | 0 | Opportunities inventoried in each row; no assets authorized before pilot approval | 0 | Later chapters remain empty and outside this job. |

## Sources and accuracy

The deck-local source register is in `README.md`. Chapter 1 content and sequence
were checked against the official Common Core Expressions & Equations standards
and England's statutory mathematics programme; their authority, terms, source
role, and 2026-08-24 access date are recorded there. Cards, problems, and
representations are original.

## Validation gate

Before handoff:

1. Run deterministic prerequisite, stabilization, and deck validation.
2. Confirm Chapter 1 contains 20 scheduled cards with unique stable IDs and that
   no later-chapter content was materialized in the bounded workspace.
3. Confirm every problem retains complete ordered IPEE stages and every planned
   versus actual inventory is reconciled.
4. Confirm the fronts-only cold-start and separate first-use scans pass with no
   unexplained dependency.
5. Run `git diff --check` and review the complete diff.

Stop after this pilot for explicit human approval before authoring Chapter 2 or
any later chapter.
