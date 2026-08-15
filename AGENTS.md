# Golf Shot GPS development rules

- Before every commit that changes the application build, increment `APP_RELEASE.subversion` by exactly 1 and update `APP_RELEASE.date` to that build's date using English `DD MMM YYYY` format.
- Never increment `APP_RELEASE.major`, reset the subversion, or change to a new major version unless the user explicitly instructs it. Documentation-only commits that do not change the application build do not require a version increment.
- Development and publishing are restricted to `markus-bittner/golf-shot-gps`. Never push, publish, mirror, synchronize, transfer, configure deployment to, or otherwise modify `enginity-ch/golf-shot-gps` without an explicit user instruction for that specific action.
- Enginity URLs in application content are public-facing links only and do not authorize repository changes or deployment.
