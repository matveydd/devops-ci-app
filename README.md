# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

CI проверяет код и тесты, собирает Docker-образ и выполняет smoke-test. Публикация в GHCR запускается только для `main`. Pull Request проходит проверки без публикации.

- health endpoint: `/health`
- образ: `ghcr.io/matveydd/devops-ci-app`
- workflow: `.github/workflows/ci.yml`
