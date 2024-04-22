# changeset-test

Commands available:

| Command               |                                                                        |
|-----------------------|------------------------------------------------------------------------|
| `pnpm add-changeset`  | Create a changeset within this repo                                    |  
| `pnpm push-with-tags` | Push this repo to there remote with any locally created tags for `git` |
| `pnpm create-tag`     | Create a tag within this repo for Github                               |
| `pnpm create-version` | Create a version for this repo based on the changesets                 |

### Learning

- When using the add changeset file it will create a randomly named file within `./changeset`
- These files get deleted when you create a version, to save on disk space
- Tags normally get created when publishing to `npm`, but there is another way to just create the tag
- Using the `--follow-tags` option in `git` will push any tags created locally to the repo
- 
