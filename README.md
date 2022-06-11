# What is this about
This is a sample repo for testing commit linting using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
## How to test
1. clone the repo inot your local workspace(laptop, VM, etc)
2. run `yarn install`
3. Make some changes in index.ts file
4. Try to commit changes without conventional commit message. It will fail immediately.
5. Now, add message as per conventional commit messgae. e.g `git commit -m "feat: Adding more code lines in index.js."`. It should work.

For more details about conventional commit message, Please refer [this](https://www.conventionalcommits.org/en/v1.0.0/)
