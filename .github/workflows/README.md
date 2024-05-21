# Workflows

## nightly_cleanup.yml

The required token environment variable provided from the secret `secrets.DELETE_ARTIFACTS_PAT` needs to have the following access requirements:

- `repo`
  - `repo:status`
  - `repo_deployment`
  - `public_repo`
  - `repo:invite`
  - `security_events`

FIXME: It may not require all of the access requirements shown above. Clean this up at a future point in time.
