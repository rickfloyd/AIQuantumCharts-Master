# Contributing to AIQuantumCharts

Thank you for your interest in contributing! This document provides guidelines for contributing to this project in a secure and effective manner.

## Getting Started

### Prerequisites

Before contributing, ensure you have:
- A GitHub account
- Git installed locally
- Familiarity with the project's security policies (see [SECURITY.md](SECURITY.md))

### Setting Up Your Development Environment

1. **Fork the repository**
   ```bash
   # Fork via GitHub UI, then clone your fork
   git clone https://github.com/YOUR-USERNAME/AIQuantumCharts-Master.git
   cd AIQuantumCharts-Master
   ```

2. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Set up environment variables**
   ```bash
   # Copy example environment file
   cp .env.example .env
   # Edit .env with your local settings (never commit this file!)
   ```

## Contribution Guidelines

### Code Standards

- Write clear, readable code with meaningful variable names
- Follow existing code style and conventions
- Add comments for complex logic
- Keep functions small and focused
- Write self-documenting code where possible

### Security Requirements

**Critical: All contributions must follow security best practices**

- ✅ **DO**: Use environment variables for sensitive data
- ✅ **DO**: Validate and sanitize all user inputs
- ✅ **DO**: Use parameterized queries for database operations
- ✅ **DO**: Keep dependencies up to date
- ✅ **DO**: Follow principle of least privilege

- ❌ **DON'T**: Commit API keys, passwords, or tokens
- ❌ **DON'T**: Commit `.env` files or local configuration
- ❌ **DON'T**: Use deprecated or vulnerable dependencies
- ❌ **DON'T**: Disable security features without justification
- ❌ **DON'T**: Store sensitive data in plain text

### Commit Messages

Write clear, descriptive commit messages:

```
Short summary (50 chars or less)

More detailed explanation if needed. Wrap at 72 characters.
Explain what changed and why, not how.

- Bullet points are okay
- Use present tense: "Add feature" not "Added feature"
- Reference issues: Fixes #123
```

### Pull Request Process

1. **Before submitting:**
   - Ensure your code follows the project style
   - Run all tests and ensure they pass
   - Update documentation if needed
   - Check for security issues
   - Review your own changes first

2. **Submit your PR:**
   - Use a clear, descriptive title
   - Fill out the PR template completely
   - Link related issues
   - Request review from maintainers

3. **After submitting:**
   - Respond to feedback promptly
   - Make requested changes
   - Keep your branch up to date with main
   - Be patient and respectful

### Testing

- Write tests for new features
- Ensure existing tests pass
- Aim for good test coverage
- Test edge cases and error conditions

### Documentation

- Update README.md if adding features
- Document public APIs and functions
- Include examples where helpful
- Keep documentation accurate and up to date

## Types of Contributions

### Bug Reports

When reporting bugs, include:
- Clear description of the issue
- Steps to reproduce
- Expected vs actual behavior
- Environment details (OS, version, etc.)
- Screenshots if applicable

**For security bugs**: Follow [SECURITY.md](SECURITY.md) instead

### Feature Requests

When suggesting features:
- Explain the use case
- Describe the proposed solution
- Consider alternatives
- Think about implementation complexity

### Code Contributions

Welcome areas for contribution:
- Bug fixes
- New features
- Performance improvements
- Documentation improvements
- Test coverage
- Code refactoring

## Development Workflow

```bash
# 1. Update your fork
git checkout main
git pull upstream main

# 2. Create feature branch
git checkout -b feature/my-feature

# 3. Make changes and commit
git add .
git commit -m "Add my feature"

# 4. Push to your fork
git push origin feature/my-feature

# 5. Open pull request on GitHub
```

## Code Review Process

- Maintainers will review PRs as time permits
- Address feedback constructively
- Be open to suggestions and improvements
- Reviews focus on code quality, security, and maintainability

## Community

- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)
- Be respectful and professional
- Help others when you can
- Ask questions if unclear
- Support a positive, inclusive environment

## Questions?

- Open an issue for general questions
- Check existing issues and PRs first
- Be specific and provide context

## License

By contributing, you agree that your contributions will be licensed under the same license as the project (see [LICENSE](LICENSE)).

---

Thank you for contributing to AIQuantumCharts! Your efforts help make this project better and more secure for everyone.
