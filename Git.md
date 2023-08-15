first commit on git branch


change -> git dont care about this

change -> put into staged state -> git add --all

change is staged -> git commit ---message "feat: xyx"

after commit -> git push

after pull request is merged -> update master

git pull origin/master --rebase

Conventional commit:

{type}({scope}): {subject} = feat(ui-components): button is created

Types:

- feat: new feature is created or additional logic is added
- fix: bugfix, styling fix
- chore: maintenance, configuration update, dependency updates
- docs: documentation update
- test: test fix or create additional tests
- build:, ci: CI/CD configuration update
- style: css file update, code formatting
- perf: performance changes
- refactor: code changes for better readability and maintainability
