# AI Agent Boilerplate 🤖

A collection of scaffolding templates and guidelines for popular AI agent frameworks. This repository aims to provide a structured starting point for building AI agent-based applications. Right now, the scaffold works with cursorrules (Read more about cursorrules [here](https://medium.com/@ashinno43/what-are-cursor-rules-and-how-to-use-them-ec558468d139)).

## 🎯 Motivation

Building AI agents can be complex, with different frameworks offering various approaches and architectures. This repository was inspired by VRSEN's [Agency Swarm](https://vrsen.github.io/agency-swarm). This serves as a centralized resource for:

- Standardized project structures for different AI agent frameworks
- Best practices and guidelines for each framework
- Quick-start templates to accelerate development
- Framework-specific configuration and setup instructions

## 🚀 Supported Frameworks

Currently, this repository includes templates for:

### [Agency Swarm](https://vrsen.github.io/agency-swarm)
- Multi-agent collaborative framework
- Focused on creating agencies of specialized AI agents
- Includes tool integration and agent communication patterns

### [Crew AI](https://docs.crewai.com)
- Role-based autonomous AI agents
- YAML-based configuration for agents and tasks
- Structured workflow orchestration

## 📁 Repository Structure

```
agent-boilerplate/
├── agency-swarm/
│   └── .cursorrules       # Agency Swarm guidelines and setup
├── crew-ai/
│   └── .cursorrules       # Crew AI guidelines and setup
└── README.md
```

## 🛠️ Getting Started

### Using .cursorrules Files

The `.cursorrules` files in this repository act as intelligent scaffolding assistants that help you build your AI agent projects. Here's how to use them:

1. **Using degit (Recommended)**
   ```bash
   # For Agency Swarm
   npx degit epireve/agent-boilerplate/agency-swarm/.cursorrules .cursorrules

   # For Crew AI
   npx degit epireve/agent-boilerplate/crew-ai/.cursorrules .cursorrules
   ```

2. **Manual Copy**
   - Navigate to the framework directory you want to use
   - Copy the `.cursorrules` file to your project root
   - Make sure to name it exactly as `.cursorrules`

### Using with Cursor Editor

1. Open your project in Cursor
2. The `.cursorrules` file will automatically be detected
3. Start Cursor Composer
4. Describe your agents and tasks:
   - Be specific about each agent's role and responsibilities
   - Define clear tasks and goals
   - Include any specific tools or APIs needed
   - Example: "Create a research agent that analyzes market data and a writer agent that generates reports based on the analysis"
5. Watch Cursor Composer scaffold your project:
   - It will create necessary files and directories
   - Set up agent configurations
   - Generate boilerplate code
   - Add required dependencies


## 🚧 Work in Progress

This project is actively under development. We are:
- Adding more framework templates
- Expanding documentation and examples
- Incorporating community feedback
- Adding real-world use cases and patterns

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add support for new frameworks
- Improve existing templates
- Share best practices
- Report issues or suggest improvements

## 📄 License

MIT License - feel free to use this in your own projects!

---
⚡️ Build for [Cursor](https://cursor.com/)
