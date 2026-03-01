# Security Audit

## Description
Perform comprehensive security audits of code, configurations, and infrastructure to identify vulnerabilities and compliance issues.

## When to Use
- Before deploying to production
- After major code changes
- Regular security assessments
- Compliance requirements
- Third-party code review

## Example Usage
```bash
# Audit code for security issues
claude security-audit src/app.js

# Audit entire project
claude security-audit .
```

## Benefits
- ✅ Identify security vulnerabilities early
- ✅ Ensure compliance with security standards
- ✅ Protect sensitive data
- ✅ Reduce breach risk
- ✅ Build user trust

## Tips
- Check for SQL injection vulnerabilities
- Verify input validation and sanitization
- Review authentication and authorization
- Ensure proper error handling (don't leak sensitive info)
- Check for hardcoded secrets
- Verify data encryption
- Review API security (rate limiting, CORS)
- Check for XSS vulnerabilities
- Audit dependencies for known CVEs
- Review configuration files for misconfigurations
- Ensure HTTPS is properly configured
- Check for insecure direct object references
- Review file permissions
- Verify logging and monitoring
- Use security scanning tools (OWASP ZAP, SonarQube)
- Regularly update dependencies
- Perform penetration testing
