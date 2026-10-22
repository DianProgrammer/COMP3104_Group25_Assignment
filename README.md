# COMP3104 Group 25 Assignment

## Project Overview

This repository contains the Group 25 assignment for COMP3104 - DevOps at George Brown Polytechnic.

The project demonstrates version control, branching strategies, GitHub collaboration, pull requests, and continuous integration using GitHub Actions.

## Group Information

**Group:** 25

**Student:** Kiana Sepasian

**Student ID:** 101475855

**GitHub:** https://github.com/DianProgrammer

### Simulated Roles

With permission from Professor Pritesh Patel, I am completing this assignment independently while simulating two roles:

- **Team Lead:** Repository management, CI/CD configuration, documentation, and final submission.
- **Developer:** Creating and updating the required text files, maintaining commit history, and participating in the pull request workflow.

## Repository Structure

- `101475855_gb.txt` - Information about George Brown Polytechnic.
- `101475855_devops.txt` - Overview of DevOps concepts and practices.
- `101475855_sdlc.txt` - Importance of DevOps in the software development lifecycle.
- `.github/workflows/ci.yml` - GitHub Actions CI workflow.
- `.github/PULL_REQUEST_TEMPLATE.md` - Pull request template.

## Branching Strategy

The repository uses three branches:

- `master` - Main integration branch.
- `101475855-Kiana-TeamLead` - Team Lead responsibilities.
- `101475855-Kiana-Developer` - Developer responsibilities.

Changes are committed locally, pushed to GitHub, reviewed through pull requests, and merged into the main branch.

## Setup Instructions

Clone the repository:

```bash
git clone https://github.com/DianProgrammer/COMP3104_Group25_Assignment.git
```

Navigate to the project directory:

```bash
cd COMP3104_Group25_Assignment
```

View available branches:

```bash
git branch -a
```

## CI/CD Integration

GitHub Actions is configured in `.github/workflows/ci.yml`.

The workflow runs on Ubuntu and is triggered by pushes and pull requests.

It checks out the repository and executes basic commands to verify that the CI pipeline runs successfully.

## Learning Outcomes

Through this assignment, I am applying Git and GitHub concepts, maintaining meaningful commit history, working with separate branches, and understanding how CI/CD supports collaborative software development.

### Monitoring CI Pipeline

The CI pipeline is monitored through the Actions tab in GitHub.

Each workflow run shows whether the automated checks have passed or failed. A successful run confirms that the configured workflow completed its steps.

If a workflow fails, I can review the job logs to identify the problem, correct the configuration, and push the updated changes to trigger another run.

## Pull Request and Review Process

For this assignment, I am using separate branches to simulate the Team Lead and Developer roles, as approved by Professor Pritesh Patel.

Each branch is used to organize changes related to its responsibilities. After completing the required work, the changes are pushed to GitHub and submitted through pull requests.

Before merging a pull request, I will review the changed files, check the commit history, and confirm that the GitHub Actions workflow has completed successfully.

This process helps demonstrate how code review and branch management can support a more organized development workflow.
