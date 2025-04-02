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

# Example Title

A rough amount of text that looks good.

<footer>
  <p>April 2025</p>
</footer>

---
layout: image-block
title: Image Block
image: https://images.unsplash.com/photo-1656574446871-02ec50c12b76?q=80&w=2574&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: ""
caption: "© Jeremy Bishop"
---

# Image Block

<v-click><p>A brand new, standardised legal & technical framework.</p></v-click>

<v-click><p>Based on <strong>EN 301 549</strong> (3.2.1) and the <strong>WAD</strong>.</p></v-click>

<v-click><p>Impacts <strong>all</strong> companies within the EU.</p></v-click>

<v-click><p>Enforced from <strong>June 28th, 2025</strong>.</p></v-click>

<v-click><p>Supersedes, but does not replace, existing rules.</p></v-click>

<!--
Add notes here.
-->

---
layout: text-block
title: Text Block
---

# Text Block

<v-click><p>Applies to customers <strong>and</strong> staff.</p></v-click>

<v-click><p>No EU-wide fixed penalties.</p></v-click>

<v-click><p>Member states are defining their own laws.</p></v-click>

<v-click><p><strong>Article 32</strong> won't save you.</p></v-click>

<v-click><p>Brexit (probably) won't save you.</p></v-click>

<!--
Notes
-->

---
layout: resource-block
title: Resource Block
---

# Resource Block

-   Shameless plug: https://theadhocracy.co.uk/wrote/european-accessibility-act
-   Official: https://digital-strategy.ec.europa.eu/en/policies/latest-changes-accessibility-standard
-   Web accessibility: https://www.a11y-collective.com/get-ready-for-the-european-accessibility-act/
-   Web breakdown (very detailed): https://tetralogical.com/blog/2025/03/19/understanding-the-eaa/

---
layout: code-block
codepen: ogvrxYe
title: Code Block
---

# Accessibility

Most is provided by default, but you should provide an accessible name.

Implicitly has the ARIA role `dialog`.

If being used as an alert (requires user confirmation or response) then should have `role="alertdialog"` set.

Focus needs to be considered, but should be largely covered.
