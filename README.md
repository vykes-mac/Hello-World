# WordPress Theme Template 1 - Underscore

A template theme for GitHub deployments inspired by [Underscores Theme Boilerplate](https://github.com/automattic/_s).

## Contents

With this template you can easily develop your theme and connect it with our [WordPress.com GitHub versioning system](https://wordpress.com/support/deploy-from-github-workflow).

## Installation

- Connect your GitHub with WordPress.com [following these steps](https://wordpress.com/support/deploy-from-github-workflow)
- Once you have cloned this repository follow the installation steps of [Underscores Theme Boilerplate](https://github.com/automattic/_s)
- Add the `SSH_PRIVATE_KEY` secret with your private GitHub for this repository on repository settings
- Start developing and notice that each change will reflect in realtime on our servers

[screenshot showing the connection]

[video showing how to use it]

## Workflow

This theme has built-in workflows to update your file changes on WordPress.com once it detects merges on the trunk branch.

To edit the workflow by adding your commands, head to the [dotcom-build-artifact.yml](./.github/workflows/dotcom-build-artifact.yml) file.