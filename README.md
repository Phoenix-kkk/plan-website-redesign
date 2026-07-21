# GEO Website Audit & Redesign PRD

Enter a website URL to identify GEO issues and improvement opportunities, then turn the findings into two actionable deliverables:

1. A concise website problem report.
2. An implementation-ready website redesign PRD for design, content, engineering, sales, and legal teams.

## Install

```bash
npx skills add Phoenix-kkk/plan-website-redesign -g -y
```

Alternatively, clone this repository and place the `plan-website-redesign` folder in your Codex skills directory.

## Usage

```text
Use $plan-website-redesign to turn https://example.com/ into an actionable website redesign plan for design, content, and engineering teams.
```

The skill produces the problem report first, followed by the redesign PRD. It does not modify the target website unless implementation is explicitly requested.

## What You Get

- **Problem report:** Executive diagnosis, scope and limitations, assets to preserve, a `Priority | Problem | Impact` issue table, and decisions to confirm.
- **Redesign PRD:** Information architecture and navigation, page map, site-wide TDK and Schema, page-level content specifications, global components, SEO/GEO, analytics, migration, phases, and acceptance criteria.

Every core module includes a title, subtitle, body copy, component content, CTA, visual requirements, and SEO requirements. When SEO, GEO, AI visibility, or structured data is in scope, the skill applies the relevant audit workflow. It does not promise rankings, traffic, or AI citations.

## Best For

- Corporate, product, and service website redesigns
- Website audits and information architecture restructuring
- SEO, GEO, and AI-visibility planning
- Converting an existing audit or content materials into an executable redesign PRD

## Structure

```text
SKILL.md       # Workflow and delivery rules
assets/        # Problem-report and redesign-PRD templates
references/    # Discovery, page specification, SEO/GEO, and acceptance guidance
```

## Boundaries

Unsupported claims about pricing, customers, results, certifications, capabilities, or legal terms are marked as pending confirmation rather than presented as facts. Business, product, legal, and engineering owners must verify them before launch.
