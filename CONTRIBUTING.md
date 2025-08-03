# Contributing to Agent Mesh Protocol

Thank you for your interest in contributing to the Agent Mesh Protocol! We welcome contributions from the community and are excited to have you join us in building the future of AI agent interoperability.

## 🤝 Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

## 🚀 Ways to Contribute

There are many ways to contribute to the Agent Mesh Protocol:

### 📝 Documentation
- Improve existing documentation
- Write tutorials and guides
- Create examples and use cases
- Fix typos and clarify explanations

### 🐛 Bug Reports
- Report bugs and issues
- Provide detailed reproduction steps
- Help triage existing issues

### ✨ Feature Requests
- Propose new features
- Suggest improvements to existing functionality
- Design new capabilities for the protocol

### 💻 Code Contributions
- Fix bugs and implement features
- Improve performance and reliability
- Add support for new frameworks
- Write tests and improve coverage

### 🔧 Tools and Infrastructure
- Improve build and deployment processes
- Create development tools
- Enhance CI/CD pipelines

## 🏁 Getting Started

### 1. Fork and Clone

```bash
# Fork the repository on GitHub
# Then clone your fork
git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME

# Add upstream remote
git remote add upstream https://github.com/agentmeshprotocol/REPOSITORY_NAME.git
```

### 2. Set Up Development Environment

```bash
# Create virtual environment (for Python projects)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -e ".[dev]"

# Install pre-commit hooks
pre-commit install
```

### 3. Create a Branch

```bash
# Create and switch to a new branch
git checkout -b feature/your-feature-name

# Or for bug fixes
git checkout -b fix/issue-description
```

## 📋 Development Guidelines

### Commit Messages

Follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
type(scope): description

[optional body]

[optional footer]
```

Types:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or modifying tests
- `chore`: Maintenance tasks

Examples:
```
feat(sdk): add WebSocket transport support
fix(validation): handle edge case in message parsing
docs(readme): update installation instructions
```

### Code Style

#### Python Projects
- Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- Use [Black](https://black.readthedocs.io/) for formatting
- Use [isort](https://isort.readthedocs.io/) for import sorting
- Type hints are required for public APIs

#### TypeScript/JavaScript Projects
- Follow [TypeScript ESLint](https://typescript-eslint.io/) recommendations
- Use [Prettier](https://prettier.io/) for formatting
- Prefer functional programming patterns
- Use strict TypeScript configuration

### Testing

- Write tests for all new features and bug fixes
- Maintain or improve test coverage
- Run the full test suite before submitting

```bash
# Run tests
pytest                          # Python
npm test                        # Node.js

# Run with coverage
pytest --cov=amp               # Python
npm run test:coverage          # Node.js
```

### Documentation

- Update documentation for any API changes
- Include docstrings for all public functions and classes
- Add examples for new features
- Update README if necessary

## 🔄 Pull Request Process

### 1. Before Submitting

- [ ] Ensure your code follows the style guidelines
- [ ] Add or update tests as needed
- [ ] Update documentation
- [ ] Run the full test suite
- [ ] Check that your commits are well-formed

### 2. Create Pull Request

1. Push your branch to your fork
2. Create a pull request against the main repository
3. Fill out the pull request template completely
4. Link any related issues

### 3. Pull Request Template

```markdown
## Description
Brief description of what this PR does.

## Type of Change
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update

## Testing
- [ ] Tests pass locally
- [ ] Added new tests for new functionality
- [ ] Updated existing tests if needed

## Documentation
- [ ] Updated relevant documentation
- [ ] Added docstrings for new functions/classes
- [ ] Updated README if needed

## Related Issues
Fixes #(issue number)
```

### 4. Review Process

- Maintainers will review your PR
- Address any feedback or requested changes
- Once approved, a maintainer will merge your PR

## 🐛 Bug Reports

When reporting bugs, please include:

### Required Information
- **Version**: AMP version you're using
- **Environment**: OS, Python/Node version, framework versions
- **Expected Behavior**: What should happen
- **Actual Behavior**: What actually happens
- **Steps to Reproduce**: Minimal steps to reproduce the issue

### Bug Report Template

```markdown
## Bug Description
Clear description of the bug.

## Environment
- AMP Version: 
- Python/Node Version: 
- Framework: 
- OS: 

## Steps to Reproduce
1. 
2. 
3. 

## Expected Behavior
What should happen.

## Actual Behavior
What actually happens.

## Additional Context
Any additional information, logs, or screenshots.
```

## 💡 Feature Requests

When requesting features, please include:

- **Problem**: What problem does this solve?
- **Solution**: Describe your proposed solution
- **Alternatives**: What alternatives have you considered?
- **Use Cases**: How would you use this feature?

## 📞 Getting Help

If you need help or have questions:

- **GitHub Discussions**: For general questions and community support
- **GitHub Issues**: For bug reports and feature requests
- **Discord**: For real-time chat and community interaction
- **Documentation**: Check our comprehensive docs first

## 🏷️ Issue Labels

We use labels to categorize issues:

- `bug`: Something isn't working
- `enhancement`: New feature or request
- `documentation`: Improvements or additions to documentation
- `good first issue`: Good for newcomers
- `help wanted`: Extra attention is needed
- `question`: Further information is requested

## 🚀 Release Process

For maintainers:

1. Update version numbers
2. Update CHANGELOG.md
3. Create release notes
4. Tag the release
5. Publish to package registries

## 📄 License

By contributing, you agree that your contributions will be licensed under the same license as the project (MIT License).

---

Thank you for contributing to the Agent Mesh Protocol! 🎉