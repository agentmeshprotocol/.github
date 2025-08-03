# Agent Mesh Protocol GitHub Publishing Guide

This directory contains the complete setup for the Agent Mesh Protocol GitHub organization. **Not all files should be published** - this guide explains what to publish and what to keep private.

## 🚫 **Files That Should NOT Be Published**

### **Planning and Internal Documentation**
- `INSTRUCTIONS.md` - Internal GitHub setup instructions
- `REPOSITORY_PLANNING.md` - Internal organizational planning
- `ORGANIZATION_PROFILE.md` - Organization setup template
- `GITHUB_ACTIONS_README.md` - Internal workflow documentation
- `organization-profile.md` - Duplicate internal profile
- `SETUP_INSTRUCTIONS.md` - Deployment instructions
- `README.md` - Internal setup documentation
- `PUBLISHING_GUIDE.md` - This file

### **Setup and Deployment Scripts**
- `setup-repositories.sh` - Repository creation script
- `push-*.sh` - All deployment scripts
- `verify-setup.sh` - Setup verification script

### **Development Artifacts**
- `.gitignore` - Internal gitignore for this directory
- Any temporary files, logs, or IDE configurations

## ✅ **Directories That SHOULD Be Published**

The following directories contain the actual repository content that should be published to GitHub:

### **Core Repositories**
- **`agentmeshprotocol/`** → Published to `github.com/agentmeshprotocol/agentmeshprotocol`
- **`amp-python-sdk/`** → Published to `github.com/agentmeshprotocol/amp-python-sdk`
- **`amp-typescript-sdk/`** → Published to `github.com/agentmeshprotocol/amp-typescript-sdk`
- **`amp-docs/`** → Published to `github.com/agentmeshprotocol/amp-docs`
- **`amp-examples/`** → Published to `github.com/agentmeshprotocol/amp-examples`
- **`amp-community/`** → Published to `github.com/agentmeshprotocol/amp-community`

### **Organization Profile**
- **`profile/`** → Published to `github.com/agentmeshprotocol/.github` (organization profile repository)

## 🔒 **Security Considerations**

### **What Gets Protected**
- Internal planning and strategy documents
- Setup scripts that could reveal organizational structure
- Deployment credentials and configuration details
- Development workflow documentation

### **What Gets Published**
- Production-ready code and documentation
- Public-facing README files and examples
- Community contribution guidelines
- Security policies for public repositories

## 📁 **Directory Structure After Publishing**

```
GitHub Organization: agentmeshprotocol
├── agentmeshprotocol (main protocol repository)
├── amp-python-sdk (Python SDK)
├── amp-typescript-sdk (TypeScript SDK)
├── amp-docs (documentation website)
├── amp-examples (examples and tutorials)
├── amp-community (community resources)
└── .github (organization profile from profile/ directory)
```

## 🚀 **Publishing Process**

### **Automated Publishing**
The setup scripts handle this automatically:
```bash
./push-all-repositories.sh
```

### **Manual Publishing**
If publishing manually, only copy the content from these directories:
- `agentmeshprotocol/` → Main repository
- `amp-python-sdk/` → Python SDK repository
- `amp-typescript-sdk/` → TypeScript SDK repository
- `amp-docs/` → Documentation repository
- `amp-examples/` → Examples repository
- `amp-community/` → Community repository
- `profile/` → Organization profile repository

## ⚠️ **Important Notes**

1. **Never commit this directory to a public repository** - it contains internal planning documents
2. **Use the automated scripts** - they handle the separation automatically
3. **Keep planning documents private** - store in a private repository or local system
4. **Review before publishing** - always verify content before making public

## 🔍 **Verification**

Before publishing, verify that:
- [ ] No planning documents are included in repository content
- [ ] No setup scripts are included in repository content
- [ ] All repository content has appropriate .gitignore files
- [ ] All sensitive information has been removed
- [ ] All repositories have professional README files

Use the verification script:
```bash
./verify-setup.sh
```

---

**Remember**: This directory structure is for organizational setup only. The individual repository directories contain the actual content that should be published to GitHub.