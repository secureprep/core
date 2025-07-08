# Contributing to SecurePrep

Thank you for your interest in contributing to SecurePrep! 🎉

## 📋 Before You Start

### 1. Sign the CLA
All contributors must sign our [Contributor License Agreement](CLA.md) before their contributions can be merged. The CLA Assistant will automatically prompt you when you create your first pull request.

### 2. Code of Conduct
Please be respectful and professional in all interactions. We maintain a welcoming environment for all contributors.

## 🔧 Development Setup

```bash
# Fork and clone the repository
git clone https://github.com/YOUR-USERNAME/core.git
cd core

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies (when available)
pip install -r src/requirements.txt

# Install development dependencies
pip install flake8 pytest
```

## 🚀 Making Changes

### 1. Create a Branch
```bash
git checkout -b feature/your-feature-name
```

### 2. Make Your Changes
- Write clear, well-documented code
- Follow existing code style and conventions
- Add tests for new functionality
- Update documentation as needed

### 3. Test Your Changes
```bash
# Run linting
flake8 src/

# Run tests
pytest tests/
```

### 4. Commit Your Changes
```bash
git add .
git commit -m "feat: add your feature description"
```

Use conventional commit messages:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `test:` for adding tests
- `refactor:` for code refactoring

### 5. Push and Create PR
```bash
git push origin feature/your-feature-name
```

Then create a pull request on GitHub.

## 🎯 What We're Looking For

- **Bug fixes** - Help us squash bugs!
- **Documentation** - Improve our docs and examples
- **Tests** - Increase test coverage
- **Performance improvements** - Make SecurePrep faster
- **New features** - Add useful functionality (discuss first in issues)

## 📞 Getting Help

- 🐛 **Bug reports**: Create an issue with details
- 💡 **Feature requests**: Open an issue for discussion
- ❓ **Questions**: Use GitHub Discussions or email team@secureprep.dev

## 📝 Code Style

- Format & test your code before submitting
- Follow PEP 8 for Python code
- Use clear, descriptive variable names
- Add docstrings for public functions
- Keep functions focused and small

## 🔍 Review Process

1. **Automated checks**: CI must pass
2. **CLA signature**: Required for all contributors
3. **Code review**: Maintainers will review your changes
4. **Testing**: Ensure all tests pass
5. **Merge**: Once approved, we'll merge your PR

Thank you for contributing to SecurePrep! 🙏
