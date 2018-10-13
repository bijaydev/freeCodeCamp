---
title: Git lfs (Large File System)
---

## Git LFS
In some cases, we may need to edit very large files (size >2MB), Git LFS helps to do the same efficiently by downloading the relevant 
versions of the large files at the time of checkout process rather than during cloning or fetching.

```shell
$ git lfs install
$ git lfs pull
$ git lfs fetch --all
```
### More Information:  <a name="more-information"></a>
- The `git lfs` command: <a href='https://www.atlassian.com/git/tutorials/git-lfs' target='_blank' rel='nofollow'>Webpage</a>
