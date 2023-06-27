# License Approval Example

This repo serves as a demo and test of the [license_approval](https://github.com/ralexander-phi/license_approval) GitHub Action.

## Local Testing

Try running [`act`](https://github.com/nektos/act).

## Expected Behaviors

The `main` branch has only `MIT` dependencies which are permitted, so the build will pass.

[PR #1](https://github.com/ralexander-phi/test-license_approval/pull/1) should fail as it adds a dependency with the unapproved Apache 2.0 license.

