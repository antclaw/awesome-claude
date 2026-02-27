# Contributing to Awesome Claude Code Skills

Thank you for your interest in contributing to Awesome Claude Code Skills! This guide will help you get started.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Adding a New Skill](#adding-a-new-skill)
- [Skill File Guidelines](#skill-file-guidelines)
- [Pull Request Process](#pull-request-process)
- [Questions?](#questions)

## Code of Conduct

- Be respectful and constructive
- Provide clear, actionable feedback
- Follow the project's style guide
- Focus on the project's goals

## How to Contribute

### 1. Fork and Clone

```bash
git clone https://github.com/YOUR_USERNAME/awesome-claude.git
cd awesome-claude
```

### 2. Create a Branch

```bash
git checkout -b feature/add-new-skill
```

### 3. Make Your Changes

- Add or modify skill files in the `skills/` directory
- Update the README.md if needed
- Test your changes locally

### 4. Commit and Push

```bash
git add .
git commit -m "Add [skill name] skill"
git push origin feature/add-new-skill
```

### 5. Open a Pull Request

- Go to the GitHub repository
- Click "Pull Requests" → "New Pull Request"
- Fill in the PR template
- Submit your PR

## Adding a New Skill

### Skill File Structure

Each skill should be a separate Markdown file in the `skills/` directory with the following structure:

```markdown
# [Skill Name]

## Description
Brief description of what this skill does.

## When to Use
- Condition 1
- Condition 2

## Example Usage
```bash
# Example command or usage
```

## Benefits
- Benefit 1
- Benefit 2

## Tips
- Tip 1
- Tip 2
```

### Skill File Guidelines

1. **Title**: Use clear, descriptive titles
   - ✅ Good: "Code Quality Review"
   - ❌ Bad: "Review Code"

2. **Description**: Keep it concise (2-3 sentences max)
   - Explain what the skill does
   - Mention the main benefit

3. **When to Use**: List specific scenarios
   - Use bullet points
   - Be specific about when to apply the skill

4. **Example Usage**: Provide concrete examples
   - Use code blocks for clarity
   - Show before/after when applicable

5. **Benefits**: Highlight the advantages
   - Use bullet points
   - Focus on value proposition

6. **Tips**: Share expert knowledge
   - Include best practices
   - Warn about common pitfalls

### Skill Categories

Skills should be organized into these categories:

1. **Coding Skills** - Writing code, refactoring, architecture
2. **Code Review** - Quality, security, performance reviews
3. **Debugging** - Finding and fixing bugs
4. **Testing** - Test creation, coverage, automation
5. **Documentation** - API docs, code comments, READMEs
6. **Performance** - Optimization, caching, algorithms
7. **Security** - Authentication, validation, protection
8. **DevOps** - CI/CD, containers, infrastructure

### Adding to README

After adding a new skill, update the README.md:

1. Find the appropriate section
2. Add your skill to the list
3. Follow the existing formatting
4. Update the table of contents if needed

## Pull Request Process

### PR Template

```markdown
## Description
Brief description of your changes

## Changes Made
- [ ] Added new skill
- [ ] Modified existing skill
- [ ] Updated documentation
- [ ] Fixed bugs

## Testing
Describe how you tested your changes

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-reviewed the code
- [ ] Added tests (if applicable)
- [ ] Documentation updated
- [ ] PR description clear and complete

## Related Issues
Fixes #issue-number
```

### Review Process

1. Automated checks run (linting, tests)
2. Maintainers review your PR
3. Address feedback and iterate
4. Get approval and merge

## Questions?

- Open an issue for questions
- Check existing issues for similar questions
- Ask in the repository discussions

## Thank You!

Your contributions make this project better for everyone. Thank you for contributing to Awesome Claude Code Skills! 🙏
