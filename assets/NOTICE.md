# Technology artwork

`java.svg` embeds the unmodified Java original icon from [Devicon](https://github.com/devicons/devicon), pinned to revision `7330accdbc47e2dc0c19789a48533c4a3c50fe58`:

[Original source](https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/java/java-original.svg).

Its artwork, colors, and proportions are preserved inside a locally authored badge. The icon was copied from the reviewed public portfolio asset. Java and other technology names and marks belong to their respective owners; their use identifies engineering tools and does not imply endorsement.

Other README badges are served by [Shields.io](https://shields.io/) using its available Simple Icons logos and brand colors. Explicit brand colors prevent white fallback glyphs from disappearing on light badges; light blue marks use a dark background. They are not vendored here. The OpenTelemetry mark is credited to the OpenTelemetry project / CNCF, from [CNCF brand resources](https://cncf-branding.netlify.app/projects/opentelemetry/), under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), as recorded by Simple Icons. The badge displays its monochrome glyph in black.

`aws.svg` embeds the unmodified AWS original wordmark from the same pinned Devicon revision inside a locally authored badge. [Original source](https://raw.githubusercontent.com/devicons/devicon/7330accdbc47e2dc0c19789a48533c4a3c50fe58/icons/amazonwebservices/amazonwebservices-original-wordmark.svg). The original artwork colors and proportions are preserved.

OpenAI API and Agno use text badges because their logos are not assumed to be available from the Shields.io Simple Icons catalog.

## Devicon license

The MIT License (MIT)

Copyright (c) 2015 konpa

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Product architecture diagrams

The product architecture artwork is an original conceptual summary of patterns across Gonzalo's projects, not a deployment diagram for any employer. The SVGs are generated locally with [Mermaid 10.9.3](https://github.com/mermaid-js/mermaid/tree/v10.9.3), distributed under the [MIT license](https://github.com/mermaid-js/mermaid/blob/v10.9.3/LICENSE). No employer diagrams or private implementation materials are embedded.

- `product-architecture.mmd`: full seven-node source with three visual layers.
- `product-architecture-compact.mmd`: the same capabilities grouped into four compact layers for narrow screens.
- `product-architecture.config.json`: renderer options and portfolio-based dark/light colors.
- `product-architecture-{dark,light}.svg` and `product-architecture-compact-{dark,light}.svg`: reviewed static vector outputs.

Rendering uses strict Mermaid security, SVG text labels (`htmlLabels: false`), Arial/Helvetica fallback fonts, and the recorded spacing/curve settings. Generated node corners are rounded to 14 px and group/canvas corners to 20 px. Titles use weight 700 and details weight 500; full-view node titles are 18 px with 14 px secondary details, compact titles are 16 px. Layer headings are 14 px with background plates to keep connectors from crossing their text. These presentation settings are recorded in the config. Outputs include a title and description and contain no scripts, `foreignObject`, external resources, or interactive handlers. The README uses [GitHub-supported picture/media theme selection](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images); a static light image and a text overview provide fallbacks.
