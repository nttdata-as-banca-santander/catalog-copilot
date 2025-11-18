---
title: 'Create ARCHITECTURE.md'
mode: agent
tags: ["document", "code"]
description: 'Create a comprehensive ARCHITECTURE.md file for the project'
excerpt: 'Create a comprehensive ARCHITECTURE.md file for the project'
layout: prompt_detail
---

Review the entire project folder and codebase to create a comprehensive ARCHITECTURE.md file that includes essential sections such as system overview, components, data flow, architectural decisions, and module interaction patterns. Ensure the documentation is clear, concise, and follows best practices for technical documentation.

## Content Requirements

### High-Level System Overview
- Describe the overall purpose and functionality of the system.
- Explain the architectural style/pattern used (e.g., Hexagonal, Microservices, Layered).
- Mention the main technologies and frameworks employed.

### Main Components
- Identify and describe the primary components/modules of the system.
- Explain the responsibilities of each component.
- Describe how components interact with each other.

### Data Flow

- Illustrate the data flow within the system using mermaid diagrams.
- Ensure diagrams are accessible (clear shapes, labels, colors).
- Explain the interactions and data exchanges between components.

### Key Architectural Decisions
- Document significant architectural decisions made during development.
- Justify why certain patterns, technologies, or structures were chosen.
- Discuss trade-offs and alternatives considered
- Highlight any scalability, maintainability, performance, or security considerations.

## Guidelines

### Content and Structure
- Focus only on information necessary for developers to understand the system architecture.
- Use clear, concise language and keep it scannable with good headings.
- All text must be written in English.
- Keep content under 500 KiB (GitHub truncated beyond this).

### Technical Requirements
- Use Github Flavored Markdown.
- Use relative links instead of absolute URLs for files within the repository.
- Ensure all links works when the repository is cloned.
- Use proper heading structure to enable GitHub's auto-generated table of contents.
- Verify mermaid syntax is correct and create the diagrams taking accessibility guidelines into account (styling, colors, etc.).

### What NOT to include

Do NOT include:
- Detailed API documentation (link to separate docs instead)
- License text

Analyze the project structure, dependencies, and code to make the ARCHITECTURE.md file accurate and comprehensive.