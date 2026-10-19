# Portfolio project instructions and change log

## Project context

- Owner: Franklyn Daufa.
- Live website: https://daufa.github.io/
- GitHub repository: https://github.com/Daufa/Daufa.github.io
- Publishing branch: `main`. Pushing site changes to this branch publishes through GitHub Pages.
- Use this `Portfolio` checkout for future work. The older checkout at `../rea/outputs/portfolio` and HTML snapshots under `../rea/work` are historical copies, not the working source.
- Homepage content, styles, and scripts: `index.html`.
- Workflow demo: `agent-supervisor/index.html`.
- Assets: `favicon.svg`, `social-preview.png`; retain `.nojekyll`.
- The site has no resume download link. Resume work was explicitly excluded from the latest website update; do not add or update a resume unless requested.

## Editing preferences

- Keep changes within the user's requested scope. For wording edits, preserve layout, HTML structure, CSS, JavaScript, links, and unrelated text.
- Use direct, factual language. Remove unnecessary hedging without implying results or validation that have not happened.
- Avoid unnecessary hyphens in prose. Established examples: hands on, anomaly detection, multitenant, multitenancy, code review, Multiagent systems, cross review, diagnostic write, age based, self serve, quote preparation, proposal drafting, cloud based, LLM integrated, AI drafted, semiprofessional, and Non Finance.
- Preserve technical identifiers such as `SHA-256`, URLs, filenames, CSS classes, and code syntax. Do not perform a blanket hyphen replacement.
- The LLM Council benchmark compares against one model within the same budget. Its paragraph already explains this; do not add a redundant final sentence or claim an unverified benchmark result.
- Agent Supervisor copy describes an offline test suite and a live run that caught and fixed a bug. Do not imply repeated successful runs without evidence.
- Preserve commercial impact figures and the Workflow demo link unless the user specifically requests changes to them.

## Workflow for future sessions

1. Read this file and inspect Git status and recent commits. Preserve any existing user changes.
2. Fetch `origin` before editing. Check for newer remote commits and reconcile safely; do not overwrite or reset local work.
3. Apply the requested changes to the current source. If the user asks to discuss first, keep the work read-only until they authorize edits.
4. Review the diff and run checks appropriate to the change. For wording-only work, check that structure, scripts, styles, links, and numbers remain unchanged. Preview visually when layout or styling changes.
5. Update the change log below for completed work. Record the date, changes, validation, and publishing status. Use Git history for exact commit IDs; never invent them.
6. When publishing is requested, commit only relevant files and push to `origin/main`. Otherwise, report that changes remain local.
7. After pushing website changes, allow GitHub Pages time to deploy and fetch the live HTML to verify the new content. Do not equate a successful push with a confirmed live deployment.
8. If someone sees old content, check the actual live response first. Browser, CDN, and AI retrieval caches can differ. A version query string can help diagnose caching, but does not guarantee a third-party tool refreshes its copy.

This file is durable project context, not a transcript or automatic memory of other chats. Keep it concise and factual. New user instructions override older preferences recorded here.

## Change log

### 2026-10-18 — Dedicated checkout and session continuity

- Created this dedicated `Portfolio` checkout from the existing GitHub repository, at commit `cc3444d` with a clean working tree.
- Added this instruction file and historical change log at the user's request so future sessions can continue the project.
- Documentation only; no website content or assets changed. Check Git history and remote status for this file's commit and publishing state.

### 2026-10-18 — Portfolio wording update

- Commit: `cc3444d` — Refine portfolio wording and remove hedging.
- Removed the redundant final LLM Council sentence about the pending comparison; retained the existing benchmark description.
- Simplified Agent Supervisor validation wording and removed the "Early days" qualification; changed "per-turn timeouts" to "a timeout on every turn" and retained `SHA-256`.
- Applied the requested prose hyphen corrections in metadata, the hero tagline, project cards, and About content. Updated the prior CGA workshop wording to "helped present a CGA workshop on gas measurement".
- Preserved unrelated copy, commercial figures, links, page structure, styles, and scripts. No resume changes.
- Validation: reviewed the diff, passed `git diff --check`, and verified unchanged HTML structure (except description metadata), styles, scripts, links, and numbers.
- Published to `origin/main`; subsequently fetched the live homepage and confirmed it matched the committed file byte for byte. A later direct check also matched despite reports of stale content from another retrieval tool.

### 2026-09-23 — Initial publication and refinements

The following entries are reconstructed from Git commit history:

- `facdf94` — Publish portfolio with commercial proof and accessible project navigation.
- `09b9be7` — Host Agent Supervisor workflow demo and link from portfolio.
- `0eac5f0` — Link LLM Council to its GitHub repository.
- `1355f58` — Focus portfolio introduction on work and customer ownership.
- The original checkout's remote reflog recorded successful pushes for all four commits.
