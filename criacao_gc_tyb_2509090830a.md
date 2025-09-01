---
date: 2025-09-01
ref: 2509090830a
tags:
---
# Criação gc_tyb

```
# CRIACAO DO REPOSITORIO GITHUB

git init
git lfs install
git add .
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/schlinux/roamer_twu.git
git push -u origin master

# Setar branch develop
git branch develop
git checkout develop
git push --set-upstream origin develop

# Para copiar para drive exFAT ou NTFS:

time rsync -az --info=progress2 --delete --no-perms --no-owner --no-group --no-times /mnt/work-tgr/git_we3_server/git_we3_git/git_we3/roamer_twu/ /mnt/netac-tgi/roamer_twu 2>&1
```

---

##EOL
