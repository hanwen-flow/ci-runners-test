A trivial bazel repository to demonstrate CI runners configuration


# GitHub actions

Example workflows are listed under
[.github/workflows](.github/workflows). These are used for QA on our
CI runners, so they run against a cluster called `local`. For
production use, substitute the name of the production cluster.

# Buildkite

Example YAML steps for buildkite are in the file
[buildkite.yaml](buildkite.yaml). Again, substitute an actual cluster
name for `local`.