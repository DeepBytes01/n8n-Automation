# 🚀 n8n Automation Learning Hub

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![n8n](https://img.shields.io/badge/n8n-v1.0+-blue.svg)](https://n8n.io/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

> A curated collection of n8n automation workflows, examples, and learning resources. Master workflow automation one node at a time.


## 🎯 About

This repository serves as my personal journey into mastering **n8n** - the fair-code workflow automation tool. Here you'll find:
- Practical automation workflows
- Real-world use cases
- Learning exercises and experiments
- Best practices and patterns
- Integration examples with popular services

## 📦 Prerequisites

- [n8n](https://n8n.io/) (self-hosted or cloud version)
- [Docker](https://www.docker.com/) (optional, for local setup)
- Basic understanding of APIs and webhooks
- Accounts for services you want to automate (varies by workflow)

## 🚀 Getting Started

### Local Setup with Docker

```bash
# Clone the repository
git clone https://github.com/yourusername/n8n-learning.git
cd n8n-learning

# Run n8n with Docker
docker run -it --rm \
  --name n8n \
  -p 5678:5678 \
  -v ~/.n8n:/home/node/.n8n \
  n8nio/n8n
