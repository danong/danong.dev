# danong.dev

My personal website. Theme forked from https://github.com/markhorn-dev/ and hosted on https://www.cloudflare.com/products/pages/.

## Shipping a change with Jujutsu

Run `./scripts/jj-ship` to push the current Jujutsu change on a `ship/*` bookmark,
open a pull request against `main`, wait for its checks, and squash-merge it if
they pass. The script accepts an optional revision, such as
`./scripts/jj-ship @-`. It requires `jj`, `gh`, and GitHub CLI authentication.
