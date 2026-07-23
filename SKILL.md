---
name: journal-copyeditor-docx
description: Comprehensive academic journal copyediting and manuscript review for Microsoft Word (.docx) files across disciplines and target journals. Use when the user asks to proofread, line-edit, polish, revise, redline, or prepare a manuscript with tracked changes, editor comments, a clean accepted copy, PDF review copy, and a structured editorial report. The skill preserves existing formatting, revisions, comments, citation fields, equations, tables, figures, footnotes, and document structure while auditing language, argument logic, construct terminology, methods, statistical reporting, citation-reference correspondence, causal claims, reviewer risks, and document integrity. It supports target-journal profiles when supplied but does not assume any specific journal.
---

# Journal Copyeditor DOCX

Conduct publication-oriented copyediting and consistency review of academic manuscripts in `.docx` format. Apply the core `docx` skill for document editing, tracked changes, comments, rendering, and integrity verification.

## Default Scope

For a request described as **comprehensive**, **submission-ready**, or **journal copyediting**, perform all of the following unless the user narrows the task:

1. Language and readability editing.
2. Theory, argument, and claim-boundary review.
3. Construct and terminology consistency review.
4. Methodological and statistical reporting audit.
5. Citation and reference correspondence audit.
6. Target-journal or journal-neutral submission-suitability review.
7. DOCX structure, formatting, field, revision, and rendering validation.

## Intake Profile

Determine from the manuscript and request:

- manuscript file and supplementary files;
- target journal, discipline, and article type, if specified;
- English variety and citation style, if specified;
- editing intensity: light, medium, heavy, or comprehensive;
- required reviewer name and initials;
- required deliverables.

If the target journal is not specified, use a **journal-neutral, high-quality academic profile** appropriate to the discipline. Do not infer or hard-code a particular journal. If a journal is specified and current author guidance is needed, verify only against the journal's official current instructions and state the profile used in the report.

Default reviewer identity: `Copy Editor` / `CE`.

## Non-Negotiable Editorial Contract

- Preserve the source file. Work only on copies.
- Preserve all existing tracked revisions and comments in the tracked deliverable.
- Preserve citation-manager fields, cross-references, equations, hyperlinks, footnotes/endnotes, section breaks, tables, figures, captions, numbering, and styles.
- Do not fabricate, infer, or repair empirical facts without evidence from the supplied manuscript or verified source files.
- Do not invent theories, constructs, mechanisms, hypotheses, citations, sample details, analyses, coefficients, p-values, confidence intervals, or reference metadata.
- Do not strengthen novelty, causality, generalizability, or managerial implications beyond what the design and evidence support.
- Use the same term for the same construct. Do not rotate technical terms for stylistic variety.
- Make the smallest safe tracked edit. Avoid paragraph-wide delete-and-reinsert revisions for ordinary copyediting.
- Make substantive meaning changes only when clearly supported. Otherwise add a concise Word comment and report item.
- Never silently reconcile conflicting values. Flag them and identify every affected location.
- Do not update citation fields, reference-manager fields, numbering fields, or cross-references unless explicitly requested and verified.

## Edit, Comment, or Report Decision Rule

**Edit directly with tracked changes** when the correction is local, unambiguous, and meaning-preserving, including grammar, syntax, punctuation, concision, transition, terminology normalization, and defensible hedging.

**Add a Word comment** when resolution requires author knowledge, new evidence, reanalysis, construct choice, theoretical repositioning, methodological justification, or interpretation of conflicting values.

**Add a report item** when the issue is global, repeated, submission-level, or difficult to anchor at one location. Use both a comment and a report item for serious issues.

Do not use comments for routine grammar edits.

## Comprehensive Audit Domains

### 1. Language and Readability

- Correct grammar, punctuation, spelling, agreement, syntax, articles, prepositions, parallelism, and word choice.
- Replace translationese and Chinese-influenced sentence structure with natural academic English.
- Reduce redundancy, nominalization, vague pronouns, unnecessary passive voice, inflated wording, and AI-like filler.
- Improve paragraph unity, topic sentences, transitions, and section flow.
- Preserve technical nuance and the authors' intended meaning.

Open `references/language-and-argument.md` for detailed rules.

### 2. Theory and Argument Quality

- Check that each section performs its proper function.
- Trace the logic from research problem to gap, research question, theory, hypotheses, findings, contributions, implications, limitations, and conclusion.
- Test whether each claim has a stated basis, logical bridge, boundary, and evidentiary support.
- Flag unsupported novelty claims, missing comparators, circular logic, construct substitution, post hoc theorizing, and implications that exceed the findings.
- Do not introduce a new theory, construct, mechanism, or citation unless clearly marked as an editorial recommendation.

Open `references/theory-construct-review.md`.

### 3. Construct and Terminology Consistency

Create an internal construct dictionary covering:

- canonical construct name and abbreviation;
- conceptual definition and defining attributes;
- conceptual domain, referent, unit, and level of analysis;
- temporal status and dimensional structure;
- role in the theoretical and empirical model;
- operationalization, manipulation, proxy, or scale;
- item labels, subdimensions, and scoring direction;
- expected relationship with other variables;
- neighboring constructs that require differentiation;
- sections, tables, figures, and appendices where the construct appears.

Apply a general construct-differentiation check rather than relying on fixed construct pairs. For every focal and neighboring construct, compare definition, conceptual domain, referent, level, temporal scope, dimensionality, nomological role, and operationalization. Verify that:

- one construct is not given multiple labels without justification;
- one label is not used for substantively different constructs;
- distinct constructs have an explicit conceptual boundary rather than merely different names;
- the measure or manipulation represents the stated construct rather than an adjacent attribute;
- proxies, indicators, dimensions, mechanisms, outcomes, and manipulation checks are not presented as interchangeable;
- construct meaning remains stable across theory, hypotheses, methods, results, discussion, tables, figures, and appendices.

Flag duplicated or mismatched items, undeveloped or unmeasured constructs, silent changes in level or referent, and distinctions that require author judgment or additional validity evidence.

### 4. Methods and Statistical Reporting

Check across text, tables, figures, notes, appendices, and supplementary materials:

- study numbering, sample sizes, exclusions, cell sizes, demographics, and conditions;
- variable names, coding, reference categories, scale anchors, item wording, reliability, validity, and manipulation checks;
- coefficients, standard errors, test statistics, degrees of freedom, p-values, confidence intervals, effect sizes, odds ratios, and directions;
- model names, bootstrap samples, conditional effects, indirect-effect scale, covariates, robustness checks, and stated conclusions;
- causal language, mediation language, and generalization relative to design.

Do not alter a numerical result merely because it appears wrong. Flag it, report the locations, and request verification.

Open `references/methods-statistics-review.md`.

### 5. Citations and References

- Match in-text citations to reference entries and identify uncited references.
- Check names, years, suffixes, citation order, duplicate records, incomplete metadata, DOI/URL formatting, and inconsistent journal-title styling.
- Preserve reference-manager fields. Do not convert fields to plain text unless explicitly requested.
- Do not fabricate or replace references. When external verification is requested, use authoritative bibliographic sources and clearly distinguish verified corrections from editorial suspicions.

Open `references/citation-reference-review.md`.

### 6. Submission Suitability and Reviewer Risk

If a target journal is supplied, assess fit using its verified profile. Otherwise assess against general standards for a strong peer-reviewed article in the discipline.

Review for:

- unclear marketing, management, social-science, or discipline-specific problem relevance;
- incremental contribution or excessive overlap with adjacent research;
- weak mechanism, missing boundary conditions, construct overlap, and overclaimed novelty;
- identification weaknesses, manipulation confounds, common-method concerns, selective controls, or outcome-validity problems;
- weak connection among abstract, introduction, results, discussion, and conclusion;
- practical implications unsupported by the evidence;
- missing ethics, consent, transparency, data availability, funding, conflict, or AI-use statements when applicable.

Assign risk severity using `references/reviewer-risk-rubric.md`.

### 7. Document Integrity

Audit before and after editing:

- existing revisions and comments;
- field codes and hyperlinks;
- equations and symbols;
- tables, figures, captions, and image relationships;
- footnotes/endnotes;
- headings, numbering, page/section breaks, headers/footers, and styles;
- unexpected CJK characters, mojibake, replacement glyphs, missing text, formatting drift, and corrupted package parts.

Open `references/tracked-changes-integrity.md`.

## Workflow

### Phase 1: Baseline Inspection

1. Copy the source into a dedicated work directory.
2. Confirm that the DOCX opens and is a valid ZIP package.
3. Run `scripts/audit_docx.py` on the source.
4. Run `scripts/audit_citations.py` and `scripts/audit_statistics.py` when relevant.
5. Record source counts for paragraphs, tables, figures, fields, comments, revisions, sections, footnotes, and hyperlinks.
6. Render the source and inspect representative high-risk pages before editing.

### Phase 2: Editorial Map

1. Identify article structure and study structure.
2. Build the construct dictionary and study-consistency matrix.
3. Identify global terminology decisions before local editing.
4. Separate copyediting issues from author-decision issues.
5. Establish a target-journal profile only when one is specified.

### Phase 3: Tracked Copyedit

Preferred implementation order:

1. Microsoft Word automation with Track Changes, when available.
2. A reliable office automation path that preserves revisions and fields.
3. Targeted OOXML redlines using the core `docx` skill, followed by strict structural and visual validation.

Edit paragraph by paragraph and table by table. Preserve local run formatting. Use verified global replacement only for low-risk, exact terminology normalization.

### Phase 4: Comments and Review Report

Add comments for unresolved author decisions. Comments should:

- identify the exact issue;
- explain why it matters;
- specify the action or evidence needed;
- avoid rewriting the manuscript in the comment.

Prepare a separate review report using `references/report-template.md`. For comprehensive tasks, the report must cover:

- major language issues;
- construct and terminology inconsistencies;
- theoretical and logical weaknesses;
- methodological and statistical inconsistencies;
- citation and reference problems;
- potential reviewer concerns;
- issues requiring clarification, reanalysis, or substantive revision;
- journal profile and style assumptions used;
- integrity and validation summary.

### Phase 5: Clean Derivative and PDF

Create the clean DOCX from the tracked copy, not from the source:

- accept all revisions in the clean derivative;
- remove comments from the clean derivative unless the user requests otherwise;
- preserve all substantive document structures and fields;
- export the clean version to PDF.

Never accept revisions or remove comments in the tracked deliverable.

### Phase 6: Validation and Visual QA

1. Reopen all DOCX deliverables.
2. Run `scripts/audit_docx.py` on tracked and clean copies.
3. Confirm source structures were retained unless intentionally changed.
4. Confirm tracked insertion/deletion and comment counts are plausible.
5. Confirm the clean copy contains no unresolved revision markup.
6. Render the tracked and clean DOCX files with the core `docx` renderer.
7. Inspect every page at normal reading scale.
8. Check title/abstract, tables, figures, equations, references, appendices, comment locations, and edited high-density pages at higher zoom.
9. Correct and repeat until all gates pass.

## Default Deliverables

For a comprehensive manuscript request, provide:

1. `manuscript_tracked_changes.docx`
2. `manuscript_clean.docx`
3. `manuscript_clean.pdf`
4. `copyediting_manuscript_review_report.docx`

Optionally provide machine-readable audit files in a separate `audit/` folder, but do not clutter the main delivery unless requested.

For limited proofreading or a user-specified output, deliver only the requested files.

## Final Quality Gates

Do not deliver until all applicable gates pass:

- source file remains unchanged;
- tracked edits are local and reviewable;
- existing revisions/comments are preserved in tracked output;
- clean output has revisions accepted and review comments removed as intended;
- figures, tables, fields, equations, footnotes, and hyperlinks remain intact;
- no unexpected characters, mojibake, missing glyphs, clipping, overlap, or broken page layout;
- no unsupported factual, theoretical, methodological, or bibliographic additions;
- all serious unresolved issues appear in comments or the report;
- every delivered DOCX has been rendered and visually inspected page by page.

## Stop Conditions

Stop and repair before delivery if any of the following occurs:

- document corruption or missing package relationships;
- lost fields, citations, figures, tables, equations, footnotes, comments, or revisions;
- whole-paragraph redline blocks caused by routine language editing;
- formatting drift in inserted text;
- unexplained numerical changes;
- unexpected CJK or mojibake in an English manuscript;
- incomplete clean acceptance or residual comments in the clean deliverable;
- inability to render and visually verify the final document.

If a limitation cannot be resolved, disclose it precisely and do not describe the output as fully validated.

## Bundled Audit Scripts

```bash
python scripts/audit_docx.py manuscript.docx --json audit_docx.json --markdown audit_docx.md
python scripts/audit_citations.py manuscript.docx --json citation_audit.json --markdown citation_audit.md
python scripts/audit_statistics.py manuscript.docx --json statistics_audit.json --markdown statistics_audit.md
```

These scripts are heuristic evidence-gathering tools. Verify each flagged issue in context before editing or commenting.
