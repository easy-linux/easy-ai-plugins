---
name: frontend-review
description: Review React and TypeScript frontend code for correctness, accessibility problems, SSR issues, and security risks.
---

# Frontend Review

Use this skill when asked to review a React or TypeScript component.

## Checklist

1. **Types** — check prop types, generics, and return types for correctness.
2. **React** — check hook dependencies, state updates, and rendering correctness.
3. **SSR** — check for browser-only APIs (`window`, `document`) used outside effects.
4. **Accessibility** — flag accessibility problems such as missing labels, roles, keyboard support, or `alt` text.
5. **Security** — check for unescaped HTML (`dangerouslySetInnerHTML`), unsafe URLs, and unvalidated user input.

Report findings grouped by category, with file and line references.
