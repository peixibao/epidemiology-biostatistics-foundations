# Course Protocol
**Foundations of Epidemiology & Biostatistics**  
**Version:** 1.1 · **Maintained in:** this repository

## Mission and audience
Build a coherent, scientifically rigorous foundation in epidemiology and biostatistics for undergraduates entering **clinical and public health research**. Outcomes include being able to formulate answerable questions, choose and critique designs, understand data and models, interpret uncertainty, recognize bias, and communicate findings.

**Instruction:** academic English first, with Chinese explanations of difficult terms. Establish the transferable theory before introducing illustrative studies. Examples must vary across clinical medicine and population/public health; no one research project determines the syllabus.

## Non-negotiable teaching standards
1. **Curriculum coherence.** Use the sequence and prerequisite map in [SYLLABUS.md](SYLLABUS.md). Do not silently move to another topic because a side question was asked.
2. **Small blocks, complete conceptual scope.** State the scope of each block. Define *all essential branches* of any classification taught within that scope. Mark illustrative or non-exhaustive lists explicitly.
3. **Definitions → relationships → reasoning → research implications.** Introduce technical terms accurately; distinguish definitions, conventions, heuristics, assumptions, and contested claims.
4. **Appropriate depth.** Emphasize independent research decisions and correct interpretation. Mathematical derivations should serve understanding, not crowd out it.
5. **Examples support principles.** Use diverse epidemiologic, clinical, and public health examples. Personal T2DM/OSA projects are optional examples only; avoid dependence on them.
6. **Scientific quality.** Check the accuracy of methods, units, inference, bias, and causal wording. Distinguish statistical association, prediction, and causation.
7. **Student-paced advancement.** One active lesson at a time; permit interruption and questions. Explanation delivered ≠ understanding confirmed ≠ lesson completed.
8. **Do not invent mastery or outcomes.** Completion needs explicit student confirmation and a completeness review.

## Standard lesson lifecycle
- **Plan:** learning objectives; scope; necessary prerequisites; conceptual map; full inventory of essential subtopics.
- **Teach:** one coherent block; English-first explanation; logic, distinctions, assumptions, varied examples.
- **Pause:** address questions; avoid advancing automatically.
- **Checkpoint:** update [COURSE_STATE.md](COURSE_STATE.md) with last taught block, status, questions/corrections, and next planned block.
- **Complete:** when all blocks/objectives have been covered and reviewed with the learner, add an audited lesson completion entry and update the README.
- **Teach-back:** the learner may write a Vlog script; review scientific accuracy before public educational use.

## GitHub synchronization policy
**Source of truth:** repository files on the default branch, especially `COURSE_STATE.md` and the relevant lesson note.

### Every substantive teaching block
1. Check the latest state/file to avoid overwriting an external change.
2. Update `COURSE_STATE.md`, and update the corresponding lesson working note as needed.
3. Commit changes to GitHub; verify by reading back the file or checking the returned commit and content.
4. Report the exact checkpoint and whether remote synchronization succeeded. Never claim a push if it failed.

### Every finished lesson
1. Audit completeness and methodological accuracy against the scope.
2. Write/update the completed lesson under `lessons/`.
3. Update `COURSE_STATE.md`, `README.md`, and `CHANGELOG.md`.
4. Record Vlog draft/review status separately. Drafting a Vlog is not a prerequisite for closing the learning lesson unless the learner elects that workflow.

### New-conversation recovery
Read `COURSE_PROTOCOL.md`, `COURSE_STATE.md`, `SYLLABUS.md`, and the active lesson file **before continuing**. If a mismatch exists, ask which revision is authoritative rather than silently overwriting work. A pasted GitHub link helps locate the repository; repository access must actually be available in the current chat.

### Limits
GitHub changes require a live conversation with an authorized connected GitHub tool; this setup does **not** run autonomously in the background. A failed or unavailable connector requires a transparent status report and later reconciliation. Git history tracks revisions; it does not itself validate scientific correctness.

## Completion quality gate
A lesson cannot be marked **Completed** without reviewing:
- Scope and objectives; all necessary classification branches.
- Prerequisite chain and conceptual distinctions.
- Definitions, model/design assumptions, and exceptions.
- Correct generalization/causation/uncertainty statements.
- Examples that match—not substitute for—the theory.
- Open questions, needed corrections, and deferred extensions.

## Publication guardrails
This repository is **public**. Do not upload personally identifying or patient-level data, unreleased manuscripts, private feedback, proprietary course slides, unlicensed figures, or confidential research documents. Keep educational examples anonymized/synthetic as needed; cite external sources when used. Where content is provisional, label it clearly. No license has been chosen yet; permission to reuse should not be presumed.

## State vocabulary
- `Not started`
- `In progress`
- `Taught — pending learner review`
- `Completed — audited and confirmed`
- `Needs correction`

**Rule:** a finished response is not a finished lesson.
