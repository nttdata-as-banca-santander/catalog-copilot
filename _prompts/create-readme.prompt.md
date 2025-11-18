---
title: 'Create README.md'
mode: agent
tags: ["document", "code"]
description: 'Create a comprehensive README.md file for the project'
excerpt: 'Create a comprehensive README.md file for the project'
layout: prompt_detail
---

Review the entire project folder and codebase to create a comprehensive README.md file that includes essential sections such as description, installation, usage and contribution guidelines. Ensure the documentation is clear, concise, and follows best practices for technical documentation.

## Content Requirements

### Description
- Add an extensive project description explaining what the project does.
- Highlight the main features and functionalities.
- Add subsections for each component to elaborate on features or functionalities.
- Explain the components for each major part of the project.

### Project Architecture
- Provide a high-level overview of the system architecture.
- Explain how different components interact with each other.
- Link the ARCHITECTURE.md file for detailed architecture information.

### Installation
- Provide clear installation and setup instructions.
- Include prerequisites, dependencies, configuration and step-by-step setup guide.
- Mention any environment variables or configuration needed.
- Include troubleshooting tips for common installation issues.

### Usage
- Explain how to use the project with code examples.
- Include command-line examples, API usage, or GUI instructions as applicable.
- If the project is a code library, provide sample code snippets demonstrating all functionalities and how to integrate and use it.
- Add a sections for each component.

### Contribute
- Provide contribution guidelines for developers.
- Add the folder structure of the project to help contributors navigate the codebase. **Do not show files, onlt folders and subfolders.**
- Include information about coding standards.

## Guidelines

### Content and Structure
- Focus only on information necessary for developers to understand and get started using and contributing to the project.
- Use clear, concise language and keep it scannable with good headings.
- Include relevant code examples and usage snippets.
- Add badges for building status, version, if appropriate.
- All text must be written in English.
- Keep content under 500 KiB (GitHub truncated beyond this).

### Technical Requirements
- Use Github Flavored Markdown.
- Use relative links instead of absolute URLs for files within the repository.
- Ensure all links works when the repository is cloned.
- Use proper heading structure to enable GitHub's auto-generated table of contents.

### What NOT to include

Do NOT include:
- Detailed API documentation (link to separate docs instead)
- Extensive troubleshooting guides (use wikis or separate documentation)
- Changelogs (use CHANGELOG.md instead)
- License text

Analyze the project structure, dependencies, and code to make the README.md file accurate, helpful, and focused on getting users productive quickly.