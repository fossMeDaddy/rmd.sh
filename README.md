# ReleaseMeDaddy! [WIP]
---

internal tool for distributing & installing binaries.

```bash
curl -sS https://rmd.sh/PKGNAME/PKGVERSION | bash
```

> "where's windows powershell installation command?"
>
> whats that?

![](https://api.simplefs.io/c3df3b13-6d04-4348-b26a-409e953c8e56)

**features:**
- [x] automated installer script to detect and fetch the correct package for the detected arch & os
- [x] host a simple server to serve the thing (simple... my ass)
- [ ] gh app integration for deploying packages & their version on new pushes
- [ ] gh app integration for tracking PRs and automatically assigning semver versions & tags
- [ ] setup up a cloud cross compilation pipeline for building binaries

if you like the idea consider starring the repo, helps me get an idea of what to keep working on.

> "oi! i can't find the source code, where is it?"

there are 2 reasons for that:
1. I accidentally published the prod DB url in the first commit
2. the code is a gigantic flaming hot pile of garbage, need to rewrite

source code commmiiing sooooooooooooon uwu
