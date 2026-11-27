# Instructions for AI agents

This is the organisation's root repo (`evocaslab/.github`). It is **public** and must stay public: GitHub shows
`profile/README.md` on the organisation page and gives `SECURITY.md` and `CONTRIBUTING.md` to every repo without its own
copy. Read `README.md` for what it holds.

## Rules

- Everything here is public. Never add a private repo name, a person's or client's name, a host, a path on a machine,
  a personal e-mail address or a secret.
- Commit with a GitHub noreply or an `@evocaslab.com` address, never a personal one.
- Keep each file short and in plain English. Text is CC BY 4.0, workflows and configuration `MIT OR Apache-2.0`
  (`README.md`, License).
- Pin every GitHub Action to a full commit SHA with the tag in a comment; the repo setting requires it.
- Gate: `prek run --all-files` must pass before a commit (the `gate` CI job runs the same). Never skip or weaken a hook.
- `main` takes direct pushes; its ruleset blocks force-pushes and deletion.
