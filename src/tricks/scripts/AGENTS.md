# Writing Tricks

Read `node_modules/beebox/box-docs/tricks.md` before writing, changing, or debugging a trick.

## Structure

```
src/tricks/
  package.json        <- npm dependencies for tricks
  node_modules/       <- installed packages (gitignored)
  lib/                <- Shared utilities (import with relative paths)
  scripts/            <- this file's directory
    clean-inbox/
      secrets.json     <- optional declared credentials for this trick
      index.ts        <- bbx trick clean-inbox
    summarize/
      index.ts        <- bbx trick summarize
```

## This box's tricks

Add conventions this box's tricks share (naming, shared helpers in `lib/`,
what each trick is for) here.
