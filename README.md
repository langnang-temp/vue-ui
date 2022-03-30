# Vue Template

- `Vue`: Vue
- `Router`: Vue-Router
- `State`: Vuex
- `Request`: axios
- `FontIcon`: FontAwesome
- `JavaScript`: Lodash
- `Date`: moment

## Branches

```sh
┌───────────────────────┐       ┌─────────────────────────┐       ┌───────────┐       ┌──────────┐
|                       |       |                         |       |           |       |          |
|  @langnang-temp/node  | ====> |    @langnang-temp/vue   | ====> |  develop  | ====> |  master  |
|  Sync from template   |       |      Sync to remote     |       |           |       |          |
└───────────────────────┘       └─────────────────────────┘       └───────────┘       └──────────┘
```

### Sync to remote

```sh
# add remote url
git remote set-url --add origin [url]
# checkout the branch for sync
git checkout [branch]

git pull
# force push
git push -f
```
