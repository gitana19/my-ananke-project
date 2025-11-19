+++
title = "First Post"
date = 2025-11-18
tags = ["sample", "hugo"]
categories = ["blog"]
+++
Here’s my first post.
Now I want to change something here to see if the **"hard reset"** of the local branch to match the remote has gone well.

```toml
git fetch origin
git reset --hard origin/main
(optional) git clean -fd
```

- **git clean -fd** removes all untracked files and directories from your working directory.
- The listed folders (assets/, data/, i18n/, layouts/) were **not tracked by git** (i.e., not part of any commit).
- After this, those folders are **deleted locally**.

![some quad sky image](/my-ananke-project/images/sky_quad.png)
![dino quad image](/my-ananke-project/images/dino_quad_small.png)
