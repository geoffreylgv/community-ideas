# Contributing to Community Ideas

Thank you for your interest in contributing to Community Ideas!

This guide explains how to contribute to the project using Git and GitHub.

## 1. Prerequisites

Before getting started, make sure you have:

* A [GitHub account](https://github.com/).
* [Git](https://git-scm.com/downloads) installed on your computer.
* A terminal or command-line interface.

Check whether Git is installed:

```bash
git --version
```

## 2. Configure Git

If you have never used Git on your computer, configure your name and email address:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Use the name and email address you want associated with your commits.

## 3. Fork the repository

1. Open the Community Ideas repository on GitHub.
2. Click **Fork**.
3. Create a fork under your GitHub account.

Your fork is your personal copy of the project, where you can make changes without modifying the original repository directly.

## 4. Clone your fork

Replace `YOUR-USERNAME` with your GitHub username:

```bash
git clone https://github.com/YOUR-USERNAME/community-ideas.git
cd community-ideas
```

## 5. Create a branch

Create a separate branch for your contribution:

```bash
git switch -c add/my-contribution
```

Choose a descriptive branch name, for example:

```bash
git switch -c add/python-workshop-idea
```

## 6. Make your changes

Open the project folder in your preferred editor.

For example, with Visual Studio Code:

```bash
code .
```

Make your changes locally. You can add a new idea, improve the documentation, fix an error, or suggest an improvement.

Before continuing, review your changes:

```bash
git status
git diff
```

## 7. Stage and commit your changes

Stage the files you want to include:

```bash
git add .
```

Create a commit with a clear message:

```bash
git commit -m "Add a Python workshop idea"
```

A commit records your changes locally.

## 8. Push your branch to GitHub

Push your branch to your fork:

```bash
git push -u origin add/my-contribution
```

If you used a different branch name, replace `add/my-contribution` with your actual branch name.

Your changes are now available on your GitHub fork.

## 9. Open a Pull Request

1. Open your fork on GitHub.
2. Click **Compare & pull request**, or use the prompt displayed after pushing.
3. Make sure the base repository is the original Community Ideas repository.
4. Add a descriptive title and explain your changes.
5. Submit your Pull Request.

The maintainers will review your contribution and may request changes before merging it.

## 10. If you need to make changes

If the maintainers request changes, edit your files locally and run:

```bash
git add .
git commit -m "Update contribution based on feedback"
git push
```

Your existing Pull Request will update automatically.

## Important notes

* Do not push directly to the original repository unless you have explicit write access and have been asked to do so.
* Do not commit passwords, API keys, tokens, or other secrets.
* Keep your contribution focused and use descriptive commit messages.
* You can contribute in English or French.
* Opening a Pull Request does not guarantee that it will be merged.

Thank you for helping us build together!