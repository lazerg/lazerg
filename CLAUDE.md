# lazerg/lazerg

GitHub profile README. `README.md` is the only content that matters, it renders on https://github.com/lazerg.

## Rules

- "Latest contributions" has one section per watched repo, each its own `**\`owner/repo\`**` heading (repo name in
  backticks) followed by a list, in this fixed order:
  1. `php/php-src`: the 5 most recently merged PRs by this account, hard cap of 5.
  2. `laravel/framework`: every merged PR by this account, no cap.
  3. `symfony/symfony`: the 5 most recently merged PRs by this account, hard cap of 5.
  4. `nodejs/node`: the 5 most recently merged PRs by this account, hard cap of 5.
  5. `vuejs/core`: the 5 most recently merged PRs by this account, hard cap of 5.
- Sort each section by merge date, newest first. That is the only sort key.
- Format per entry: `- [#N](url): title`.
- To refresh a section: `gh search prs --author=lazerg --repo=<owner/repo> --merged --json number,title,url`, then
  `gh pr view <n> --repo <owner/repo> --json mergedAt` per PR to get the real sort key (search results' `updatedAt`
  is not reliable for ordering).
- Keep the rest of the file (intro, contact line, profile-view badge) as-is unless explicitly asked to change it.
