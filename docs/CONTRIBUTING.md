# Contributing to [Project Name]

Thank you for your interest in contributing! We welcome contributions from the community.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Process](#development-process)
- [Coding Standards](#coding-standards)
- [Submitting Changes](#submitting-changes)
- [Reporting Bugs](#reporting-bugs)
- [Requesting Features](#requesting-features)

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone.

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone https://github.com/your-username/project-name.git`
3. Follow the setup instructions in [SETUP.md](SETUP.md)
4. Create a new branch: `git checkout -b feature/your-feature-name`

## Development Process

### Branching Strategy
- `main` - Production-ready code
- `develop` - Integration branch for features
- `feature/*` - New features
- `bugfix/*` - Bug fixes
- `hotfix/*` - Urgent production fixes

### Commit Messages
Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:
```
<type>(<scope>): <subject>

<body>

<footer>
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Example:
```
feat(auth): add OAuth2 authentication

Implement OAuth2 flow with Google and GitHub providers.
Includes token refresh mechanism.

Closes #123
```

## Coding Standards

### General Guidelines
- Write clean, readable, and maintainable code
- Follow the existing code style
- Add comments for complex logic
- Keep functions small and focused
- Use meaningful variable and function names

### JavaScript/TypeScript
- Use ESLint and Prettier configurations
- Prefer `const` over `let`, avoid `var`
- Use async/await over promises when possible
- Write JSDoc comments for public APIs

### Testing
- Write unit tests for new features
- Maintain or improve code coverage
- Run tests before submitting: `npm test`
- Include both positive and negative test cases

## Submitting Changes

1. **Update your branch** with the latest changes:
   ```bash
   git checkout develop
   git pull origin develop
   git checkout your-feature-branch
   git rebase develop
   ```

2. **Run tests and linting**:
   ```bash
   npm run lint
   npm test
   npm run build
   ```

3. **Commit your changes** following the commit message guidelines

4. **Push to your fork**:
   ```bash
   git push origin your-feature-branch
   ```

5. **Create a Pull Request**:
   - Use the PR template provided
   - Link related issues
   - Provide a clear description of changes
   - Add screenshots for UI changes
   - Request review from maintainers

### Pull Request Review Process

- At least one maintainer approval required
- All CI checks must pass
- Code coverage must not decrease
- No merge conflicts
- Documentation updated if needed

## Reporting Bugs

Use the bug report template when creating issues:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Environment details
- Screenshots if applicable

## Requesting Features

Use the feature request template:
- Describe the problem you're trying to solve
- Propose a solution
- Explain benefits to the project
- Include mockups or examples if relevant

## Questions?

If you have questions, please:
- Check existing issues and discussions
- Create a new issue with the question label
- Reach out to maintainers

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for contributing! 🎉
