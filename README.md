# CI/CD Setup for My Website

This repository demonstrates a Continuous Integration (CI) and Continuous Deployment (CD) workflow for a simple HTML/CSS/JS website using GitHub Actions and GitHub Pages

# Overview

- Every push to the main branch automatically triggers the CI/CD workflow.
- GitHub Actions runs a temporary Ubuntu VM, checks out the repository, and deploys the website to GitHub Pages.
- Workflow permissions ensure the Action can read the repository contents and write to GitHub Pages.
- Future updates (HTML/CSS/JS changes) are automatically deployed without manual intervention.
