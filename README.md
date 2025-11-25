# Vanij MCP Platform


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js](https://img.shields.io/badge/Node.js-20%2B-green.svg)](https://nodejs.org/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

A comprehensive Model Context Protocol (MCP) platform providing standardized integrations between AI assistants and various services and APIs. This repository contains both JavaScript and Python implementations of MCP servers and clients for seamless service integration.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Quick Start](#quick-start)
- [JavaScript Setup](#javascript-setup)
- [Python Setup](#python-setup)
- [Sample MCP Servers](#sample-mcp-servers)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [API Collections](#api-collections)
- [Contributing](#contributing)
- [License](#license)

## 📁 Project Structure

```
.
├── mcp_servers/
│   ├── js/                           # JavaScript implementation
│       ├── clients/                  # MCP clients
│       │   ├── src/
│       │   │   ├── client_and_server_config.ts  # Listed MCP Clients & Servers Configurations.
│       │   │   └── ...
│       │   ├── package.json   
│       │   └── ...
│       ├── servers/                  # MCP servers
│       │   └── GCLS_MCP
│       └── package.json
│   
├── mcp_servers_documentation/        # Detailed documentation of about MCP servers
├── postman_api_collections/         # API testing collections
└── README.md
```

## 🚀 Quick Start

### Prerequisites

- **Node.js**208+ (for JavaScript implementation)
- **npm** or **yarn** (for JavaScript dependencies)

## 🟨 JavaScript Setup

### 1. Navigate to JavaScript Directory

```bash
cd mcp_servers/js
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Build All Components

```bash
npm run build:all
```

### 4. Start Development Server

```bash
npm run dev:client
```

### 5. Available Scripts

- `npm run build:all` - Build all clients and servers
- `npm run dev:client` - Run client in development mode
- `npm run test` - Run test suite
- `npm run lint` - Run linting checks

### Configuration

JavaScript configuration is managed in:
```
mcp_servers/js/clients/src/client_and_server_config.ts
```

## 📚 Documentation

Comprehensive documentation for each MCP server is available in the `mcp_servers_documentation/` directory:

- Server-specific setup guides
- API reference documentation
- Integration examples
- Troubleshooting guides

### Key Documentation Files

- `mcp_servers_documentation/server_setup.md` - General server setup
- `mcp_servers_documentation/api_reference.md` - API documentation
- `mcp_servers_documentation/examples/` - Integration examples

## 🧪 API Collections

The `postman_api_collections/` directory contains Postman collections for testing and interacting with MCP servers:

1. Import collections into Postman
2. Configure environment variables
3. Test API endpoints
4. Validate integrations

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Development Guidelines

- Follow existing code style and conventions
- Add tests for new features
- Update documentation as needed
- Ensure all tests pass before submitting PR

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Documentation**: Check the `mcp_servers_documentation/` directory
- **Issues**: Open an issue on GitHub
- **Discussions**: Use GitHub Discussions for questions

## 🏗️ Roadmap

- [ ] Additional language implementations (Go, Rust)
- [ ] More third-party service integrations
- [ ] Enhanced monitoring and logging
- [ ] Docker containerization
- [ ] Kubernetes deployment guides

---
