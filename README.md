# Debarghya's Modded Profile

```bash
PS1='${debian_chroot:+($debian_chroot)}\[\e[01;32m\][\[\e[m\]\[\e[01;31m\]\u\[\e[m\]\[\e[01;33m\]@\[\e[m\]\[\e[01;32m\]\h\[\e[01;32m\]]\[\e[m\]:$([ $? == 0 ] && echo ✅ || echo ❌) \[\e[01;36m\](\W)\[\e[m\]\[\e[m\]\[\e[01;34m\]\n$(__git_ps1 2>/dev/null)$([[ $(git status --porcelain 2>/dev/null | wc -l) == 0 ]] && echo  || echo "*") →  \[\e[m\]'
```
