# Contributing to DIU OS

Thank you for your interest in contributing to DIU OS! We're building the future of scientific discovery through open collaboration, and every contribution matters.

## 🚀 Quick Start

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/YOUR-USERNAME/REPO-NAME`
3. **Create** a branch: `git checkout -b feature/your-feature-name`
4. **Make** your changes
5. **Test** your changes
6. **Commit**: `git commit -m "feat: add new feature"`
7. **Push**: `git push origin feature/your-feature-name`
8. **Submit** a Pull Request

## 📝 Commit Message Convention

We use [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting, semicolons, etc)
- `refactor:` Code refactoring
- `test:` Adding or updating tests
- `chore:` Maintenance tasks
- `perf:` Performance improvements

Examples:
```
feat: add quantum tunneling visualization
fix: correct wave function normalization
docs: update API documentation
```

## 🎯 What Can You Contribute?

### Code Contributions
- **Features**: New functionality aligned with our roadmap
- **Bug Fixes**: Help us squash bugs
- **Performance**: Optimization and improvements
- **Tests**: Unit tests, integration tests, E2E tests

### Non-Code Contributions
- **Documentation**: Improve docs, fix typos, add examples
- **Translations**: Help make DIU OS accessible globally
- **Design**: UI/UX improvements, graphics, animations
- **Research**: Scientific accuracy, algorithm improvements

## 🛠️ Development Setup

### Prerequisites
- Git
- Node.js 18+ (for frontend)
- Rust 1.70+ (for backend)
- Docker (optional)

### Backend (Rust)
```bash
cd diu-backend
cargo build
cargo test
cargo run
```

### Frontend (React)
```bash
cd diu-frontend
npm install
npm test
npm run dev
```

### Physics Simulations
```bash
cd physics-tutorial
npm install
npm run dev
# Open http://localhost:5173
```

## 🧪 Testing

Before submitting a PR, ensure:

- [ ] All tests pass: `npm test` or `cargo test`
- [ ] Code is formatted: `npm run format` or `cargo fmt`
- [ ] Code is linted: `npm run lint` or `cargo clippy`
- [ ] Documentation is updated if needed

## 📋 Pull Request Process

1. **Update** the README.md with details of changes if applicable
2. **Ensure** all tests pass and code is properly formatted
3. **Update** the documentation if you're changing functionality
4. **Reference** any relevant issues in your PR description
5. **Wait** for code review from maintainers

### PR Template
```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Breaking change
- [ ] Documentation update

## Checklist
- [ ] Tests pass
- [ ] Code is formatted
- [ ] Documentation updated
- [ ] PR title follows commit convention

## Related Issues
Fixes #123
```

## 🎨 Code Style

### Rust
- Follow [Rust API Guidelines](https://rust-lang.github.io/api-guidelines/)
- Use `cargo fmt` for formatting
- Use `cargo clippy` for linting

### TypeScript/JavaScript
- Use ESLint configuration provided
- Prefer functional components in React
- Use TypeScript for type safety

### General
- Write clear, self-documenting code
- Add comments for complex logic
- Keep functions small and focused
- Write tests for new features

## 🐛 Reporting Issues

### Bug Reports
Include:
- Clear description
- Steps to reproduce
- Expected behavior
- Actual behavior
- System information
- Screenshots if applicable

### Feature Requests
Include:
- Use case description
- Proposed solution
- Alternative solutions considered
- Additional context

## 💬 Communication Channels

- **Discord**: [Join our community](https://discord.gg/diu-os)
- **GitHub Discussions**: For general discussions
- **GitHub Issues**: For bugs and features
- **Email**: dev@diu-os.dev for private matters

## 🏆 Recognition

Contributors are recognized in:
- Repository README
- Website contributors page
- Release notes
- Special Discord role

## 📜 Code of Conduct

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before contributing.

## 📄 License

By contributing to DIU OS, you agree that your contributions will be licensed under the MIT License.

## 🙏 Thank You!

Every contribution, no matter how small, helps build the future of scientific discovery. Thank you for being part of the DIU OS community!

---

**Questions?** Feel free to ask in our [Discord](https://discord.gg/diu-os) or open a [Discussion](https://github.com/diu-os/.github/discussions).
