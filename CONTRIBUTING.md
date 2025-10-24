# Contributing to ÉBAN Federated

First off, thank you for considering contributing to ÉBAN Federated! It's people like you that make this project a great tool for ethical data management.

## Code of Conduct

This project and everyone participating in it is governed by our commitment to ethical, privacy-first development. By participating, you are expected to uphold this commitment.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

**Bug Report Template:**
- **Description**: Clear description of the bug
- **Steps to Reproduce**: Numbered steps to reproduce the behavior
- **Expected Behavior**: What you expected to happen
- **Actual Behavior**: What actually happened
- **Screenshots**: If applicable
- **Browser**: Browser name and version
- **Device**: Desktop/Mobile and OS version

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- **Clear title and description**
- **Use case**: Why this enhancement would be useful
- **Possible implementation**: If you have ideas on how to implement it
- **Alternatives considered**: Other solutions you've thought about

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following the style guidelines below
3. **Test thoroughly** on multiple browsers
4. **Update documentation** if you're changing functionality
5. **Write clear commit messages**
6. **Submit the pull request**

## Development Guidelines

### Style Guidelines

#### HTML
- Use semantic HTML5 elements
- Include proper ARIA labels for accessibility
- Keep structure clean and well-indented
- Use descriptive IDs and classes

#### CSS
- Use CSS custom properties (variables) defined in `:root`
- Follow BEM naming convention where applicable
- Keep specificity low
- Comment complex selectors
- Maintain mobile-first responsive design

#### JavaScript
- Use ES6+ features
- Write pure functions where possible
- Add comments for complex logic
- Use meaningful variable and function names
- Avoid global variables (except `appState`)
- Handle errors gracefully

### Code Organization

```
index.html
├── <head>
│   ├── Meta tags
│   └── <style> CSS
├── <body>
│   ├── Header
│   ├── Main sections
│   ├── FAB button
│   ├── Navigation
│   └── <script> JavaScript
```

### Accessibility Requirements

All contributions must maintain accessibility standards:

- ✅ Proper semantic HTML
- ✅ ARIA labels on interactive elements
- ✅ Keyboard navigation support
- ✅ Sufficient color contrast (WCAG AA)
- ✅ Focus indicators
- ✅ Screen reader compatibility

### Testing Checklist

Before submitting a PR, please verify:

- [ ] Code works in Chrome, Firefox, Safari, and Edge
- [ ] Mobile responsive (test on actual devices if possible)
- [ ] Keyboard navigation works
- [ ] All forms validate correctly
- [ ] No console errors
- [ ] Privacy mode functions correctly
- [ ] Animations are smooth
- [ ] No accessibility regressions

## Privacy-First Principles

All contributions must respect these core principles:

1. **No External Dependencies**: Keep the project self-contained
2. **No Data Persistence**: Maintain in-memory storage for demo
3. **No Tracking**: Zero analytics or external calls
4. **Pseudonymization**: Protect user identities
5. **Consent-Driven**: Respect granular consent controls

## Commit Message Guidelines

Use clear, descriptive commit messages:

```
feat: Add dark mode toggle
fix: Correct pseudonym generation algorithm
docs: Update installation instructions
style: Improve button hover states
refactor: Simplify navigation logic
test: Add form validation tests
```

Prefixes:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: CSS/UI changes
- `refactor`: Code restructuring
- `test`: Adding tests
- `chore`: Maintenance tasks

## Review Process

1. **Automated checks**: Code is reviewed for basic quality
2. **Manual review**: Maintainers review functionality and style
3. **Testing**: Changes are tested on multiple browsers
4. **Feedback**: You may be asked to make changes
5. **Merge**: Once approved, changes are merged

## Getting Help

- **Documentation**: Check README.md first
- **Issues**: Search existing issues
- **Discussions**: Use GitHub Discussions for questions
- **Email**: For sensitive matters only

## Recognition

Contributors will be recognized in:
- GitHub contributors list
- README.md acknowledgments section
- Release notes for significant contributions

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

---

**Thank you for helping make ÉBAN Federated better!** 🎉
