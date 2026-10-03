# Claude Code Operating Authority

Routine development is pre-authorized. Work continuously and do not ask for permission for ordinary reversible engineering tasks already allowed by `.claude/settings.json`, including reading/searching, editing files, running tests/builds/linters/formatters, dependency tooling, Git inspection, staging, and commits.

Use the least-destructive effective action. Verify work with tests, command output, diffs, hashes, or other concrete evidence. If a routine command is blocked only because it is not yet represented by the allow-list, prefer the closest already-authorized safe equivalent and record the missing permission for later policy expansion rather than repeatedly interrupting the user.

Stop and request explicit approval only for materially consequential or irreversible actions: destructive data loss; force-push/history rewriting; destructive database/schema/data operations; exposing, rotating, or replacing credentials/secrets; changing security/privacy/access controls; purchases or paid-resource commitments; external communications or commitments made as the user; or production actions with a meaningful irreversible blast radius.

Project-specific security, governance, secret-scanning, and destructive-command hooks remain authoritative and must not be bypassed.

The objective is high autonomy with bounded risk: execute routine work, verify it, continue to the next dependent task, and escalate only genuine decision boundaries.
