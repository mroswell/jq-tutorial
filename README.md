# jq-tutorial
```
$ brew install jq
$ man jq
$ <congressmembers-114th.json jq . | less
$ <congressmembers-114th.json jq '.results[0].members' | less
$ <congressmembers-114th.json jq '.results[0].members' > members-114.json
```
