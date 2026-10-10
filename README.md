# MH4U Armor Skills Explained

Every armor skill in **Monster Hunter 4 Ultimate**: the game's own description, then a detailed explanation of
what the skill actually does — the exact amounts, what counts and what doesn't, the differences per weapon, how
it stacks with other skills (Felyne kitchen skills, combo skills like Honed Blade), and what isn't confirmed yet.

Live: https://armoredraven17.github.io/mh4u-armor-skills-explained/

The in-game descriptions say *what* a skill touches. This page says *how*: for example, Focus fills the Long
Sword, Dual Blades and Charge Blade gauges x1.2 faster but is never checked by the Lance, Gunlance or bowguns,
and Weakness Exploit in 4U adds +5 to hitzones of 45 or more rather than affinity.

## Where the numbers come from

The numbers were read from the game's own code and data (a personally-owned copy), not taken from guides.
Community figures were only used as a check. Where something could not be confirmed, the skill says so under
"Not confirmed yet".

## How it fits the family

Static site served from `docs/`, no build step, deployed to GitHub Pages on push to `master` by
[.github/workflows/deploy-pages.yml](.github/workflows/deploy-pages.yml). It shares the look of the sibling
MH4U apps (the MHFU font and the menu textures) and links to them from the 🔗 button. It is the MH4U counterpart
of [MHGU Armor Skills Explained](https://armoredraven17.github.io/mhgu-armor-skills-explained/).

`docs/index.html` is generated (with the skill text embedded) from the research notes kept outside this
repository; edit those and regenerate rather than editing the page by hand.

See [NOTICE.md](NOTICE.md) for attributions. Code is MIT-licensed ([LICENSE](LICENSE)).
