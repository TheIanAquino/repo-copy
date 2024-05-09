---
title: HTML
draft: false
date created: 2024-05-05
last modified: 2024-05-05 06:31:07 PM
---


> [!INFO] What's this?
> Here lies all interesting stuff I find about **HTML**. These would include all bugs, errors, fixes, and other technical information that I could find useful in my [[dev-2024-05-05|development journey]].

# **[[dev-2024-05-05|dev-2024-05-05-Making CSS Interactive]]** | *06:42:32 PM*

![[dev-2024-05-05#^96e62b]]

![[dev-2024-05-05#^edc43e]]

As stated above, this code block styles the page to **"look similar on mobile as it does on a desktop or laptop."**

# **[[dev-2024-05-07|dev-2024-05-07-Adding multiple classes to an HTML element]]** | *11:27:25 AM*

>[!TIP]- Adding multiple classes to an HTML element
>![[Pasted image 20240507112756.png]]

For us to add multiple classes to an HTML element, we just need to add a space per value of the `class` in the attribute. Here's how it looks like:

```
<p class="restaurant eatery carinderia">somewhere to eat</p>
```

However, when working with CSS, we need to keep this in mind:

>[!QUOTE]- Working with multiple HTML classes in CSS
>If you add multiple classes to an HTML element, the styles of the first classes you list may be overridden by later classes.

# **[[dev-2024-05-09|dev-2024-05-09-for and id atrributes]]** | *11:00:14 PM*

![[dev-2024-05-09#^d41dd7]]

A `for` attribute needs to have an `id` attribute, for it to work. [^1]

[^1]: I'm not sure about this one. I'll eventually confirm it as I go. The rationale behind me writing this as a *context* is that I somehow correlated the presence of a `for` attribute to the `id` attribute -- that the former cannot exist without the latter. **However**, I am met with the confusion caused by the possibility of the `id` attribute existing without the `for` attribute (e.g. as a selector for [[CSS]], i.e. `.id-here`).