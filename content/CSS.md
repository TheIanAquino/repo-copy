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

# **[[dev-2024-05-07|dev-2024-05-07-What it means to have two values in the CSS margin property]]** | *11:17:22 AM*

![[dev-2024-05-07#^e6e56d]]

>[!TIP] This also works for the padding property!

If there are two values in a margin property, they set the margin values of top & bottom, left & right. Here's a code snippet to understand it more. Say we have an HTML `p` element with the attribute `class="something"`, and we wanted to add a `10px auto` value in its `margin`:

It would look something like this in the HTML file:

```
<p class="something">style me, please!</p>
```

In the CSS stylesheet, it would look like this:

```
p.something {
	margin: 10px auto;
}
```

If there were two values and, say, we wanted to create a CSS attribute that sets the `margin-top` & `margin-bottom` to `20px`, and `marign-left` and `margin-right` to `10px`. It would look like this:

```
p.something {
	margin: 20px auto 10px auto;
}
```

# **[[dev-2024-05-07|dev-2024-05-07-Color hexadecimal values]]** | *11:57:21 AM*

>[!TIP]- Color hexadecimal values
> ![[Pasted image 20240507115651.png]]


# **[[dev-2024-05-07|dev-2024-05-07-using HSL in CSS]]** | *12:01:00 PM*

>[!TIP]- Using HSL in CSS
> ![[Pasted image 20240507120047.png]]

# **[[dev-2024-05-08|dev-2024-05-08-A simple use-case for a linear gradient in CSS:]]** | *10:02:12 AM*

![[dev-2024-05-08#^2c7c06]]

# **[[dev-2024-05-09|dev-2024-05-09-the CSS vh attribute]]** | *10:41:31 PM*


![[dev-2024-05-09#^a2f589]]

![[dev-2024-05-09#^a4b656]]

