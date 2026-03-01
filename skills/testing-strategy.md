# Testing Strategy

## Description
Design and implement comprehensive testing strategies to ensure code reliability and prevent regressions.

## When to Use
- Before releasing new features
- During code development
- After major refactoring
- When adding new functionality
- For critical paths

## Example Usage
```bash
# Generate test suite
claude test src/app.js

# Create test cases for new feature
claude test src/features/auth.js
```

## Benefits
- ✅ Catch bugs early
- ✅ Increase confidence in code
- ✅ Reduce debugging time
- ✅ Enable refactoring
- ✅ Improve documentation

## Tips
- Write tests before code (TDD)
- Test driven development (TDD)
- Unit tests for individual functions
- Integration tests for API endpoints
- End-to-end tests for user flows
- Test edge cases and corner cases
- Use mock objects and stubs
- Keep tests independent and fast
- Aim for high code coverage (80%+)
- Test both happy paths and error cases
- Use testing frameworks (Jest, Mocha, pytest)
- Use assertion libraries (Chai, Jest)
- Test asynchronous code properly
- Test user interfaces (Cypress, Playwright)
- Test database operations
- Test external API integrations
- Use property-based testing (QuickCheck)
- Test performance under load
- Regularly run test suites
- Fix failing tests immediately
- Use CI to run tests automatically
- Test in different environments
- Use mutation testing
- Test backward compatibility
