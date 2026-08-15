# Golf Shot GPS development rules

- Before every commit that changes the application build, increment `APP_RELEASE.subversion` by exactly 1 and update `APP_RELEASE.date` to that build's date using English `DD MMM YYYY` format.
- Never increment `APP_RELEASE.major`, reset the subversion, or change to a new major version unless the user explicitly instructs it. Documentation-only commits that do not change the application build do not require a version increment.
- Development and publishing are restricted to `markus-bittner/golf-shot-gps`. Never push, publish, mirror, synchronize, transfer, configure deployment to, or otherwise modify `enginity-ch/golf-shot-gps` without an explicit user instruction for that specific action.
- Enginity URLs in application content are public-facing links only and do not authorize repository changes or deployment.

## Enginity production snapshot releases

- Every Enginity publication requires explicit user authorization for that specific release. Never publish merely because a development task is complete.
- At the start of every authorized release task, restate and follow this flow: `markus-bittner/golf-shot-gps` → approved, tested exact file snapshot → copy only required production/public files → `enginity-ch/golf-shot-gps` → one simple production release commit.
- Never mirror, merge, rebase, or otherwise transfer Markus Git history into Enginity. Enginity is production-only and contains snapshot/maintenance commits, not development commits.
- Never make a new application build for publication, modify application files during publication, rebuild the app, or increment its version at release time.
- Before copying, verify the Markus source state is the explicitly approved and tested version. Copy required production files exactly as-is, verify their content, and use a simple Enginity commit such as `Release V1.2`.
- Keep Enginity limited to the running app, GitHub Pages requirements, public user documentation, required legal/license information, and public app assets. Do not copy development instructions, tests, local configuration, logs, temporary artifacts, editor settings, or other development-only metadata.
