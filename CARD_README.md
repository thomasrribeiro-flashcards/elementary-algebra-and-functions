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
  distinguish linear from elementary nonlinear structure.
- Important exclusions: formal proof, geometry theory, calculator-dependent
  graphing, rational and radical function analysis, logarithms, trigonometry,
  complex numbers, and long multi-step applications better practiced outside SRS.

Unconfirmed algebra knowledge is not mastered. The pilot gate permits authoring
only Chapter 1 until a human approves it.

## Curriculum and prerequisite graph

The full arithmetic deck is a hard deck prerequisite. Chapter 1 adds no local
chapter edge; later chapters must declare their own actual concept or chapter
edges when authored. File order alone never grants inbound knowledge.

Rejected boundary choices:

- Coordinate notation, function notation, slope, domain, and range are not used
  to make the symbolic-language pilot appear more advanced.
- Signed multiplication is not assumed from the prerequisite's signed-addition
  chapter, so the pilot evaluates expressions only at nonnegative values.
- Geometry formulas, rational expressions, radicals, and quadratic examples are
  reserved for chapters whose dependency chains establish them.

## Concept-dependency ledger — pilot

Front numbers refer to the scheduled order in
`flashcards/01_variables_and_expressions.md`.

| Concept or representation | Front(s) requiring it | Confirmed inbound source or first explanation | First supported retrieval | Later application | Status |
|---|---|---|---|---|---|
| Quantity, numeral, and whole-number arithmetic | 1, 5, 9, 11, 13–18 | Arithmetic deck Chapters 1–3 | Inbound | Throughout pilot | ready |
| Arithmetic expression, grouping, powers, and operation order | 3, 9–12, 16, 18 | Arithmetic deck Chapter 4 | Inbound | Expression evaluation | ready |
| Equals sign as an equality claim | 3–4 | Arithmetic deck Chapter 2 | Inbound | Expression/equation discrimination | ready |
| Table rows representing paired values | 18 | Arithmetic deck Chapter 8; Front 18 also states what the table records | Front 18 | Later functions chapters | ready |
| IPEE problem labels and inverse/size checks | 11, 16, 18 | Repeatedly established in the arithmetic deck | Inbound | All pilot problems | ready |
| Variable | 1–18 | Front 1 defines the term and maps `n` to a known count | Front 2 | Fronts 3–18 | ready |
| Algebraic expression | 3, 6–18 | Front 3 defines it and contrasts it with an equality claim | Front 3 | Fronts 6–18 | ready |
| Equation | 4 | Front 4 defines it before asking for identification | Front 4 | Reserved for Chapters 3–4 | ready |
| Juxtaposed multiplication such as `4x` | 5–18 | Front 5 explains that `4x` means `4 times x` | Front 5 | Fronts 6–18 | ready |
| Term | 6–8 | Front 6 defines separation by addition or subtraction | Front 6 | Coefficient and constant interpretation | ready |
| Coefficient | 7, 17 | Front 7 defines the numerical factor multiplying a variable | Front 7 | Front 17 | ready |
| Constant term | 8 | Front 8 defines a term with no variable | Front 8 | Later expression rewriting | ready |
| Substitution | 9–12, 16, 18 | Front 9 demonstrates replacement before asking for the resulting value | Front 9 | Fronts 10–12, 16, 18 | ready |
| Evaluation of an algebraic expression | 9–12, 16, 18 | Front 9 gives an analyzed example; Front 10 names the procedure | Front 9 | Problems 11, 16, and 18 | ready |
| One variable has one chosen value within an evaluation | 12 | Front 12 states the convention before asking why both occurrences match | Front 12 | Later equation and function work | ready |
| “More than,” “less than,” and “times” translation | 13–16 | Each of Fronts 13–15 explains one phrase before asking for its expression | Fronts 13–15 | Context problem 16 | ready |

Rejected pilot examples included function notation `f(x)`, coordinate graphs,
slope, negative substitution values, area formulas, and quadratic contexts. Each
would require a later chapter or a needless prerequisite chain for the pilot's
actual target.

## Retrieval portfolio

The course prioritizes operational definitions, structural interpretation,
translation among authentic representations, method selection, error diagnosis,
and short checked execution. Likely interference pairs are handled only after both
members are established: expression/equation, coefficient/exponent,
additive/multiplicative comparison, solution/value, relation/function,
rate/intercept, and linear/quadratic/exponential change.

## Chapter design ledger

Rows for Chapters 2–12 are plans only. Their cards and figures remain unauthored
behind the pilot gate.

| Chapter | Retrieval targets | Basic-card roles | Cloze candidates | Problem progression | Representations and figure opportunities |
|---|---|---|---|---|---|
| 1. Variables and expressions | Variable meaning; expression/equation distinction; terms, coefficients, constants; substitution; evaluation; short verbal translation | Definitions with inference, symbolic interpretation, translation, and misconception diagnosis | None: every target requires interpretation or a procedure, not isolated exact wording | Analyzed substitution on Front 9 → scaffolded calculation on Problem 11 → independent contextual translation/evaluation on Problem 16 → tabular transfer on Problem 18 | Verbal, symbolic, numerical, contextual, and Markdown table included. Omit unknown-bag drawing: text already supplies the relationship. Omit expression tree: prerequisite already established tree grammar and no new visual decision results. Omit substitution arrows: the symbolic before/after sequence is clearer and accessible without an asset. |
| 2. Equivalent expressions | Operation properties, distributive property, like terms, equivalence checks | Explain why rewrites preserve value; diagnose non-equivalent rewrites | Possible exact property names only after meaning is established; otherwise none | Analyzed distribution → combine-like-terms completion → independent rewrite → mixed equivalence discrimination | Symbolic and numerical-check tables. Candidate area model: include if it tests distribution rather than geometry; candidate expression tree: include only for structure translation. |
| 3. Equations and equality | Solution meaning, balance principle, one-step inverse operations, verification | Interpret and diagnose balance moves | None anticipated; equation solving is procedural | Analyzed balance → completion → one-step independent equations → mixed operation choice | Symbolic, verbal, and balance representation. Candidate balance-scale figure: include for equality-preserving transformations; omit decorative scales. |
| 4. Multi-step equations and formulas | Simplify then isolate, variables on both sides, identities/contradictions, rearranging formulas | Method choice, step justification, special-case discrimination | None anticipated | Fully analyzed multi-step equation → faded plan → independent formula rearrangement → mixed cases | Symbolic and contextual formulas. Candidate flow/reversal diagram: include only if it supports inverse-operation selection. |
| 5. Inequalities and solution sets | Inequality meaning, boundary inclusion, negative reversal, interval and number-line interpretation | Explain direction changes; interpret and diagnose graphs | Compact inequality-symbol meanings may become clozes after visual meaning is learned | Analyzed one-step inequality → graph completion → independent solve/check → mixed equation/inequality choice | Symbolic and number-line representations. Include distinct open/closed-boundary and reversal figures if each supports a separate retrieval decision. |
| 6. Coordinate plane and relations | Axes, origin, ordered-pair order, scale, plotted solution sets | Figure reading, representation translation, scale diagnosis | None anticipated | Guided plotting → read a point → independent table-to-plot → mixed equation/graph check | Tables, ordered pairs, coordinate graphs. Include coordinate-plane figures for point reading, scale interpretation, and equation-solution membership; these are distinct visual roles. |
| 7. Functions across representations | Exactly-one-output rule, input/output, domain, range, notation, representation translation | Function/non-function discrimination and contextual interpretation | Function-notation components may be clozed only after conceptual establishment | Mapping analysis → table completion → notation evaluation → mixed representation discrimination | Verbal rules, mappings, tables, graphs, formulas. Include mapping and vertical-line-test figures for distinct decisions; omit figures that merely restate a table. |
| 8. Proportional and linear functions | Constant rate, initial value, proportional versus non-proportional linear relationships | Interpret parameters and compare representations | None anticipated | Analyze arithmetic-deck proportional table → infer rate → independent linear model → mixed linear/nonlinear discrimination | Tables, graphs, equations, contexts. Include proportional/non-proportional graph comparison and rate triangles if each tests a separate translation. |
| 9. Equations of lines | Slope from points/tables/graphs, intercepts, equation forms, building a line | Method selection and parameter interpretation | Exact form names may be clozed only if useful after meaning is stable | Analyzed line construction → missing-parameter completion → independent equation → mixed form choice | Coordinate graphs, tables, equations. Include slope and intercept figures; use separate figures only where the visual decisions differ. |
| 10. Systems of linear equations | Shared solution, graphing/substitution/elimination choice, no/one/many solutions | Interpret intersections and choose methods | None anticipated | Analyzed graph → substitution completion → elimination independent → mixed method selection | Paired equations and overlaid graphs. Include intersection and parallel/coincident figures; visual configuration is the target. |
| 11. Exponents and polynomial expressions | Exponent laws, repeated factors, simple exponential change, polynomial vocabulary and operations | Explain law conditions; contrast additive and multiplicative change | A few compact exponent laws may be clozed after derivation; no quota | Numeric pattern analysis → law completion → polynomial operation → mixed linear/exponential choice | Symbolic, tables, and graphs. Include linear/exponential table or graph comparison if it tests growth structure; omit decorative growth imagery. |
| 12. Factoring, quadratics, and nonlinear models | Factoring as reverse multiplication, zeros, elementary quadratic solutions, graph features, model-family contrast | Structure recognition, method choice, boundary checks | Quadratic formula is intentionally omitted at this level unless later review changes the boundary | Area/product analysis → factor completion → independent zero-product solve → mixed linear/quadratic/exponential model choice | Symbolic, tables, and parabolic graphs. Include factor-area model, zero/intercept graph, and model comparison only when each earns a distinct retrieval role. |

## Initial-learning path

Chapter 1 begins with a scheduled front that defines a variable and gives it a
concrete numerical meaning. Every later new term is similarly defined on a front
that permits inference before a less-supported retrieval. Substitution is first
shown as a replacement step; the learner then retrieves the procedure, completes a
scaffolded problem, applies it in context, and transfers it to a table. No heading,
lesson paragraph, or unscheduled figure is relied upon for instruction.

## Figure policy and pilot decision

Figures will be authored in TikZ and compiled to accessible SVG when visual
inspection is itself the retrieval target. Chapter 1 deliberately has no figure:
its symbolic transformations remain legible at phone width, and a drawing would
not change the grading decision. The authentic table on Problem 18 is live text,
which is more accessible and easier to inspect than a rasterized or SVG table.

## Planned-versus-actual reconciliation

| Chapter | Planned card types | Actual card types | Planned problems | Actual problems | Planned figures | Actual figures | Reconciliation |
|---|---|---|---|---|---|---|---|
| 1 | 15 basic, 0 cloze, 3 problem | 15 basic, 0 cloze, 3 problem | Analyzed bridge plus scaffolded, independent contextual, and tabular transfer | Front 9 analyzed bridge; Problems 11, 16, and 18 provide the planned progression | 0 included; three candidates intentionally omitted in the design ledger | 0 | Exact match; omissions are explained and no visual retrieval target is lost. |
| 2–12 | Planned in the chapter design ledger | 0 | Planned only | 0 | Opportunities inventoried, include/omit decisions deferred until authoring | 0 | Expected under the pilot gate; no later chapter card or asset was authored. |

## Sources and accuracy

The deck-local source register is in `README.md`. Pilot computations were checked
by direct substitution and arithmetic against the resolved prerequisite closure.

## Validation gate

Before handoff:

1. Run `flashcards deck stabilize . --check`.
2. Run `flashcards deck validate .`.
3. Confirm no later chapter or figure was created.
4. Reconcile planned versus actual card types, problems, and figures.
5. Complete `.flashcards/audits/pilot-cold-start.md` front by front.
6. Run `git diff --check` and review the complete diff.
