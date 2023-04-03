### Husky precommit hook testing

1. Clone project to your computer.
2. Use `npm i` to download all dependencies.
3. Make an error does not match the eslint config (airbnb) rules and try to commit.
4. Husky's precommit hook is expected to prevent a commit if there are inconsistencies with the eslint config.
5. There is also a lint-staged plugin to check only those files that are being staged.
