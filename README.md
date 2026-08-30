<div align="center">

# Mei
### An autonomous AI agent platform for creating, building, researching, and operating software.

Mei is an independent MEIOCG project derived from the Agent Zero open-source project. It provides a capable foundation for agentic work across a Linux environment, browser, files, projects, memory, tools, skills, plugins, and multi-agent workflows.

**Current public endpoint:** https://realizer.meiocg.org

[![Project](https://img.shields.io/badge/Project-Mei-111827?style=for-the-badge)](https://github.com/castelnoleal/myMei)
[![Realizer](https://img.shields.io/badge/Realizer-realızer.meiocg.org-4F46E5?style=for-the-badge)](https://realizer.meiocg.org)
[![License](https://img.shields.io/badge/License-MIT-16A34A?style=for-the-badge)](./LICENSE)

</div>

# What is Mei?

Mei is being developed as the agent layer of the MEIOCG ecosystem. The goal is not to create a simple chat interface, but an agent that can reason about a goal, use tools, work with files and software, coordinate specialized agents, inspect results, recover from failures, and complete real tasks.

## Current foundation

The repository inherits the mature capabilities of its upstream foundation, including:

- Linux desktop and application interaction
- browser automation and web-page inspection
- projects, workspace isolation, and memory
- tools, skills, plugins, MCP, and extensibility
- document and office workflows
- multi-agent cooperation
- model-provider abstraction through LiteLLM
- Docker-based deployment

## Mei direction

We are progressively replacing the upstream product identity with Mei-specific behavior and infrastructure while preserving required upstream attribution and licensing.

Planned Mei capabilities include:

- autonomous planning and execution loops
- verification and self-repair workflows
- MEIOCG-specific tools and project integrations
- Realizer media-generation integration
- coding and app-building workflows
- browser and computer-use automation
- specialized research, development, design, testing, and deployment agents
- a product-focused web experience

## Realizer

Mei's current public media/product endpoint is:

**https://realizer.meiocg.org**

Realizer is intended to become one of Mei's specialized execution capabilities, especially for AI-generated media and creation workflows.

## Upstream

Mei is derived from:

https://github.com/agent0ai/agent-zero

The original MIT license and required copyright notice are retained in `LICENSE`.

## Development principle

Mei should preserve what already works, add functionality in small verifiable increments, and test changes against the actual running system before considering a capability complete.
