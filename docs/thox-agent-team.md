# THOX GitHub Agent Team

## Review coverage

The repository must review new and changed issues, issue comments, and pull requests. The workflow also supports manual validation and a daily policy check.

## Safe merge gates

A pull request may be merged only when all of the following are true:

- The pull request is open, non-draft, and mergeable.
- Every required check has completed successfully.
- Branch protection permits the selected merge method.
- The expected head SHA matches immediately before merge.
- Unresolved review threads and requested changes are cleared.
- Security-sensitive, authentication, permissions, dependency, release, or infrastructure changes receive human review.
- Fork pull requests are never merged automatically.

The policy workflow validates coverage and documentation only. It does not bypass protections or perform merges.

## Branch pruning

After a pull request is merged, delete its head branch only when it is:

- hosted in this repository,
- not the default branch,
- not protected,
- not a release, maintenance, or long-lived integration branch, and
- no longer referenced by another open pull request.

Prefer GitHub's automatic deletion of merged head branches. Any janitor automation must use least-privilege contents write access and re-check these conditions immediately before deletion.
