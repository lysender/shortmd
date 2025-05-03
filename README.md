# shortmd

GIT command aliases

## Installation

For Windows, copy the batch files from `cmd` folder to your executable path.

- `gff` - git diff
- `gpl` - git pull
- `gt` - git status
- `gtc` - git add then commit 
- `gtp` - git push

For Linux, copy the contents of `alias.sh` to your `~/.bashrc` or `~/.zshrc`.

```bash
alias gff='git diff'
alias gpl='git pull'
alias gt='git status'
alias gtc='git add . && git commit -m'
alias gtp='git push'
alias nb='npm run build'
alias nt='npm run test'
```
