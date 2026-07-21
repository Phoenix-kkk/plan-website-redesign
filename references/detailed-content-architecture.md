# Detailed content architecture

Use this reference when writing the redesign plan. Match the level of detail to the page's business importance, but never leave a core page at the level of a module inventory.

## Contents

- [Required page layers](#required-page-layers)
- [Content fidelity levels](#content-fidelity-levels)
- [TDK specification](#tdk-specification)
- [Heading outline](#heading-outline)
- [Module specification](#module-specification)
- [Common page patterns](#common-page-patterns)
- [Shared modules](#shared-modules)
- [Evidence safeguards](#evidence-safeguards)

## Required page layers

Write each core page in this order:

1. **Page goal**: route, job, audience, intent, and primary conversion.
2. **TDK and Schema**: exact Title, Description, keyword/entity set, H1, canonical, indexing, Schema, and social metadata.
3. **Module sequence**: the complete page from first-screen answer through final CTA, using ordered H1/H2/H3 headings.
4. **Module specifications**: exact draft content, component fields, CTA, visual direction, responsive behavior, and discovery requirements.
5. **Page-level visual / SEO rules**: only cross-module rules such as author/date, analytics, legal, performance, or validation.

## Content fidelity levels

Use one of these statuses for every material content block:

- `Ready`: supplied or verified content can be published after normal editing.
- `Draft`: recommended first-draft language based on verified positioning and evidence.
- `Draft pending evidence`: direction is clear, but a number, claim, quote, certification, feature, price, or legal statement needs evidence.
- `Owner decision`: content depends on a business choice that cannot be inferred safely.

Never conceal a missing fact with polished-sounding copy.

## TDK specification

For each indexable page, provide:

```text
Title: [Exact draft]
Description: [Exact draft]
Keywords: [Primary query]; [secondary queries]; [entities]; [excluded or overlapping intent]
H1: [Exact draft]
Canonical: [Exact URL or rule]
Indexing: [index/follow or other justified rule]
Schema: [Main entity and supporting types]
OG title: [Exact draft or inherit rule]
OG description: [Exact draft or inherit rule]
```

Treat `Keywords` as a planning field. Do not claim that a meta keywords tag creates ranking value.

## Heading outline

Show the semantic and editorial structure before module details:

| Order | Level | Exact heading draft | Visitor question answered | Source requirement |
|---|---|---|---|---|

Avoid multiple competing H1s. Do not use headings solely to achieve a visual size.

## Module specification

Use this seven-field structure for every major module:

```text
MODULE-[PAGE]-01｜[Module name]
Title: [Exact heading]
Subtitle: [Exact subtitle, or none]
Body copy: [Publishable first draft; mark unsupported claims as Draft pending evidence]
Component content: [Exact card count, labels, fields, order, interactions, states, and mobile behavior]
CTA: [Exact label → exact destination]
Visual requirements: [Asset subject, layout, caption/ALT, responsive behavior, accessibility]
SEO requirements: [Heading level, internal links, visible Schema content, indexing detail]
```

Put proof, analytics, dependencies, and acceptance in the relevant field or page-level rules when they matter. Do not add a standalone `Source` / `来源` field. Use paragraphs outside a table when copy is long.

## Common page patterns

### Home

Specify the hero, proof strip, value proposition, product or service paths, solution paths, cases, trust, insights, and final CTA. Write the exact hero headline, subheadline, CTA labels, proof labels, card titles, and card descriptions.

### Product or service hub

Specify category framing, comparison criteria, item cards, selection guidance, trust, FAQ, and CTA. Explain how the user distinguishes offerings.

### Product or service detail

Specify hero, problem, mechanism, features, architecture or process, security/compliance, use cases, proof, versions/pricing, FAQ, related content, and CTA. Separate verified capabilities from future roadmap.

### Solution page

Specify audience conditions, pains, consequences, solution model, product/service composition, implementation stages, responsibilities, proof, risks, FAQ, and consultation CTA. Do not duplicate a product feature page.

### Case page

Specify customer context, baseline, constraints, intervention, implementation, measurable result, measurement method, authorization status, quote, related offer, and CTA.

### Article or resource

Specify answer-first summary, author and reviewer, dates, contents, evidence, body outline, related pages, update policy, and CTA.

### Contact or application

Specify entry intent, form fields, labels, placeholders, required/optional state, privacy notice, validation, submission states, routing, response expectation, alternate channels, analytics, and personal-data restrictions.

### About

Specify company definition, history, leadership or team, mission, capabilities, verified milestones, certifications, contact details, and entity-consistent structured data.

## Shared modules

Write concrete specifications for Header, mega menu or mobile drawer, Footer, breadcrumbs, CTA banners, consent language, search/filter, pagination, empty state, error state, and 404 when they are in scope.

## Evidence safeguards

- Trace strong claims to supplied or independently verified evidence.
- Give numbers a timeframe, scope, method, and owner.
- Do not treat example copy in a reference document as truth about another business.
- Flag legal, financial, medical, security, compliance, certification, pricing, and performance language for owner review.
- When content cannot be completed safely, state exactly what evidence is missing and who should supply it.
