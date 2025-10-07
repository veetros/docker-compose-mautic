# Deploy Mautic 6 to DigitalOcean with GitHub Actions

> **⚡ This repository uses the [Deploy Mautic to DigitalOcean](https://github.com/marketplace/actions/deploy-mautic-to-digitalocean) GitHub Action for one-click deployments.**

Automated deployment of Mautic 6 to DigitalOcean VPS using GitHub Actions. Deploy Mautic in minutes with automatic SSL certificates, monitoring, and maintenance.

## 🎥 Mautic Conference Global 2024 

My presentation of the previous version of this idea. It's way simpler now as I moved the complexities to a GitHub action.

[![Docker Compose for Mautic introduced in the Mautic Conference Global 2024](https://github.com/user-attachments/assets/7841185f-5137-4130-9f23-6871606f4c7d)](https://www.youtube.com/watch?v=lzyjbUKZZlY)

## 🚀 Quick Start

### 1. Fork this Repository
Click the "Fork" button to create your own copy.

### 2. Setup Instructions
**Complete setup guide**: https://github.com/marketplace/actions/deploy-mautic-to-digitalocean

The action's documentation covers:
- Prerequisites and requirements
- GitHub Secrets and Variables configuration  
- DigitalOcean API token setup
- SSH key generation and setup
- Domain configuration for SSL
- VPS sizing recommendations
- Troubleshooting common issues

### 3. Deploy Mautic

#### Automatic Deployment
Push to `main` branch and deployment runs automatically.

#### Manual Deployment
1. Go to `Actions` tab → "Deploy Mautic to DigitalOcean"
2. Click "Run workflow" 
3. Choose VPS name and size
4. Deploy!

## ✨ Features

- **🚀 One-click deployment** - Deploy in under 10 minutes
- **🔒 Automatic SSL** - Let's Encrypt certificates with domain setup
- **📊 Built-in monitoring** - DigitalOcean monitoring + Docker health checks
- **🔄 Easy updates** - Update Mautic version and redeploy
- **🎨 Extensible** - Custom themes and plugins via Composer
- **👥 Team-friendly** - GitHub collaboration and audit trail

## 🔗 Resources

- **📖 Complete Documentation**: https://github.com/marketplace/actions/deploy-mautic-to-digitalocean
- **🛠️ Action Source Code**: https://github.com/escopecz/mautic-do-action
- **📋 Migration Guide**: [MIGRATION-TO-ACTION.md](MIGRATION-TO-ACTION.md)
- **🔍 Validation Report**: [VALIDATION-SUMMARY.md](VALIDATION-SUMMARY.md)

## 💬 Support

- **Mautic Community**: https://www.mautic.org/community
- **Action Issues**: https://github.com/escopecz/mautic-do-action/issues
- **DigitalOcean Support**: https://www.digitalocean.com/support

---

**Prefer managed hosting?** Consider [Mautic's official partners](https://www.mautic.org/mautic-partners) or start a [free trial](https://m.mautic.org/mautic-start-your-trial).

