# nodejs-commits-patterning-sample

Sample repository for patterning Git commits on Node.js projects

## Usage

It will prompt commitzen for you to compose your commit

```sh
git commit
```

## Hooks

- `prepare-commit-msg` Runs commitzen to compose commit messages
- `pre-commit` Runs static code linting on staged files before git commit
- `commit-msg` Runs commitlint to lint commit message according to conventional commits
- `pre-push` Runs project's test suite before git push

## References

- https://github.com/typicode/husky
- https://github.com/conventional-changelog/commitlint
- https://github.com/commitizen/cz-cli