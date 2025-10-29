# Heavens Above - Project Documentation

## Overview
This project scrapes data from heavens-above.com for astronomical observations.

## Workflows Overview

### Continuous Integration
- **Trigger**: On every push to main branch
- **Purpose**: Run tests and ensure code quality
- **Tools**: Node.js, npm

### Deployment Pipeline  
- **Trigger**: On pushes to main branch
- **Purpose**: Deploy documentation to GitHub Pages
- **Output**: https://ali123CODERALI789.github.io/heavens-above/

### Code Review
- **Trigger**: On pull requests
- **Purpose**: Automated code quality checks and security scanning
- **Tools**: Super-Linter, Dependency Review

### Scheduled Maintenance
- **Trigger**: Daily at 2 AM UTC
- **Purpose**: Run maintenance tasks and cleanup

### Dependency Updates
- **Trigger**: Weekly automated checks
- **Purpose**: Keep npm and GitHub Actions dependencies updated
- **Tool**: Dependabot
