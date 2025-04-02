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

# European Accessibility Act

The new European standard for digital accessibility.

<footer>
  <p>April 2025</p>
</footer>

---
layout: image-block
title: Overview
image: https://images.unsplash.com/photo-1656574446871-02ec50c12b76?q=80&w=2574&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: ""
caption: "© Jeremy Bishop"
---

# A Brief Overview

<v-click><p>A brand new, standardised legal & technical framework.</p></v-click>

<v-click><p>Based on <strong>EN 301 549</strong> (3.2.1) and the <strong>WAD</strong>.</p></v-click>

<v-click><p>Impacts <strong>all</strong> companies within the EU.</p></v-click>

<v-click><p>Enforced from <strong>June 28th, 2025</strong>.</p></v-click>

<v-click><p>Supersedes, but does not replace, existing rules.</p></v-click>

<!--
EU-wide piece of legislation based on a technical standard (EN 301 549) and existing, public sector rules that have been refined for the last decade or so in the European Web Accessibility Directive.

All companies means: any company based on the EU, that employs EU citizens, pays EU taxes, or sells any good or service to EU citizens or within EU countries. Basically, the entire private sector.

Also sits on top of WAD, so impact public sector as well.

Only companies not affected: < 10 employees **and** less than €2 million annual turnover.

Existing rules still apply, but EAA is the new baseline legal requirement. E.g. French RGAA is still applicable within France
-->

---
layout: text-block
title: Impact
---

# Business Impact

<v-click><p>Applies to customers <strong>and</strong> staff.</p></v-click>

<v-click><p>No EU-wide fixed penalties.</p></v-click>

<v-click><p>Member states are defining their own laws.</p></v-click>

<v-click><p><strong>Article 32</strong> won't save you.</p></v-click>

<v-click><p>Brexit (probably) won't save you.</p></v-click>

<!--
Not just external, but internal, and staff can levy complaints directly against employers.

Example: Germany has proposed up to €100,000 fines, restriction of business licenses, and sanctions under the Unfair Competition Law.

Result is that if you operate in the EU, you could end up with multiple court cases across multiple countries, each with their own penalties.

Article 32 is a controversial part of EAA that extends the deadline to **June 2030** in certain scenarios: contracts that pre-exist 2025 (as well as some eWaste provisions for hardware). But anything sold or renegotiated after June 28th must be compliant.

Legacy codebases do not need to apply, but cannot be resold. And even these must be accessible by 2030.

UK already has the Equality Act which applies to private sector businesses. We already harmonised with the WAD for public sector businesses. And the government has signalled a desire to harmonise with the EAA completely. Plus, if you sell anything within the EU or hire anyone from the EU, you have to be compliant.

For us, right now, probably not that impactful.
-->

---
layout: image-block
title: Requirements
image: https://images.unsplash.com/photo-1522252234503-e356532cafd5?q=80&w=2525&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D
alt: ""
caption: "© Karl Pawlowicz"
---

# Web Requirements

<v-click><p><strong>WCAG 2.1</strong> AA for the web.</p></v-click>

<v-click><p>Also: native apps, emails, attachments, and downloadable files.</p></v-click>

<v-click><p><strong>File uploads</strong> cannot strip accessibility affordances.</p></v-click>

<v-click><p><strong>Biometrics</strong> cannot be sole auth method.</p></v-click>

<v-click><p>Support channels must be accessible.</p></v-click>

<!--
EAA goes beyond the web; covers everything from ATMs to eBook formats to Oyster cards.

WCAG 2.2 is not yet included and new WCAG versions are not automatically applied.

Includes PDFs, for instance, which now have their own near-WCAG standards as part of EAA **or** offer an alternative, accessible version.

E.g. a video file with embedded captions or an image with baked in descriptive text can ignore it, but cannot remove it. Conversion gets tricky; may require sidecar files.

Provide multiple authentication methods, with at least one being non-biometric e.g. password or One Time Code.

Support cannot be simply phone or chat bot only.

Also a few niche requirements around:

- media players (minimum resolution; Braille interfaces; text, audio, and video must sync within 100ms affordance)
- two-way communication e.g. telephony/VOIP and chat interfaces, which must also keep tight synchronisation and minimum resolutions
- key repeater patterns/shortcodes: if a user can type a key X number of times and then something else happens, there must be an adjustable time delay
- do not block assistive tech and if you do, you have to recreate that functionality e.g. if you block headphones, you have to provide text captions
-->

---
layout: resource-block
title: Resources
---

# Resources

-   Shameless plug: https://theadhocracy.co.uk/wrote/european-accessibility-act
-   Official: https://digital-strategy.ec.europa.eu/en/policies/latest-changes-accessibility-standard
-   Web accessibility: https://www.a11y-collective.com/get-ready-for-the-european-accessibility-act/
-   Web breakdown (very detailed): https://tetralogical.com/blog/2025/03/19/understanding-the-eaa/
