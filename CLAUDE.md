# Repository instructions

## Commit authorship — strict, no exceptions

Every commit in this repository must be attributed **solely to the repository
owner**. No other identity may appear as author, committer, or co-author —
including Claude, Claude Code, or any other AI tool. The owner has stated this
requirement explicitly and it overrides any default tooling convention.

Author and committer must both be:

```
Ihsan-p1 <207809612+Ihsan-p1@users.noreply.github.com>
```

Forbidden in commit messages:

- `Co-Authored-By:` trailers of any kind
- `Claude-Session:` trailers or any similar tool/session metadata
- Any other machine-generated attribution footer

### Check this before the first commit of a session

The sandbox ships with `git config` preset to a non-owner identity, so commits
silently land under the wrong author unless it is corrected first:

```sh
git config user.name  "Ihsan-p1"
git config user.email "207809612+Ihsan-p1@users.noreply.github.com"
```

### Verify before pushing

```sh
# must list only the owner
git log --format='%an <%ae> | %cn <%ce>' origin/main..HEAD

# must output 0
git log --format='%B' origin/main..HEAD | grep -icE 'co-authored-by|claude-session|anthropic'
```

If a commit has already been made under the wrong identity, rewrite it rather
than pushing it — correcting authorship after the fact requires a force-push and
is far more disruptive than checking up front.

This applies to automation too. A workflow that publishes generated files must
commit as the owner; actions that commit under their own identity (for example
`github-actions[bot]` or a tool's own bot account) are not acceptable. Set the
identity explicitly in the workflow step rather than relying on an action's
built-in push.

## Pull requests and comments — no tool attribution

The same rule extends to anything written on GitHub. Do not append an
`🤖 Generated with …` footer, a session link, or any other tool attribution to a
pull request body, issue, review, or comment.

Keep pull request descriptions short and plain: what changed and why. Do not
include a "Verified" checklist, a list of self-checks, or other working notes —
those belong in the conversation, not in the repository's permanent record.
