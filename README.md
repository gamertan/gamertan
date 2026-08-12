# Hi, I’m Cole. 👋

I build software under **[Gamertan](https://gamertan.com/)**: a small,
independent home for useful tools, strange ideas, and projects I care enough to
operate in public.

I’m a developer, designer, and systems builder—as well as a husband and dad.
I’m disabled and neurodivergent, too. I don’t share that as a diagnosis-shaped
résumé item; it simply explains some of the care behind the work. Time, energy,
attention, bodies, and brains vary. Software should make room for that.

That usually means accessible paths, plain language, recoverable mistakes,
boring deployments, and systems a future human can understand. I like clever
code. I trust legible code more.

> Don’t bother me—I’m working on my gamer tan.

## Where the work lives

**Gamertan is the public homebase. [Gamertan Gitea](https://gitea.speelman.ca/gamertan)
is the canonical forge**: source, release history, contribution and security
instructions, and project stewardship live there.

This GitHub account exists for discovery and accessibility. Project repositories
mirrored here are read-only discovery snapshots. If GitHub and Gitea disagree,
Gitea is authoritative. Please use each canonical repository’s contribution and
security instructions rather than opening issues or pull requests against a
mirror.

## Things worth visiting

### [Sandwich Hime](https://sandwichhime.com/)

An HTML-first, ahead-of-time template engine for Go. It keeps the immediate,
mixed-markup feeling I loved on the old web, then generates typed ordinary Go
components with contextual escaping and a small production runtime.

**v1.0.0-beta.1 is live** as a signed, installable public beta for classrooms,
learning, prototypes, and compatibility feedback. It is not a production
stability promise: interfaces may still change before final v1, and native
macOS maintainer testing remains provisional until I can run it directly.

```sh
go get gamertan.com/sandwich-hime/sando@v1.0.0-beta.1
go install gamertan.com/sandwich-hime/cmd/himesan@v1.0.0-beta.1
```

That runtime-first order is intentional for Beta 1. The exact release source
passed Go 1.25.12 and 1.26.5 on native Windows and executed Linux, and clean
direct and public Go-proxy installs are verified.

- [Start with the tutorial](https://sandwichhime.com/docs/tutorial/)
- [Read the documentation](https://sandwichhime.com/docs/)
- [Inspect the canonical source](https://gitea.speelman.ca/gamertan/sandwich-hime)
- [Browse the GitHub discovery snapshot](https://github.com/gamertan/sandwich-hime)
- [Use the 0BSD tutorial starter](https://github.com/gamertan/sandwich-hime-tutorial)
- [Open the canonical Beta tags](https://gitea.speelman.ca/gamertan/sandwich-hime/tags)

### [EQL Helper](https://eql.gamertan.com/)

A fast, accessible EverQuest reference built from public EQL Wiki data. It is
for the wonderfully specific moment when your adventure needs an item, spell,
NPC, zone, recipe, merchant, or faction answer more quickly than your memory
can supply it.

- [See the data sources](https://eql.gamertan.com/sources)
- [Use the developer resources](https://eql.gamertan.com/developers)

### San — someday

San is a separate programming-language project I am still thinking through and
building privately. It is **not released**, has no supported toolchain, and
should not be inferred from unfinished experiments or domains. `.san` belongs
to San; Sandwich Hime templates use `.sando`.

When San has something honest and useful to show, it will have its own
announcement and canonical home. Until then: the mountain on the horizon, not
a product claim.

## A small operating principle

Accessibility is not polish. Maintenance is part of design. Public work should
say who stewards it, where its source lives, what is experimental, and what
people can safely rely on.

Family also puts software in its proper place. I want to make things that are
useful and durable, without pretending every idea must become a company or
every evening must become a launch.

I learn by building. I try to leave the result easier to inspect, repair, and
inherit than I found it.

<sub>The much longer April 2026 profile is preserved in [the archive](archive/README.md).
It was sincere; this one is simply closer to where the work is now.</sub>
