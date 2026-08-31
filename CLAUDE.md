# lazerg/lazerg

GitHub profile README. `README.md` is the only content that matters, it renders on https://github.com/lazerg.

## Rules

- "Latest contributions" lists every merged PR by this account in the `laravel/*` org, split into two sections:
  `laravel/framework` and `Others in the Laravel ecosystem`. No cap, no per-repo limit, show all of them.
- Sort each section by merge date, newest first. That is the only sort key, don't group by repo.
- Format per entry: `- [repo#N](url): title` (no `laravel/` prefix inside the `laravel/framework` section, since the
  section header already says it).
- To refresh: `gh search prs --author=lazerg --owner=laravel --merged --json repository,number,title,url`, then
  `gh pr view <n> --repo laravel/<repo> --json mergedAt` per PR to get the real sort key (search results' `updatedAt`
  is not reliable for ordering).
- Keep the rest of the file (intro, contact line, profile-view badge) as-is unless explicitly asked to change it.
