---
title: "Accessibility"
component: "MaskedTextBox"
description: "Accessibility support in masked textbox"
---

# Accessibility

The MaskedTextBox is characterized with complete ARIA Accessibility support that helps to access
using on-screen readers and other assistive technology devices. This component is designed with the
reference of the guidelines document given in [WAI ARAI Accessibility practices](http://www.w3.org/WAI/PF/aria-practices/).

The MaskedTextBox uses the `textbox` role and following ARIA properties for its element based on its state.

| **Property** | **Functionality** |
| --- | --- |
| aria-live | Indicates the priority of updates to a live region. |
| aria-disabled | Indicates the disabled state of the MaskedTextBox. |
| aria-valuenow | Specifies the current value of the MaskedTextBox. |
| aria-invalid | Indicates that the user input is incorrect or not within the acceptable ranges. |
| aria-placeholder | It is a short hint to help the users with data entry when the MaskedTextBox has no value. |
| aria-labelledby | Indicates the floating label element of the MaskedTextBox. |