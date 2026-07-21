# Page requirements

Write one detailed specification per distinct core page and one shared specification per reusable template.

## Page definition

Include:

- **Route and page type**: Proposed path and whether it is unique or templated.
- **Purpose**: The single job this page performs.
- **Primary audience and intent**: Who arrives and what they need to resolve.
- **Entry contexts**: Search, navigation, campaign, referral, product, or direct visit.
- **Primary conversion**: One dominant next action; list secondary actions separately.
- **Core promise**: The main conclusion a qualified visitor should understand.
- **Required proof**: Evidence needed to make the promise credible.
- **TDK**: Exact draft Title, Description, and target keyword/entity set.
- **Discovery controls**: Canonical, indexing rule, schema direction, OG/Twitter content, and language behavior.
- **Heading outline**: Exact H1 and ordered H2/H3 drafts.
- **Content modules**: Ordered module specifications with concrete copy and evidence dependencies.
- **Internal links**: Incoming and outgoing relationships that support the journey.
- **Measurement**: Page context and meaningful conversion or engagement events.
- **States and edge cases**: Empty, error, loading, validation, gated, expired, or unavailable states.
- **Dependencies**: Content, design, data, legal, engineering, or third-party needs.
- **Acceptance criteria**: Observable conditions for completion.

## Sitemap decision rules

Create a separate page when it has a distinct primary intent, audience decision, conversion path, or durable body of evidence. Prefer a section or module when content would repeat another page's purpose.

Reject or merge pages that lack:

- a unique primary job;
- enough substantive content;
- a clear place in navigation or internal linking;
- an owner or maintenance path when freshness matters.

## TDK rules

- Draft Title and Description as exact publishable text, not directions such as “include the main keyword.”
- Keep the primary topic, user value, and brand distinguishable without repeating a fixed formula mechanically.
- Record `Keywords` as a content targeting set: primary query, secondary queries, entities, and exclusions. Only render a `meta keywords` tag if the user's platform or regional strategy explicitly requires it; do not imply that it guarantees ranking.
- Give every indexable page a unique TDK set aligned with its primary intent.
- Mark unsupported product, performance, compliance, or market claims as evidence dependencies.
- Define the self-canonical or alternate canonical behavior, indexing state, and relevant schema.

## Heading and message hierarchy

Organize modules around visitor questions, typically:

1. What is this and is it for me?
2. What problem or goal does it address?
3. How does it work?
4. Why should I believe it?
5. What should I do next?

Use one primary H1. Write exact H2/H3 drafts in page order. Change the sequence when intent requires it; do not force every page into the same landing-page formula.

## Module content standard

For each module, specify:

- module ID, name, position, and purpose;
- H2/H3 or non-heading label;
- exact headline, supporting copy, labels, list items, CTA text, and microcopy;
- required data, claim, testimonial, certification, or other proof;
- content status: `Ready`, `Draft`, `Draft pending evidence`, or `Owner decision`;
- media subject, asset source, aspect behavior, caption, and draft ALT text;
- desktop, mobile, keyboard, reduced-motion, and empty/error behavior as relevant;
- internal links and destination rules;
- analytics events and properties;
- legal, content, design, engineering, or data dependencies;
- issue/goal traceability and acceptance criteria where they materially affect implementation.

Do not write “add a hero,” “show advantages,” or “include cases” without specifying the actual first-draft content and evidence needed.

## Design direction

State outcomes such as hierarchy, density, readability, trust, differentiation, and responsive behavior. Specify exact colors, typography, motion, or component styling only when the user supplies brand rules or evidence supports those choices.

## Reusable templates

For products, services, locations, cases, resources, or articles, define shared fields and optional modules once. Then document meaningful exceptions per subtype. Include rules for missing media, long titles, sparse content, related content, authorship, dates, structured data, and unverified claims.
