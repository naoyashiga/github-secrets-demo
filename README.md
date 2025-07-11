hello

# Fetch repository events

```bash
curl -L \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/repos/naoyashiga/github-secrets-demo/events
```

resetしたcommitを確認できた。

```
https://github.com/naoyashiga/github-secrets-demo/commit/eb57bf9e296be478a704949dd79cad3b7a8d71aa
```