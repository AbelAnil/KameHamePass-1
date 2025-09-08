# Contributing to Kamehame Pass

## Branching
- `main` — production (protected)
- `dev` — integration branch
- Feature branches: `feature/<name>`
- Hotfix branches: `hotfix/<name>`

## Workflow
1. Create an issue for any task.
2. Branch from `dev`: `git checkout -b feature/NAME`.
3. Commit logically. Use clear messages: `feat: add auth endpoints`.
4. Push and open a Pull Request into `dev`.
5. PR needs at least 1 approval + passing CI.

## Code style & tests
- Follow existing style (ESLint + Prettier).
- Add tests for backend endpoints.

