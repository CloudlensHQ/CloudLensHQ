# Welcome to CloudLens 🔍☁️

**Open-source cloud inventory and visibility for Cloud environments**

---

## 🚀 What is CloudLens?

CloudLens is a powerful, open-source cloud inventory and visibility tool designed to help security and operations teams gain comprehensive insights into their AWS cloud environments. We believe that **visibility is the foundation of security**, and our mission is to eliminate blind spots in your cloud infrastructure.

### 🎯 Key Features

- **🌍 Region-wise Visibility** - Map your entire AWS footprint across all regions
- **🔒 Security-First Approach** - Read-only access with non-intrusive discovery
- **🌐 Internet Exposure Detection** - Identify services exposed to the public internet
- **📊 Interactive Dashboard** - React-based visualization of your cloud attack surface
- **🛠️ CLI & API** - Flexible tooling for automation and integration
- **☁️ Multi-Service Support** - EC2, S3, IAM, CloudTrail, RDS, Lambda, KMS, Config, GuardDuty, and more

## 🎖️ Why CloudLens?

### For Security Teams
- **Reduce Unknown Risks** - Discover shadow IT and forgotten resources
- **Surface Exposure Points** - Identify internet-facing services and potential attack vectors
- **Compliance Readiness** - Maintain accurate inventory for audits and compliance

### For Operations Teams
- **Resource Optimization** - Identify unused or underutilized resources
- **Cost Management** - Track resource distribution across regions
- **Change Management** - Monitor infrastructure changes over time

## 🏗️ Architecture

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   CloudLens     │───▶│   AWS APIs       │───▶│   Your AWS      │
│   Dashboard     │    │   (Read-Only)    │    │   Resources     │
└─────────────────┘    └──────────────────┘    └─────────────────┘
         │                                               │
         ▼                                               ▼
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Structured    │    │   Data           │    │   Multi-Region  │
│   Analysis      │    │   Aggregation    │    │   Discovery     │
└─────────────────┘    └──────────────────┘    └─────────────────┘
```

## 🛡️ Security & Trust

- **Read-Only Access** - Never modifies your AWS resources
- **No Data Storage** - Your cloud data stays in your environment
- **Open Source** - Full transparency with community-driven development
- **Minimal Permissions** - Uses least-privilege AWS access patterns

## 🤝 Community & Contributing

We're building CloudLens as a community-driven project. Whether you're a security professional, DevOps engineer, or cloud enthusiast, there are many ways to get involved:

- 🐛 **Report Issues** - Help us improve by reporting bugs
- 💡 **Feature Requests** - Share ideas for new capabilities
- 🔧 **Code Contributions** - Submit pull requests
- 📝 **Documentation** - Help improve our guides and tutorials
- 💬 **Community Support** - Help others in discussions

### Contributing Guidelines
- Fork the repository and create feature branches
- Follow our coding standards and include tests
- Update documentation for new features
- Join our community discussions for design decisions

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/CloudLensHQ/cloudlens-project?style=social)
![GitHub forks](https://img.shields.io/github/forks/CloudLensHQ/cloudlens-project?style=social)
![GitHub issues](https://img.shields.io/github/issues/CloudLensHQ/cloudlens-project)
![GitHub pull requests](https://img.shields.io/github/issues-pr/CloudLensHQ/cloudlens-project)


**Ready to illuminate your cloud?** Start with CloudLens today and take control of your AWS visibility.

[![Get Started](https://img.shields.io/badge/Get%20Started-brightgreen?style=for-the-badge)](https://github.com/CloudLensHQ/cloudlens-project)