repo: Web3Lion/compsci_classpages
branch: main
## Last sync
date: 2026-08-27T00:00:00Z
commit: (user manually pushed all prior changes — no new commit sha known)

### Updated in this project (NOT yet pushed to GitHub)
- Day-0 "already submitted" gating + prefill/resync fix — apcsp/student-info.html, cyber1/are-you-a-target.html, cyber2/are-you-a-target.html
- AP CSP Exam Reference Sheet link added to homepage — config.js
- Adversary fix: cyber1 SPECTER → VECTOR (config, gate screen, boss finale, 8 flag/cert pages) — config.js, gate-art.js, ctf.js, cyber1/*.html
- Voice tuner Reset button now restores "Google UK English Female" default — ctf.js
- AP CSP Module 1 flags: 7 new leveled flag sets + 3 interactive captures + relabeled all Module 1 flags to match lesson order (1a, 2a/2b, 3a, 4a, 6a, 7a, 9a/9b, 12e, 13e, 14a, 15e, 16a, 17e, 21e) — config.js, answers.local.js
- External-account sign-in loop fix: added ctf_allowed_emails_public() RPC so the client-side sign-in gate sees emails added via teacher.html Settings (previously only checked a static config array); removed the `hd` domain restriction on the Google account chooser, which could race-hide a newly-allowed external account — auth.js, supabase/allowed-emails.sql (must be re-run in Supabase SQL editor)

NOTE: everything from before this session was manually pushed by the user. Only the items above are still pending.

## Screen map
| Screen | Repo files |
|---|---|
| Course homes | apcsp/index.html, cyber1/index.html, cyber2/index.html, web3/index.html |
| Simulators hub | simulators/index.html + simulators/*.html |
| Config | config.js |
