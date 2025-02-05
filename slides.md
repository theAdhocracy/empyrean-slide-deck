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
layout: code-block
codepen: GgKboqr
title: Basic Dialog Element
---

# A Basic Dialog

Used to create a sub-window of a web page.

Introduces the new `open` HTML attribute.

Closed with the new `dialog` form method.

---
layout: code-block
codepen: emOwJXO
title: JS for Dialog Element
---

# JavaScript Control Methods

Three new methods:

1. `show()`
2. `close()`
3. `showModal()`

---
layout: code-block
codepen: ogvrxXW
title: Modal Element
---

# Modal vs Dialog

Dialogs allow interaction with the rest of the page.

Modals do not; everything outside of the `<dialog>` element becomes inert.

---
layout: code-block
codepen: ogvrxYe
title: Advanced Modal Functionality
---

# Modal Tricks

Modals have a styleable `:backdrop` psuedo-element.

Automatically provide `Esc` key dismiss.

---
layout: code-block
codepen: EaYBKQW
title: Modal Light Dismiss
---

# Light Dismiss

Commonly expected feature, but not provided by default.

Can be implemented using a few lines of JavaScript.

Be careful of default browser styles, margins, and padding.

---
layout: code-block
codepen: EaYBKrv
title: Modal Background Lock
---

# Inert Background

People should not be able to scroll the rest of the page.

Not automatic, but can be done with a single line of CSS, globally.

---
layout: code-block
codepen: ogvrxYe
title: JS for Dialog Element
---

# Accessibility

Most is provided by default, but you should provide an accessible name.

Implicitly has the ARIA role `dialog`.

If being used as an alert (requires user confirmation or response) then should have `role="alertdialog"` set.

Focus needs to be considered, but should be largely covered.
