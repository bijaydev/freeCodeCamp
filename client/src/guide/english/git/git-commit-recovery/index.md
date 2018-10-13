---
title: Git Commit recovery
---

## Git commit recovery
Lost commit in rebase can be recovered using the following commands:

```shell
$ git log ORIG_HEAD
$ git branch xyz ORIG_HEAD
$ git checkout –b xyz_new

```
### More Information:  <a name="more-information"></a>
- The `git commit recovery` command: <a href='https://stackoverflow.com/questions/25212573/is-there-a-way-to-recover-a-commit-that-was-accidentally-skipped-during-a-rebase' target='_blank' rel='nofollow'>Webpage</a>



     
