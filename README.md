A trivial bazel repository to demonstrate CI runners configuration

The configurations for warm bazel runners are found under

   .github/workflows/main-arm64.yml
   .github/workflows/main-x64.yml

A few other configurations are here for testing, in particular:

   fail-*.yml - always fails
   quick-*.yml - for debugging: just runs 'bazel info'

