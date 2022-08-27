# Linux Tweet App CICD Pipelines

The `ci.yml` manifests has 3 jobs that handles the CI Pipeline.

- The first job builds the app's docker image on every pull request to main.
- The second job builds, tag image with commit hash and push to GCP Artifact Registry on every commit to `main` branch.
- The third job builds, tag image with the tagged version and push to GCP Artifact Registry on every tag to `main` branch.
