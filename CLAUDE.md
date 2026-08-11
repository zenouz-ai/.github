# Repository working rules

## Scope boundary

This folder is an independent Git repository (the `.github` organisation repository). It is
often opened alongside sibling repositories in a multi-root VS Code workspace. Do not read
from or write to sibling folders. Every path you touch must resolve inside this repository.

## What this is

The organisation-level `.github` repository. `profile/README.md` renders on the public
organisation page. `profile/assets/` holds the image assets it references.

Files here can apply defaults across every repository in the organisation. A change made here
is not local to this folder in effect, even though it is local in scope.

## Working rules

- This content is public. Treat every edit as published copy.
- Do not invent organisation facts, affiliations, or metrics.
- Changing a shared workflow, issue template, or default here affects other repositories.
  State that consequence explicitly before making such a change.
- Do not rewrite or regenerate `profile/assets/` images.
- Prose is concise and uses no em dashes.
