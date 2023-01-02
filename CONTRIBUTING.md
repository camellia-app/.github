# How to Contribute

## Bugs

### Where to Find Known Issues

We are using GitHub Issues for our public bugs. Before filing a new task, try to make sure your problem doesn't already exist.

### Reporting New Issues

Please make sure you provide as much information about the issue as you can.

If it's a bug in Camellia, we recommend you to record a video and attach it to the issue, and provide debug information. To obtain debug information, open extension options, then choose "Advanced" in left menu and press "Copy debug information" button.

### Security Bugs

Check out our security policy. In the menu above each repository: "Security" → "Policy".

## How to Get in Touch

We are using [GitHub Discussions](https://github.com/orgs/camellia-app/discussions) for public discussions about our projects.

## Proposing a Change or Feature

If you intend to change something within Camellia or implement new feature, we recommend filing an issue. This lets us reach an agreement on your proposal before you put significant effort into it.

If you're only fixing a bug, it's fine to submit a pull request right away but we still recommend to file an issue detailing what you're fixing. This is helpful in case we don't accept that specific fix but want to keep track of the issue.

## Translations

Currently, we do not accept new languages contributions. However, you are welcome to update translations of existing languages.

## Updating dependencies

We use [Dependabot](https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/configuring-dependabot-security-updates) to manage automatic updates for all our dependencies. There is no need to open such pull requests on your own.

## Branch Organization

Submit all changes directly to the `main` branch. We don't use separate branches for development or for upcoming releases. We do our best to keep `main` in good shape, with all tests and quality checks passing.

## Commit Naming Convention

We follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) to make sure our commit history is clean and easy to read.

We use commit type system similar to Angular convention:

- **build**: Changes that affect the build system or external dependencies (example scopes: webpack, npm);
- **ci**: Changes to our CI configuration files and scripts (example scopes: GitHub Actions);
- **docs**: Documentation only changes;
- **feat**: A new feature;
- **fix**: A bug fix;
- **perf**: A code change that improves performance;
- **refactor**: A code change that neither fixes a bug nor adds a feature;
- **style**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc);
- **test**: Adding missing tests or correcting existing tests;
- **chore**: Anything that doesn't fit well to any type described above.

## Your First Pull Request

Working on your first Pull Request? You can learn how from this free video series: [How to Contribute to an Open Source Projects on GitHub](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github).

To help you get your feet wet and get you familiar with our contribution process, we have a list of good first issues labeled "good first issue" that contain bugs or small tasks that have a relatively limited scope. This is a great place to get started.

If you decide to fix an issue, please be sure to check the comment thread in case somebody is already working on a fix. If nobody is working on it at the moment, please leave a comment stating that you intend to work on it so other people don't accidentally duplicate your effort.

If somebody claims an issue but doesn't follow up for more than two weeks, it's fine to take it over but you should still leave a comment.

## Sending a Pull Request

The core team is monitoring for pull requests. We will review your pull request and either merge it, request changes to it, or close it with an explanation. We’ll do our best to provide updates and feedback throughout the process.

**Before submitting a pull request**, please make sure the following is done:

1. Make sure you are familiar with our internal and external documentations. Check out `README.md` files for documentation.
2. Your pull request was made from fresh version of `main` branch.
3. All status checks are passing: code style, static analysis, tests, it builds and does not produce new warnings.

It's also okay to open draft pull requests in case it's in progress.
