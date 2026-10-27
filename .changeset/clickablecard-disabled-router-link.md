---
'@astryxdesign/core': patch
---

[fix] ClickableCard: a disabled link card no longer passes an undefined `href` to the router link component, so Next.js apps and the docs preview no longer crash while rendering it.

@divyanshudhruv
