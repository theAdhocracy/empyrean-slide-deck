---
# try also 'default' to start simple
theme: ./theme
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://images.unsplash.com/photo-1476673160081-cf065607f449?q=80&w=2072&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
# some information about your slides, markdown enabled
title: The Dialog Element
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
    persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
author: Murray Champernowne
---

# \<dialog\>

A simpler, native solution for modals.

<footer>
  <p>Feb 2025</p>
</footer>

---
layout: image-block
image: https://images.unsplash.com/photo-1476673160081-cf065607f449?q=80&w=2072&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: Waves washing over golden sands.
---

# What Is The ADA?

A civil rights act enacted in 1990.

Prohibits discrimination against people based on disabilities.

Split into five sections, known as Titles.

Title II and Title III cover digital and web accessibility.

<!--
Protected classes includes: autism, blindness, deafness, mobility and cognitive disabilities, etc.

Critically, ADA predates wide internet usage, so the wording has always been ambiguous over what is/isn't covered.
-->

---
layout: image-block
image: https://images.unsplash.com/photo-1525113030886-3fbc02591711?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: Textured yellow sidewalk used to indicate the edge of a train platform.
---

# What Has Changed

April 8th: Attorney General assigns Title II protections to digital services.

April 24th: Department of Justice publishes a final ruling on Title II.

WCAG 2.1 AA level now set as the baseline.

<!--
It should be noted that the ADA has long stated that 2.1 AA is a minimum, so in reality this shouldn't change much, but it does provide clearer legal recourse for those affected by inaccessible services.
-->

---
layout: image-block
image: https://images.unsplash.com/photo-1514426003391-f583e9faa9f9?q=80&w=2568&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: Handrails on a concrete set of stairs.
---

# What Does It Mean

Public sector organisations must meet WCAG requirements.

Includes any service or programme that receives government funding.

Section 508 should now consider WCAG 2.1 a minimum requirement.

No change to private sector _yet_.

<!--
E.g. public schools, universities, public services like police, federal programmes like Medicare etc.

Section 508 covers ICT access for federal employees and also includes accessibility provisions. Long required WCAG 2.0 AA, but broad agreement that this new ruling means that it would be impractical to offer anything less than 2.1 AA.

Legal scholars in the US are fully expecting a follow-up ruling to follow a similar pattern for Title III, which would cover all
-->

---
layout: image-block
image: https://images.unsplash.com/photo-1526277712896-20b3ec88a2eb?q=80&w=2670&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: A sequence of ramps with various people shown walking and running, using them.
---

# Timeline

Changes are effective immediately, but compliance is not.

April 24th, 2026: Organisations with 50,000+ people.

April 24th, 2027: All Title II organisations.

---
layout: image-block
image: https://images.unsplash.com/photo-1696875135742-c3044510c9e2?q=80&w=2680&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: Typewriter
---

# Exceptions

Archived content.

User generated content e.g. comments.

Password-protected personal documents.

Content with alternative versions or accessibility features.

<!--
Archived: must have been online prior to 2024 and will never be edited.

User-generated content: so long as no payment has been provided in any form. Must be free and voluntary.

Alternatives: allows for failures of certain WCAG criteria so long as it can reasonably be shown that no person is excluded or impacted, or alternative methods exist that would otherwise circumvent the failure.
-->
