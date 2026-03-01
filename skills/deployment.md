# Deployment Strategy

## Description
Plan and execute deployment strategies for applications, ensuring minimal downtime and maximum reliability.

## When to Use
- Preparing for production launch
- Planning deployments
- Setting up CI/CD pipelines
- Managing releases
- Handling rollbacks

## Example Usage
```bash
# Plan deployment strategy
claude deployment-plan production

# Set up CI/CD pipeline
claude deployment-cicd .github/workflows/deploy.yml
```

## Benefits
- ✅ Reliable deployments
- ✅ Quick rollback capability
- ✅ Automated processes
- ✅ Reduced manual errors
- ✅ Better monitoring

## Tips
- Use feature flags
- Implement blue-green or canary deployments
- Automate testing before deployment
- Use containerization (Docker, Kubernetes)
- Set up proper monitoring and alerts
- Implement health checks
- Use environment-specific configurations
- Backup data before deployment
- Test deployment in staging first
- Document deployment process
- Implement rollback strategy
- Use deployment automation (GitHub Actions, GitLab CI)
- Monitor logs after deployment
- Communicate with users during deployment
- Plan for database migrations
- Use configuration management (Ansible, Terraform)
- Implement secrets management
- Consider multi-region deployment
- Regularly update deployment tools
