# Containers

This repository contains several packages of projects that either don't have arm64 containers of themselves, or don't have containers at all.

This makes use of GitHub Actions automation, so releasing new versions is trivial:
- Go to the correct workflow.
- Click `Run workflow` and fill int he version.
- Press `Run workflow`.

Moments later the new version will be available under https://github.com/users/TrueBrain/packages?repo_name=containers.

## Containers

- [FlashMQ](https://github.com/halfgaar/FlashMQ): a fast light-weight MQTT broker.
  Although it has a Dockerfile available, it is not automatically published anywhere.
  Additionally, it doesn't contain arm64 support.
