---
title: How to Create a Pull Request
description: This is a step-by-step guide on how to create a pull request for SplashKit tutorials.
sidebar:
  label: 3. Pull Request Guide
  order: 3
---

## How to Create a Pull Request

Follow these steps to create a pull request for the SplashKit tutorials repository.

### 1. Check for Upstream Branches

First, check if the upstream branches are already added to your local repository.

```shell
git remote -v
```

### 2. Add Upstream Branches (if not present)

If the upstream branches are not added, you can add them using the following command. Replace `<repo-name>` with the actual repository name.

```shell
git remote add upstream https://github.com/thoth-tech/<repo-name>.git
```

#### Example with `splashkit.io-starlight` Repository

```shell
git remote add upstream https://github.com/thoth-tech/splashkit.io-starlight.git
```

### 3. Verify Upstream Branches

Verify that the upstream branches have been added successfully.

```shell
git remote -v
```

### 4. Push Your Branch

When you are ready to push your branch to create a pull request, push it to the `thoth-tech/splashkit.io-starlight` repository.

### 5. Open GitHub to Review the Pull Request

Open GitHub and navigate to the repository to review your pull request. Initially, the page will look like this:

![pull request](/splashkit/pull-request-fig1.png)

### 6. Change to the Correct Repository

To ensure your pull request is directed to the correct repository, change the settings at the top of the page.

- **Base Repository**: Set this to `thoth-tech/splashkit.io-starlight`.
- **Base Branch**: Set this to `main`.

![pull request](/splashkit/pull-request-fig2.png)

![pull request](/splashkit/pull-request-fig3.png)

### 7. Add Pull Request Template

Use the pull request template to provide detailed information about your request. Make sure to fill out all necessary fields and complete any required checks.

![pull request](/splashkit/pull-request-fig4.png)

### 8. Submit Your Pull Request

Once you have filled out the template and completed all required checks, submit your pull request for review.