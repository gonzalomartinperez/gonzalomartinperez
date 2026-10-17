# Maintaining this profile

This repository contains my GitHub profile README and static diagrams. It has no
application runtime, package installation or deployment pipeline. Feedback about
broken links, readability and accessibility is welcome; changes are reviewed
manually through pull requests targeting `main`.

Keep `main` as the default branch and the published profile source. Maintain
`develop` as a synchronized checkpoint of the final approved `main` commit;
documentation task pull requests still target `main`. After integration, advance
`develop` to that approved commit without introducing a separate release pipeline.
Remove integrated task branches when safe, while preserving unmerged work.

## Content and evidence

- Use natural US English and keep the introduction focused on software, AI and
  product engineering. Preserve the portfolio, LinkedIn, CV and contact links.
- Check professional facts against the reviewed public portfolio and CV. Keep
  measured outcomes, estimates, project scope and individual contributions distinct.
  Do not expand a result from selected workflows into a claim about an entire product.
- Do not add credentials, private career documents, customer information, employer
  internals or invented endorsements. Avoid automatically generated activity scores,
  visitor counters and unsupported proficiency ratings.

## Markdown and diagrams

Use relative paths for repository assets and descriptive link text. Preserve image
alternatives and the text explanation of the architecture diagram. Keep the diagram
source and its rendered assets consistent, including compact layouts and both themes.
Review legibility, contrast and wrapping before replacing visual assets. SVGs should
remain static: no scripts, event handlers or remote resource dependencies. Preserve
attribution in [assets/NOTICE.md](assets/NOTICE.md).

Before opening a PR, inspect the complete diff, check local links and asset paths,
validate changed SVG XML, and run `git diff --check`. Preview changed content on
GitHub in light/dark themes and at a narrow width when visual changes require it.
There is no need to introduce dependencies or CI just to edit these documents.
State what was checked and any preview limitations in the PR. Do not merge or change
profile/account settings as part of an editorial update without authorization.
