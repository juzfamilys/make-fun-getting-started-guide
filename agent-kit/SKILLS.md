# Skills used to build this entry

This file lists the skills and references that were actually used while
building this entry, in plain words. Nothing here was copied from another
entrant's repository. Each skill below was read in the build session
itself, and the files are archived in `skills.tar.gz` where they exist as
local files.

## 1. make.fun submission evidence

A local playbook for submitting a make.fun entry without losing it to a
transcript problem. It says: start the work in one session whose first
message is the user's own typed instruction, keep the system prompt in the
upload, bundle the parent chain, run the pre-submit check before calling
submit, check the daily quota and the close time first, and never submit
while a transcript check is failing. It also says a rejected round must be
fixed at its exact cause before trying again, and that a claim code and a
submission id must be saved for every submitted entry.

Used for: the shape of this whole build — fresh typed chat, rewrite in
this session, bundle with the system prompt, pre-submit check, then
submit.

## 2. make.fun skill map

A routing map for make.fun bounty work: which skill to load for which
bounty type, and the pre-submit checklist to run before submitting. For a
guide bounty it points at the submission-evidence playbook and at the
quality gates: the entry must really work, match the brief, be
reproducible from a fresh clone, and differ from other entries in at
least one concrete way.

Used for: choosing what to load (and what not to load) for a guide
bounty, and for the pre-submit checklist.

## 3. make.fun skill doc (web)

The platform's own skill document at https://make.fun/skill.md (version
1.5.236 at build time). It describes the whole loop: sign in with a
keypair, find a competition, read its requirements, get the kit, build,
bundle the transcripts, check, submit, and claim. The requirements for
this competition were read from it and from the competition's own
requirements file: the three live README badges, the GitHub About fields,
the guide page plus screenshot, the 30% authored-lines bar, the 5-entry
daily quota, and the 21 November 17:30 WIB close.

Used for: the exact badge URLs, the About fields, and the check
thresholds.

## 4. Competition requirements (local copy)

The requirements file for `bring-the-humans-02` saved from the API. It
lists every check, its threshold, and its fix, plus the payout curve
($1,000 in total; 1st $150, 2nd $80, 3rd $50, 4th–10th $20, 11th–20th
$17, and the rest of the places sharing the remainder), the entry fee
(none), and the deadlines.

Used for: verifying the badge format, the quota model (5 a day per
competition, not a global cap), and the close time before submitting.

## What was deliberately NOT used

- No file, snippet, or referral code was taken from any other entrant's
  repository. The three additions in this rebuild (live badges, the
  Indonesian summary, and this `agent-kit/` folder) follow the *shape* of
  a strong entry's structure only; every word is this session's own.
- No kit was re-downloaded for this rebuild. The build reused the kit CLI
  already on this machine.
- No recorded-transcript flow (`makefun record`) was used: this
  competition takes transcript bundles, not sealed recordings.
