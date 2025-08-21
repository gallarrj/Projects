# n8n Codespaces Development Environment

This devcontainer provides a complete development environment for working with n8n workflows.

## What's Included

- **n8n**: Workflow automation tool installed globally
- **Node.js 18**: Runtime environment
- **Docker-in-Docker**: For containerized workflows
- **VS Code Extensions**: JSON, TypeScript, Prettier, and TailwindCSS support

## Getting Started

1. Open this repository in GitHub Codespaces
2. Wait for the container to build and n8n to start automatically
3. Access n8n at `http://localhost:5678` or use the forwarded port
4. Start building your workflows!

## n8n Commands

- Start n8n: `n8n start`
- Stop n8n: Find the process and kill it or restart the Codespace
- View logs: `cat /tmp/n8n.log`

## Port Configuration

- Port 5678: n8n Web Interface (automatically forwarded)

The n8n interface will be available through GitHub Codespaces port forwarding.