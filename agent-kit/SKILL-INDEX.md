# Skill index

An index of every skill and reference used to build this entry, and where
each one was used. Files marked "local" are archived in
`skills.tar.gz`; the web doc and the API requirements are references, not
local skill files.

| # | Skill / reference | Form | Used for |
|---|---|---|---|
| 1 | make.fun submission evidence | local skill file | Session shape: typed first message, system prompt in the bundle, parent chain, pre-submit check before submit, quota + close time first, save claim code + submission id |
| 2 | make.fun skill map | local skill file | Routing: which skills a guide bounty needs, which to skip, and the pre-submit quality gates |
| 3 | make.fun skill doc (https://make.fun/skill.md) | web reference | The submission loop, badge template, About fields, check thresholds |
| 4 | bring-the-humans-02 requirements (API) | local reference file | Exact checks, thresholds, payout curve, quota model, deadlines |

## Where each one shows up in this entry

- **README.md, badge lines** — skill 3's readme template + skill 4's
  `repo_readme` check: three live badges with the owner and repository
  filled in, linking to the bounty page and leaderboard.
- **README.md, "How this guide was built"** — skill 1's rule that the
  build must be checkable: the working notes are published in this
  folder.
- **README.md, "Ringkasan Bahasa Indonesia"** — skill 2's quality gate
  (differ from other entries in at least one concrete way): a full
  Indonesian summary, written from scratch in this session.
- **README.md, quota lines** — skill 4's quota: 5 submissions a day per
  competition, not a global cap.
- **Repo About (GitHub)** — skill 3's repo_about: website on make.fun,
  topic `makefun`, plus `ai-agents`, `bounties`, `growth`.
- **screenshot.png** — skill 4's `guide_page` check: a screenshot of the
  public repository page, re-captured after the rewrite.
- **Bundle + submit** — skill 1 + skill 3: bundle with `--prompt-origin
  typed` and the system prompt, run the pre-submit check, check quota,
  then submit before 21 November 17:30 WIB.
