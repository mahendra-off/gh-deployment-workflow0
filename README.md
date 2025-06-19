# GitHub Actions Deployment Workflow

This project demonstrates a simple GitHub Actions workflow to deploy a static website to GitHub Pages. The website consists of an `index.html` file that is automatically deployed whenever changes are pushed to the `main` branch.

## Project Structure
- `index.html`: The static website file.
- `.github/workflows/deploy.yml`: The GitHub Actions workflow file.
- `README.md`: Project documentation.

## How It Works
- The workflow triggers on every push to the `main` branch that modifies `index.html`.
- It checks out the code, sets up GitHub Pages, and deploys the `index.html` file.
- The website is accessible at `[https://<username>.github.io/gh-deployment-workflow0/](https://github.com/mahendra-off/gh-deployment-workflow0/edit/main/README.md)`.

## Setup Instructions
1. Clone this repository.
2. Make changes to `index.html` and push to the `main` branch.
3. The workflow will automatically deploy the changes to GitHub Pages.
