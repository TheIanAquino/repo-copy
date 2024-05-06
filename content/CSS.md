---
title: CSS
draft: false
date created: 2024-05-05
last modified: 2024-05-05 06:31:26 PM
---

> [!INFO] What's this?
> Here lies all interesting stuff I find about **CSS**. These would include all bugs, errors, fixes, and other technical information that I could find useful in my [[dev-2024-05-05|development journey]].

# **[[dev-2024-05-06 | dev-2024-05-06-Putting a Link in CSS]]** | *01:38:52 PM*

![[Pasted image 20240506133951.png]]

# **[[dev-2024-05-06 | dev-2024-05-06-Displaying an Inline Block]]** | *02:06:07 PM*

We can use the following to display an inline block in CSS:
```
selector-here {
	display: inline-block;
}
```
An inline block fixes the problem of working with block-level elements and `text-align` whereby the block-level element acts in a way that fills up the entirety of the `block-level` element. Refer to [[dev-2024-05-06#** 2024-05-06 ** *02 01 17 PM*|this]] for more context.

# **[[dev-2024-05-06|dev-2024-05-06-Adding hover, active, and visited looks for a link]]** | *04:09:35 PM*

Refer to [[dev-2024-05-06#** 2024-05-06 ** *04 07 59 PM*|this]] for preliminary context. Here's how it works:

CSS adds visited, hover, and active properties to a selector as follows. Say, for example, we have a selector for a `<p>` with the following attribute: `class="for-css"`, and we wanted to change its look for when it's on **hover**, **active**, and **visited**.   

It will look like this, when we modify it in the `styles.css` sheet of my project:

```
p.for-css:hover {
	color: black;
}
p.for-css:active{
	color: brown;
}
p.for-css:visited {
	color: black;
}
```
