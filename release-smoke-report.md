# Release Smoke Test Evidence Report

## Pull request

- Number: #1
- Title: Add Release Checklist section and smoke workflow
- Changed files with additions/deletions:
  - README.md: +7 / -0 (status: modified)
  - release-smoke-report.md: +39 / -0 (status: added)

## Workflow run

- Run ID: 41258281900
- Workflow: Smoke Test (.github/workflows/smoke.yml)
- Run status: completed
- Run conclusion: success
- Job: smoke
  - Job status: completed
  - Job conclusion: success
  - Steps: Set up job (completed/success), Echo marker (completed/success), Complete job (completed/success)

## Inbox

No notifications were returned. The notifications listing call failed with the following verbatim error:

failed to list notifications: GET https://api.github.com/notifications?page=1&per_page=30: 403 Resource not accessible by personal access token []

## Teams

No team memberships were returned. The teams call succeeded and reported:

- Org: mcpmark-eval-liuhezi
- Teams: [] (empty list — no team memberships under this org)

## Computed stats

- Changed files: 2
- Total additions: 46
- Total deletions: 0
FINGERPRINT=98a30e4e7afebb4a90e1ba766eb6d0eafcbb1d10f1f6a849f83dcf8728194b88

## Gist fallback note

The secret gist creation attempt failed with the following verbatim error:

failed to create gist: POST https://api.github.com/gists: 403 Resource not accessible by personal access token []

The report is therefore preserved as release-smoke-report.md in this branch instead.
