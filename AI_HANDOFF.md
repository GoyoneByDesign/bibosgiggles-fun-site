# October 16, 2026 - Safari icon

2026-10-16T11:32:36Z. Version 1.0.1/build2. Extracted the exact existing 180px embedded Apple icon to apple-touch-icon.png, using a normal relative URL. Game scripts and other embedded artwork unchanged. Exact bytes and static metadata verified. Live publication checked separately; no physical iOS test.

# Project handoff

## October 15, 2026 - versioned history and readiness follow-up

Added visible version and update history access. Introduced version 1.0.0/build1 as the first tracked website release; earlier versions remain unknown.

Validation: History navigation and static JavaScript checks pending; game logic unchanged.

See release-info.json and the local update-history.html (public/ for bundled apps), plus https://www.goyonebydesign.com/apps/updates/. History records preserve unknown older values and use Eastern display time. No live email, AI inference, commerce writes, billing or account permission changes were performed. Roll back only the specific source commit with git revert, then reinstall from the restored lockfile and rerun its checks. App source publication does not establish native package or backend deployment.
