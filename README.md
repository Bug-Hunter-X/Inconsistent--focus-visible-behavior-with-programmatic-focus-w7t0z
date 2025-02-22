# Inconsistent :focus-visible behavior with programmatic focus

This repository demonstrates an uncommon bug related to the CSS `:focus-visible` pseudo-class.  The issue arises when an element receives focus programmatically (e.g., using JavaScript's `focus()` method) rather than through direct user interaction.

The `:focus-visible` pseudo-class is intended to apply styles only when the focus is visually apparent to the user. However, its behavior isn't always consistent across browsers and assistive technologies when dealing with programmatic focus.

The `bug.css` file showcases the problem.  The `bugSolution.css` file provides a potential solution or workaround.  See the detailed explanation in the respective files.

This issue is particularly important for accessibility, as it can affect users who rely on screen readers or other assistive devices.