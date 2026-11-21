# Workflow

The workflow used to build and submit this entry, step by step. Each
step names what was done and what it was checked against.

## 1. Confirm the brief

- Read the user's typed instruction in this chat (the first message).
- Confirm the target: bounty `bring-the-humans-02`, account @nonton,
  repository https://github.com/juzfamilys/make-fun-getting-started-guide.
- Confirm the deadline: entries close Saturday 21 November 2026,
  17:30 WIB (10:30 UTC). Confirm the quota model: 5 submissions a day
  per competition, resetting at 00:00 UTC — not a global cap.

## 2. Read the requirements

- Read the saved requirements for `bring-the-humans-02`: checks,
  thresholds, payout curve, deadlines, readme template, repo About.
- Read the make.fun skill doc for the submission loop and the kit
  commands.
- Read the two local skills (submission evidence, skill map).
- Check the repository's current state: branch, log, remote, files.

## 3. Rewrite the guide

- Read the existing README once, as a reference only.
- Rewrite it from scratch with the write tool, in three parts, with
  fresh wording throughout:
  - Part 1: title, live badges (from the platform's template), referral
    callout, what make.fun is, who it is for, getting started, how it
    works.
  - Part 2: how to pick a first bounty (worked example + day-by-day
    plan + checklist), honest expectations, FAQ.
  - Part 3: links, how this guide was built, a final word, the
    Indonesian summary, the template footer.
- Fix the quota line while rewriting: 5 a day per competition, not 3.
- Keep the entrant's own referral code: `rjw8f9z8`.

## 4. Write the agent kit

- Write `agent-kit/SKILLS.md`, `SKILL-INDEX.md`, `ROUTING.md`,
  `WORKFLOW.md` (this file), and `AGENT-PROMPT.md` in this session,
  each with the write tool.
- Archive the skill files actually used into `agent-kit/skills.tar.gz`
  (the two local skill files). No file from any other entrant goes in.

## 5. Capture the screenshot

- Commit and push the rewrite first, so the public page shows the new
  README.
- Re-capture `screenshot.png` from the public repository page with the
  repo screenshot tool (headless Chrome, `--ignore-certificate-errors`).
- Check the PNG: it must be a real PNG, under 8 MB, under 16,000,000
  pixels, showing the repository page with the new README.

## 6. Commit and push

- Commit the rewrite, the agent-kit folder, and the new screenshot to
  the same repository, on `main`, as GitHub user juzfamilys (already
  logged in on this machine).
- Push, then confirm the commit is on the branch and the page shows the
  new README.
- Set the repository About from the requirements: website
  https://make.fun/bounty/bring-the-humans-02, topics `makefun`,
  `ai-agents`, `bounties`, `growth`, and a one-line description naming
  make.fun.

## 7. Bundle

- Write the user's typed instruction to a prompt file, word for word.
- Query the usage rows for this session's agent id and save them.
- Bundle this session only, with `--no-discover` and this session's
  file, `--prompt-origin typed`, the prompt file, the system prompt,
  harness `Muse app` 1.3, provider `meta`, model `muse-spark-1.3`,
  effort `default`, MCP `none`, and the usage file.
- Check the bundle: it must list this session, the system prompt, and
  the usage rows.

## 8. Pre-submit check

- Run the pre-submit check against the kit, the repository, and the
  bundle.
- Read every result. The transcript checks must pass: authored lines
  at least 30%, at most 40% unwritten, at least 2 file writes, at least
  5 assistant turns, usage priced, run record whole.
- Do not submit while any check is failing. Fix the exact cause first.

## 9. Submit

- Check the live quota for `bring-the-humans-02` again, immediately
  before submitting.
- Submit with the @nonton keypair, the repository URL, the pushed
  commit, a title, and the bundle.
- Save the submission id and the claim code.
- Never claim a prize. Claiming needs the user's explicit permission,
  and none was given for this entry.

## 10. Record

- Append the submission record (id, claim code, commit, bundle hash,
  pre-submit result, time) to the bounty-hunter claims file.
- Update the `bring-the-humans-02` entry in the seen file.
- Report the result to the user: submission id, claim code, commit,
  and what happens next (grading after the deadline, results on the
  bounty page).
