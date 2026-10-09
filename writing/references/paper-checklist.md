**Scientific Paper Writing Checklist**

*Hasenauer*

**Ideal Manuscript Architecture Summary**

A well-structured paper should read as:

**Abstract**

“Here is the problem, what we did, what we found, and why it matters.”

**Introduction**

“Here is the field → Here is what is known → Here is what is missing → Here is what we do.”

**Methods**

“Here is precisely what we define and compute.”

**Results**

“Here is what we observe under these controlled analyses.”

**Discussion**

“Here is what this means, how it relates, and what its limits are.”

Alternatively, the Methods section can come after the results

**1. Global Writing Principles (Apply to Entire Manuscript)**

**1.1. Structural Coherence**

Logical Flow

- Does each section fulfill its clear rhetorical role?

- Does each paragraph have a single identifiable function?

- Is the manuscript free of structural jumps or abrupt topic changes?

- Are transitions explicit and meaningful (not merely connective phrases)?

Progressive Narrowing

- Does the manuscript move from broad context → specific gap → concrete contribution?

- Is the problem motivated before being solved?

**1.2. Precision and Tone**

Declarative Style

- Do sentences state clearly what is done?

  - “We define…”

  - “We consider…”

  - “We derive…”

- Are weak intention phrases avoided?

  - Avoid: “We aim to…”, “We try to…”, “We attempt to…”

Controlled Novelty Language

- Are novelty claims tied to specific limitations?

- Are exaggerated terms avoided?

  - Avoid: “groundbreaking”, “revolutionary”, “unprecedented”, “first ever”

- Is interpretation proportionate to evidence?

Operationalization

- Are claims measurable or concrete?

- Are methods named?

- Are model types, dataset sizes, scales, or performance metrics specified where relevant?

**1.3. Literature Handling**

Synthesis (Not Listing)

- Are cited works grouped into trends, approaches, or methodological families?

- Is the literature used to build an argument?

- Is the limitation emerging naturally from the synthesis?

Gap Discipline

- Is the gap stated precisely?

- Is it supported by preceding literature discussion?

- Is it problem-specific rather than generic?

**1.4. Section Separation Discipline**

- Abstract = structured summary

- Introduction = problem + gap + contribution

- Results = findings (+ some procedure)

- Discussion = interpretation + implications

- Methods = definitions + procedures

No Section Leakage

- No motivation in Methods

- No detailed results in Discussion opening

- No speculation in Results

- No new data in Discussion conclusion

**  
**

**2. Abstract Checklist**

**2.1. Structure and Order**

Does the abstract follow this sequence?

- Broad context (1–2 sentences)

- More specific background

- Clear, operational problem statement

- Single main result sentence (“Here, we…”)

- Interpretation or contrast to prior work

- Broader implication (optional)

**2.2. Main Result Sentence**

Exactly one clear “Here, we …” sentence

- Is the action explicit?

- Is the result concrete?

- Does it name the method or framework?

- Is the outcome specific (not vague)?

Avoid:

- “We explore whether…”

- “Our results suggest…”

Prefer:

- “Here, we develop X and demonstrate Y under Z conditions.”

**2.3. Clarity and Accessibility**

- No jargon in opening sentences

- Acronyms defined

- No technical detail creep

- No citation-style enumeration

- No methods paragraph hidden inside abstract

**2.4. Interpretation Control**

- Interpretation separated from background

- No overclaiming

- No rhetorical intensifiers

**  
**

**3. Introduction Checklist**

**3.1. Paragraph Structure (Progressive Narrowing)**

Paragraph 1

- Broad field context

- Accessible framing

Paragraph 2

- More specific subfield

- Conceptual focus sharpened

Paragraph 3–4

- Synthesized literature discussion

- Trends or patterns identified

- Not paper-by-paper listing

Limitation Paragraph

- Concrete limitation identified

- Limitation directly linked to literature

- Consequence explained (“why this matters”)

Contribution Paragraph (Final Paragraph)

- Explicit reference to the problem

- “Here, we …” sentence

- Method/framework clearly named

- Main capability/result stated

- No exaggerated novelty language

**3.2. Literature Quality Control**

- No citation dumping

  - No extreme enrichment of publications from our group

  - If a result is well established, either use the first paper which reports this or a review

- No early gap statement before synthesis

- No vague limitation (“However, challenges remain.”)

- Limitation logically derived

**3.3. Contribution Discipline**

- Contribution directly addresses stated limitation

- No floating novelty claims or generic claims of superiority

- No missing scale/model/dataset details

**4. Results Checklist**

**4.1. Structural Strategy**

Have you chosen the correct structural mode?

- Method-centered

- Application-centered

- Hybrid

Is this choice consistent throughout?

**4.2. Subsection Template (Three Building Blocks)**

Each Results subsection should follow:

**1. Question/Setup**

- What is being tested/analyzed?

- What is the formal setup?

- What is the comparison baseline? (This can potentially also be mention in the findings part.)

**2. Findings**

- Findings described in text (not only figures)

- Quantitative or formal detail included

- Figure explained, not referenced blindly

Avoid:

- “As shown in Fig. 2.”

- Caption retelling

- Repeating abstract

**3. Mini-Conclusion**

- What does this show?

- How does it connect to next subsection?

**4.3. Results Writing Discipline**

- No interpretation beyond data

- No speculation

- No causal claims without evidence

- No rhetorical language (“remarkably”, “interestingly”)

- No figure-dependent logic

**4. Headline Discipline**

Subsection titles reflect conclusions, not just questions

Example:

- Weak: “Evaluation on Dataset A”

- Strong: “Method X Reduces Estimation Bias on Dataset A”

**5. Discussion Checklist**

**5.1. Opening Paragraph**

Must include:

- Restatement of central problem

- Restatement of key findings (high-level only)

- Synthesis, not retelling

Avoid:

- Figure references

- Detailed numeric results

- Paragraph-by-paragraph replay

**5.2. Middle Paragraphs**

Each paragraph should contain:

- Interpretation of findings

- Relation to literature

- Scope clarification

Furthermore, it can include:

- Implications / potential

- Ideas to extend the work

Questions to ask:

- What does this finding mean mechanistically or conceptually?

- Where does it generalize?

- Where does it not?

**5.3. Limitation Discipline**

- Limitations explicitly acknowledged

- Scope boundaries stated

- No defensive tone

- No undermining of core contribution

**5.4. Final Paragraph**

Must include:

- Broader implication

- Generalization beyond specific case

- Concrete future direction (if included)

Avoid:

- “More research is needed.”

- New data introduction

- Novelty marketing

**6. Methods Checklist**

**6.1. Structural Clarity**

Each subsection begins with:

- Declarative scope statement

- Immediate introduction of defined object (model/equations/algorithm)

Example:

- “We define a nonlinear ODE model…”

- “We consider a Bayesian hierarchical model…”

**6.2. Definition Discipline**

- All variables defined before use

- Notation consistent

- Objective function explicitly written

- Inference target clearly stated

**6.3. Procedural Transparency**

- Algorithm described clearly

- Optimization/inference steps specified

- Software/library mentioned where relevant

- Reproducibility ensured

<!-- -->

- No narrative motivation, e.g. “We try to improve…”

**6.4. Layer Separation**

Check that these are separated:

- Conceptual model

- Statistical model

- Algorithm

- Evaluation procedure

No mixing within same paragraph.

**6.5. Language Discipline**

- No performance claims (“robust”, “efficient”) unless defined

- No rhetorical intensifiers

- No implicit results statements

**  
**

**7. Funding, Acknowledgement and Contribution checklist**

Funding

- All funding sources mentioned -\> ask Christina

- Collaboration partners asked about their funding sources

Contributions

- Contributions assigned to all authors (all have to be listed)

- Contribution statement specific enough for use in cumulative thesis

**  
**

**8. Final Pre-Submission Diagnostic Pass**

**A. Logical Audit**

- Can the limitation be traced directly to literature?

- Can the contribution be traced directly to the limitation?

- Can each Results subsection be justified as answering a specific question?

- Does the Discussion interpret only what was shown?

**B. Claim Audit**

For every strong claim:

- Is it supported by data?

- Is the scope limited appropriately?

- Is wording proportional?

**C. Red Flag Scan**

Remove if present:

- “remarkable”, “groundbreaking”

- Citation lists without synthesis

- Motivation in Methods

- Speculation in Results

- Repetition across sections
