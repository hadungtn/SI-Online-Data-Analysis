# SI-Online-Data-Analysis
Enhancing Production Quality in Shoe Manufacturing: A Data-Driven Approach Using SI Online Metrics
## Table of Contents
- [Project Overview](#project-overview)
- [Version Control Overview](#version-control-overview)
- [Repository Structure](#repository-structure)
- [Branching Strategy](#branching-strategy)
- [Commit Guidelines](#commit-guidelines)
- [Pull Requests](#pull-requests)
- [Tagging and Releases](#tagging-and-releases)
- [Contributing](#contributing)
- [Issues and Bug Reporting](#issues-and-bug-reporting)
- [Getting Started](#getting-started)
- [FAQs](#faqs)
- [Contact Information](#contact-information)

## Project Overview
This repository contains all files and documents related to the SI Online Data Analysis project. The project focuses on analyzing and visualizing data to assess the quality of shoe manufacturing processes using the DPPM (Defective Parts Per Million) metric. The primary tool used for this analysis is Power BI.

## Version Control Overview
This project uses Git for version control to ensure that all changes are tracked, and multiple team members can collaborate effectively. Git helps manage changes to source files, track the history of modifications, and maintain the integrity of the project over time.

## Repository Structure
The repository is structured to facilitate easy navigation and collaboration. Here's an overview of the key directories:

- **/data/**: Raw and processed datasets used for analysis.
- **/scripts/**: Power BI scripts, DAX formulas, and any automation scripts.
- **/docs/**: Documentation related to the project, including the project plan, requirements, and design documents.
- **/reports/**: Final reports and visualizations generated from the analysis.
- **/notebooks/**: Jupyter notebooks or other exploratory data analysis files.
- **/tests/**: Unit tests and scripts for testing the analysis pipeline.
- **/output/**: Output files, such as exported reports or datasets.

## Branching Strategy
We follow a branching strategy to manage development and ensure stability:

- **main**: The main branch contains the stable version of the project. Only thoroughly tested and reviewed code is merged into this branch.
- **dev**: The development branch is used for integrating new features and updates. It is the working version that may undergo frequent changes.
- **feature/{feature-name}**: Feature branches are created from `dev` for developing specific features. These branches should be named according to the feature or task being worked on, e.g., `feature/add-dpp-analysis`.
- **bugfix/{bug-name}**: Bugfix branches are created from `main` or `dev` to address specific bugs. These branches should be named according to the bug being fixed, e.g., `bugfix/fix-chart-rendering`.
- **release/{version-number}**: Release branches are used to prepare a new production release. This branch is used for final testing and documentation updates before merging into `main`.

## Commit Guidelines
To maintain a clean and understandable commit history, please follow these guidelines:

- **Write meaningful commit messages**: Clearly describe the purpose of the commit. Use present tense and be concise.
  - Example: `Add DPPM calculation formula in Power BI`
- **Make atomic commits**: Each commit should represent a single logical change. Avoid mixing unrelated changes in one commit.
- **Include references to issues or tasks**: If the commit addresses a specific issue, include the issue number in the commit message.
  - Example: `Fix data loading bug in Power Query #45`
- **Use proper tags in commit messages**: Indicate the type of change using tags like `[Fix]`, `[Feature]`, `[Refactor]`, `[Docs]`.

## Pull Requests
All changes to the `main` and `dev` branches should be made through Pull Requests (PRs). Follow these steps:

1. **Create a PR**: Once your work on a feature or bugfix branch is complete, create a PR to merge your changes into `dev` or `main`.
2. **Describe the PR**: Provide a detailed description of the changes, why they are necessary, and how they were tested.
3. **Request reviews**: Assign at least one other team member to review your PR. Ensure that the changes are reviewed and approved before merging.
4. **Address feedback**: If reviewers request changes, address them promptly and update the PR.

## Tagging and Releases
We use Git tags to mark significant versions or releases of the project:

- **Version tags**: Tags should follow semantic versioning, e.g., `v1.0.0`, `v1.1.0`.
- **Release notes**: Each release should include detailed notes about what has changed, new features, and any known issues.
- **Tagging process**: After a PR is merged into `main` for a release, a tag should be created to mark the version.

## Contributing
We welcome contributions from all team members. To contribute:

1. **Fork the repository**: Create your own fork of the repository and work on your changes there.
2. **Create a branch**: Create a new branch for your feature or bugfix.
3. **Make changes**: Implement your changes and commit them with clear messages.
4. **Submit a PR**: Push your branch to the repository and submit a pull request.

## Issues and Bug Reporting
If you encounter any issues or bugs, please report them using the repository's issue tracker:

1. **Create a new issue**: Provide a descriptive title and detailed information about the issue.
2. **Label the issue**: Use appropriate labels such as `bug`, `enhancement`, or `question` to categorize the issue.
3. **Assign the issue**: If you are working on the issue, assign it to yourself or the relevant team member.

## Getting Started
To get started with the project:

1. **Clone the repository**: `git clone https://github.com/hadungtn/si-online-data-analysis.git`
2. **Install dependencies**: Follow the instructions in the `docs/setup.md` file to install any necessary dependencies.
3. **Explore the project**: Review the data, scripts, and documents to familiarize yourself with the project structure.
4. **Start contributing**: Pick a task from the issue tracker or start with your assigned work.

## FAQs
**Q1: How do I update my local repository with the latest changes?**
- Use `git pull` to fetch and merge changes from the remote repository.

**Q2: What should I do if I encounter a merge conflict?**
- Resolve conflicts manually in your text editor, then commit the changes.

**Q3: How do I revert a commit?**
- Use `git revert <commit-hash>` to create a new commit that undoes the changes.

## Contact Information
For any questions or further assistance, please contact [Dzung] at [hadung.vn@outlook.com].

---

