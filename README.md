# README

This repository is a simple repro for this bug on Storybook: https://github.com/storybookjs/storybook/issues/19964

To reproduce:

- clone the repository
- `yarn`
- `yarn storybook`

The Example Storybook doc page will not load unless you

- remove the `Source` tag or
- downgrade all Storybook dependencies to `7.0.0-alpha-51`
