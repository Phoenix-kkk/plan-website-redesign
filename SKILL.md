---
name: plan-website-redesign
description: "Inspect a website URL, audit report, codebase, screenshots, analytics summary, content document, or stakeholder notes and produce two separate deliverables in strict order: first a concise website problem report, then an implementation-ready website redesign PRD. The PRD includes information architecture, exact page-level TDK and Schema, page goals, module-by-module publishable copy, CTAs, components, visual and SEO requirements, global systems, technical release requirements, and acceptance criteria. Use when asked to audit and redesign, restructure, replatform, expand, or rewrite a marketing website. Do not use for product-feature PRDs or direct code implementation unless the primary task is website diagnosis and redesign planning."
---

# Plan Website Redesign

Produce two distinct artifacts in strict sequence:

1. **Website problem report**: establish what is true, what is wrong, why it matters, and what remains unknown.
2. **Website redesign PRD**: define what to change, how pages and components should work, how delivery is phased, and how completion is verified.

Never blend diagnosis and solution design into one document.

## Operating principles

- Inspect before prescribing.
- Preserve a traceable chain from source to evidence to issue to requirement to acceptance test.
- Label material statements as `Observed`, `Provided`, `Inferred`, or `Assumed` when status could be misunderstood.
- Never invent analytics, rankings, research, customer behavior, competitor behavior, or technical findings.
- Separate blocking failures from growth opportunities.
- Follow the user's language. Keep URLs, schema types, and technical identifiers unchanged.
- Produce reports and plans; do not modify the website unless the user separately requests implementation.

## Choose the working mode

1. **Existing-site diagnosis**: Inspect an accessible URL, screenshots, codebase, or exported data before reporting problems.
2. **Audit normalization**: Convert an existing audit or issue list into the standard problem report before planning. Do not skip the first artifact.
3. **Greenfield assessment**: Diagnose gaps in the proposed positioning, structure, proof, conversion model, and requirements. Mark unavailable current-state evidence as assumptions.
4. **Partial redesign**: Limit both artifacts to the requested page, funnel, locale, template, or subsystem. Do not expand scope silently.

## Two-stage delivery contract

- Default to producing both artifacts during one task, but finish and quality-check the problem report before starting the redesign plan.
- Save them as separate files or clearly separate attachments. Prefer names such as `{site}-website-problem-report-{date}.md` and `{site}-web-redesign-prd-{date}.md`.
- If the user asks to review, approve, or confirm findings first, deliver only the problem report and pause. Generate the plan after approval.
- If the user provides a prior audit, preserve its evidence and attribution while assigning stable issue IDs.
- Never revise a problem statement merely to justify a preferred redesign. Record changed evidence explicitly.

## Shared discovery workflow

### 1. Establish the decision frame

Read [references/discovery-framework.md](references/discovery-framework.md). Extract business goals, audiences, conversions, supplied evidence, constraints, and success signals. Ask only for missing information that would materially change the assessment or scope. Otherwise proceed with explicit assumptions.

### 2. Inspect and build an evidence ledger

Inspect accessible pages, files, rendered states, metadata, navigation, forms, and technical endpoints relevant to scope. Verify live or time-sensitive claims with current authoritative sources. Record each source, observation, consequence, confidence, and affected scope. Reconcile conflicts rather than choosing the most convenient source.

Use the evidence ledger as internal working notes. Do not include the ledger, evidence IDs, confidence fields, source appendix, or repeated attribution in the default problem report unless the user explicitly requests an audit trail.

When SEO, GEO, AI visibility, indexing, metadata, structured data, or content discovery is in scope, use the companion `$seo-geo:seo-geo` skill during this inspection if it is available. Apply its audit workflow to:

- crawlability, indexability, canonical, robots, sitemap, status codes, mobile rendering, and measurable performance evidence;
- unique Title, Description, H1/heading structure, internal links, image ALT, and page-intent fit;
- main-entity Schema accuracy and consistency with visible content;
- access for major search and AI crawlers, without assuming that crawler access guarantees inclusion or citation;
- answer-first structure, verifiable claims, cited sources, first-party expertise, content freshness, and topic-cluster/internal-link support.

Do not paste the companion skill's full checklist into the report. Merge related observations into a small number of root issues, record only verified findings, and treat platform-specific citation or ranking claims as experimental unless supported by current primary evidence. If the companion skill is unavailable, continue with [references/seo-geo-requirements.md](references/seo-geo-requirements.md).

## Stage 1: Website problem report

### 3. Separate baseline strengths from problems

Record what already works so the redesign does not destroy it. Treat a condition as a problem only when evidence connects it to a user, business, compliance, discovery, accessibility, performance, operational, or migration consequence.

### 4. Assign stable issue IDs and priorities

Assign `ISSUE-001`, `ISSUE-002`, and so on. Do not renumber IDs after they have been shared; append new IDs instead.

- `P0`: blocks crawling, use, conversion, compliance, migration safety, or launch.
- `P1`: materially weakens discovery, comprehension, trust, accessibility, or conversion.
- `P2`: improves quality, efficiency, resilience, or future growth without blocking launch.

Present all detailed issues in one table with exactly three columns: `Priority | Problem | Impact`. Put the stable `ISSUE-*` ID at the start of the problem cell so the redesign plan can still trace requirements back to the diagnosis. Write the problem as a clear current-state condition and the impact as the concrete user, business, compliance, discovery, or operational consequence. Do not add a separate issue summary or repeat each issue as a long field list. Keep owners, required outcomes, and verification methods for the redesign plan. Do not inflate priority merely because an item is strategically important.

### 5. Deliver and check the problem report

Copy [assets/website-problem-report.md](assets/website-problem-report.md). Remove irrelevant sections instead of filling them with boilerplate.

Before moving to Stage 2, verify that:

- each issue is supported by inspected or supplied information in the internal working notes;
- facts, inferences, and assumptions are distinguished during analysis even though the default report does not expose those labels;
- strengths, limitations, and unknowns are visible;
- duplicate symptoms are merged under their root issue where justified;
- priorities reflect consequences rather than effort or preference;
- the report contains one three-column issue table and no separate evidence ledger, issue summary, confidence column, owner column, or source appendix;
- the report contains no proposed sitemap, page-module specification, visual concept, or delivery roadmap;
- the executive diagnosis can be understood in under one minute.

If this gate fails, revise the problem report before planning.

## Stage 2: Website redesign plan

### 6. Convert issues into requirements

Use the completed problem report as the planning source of truth. At the start of the PRD, add one concise issue-coverage table that maps every requirement decision to one or more `ISSUE-*` IDs or to an explicit `GOAL-*` supplied by the user. Do not create a separate `REQ-*` layer unless the user explicitly asks for requirements IDs.

Every P0 and P1 issue must be `Planned`, `Deferred`, or `Out of scope` with a reason and owner. Do not silently omit an issue. Avoid requirements with no issue, goal, regulatory, or platform source.

### 7. Design the information architecture

Define the smallest sitemap that covers distinct user intents and business needs without creating thin or duplicative pages. Map every proposed page to one primary audience, one primary intent, one conversion action, and required proof. Record retained, redirected, removed, and unresolved URLs when migration is in scope.

### 8. Specify pages and shared systems

Read [references/page-requirements.md](references/page-requirements.md) and [references/detailed-content-architecture.md](references/detailed-content-architecture.md). Define purpose, audience, intent, exact TDK drafts, H1/H2/H3 hierarchy, ordered modules, module-level copy, proof, CTA, media and ALT text, internal links, structured data, analytics events, responsive behavior, states, dependencies, and acceptance criteria.

For every core page, write enough concrete content that design can create wireframes and content can edit a first draft without inventing the page structure. Do not stop at module names such as `Hero`, `Features`, or `Cases`. Supply the recommended headline, supporting copy, labels, CTA text, proof needs, media direction, and discovery requirements for each module.

When facts, numbers, legal claims, testimonials, pricing, certifications, or product capabilities lack evidence, write `Draft pending evidence` with the needed source and owner. Never fill the gap with plausible marketing copy. Keep design direction outcome-based unless supplied brand rules or evidence support exact aesthetics.

### 9. Add discovery requirements

Read [references/seo-geo-requirements.md](references/seo-geo-requirements.md) when SEO, GEO, AI visibility, content discovery, structured data, or migration is in scope. Distinguish established requirements from experimental recommendations. Never promise rankings, traffic, citations, or AI mentions.

### 10. Phase delivery

Order work by dependency:

1. blocking infrastructure, compliance, and migration decisions;
2. core positioning, navigation, conversion pages, and reusable templates;
3. supporting content, proof assets, and discovery enhancements;
4. experiments and ongoing measurement.

Use exit criteria rather than arbitrary dates unless the user supplies dates and capacity.

### 11. Define acceptance criteria

Read [references/acceptance-criteria.md](references/acceptance-criteria.md). Make each criterion observable and assign a verification method. Cover content, behavior, responsive layouts, accessibility, SEO, analytics, performance, redirects, and error states as applicable.

### 12. Deliver and check the redesign plan

Copy [assets/website-redesign-plan.md](assets/website-redesign-plan.md). Adapt depth to scope.

Use the PRD-style plan structure below unless the user requests another format:

0. **Document use and global content rules**: writing, claims, legal placeholders, CTA conventions, and implementation conventions.
1. **Recommended information architecture and navigation**: sitemap, navigation, page-map table, and migration decisions.
2. **Page delivery specifications**: one section per core page or reusable template, in sitemap order. Each page contains page goal, exact TDK and Schema, ordered modules, and page-level visual/SEO rules.
3. **Global components**: Header, footer, breadcrumbs, forms, consent, empty/error states, and reusable conversion/trust components.
4. **Technical, SEO/GEO, analytics, migration, and release requirements**.
5. **Phases, dependencies, and acceptance criteria**.

Every indexable page must have its own exact Title, Description, keywords/entities, H1, canonical/indexing rule, and Schema direction. For every core module, write: **title**, **subtitle** (when useful), **body copy**, **component content** (card count and exact card labels/fields/order), **CTA**, **visual requirements**, and **SEO requirements**. Do not replace these with a module name, a generic instruction, or a `Source` / `来源` field.

Use the page order visitors experience: first page objective and TDK, then modules in final reading order, then visual/SEO requirements. Keep proof, legal dependencies, responsive behavior, analytics, and acceptance inside the relevant module or page specification unless a cross-site rule is clearer.

Before delivery, verify that:

- every P0/P1 issue is addressed by the IA, page-map, page specification, global component, or release requirement;
- stable `ISSUE-*` IDs remain traceable where needed without requiring a separate audit chapter;
- no issue is copied into the plan without an actionable page or component decision;
- every sitemap page has a distinct job, primary intent, and primary CTA;
- every indexable page has an exact Title, Description, keyword set, H1, canonical rule, indexing rule, and schema direction;
- every core page has page goal, ordered H1/H2/H3 outline, and module-by-module content specification;
- every module includes title, subtitle where useful, body copy, component content, CTA, visual requirements, and SEO requirements;
- page requirements are implementation-ready without prescribing unsupported aesthetics;
- the executive decision communicates the recommended direction in under one minute.
