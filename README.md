## About

Repository serving as a template for application repositories.

## Repository

### Setup

1. "Use this template" button in GitHub to "Create a new repository".
1. Uncomment lines in `.github/workflows/ci.yaml`.
1. Replace `package` in `Dockerfile` with your package name.
1. Rename `package` in `src` to your package name.
1. Usually, you want to exclude `.env` file from your remote repository. To do so, run:
   ```shell
   git rm -r --cached .
   git add .
   git commit -m "chore: exclude .env"
   ```
