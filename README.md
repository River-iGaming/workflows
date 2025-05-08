# workflows

## Tags

| Tag        | Description                                  |
| ---------- | -------------------------------------------- |
| dotnet-v3  | .NET libs/microservice/specs                 |
| node-v1    | node e.g. libs for node/lerna/cli/ngx etc... |
| fe-v5      | frontend app                                 |
| vor-latest | vor config checks                            |


```bash
# move tag
git tag -f v1 {new commit hash} (or use ui for this)
git push origin v1 -f
# shorthand
TAG=<TAG> && git tag -f $TAG && git push origin $TAG -f
```