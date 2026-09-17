# Turning this into your GitHub profile README

GitHub shows a repository's README at the top of your profile when the repository is named **exactly** like your
username. That is the only special case — no configuration, no settings.

## Steps (about 5 minutes)

1. On GitHub, create a new **public** repository named exactly:

   ```
   lixiang021011-sketch
   ```

   Do not initialise it with a README (you already have one here).

2. Push this folder to it:

   ```powershell
   cd C:\Users\LorXer\Projects\github-profile
   git init
   git add -A
   git commit -m "docs: profile README"
   git branch -M main
   git remote add origin https://github.com/lixiang021011-sketch/lixiang021011-sketch.git
   git push -u origin main
   ```

3. Open `https://github.com/lixiang021011-sketch` — the README now sits at the top of the profile.

## Then do these four small things on the profile page

| Where | What to set |
| --- | --- |
| Profile → Edit profile → **Bio** | `Game designer — systems, numbers and tooling. FallenAngel (Unity), Game Forge. MSc BA at UvA.` |
| Profile → Edit profile → **Website** | your portfolio URL (once it is live) |
| Profile → **Customize your pins** | pin four: FallenAngel, StylesVN, Game Forge, Bell Garden |
| Each repository → **About** → Website | the same portfolio URL, so every repo links back to the tour |

## Why this matters more than the repo list

A profile with no README shows a stranger a table of repository names. A profile with a README answers, in fifteen
seconds: what you work on, what state it is in, what you are looking for, and where to read more. Everything below
the fold — commits, tests, tags, licenses — is then the evidence for that claim.

## Keeping it honest

The README lists only your own work. The collaboration project is not listed; keep it that way, and if anyone asks
what else you have worked on, describe the collaboration as a collaboration.
