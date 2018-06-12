+++
title = "Common Git Commands"
date = 2018-02-26T14:30:23
lastmod = 2018-06-12T18:08:00
draft = true

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

summary = "Usages of my most forgettable Git commands for reference."

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
# Use `caption` to display an image caption.
#   Markdown linking is allowed, e.g. `caption = "[Image credit](http://example.org)"`.
# Set `preview` to `false` to disable the thumbnail in listings.
[header]
image = ""
caption = ""
preview = true

+++

#### Reset remote repository to a previous commit

https://stackoverflow.com/questions/5816688/resetting-remote-to-a-certain-commit

```bash
git reset --hard <commit-hash>
git push -f origin master
```

#### Revert local changes

https://stackoverflow.com/questions/1146973/how-do-i-revert-all-local-changes-in-git-managed-project-to-previous-state

Revert unstaged changes
```bash
git checkout .  # revert all files
git checkout <path-to-file>  # revert a specific file
```

Revert changes made to the index (staged changes). This will also reset all unpushed commits.
```bash
git reset
```

Remove untracked files/directories
```bash
git clean -f  # remove files
git clean -fd  # remove directories
```

#### Change the most recent commit message

https://help.github.com/articles/changing-a-commit-message/

```bash
git commit --amend
```

If the commit is already pushed, then use
```bash
git push --force
```

