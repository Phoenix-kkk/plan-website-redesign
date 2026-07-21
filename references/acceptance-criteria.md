# Acceptance criteria

Write criteria that another person or tool can verify without interpreting intent.

## Criterion pattern

Use:

> Given [precondition], when [action or inspection], then [observable result], verified by [method].

Short declarative checks are acceptable when the precondition is obvious.

## Coverage areas

Select relevant areas rather than copying every category:

- **Content**: Required copy, proof, ownership, dates, legal text, and fallbacks are present.
- **Navigation**: Important destinations are reachable and current-page state is conveyed.
- **Behavior**: Forms, controls, validation, success, failure, and recovery paths work.
- **Responsive**: Agreed viewports preserve content, hierarchy, controls, and readable layouts.
- **Accessibility**: Keyboard flow, focus, labels, semantics, alternatives, contrast, and error messaging are checked with named methods.
- **SEO**: Status, indexability, canonical, metadata, headings, links, sitemap, robots, redirects, and structured data behave as specified.
- **Analytics**: Named events fire once with required properties and exclude sensitive data.
- **Performance**: The agreed tool, test environment, page set, percentile, and threshold are stated.
- **Migration**: Redirect mappings, removed URLs, canonicals, internal links, and monitoring are verified.
- **Operations**: Owners can update time-sensitive content and documented fallbacks exist.

## Good criteria

- `/old-service/` returns one permanent redirect to `/services/new-service/` with no redirect chain.
- Submitting a valid contact form displays confirmation and records the agreed conversion event once.
- Every indexable page has one visible H1 and a self-referencing canonical in rendered HTML.
- The article template renders a defined fallback when author photography is absent.

## Weak criteria to rewrite

- “SEO optimized”
- “Looks modern”
- “Loads fast”
- “Mobile friendly”
- “Analytics works”
- “Accessible”

Replace subjective adjectives with observable states and a named verification method.

## Targets and unknowns

Do not invent numeric thresholds. If a target is required but absent, write `Target: decision required` and identify the owner and measurement method. Separate launch checks from post-launch outcome targets.

