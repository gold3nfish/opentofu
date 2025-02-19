# OpenTofu Documentation

This directory contains the portions of [the OpenTofu website](https://opentofu.org) that pertain to the core functionality, excluding providers and the overall configuration.

## Suggesting Changes

You can [submit an issue](https://github.com/opentofu/opentofu/issues/new/choose) with documentation requests or submit a pull request with suggested changes.

Click **Edit this page** at the bottom of any OpenTofu website page to go directly to the associated markdown file in GitHub.

## Modifying Sidebar Navigation

You must update the sidebar navigation when you add or delete documentation .mdx files. If you do not update the navigation, the website deploy preview fails.

To update the sidebar navigation, you must edit the appropriate `nav-data.json` file. This repository contains the sidebar navigation files for the following documentation sets:

- OpenTofu Language: [`language-nav-data.json`](https://github.com/opentofu/opentofu/blob/main/website/data/language-nav-data.json)
- OpenTofu CLI: [`cli-nav-data.json`](https://github.com/opentofu/opentofu/blob/main/website/data/cli-nav-data.json)
- Introduction to OpenTofu: [`intro-nav-data.json`](https://github.com/opentofu/opentofu/blob/main/website/data/intro-nav-data.json)

## Previewing Changes

Currently, you can preview your changes through the [opentofu/opentofu.org](https://github.com/opentofu/opentofu.org/blob/main/README.md) repository.

Follow the [Getting Started](https://github.com/opentofu/opentofu.org/blob/main/README.md#getting-started) guide.
If you would like to fetch the documentation from another repository and another branch, you can run the make command with REPO_URL and BRANCH arguments before starting the development server:
```
make REPO_URL="<your_forked_repo_url>" BRANCH="<branch_name>"
```

## Deploying Changes

Coming soon: Documenting the deployment process for the documentation website repo.
