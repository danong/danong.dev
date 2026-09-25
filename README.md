# danong.dev

My personal website. Theme forked from https://github.com/markhorn-dev/ and hosted on https://www.cloudflare.com/products/pages/.

## Shipping a change with Jujutsu

Run `./scripts/jj-ship` to push the current Jujutsu change on a stable
`ship/<change-id>` bookmark, open a pull request against `main`, wait for its
checks, and squash-merge it if they pass. After a successful merge, the script
deletes its bookmark, fetches `origin` until the merge reaches `main`, advances
the local `main` bookmark when that is a fast-forward, and returns the working
copy to `main@origin` when it shipped the current working copy. It accepts an
optional revision, such as `./scripts/jj-ship @-`. It requires `jj`, `gh`, and
GitHub CLI authentication.
