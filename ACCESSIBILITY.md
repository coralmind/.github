# Accessibility

This page describes access to CoralMind's repositories, documentation, and websites, and how to report a barrier that stops you from using them.

If you need help now, or you have a question about the projects, see [SUPPORT.md](SUPPORT.md). CoralMind is not a clinical service.

## Priorities

We publish research and field infrastructure as text: Markdown, JSON, and YAML on GitHub, and on the websites listed under Environments. A person should be able to reach that material with a keyboard and with assistive technology.

When we publish, and when we fix a barrier, we use these priorities:

1. **Content warnings.** Material that describes suicide, self-harm, or psychiatric crisis says so before the material, so a reader can decide whether to continue.
2. **Text that stands on its own.** Figures, images, and controls have a text alternative. Meaning does not depend on color alone.
3. **Plain language.** Sentences say what they mean. An abbreviation is expanded the first time it appears.
4. **Structure assistive technology can follow.** Headings stay in order. Controls have names. A link says where it goes.
5. **Text formats.** Data and content are available as text, including when a figure or a PDF is also provided.

These are publishing priorities. We will name a conformance standard, such as a WCAG level, on this page only after an audit has checked the repositories and the websites against it.

## Environments

The repositories can be read on GitHub in a browser, or cloned and read in a local editor.

The same priorities apply to every CoralMind website. Today those include:

- [coralmind.org](https://coralmind.org), the organization site.
- [map.coralmind.org](https://map.coralmind.org), the Knowledge Library viewer (`viewer/` in [knowledge-library](https://github.com/coralmind/knowledge-library)).

A website added later is covered here until that project publishes its own `ACCESSIBILITY.md`.

We have not yet named a set of browsers and assistive technologies we test against. A report is more useful when it includes the browser, the assistive technology, and the versions you used. For a local viewer, include how you started it.

## Known barriers

We have not finished an audit of the repositories or of the websites above. This section will list each barrier we know about, and any workaround, as we confirm it.

A barrier you encounter is worth reporting even when it is not listed here.

## How to report a barrier

Open a public issue on the affected repository.

- A README, guide, or other project documentation: use the documentation report.
- Published content, such as text, data, or a figure: use the content report.
- Code, tooling, or a website: use the bug report, on the repository that builds that site. The Knowledge Library viewer is [knowledge-library](https://github.com/coralmind/knowledge-library). 

Include the page or file, what you were trying to do, what happened, and the browser, assistive technology, and versions you used.

Do not include real patient data, identifiable crisis narratives, or other personal information.

A safety-sensitive finding goes through [SECURITY.md](SECURITY.md). Do not describe it in a public issue.

## What to expect

We are a small team. We will acknowledge a report as soon as we can, and say whether we can fix the barrier. A barrier we confirm and cannot fix yet is added under Known barriers, with any workaround we have.

The maintainers of each repository own the fixes in that repository. This file is the organization default. A project adds its own `ACCESSIBILITY.md` when its barriers differ.

## Changes to pages and interfaces

Contribution guidelines are still being written, and we are not accepting pull requests yet. A report is the way to tell us about a barrier.

When we do accept changes, a change to a page, document, or interface follows the priorities above. A new figure includes a text alternative. A new control has a name. A new page that describes suicide, self-harm, or psychiatric crisis includes a content warning.
