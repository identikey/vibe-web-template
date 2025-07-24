---
trigger: always_on
description: When creating user interface, rules for components and style
---

Whenever creating a user interface, first think if there is a shadcn component that will provide what we need. If so, check src/lib/components/ui/ to see if we have it in our app. The list of components can be found at https://www.shadcn-svelte.com/docs/components
To add a shadcn component, run: `bun shadcn add -y <component_name>`.

Always use tailwind styles. Avoid custom CSS if at all possible.
