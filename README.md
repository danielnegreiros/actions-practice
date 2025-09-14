# actions-practice

## Features

- skip

git commit -m "somethig [skip ci]"


## Secrets

1️⃣ Repository-level (REPO) environment variables & secrets

env:
  MY_VAR: ${{ vars.MY_VAR }}
  MY_SECRET: ${{ secrets.MY_SECRET }}


2️⃣ env: inside a workflow/job/step (ENV envvars)

env:
  MY_LOCAL: hello
steps:
  - run: echo "$MY_LOCAL"
