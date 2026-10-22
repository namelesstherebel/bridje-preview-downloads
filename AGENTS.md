# briDJe preview downloads

Signed staging installer publication and review context is in [README.md](README.md). Preserve existing artifacts, checksums, staging identity and review instructions. This review-policy change does not authorize building, signing, uploading or releasing installers, deployment, production purchases or changes to licensing.

## Review and validation

This repository is participating in the approved staged Pullfrog migration. Automatic Pullfrog supplies current-head expert review, including security. Until the owner verifies staged-cutover readiness, preserve existing review assignments and automatic-review settings. After readiness is verified, Pullfrog is the normal automatic reviewer and GitHub Reviewer is a manual fallback when needed, not a mandatory second review. Assess valid existing legacy findings; a provider name or skipped review is not evidence of coverage.

Use the actual `pullfrog-approval` verdict from the verified Pullfrog app on the current head once its emission and required rule are established. The `pullfrog` workflow/job name alone is not that verdict; never assume or require an unverified, never-emitted check. Preserve all other applicable checks and safety, visual, release and owner-acceptance gates. Do not bypass protections or change settings under these instructions.

The current branch writer handles material findings, inspects corrections, verifies applicable source/secret checks and actual resulting-head CI, then performs a normal merge pinned to the reviewed head. Report missing, skipped, errored and non-applicable checks accurately. Source scanning is not dependency-advisory coverage; saved configuration is not proof of live review or successful provider operation.

Preserve Cubic integration, reviews and checks entirely. Retain independent Codex security review as complementary coverage; do not narrow Pullfrog's security lenses or remove security checks as duplicates. Shared expert prompts and provider settings are maintained separately, not copied or changed here.

Pullfrog fixes are opt-in, bounded handoffs only. The sole writer must explicitly hand off a contained correction and pause their own branch edits, inspect the returned diff, then obtain resulting-head CI and fresh review before normal merge. No blanket or unattended autofix is authorized; product and larger changes retain their assigned implementation owner.
