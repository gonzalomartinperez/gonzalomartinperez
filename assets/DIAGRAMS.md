# Profile architecture diagrams

[Profile](../README.md#from-product-needs-to-production-systems) · [Artwork provenance](NOTICE.md#product-architecture-diagrams)

These diagrams answer: **How do product experience, application logic, AI and
production delivery fit together across my work?** They are conceptual summaries
across multiple projects. They do not describe one employer's infrastructure,
network boundaries or service activation.

| View | Editable semantic source | Native-size artwork |
| --- | --- | --- |
| Full component context | [Seven nodes](product-architecture.mmd) | [Light](product-architecture-light.svg) · [Dark](product-architecture-dark.svg) |
| Compact capabilities | [Four groups](product-architecture-compact.mmd) | [Light](product-architecture-compact-light.svg) · [Dark](product-architecture-compact-dark.svg) |

## Meaning and reading order

Read from top to bottom: product experience → application and intelligence → data
and production. Solid arrows represent dependencies or capability flow, not
necessarily network requests. Dashed arrows identify production support through
CI/CD, observability and evaluation; they do not describe an automatic training
loop. The visible legend repeats that distinction without relying on color.
Group outlines organize responsibility; they are not security or deployment fences.

The full source preserves exactly these relationships:

| From | To | Connection |
| --- | --- | --- |
| Web / mobile / backoffice | APIs / BFFs | Solid |
| APIs / BFFs | Agent systems | Solid |
| APIs / BFFs | Domain services | Solid |
| Agent systems | AI context / memory | Solid |
| Agent systems | Domain services | Solid |
| Domain services | Data / external providers | Solid |
| AI context / memory | Production delivery | Dashed |
| Data / external providers | Production delivery | Dashed |

The compact view groups these same capabilities as product experience, application
and intelligence, data and context, and production delivery. Its two solid arrows
and final dashed arrow summarize the full view; they add no runtime components.

## Visual standard and editing

These assets follow the shared repository diagram standard: a 640 px native width,
neutral surfaces, restrained blue/cyan accents, system typography, 25 px card titles
and 20 px descriptions. Explicit lines avoid font-dependent wrapping. Both themes
must have identical geometry, wording, node IDs and arrow meaning. The README
selects the compact view on narrow screens and exposes native-size links for detail.
Top-to-bottom component context fits the question here; a sequence or deployment
notation would imply precision that this cross-project overview does not claim.

The SVGs are curated, hand-editable artwork. The Mermaid files preserve semantics;
rendering those files does not promise identical geometry. Keep source, SVG and the
[palette/graph inventory](product-architecture.config.json) synchronized. Do not add
runtime dependencies or use external rendering services to edit these documents.
Do not put scripts, event handlers, foreign objects, external resources, fonts or
embedded links inside SVGs.

Before review, parse SVG/XML and JSON, compare both theme geometries and wording,
and check each source node and edge against the inventory. Measure text contrast
against its actual card/group/canvas surface (at least 4.5:1) and significant
connectors against their surfaces (at least 3:1). Render all four assets at native
and mobile widths; inspect clipping, explicit line breaks, card/arrow intersections
and README picture selection. Check relative links and `git diff --check`.

Local rendering and source checks do not certify universal accessibility or the
exact deployed GitHub renderer. Image alternatives and the profile's prose overview
remain available independently of SVG support.
