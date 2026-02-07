# GitHub Copilot Instructions for Anton Repository

## Project Overview

Anton is an empty repository designed to be a flexible foundation for new capabilities and projects. Any task executed on this repository should be considered a new feature that needs to be created from scratch.

## Repository Structure

This is a new repository with minimal structure. Contributors and Copilot agents should:

- Create appropriate directory structures as needed for new features
- Follow modern best practices for the chosen technology stack
- Include proper documentation for any new capabilities

## General Guidelines

### Code Quality

- Write clean, maintainable, and well-documented code
- Follow industry-standard best practices for the chosen language/framework
- Include appropriate error handling and logging
- Write meaningful commit messages that describe the changes

### Testing

- Include unit tests for new functionality
- Ensure tests are comprehensive and cover edge cases
- Use appropriate testing frameworks for the technology stack
- Maintain test coverage standards

### Documentation

- Document all new features and capabilities in the README.md
- Include inline code comments for complex logic
- Provide usage examples where appropriate
- Keep documentation up-to-date with code changes

### Security

- Never commit secrets, API keys, or sensitive credentials
- Use environment variables for configuration
- Follow security best practices for the chosen technology
- Validate and sanitize all inputs

### Dependencies

- Keep dependencies up-to-date
- Only add necessary dependencies
- Document why each dependency is needed
- Use lock files to ensure reproducible builds

## File Organization

- Use clear, descriptive file and directory names
- Group related functionality together
- Keep configuration files in the root directory
- Place source code in a dedicated directory (e.g., `src/`, `lib/`, or appropriate for the stack)

## Version Control

- Make small, focused commits
- Write descriptive commit messages
- Keep the repository clean (use .gitignore appropriately)
- Don't commit build artifacts or dependencies

## Agent Responsibilities

When working on this repository:

1. **Understand First**: Since this is an empty repository, understand the requirement fully before creating new capabilities
2. **Create Structure**: Set up appropriate project structure for the technology being used
3. **Best Practices**: Follow modern best practices for the chosen stack
4. **Documentation**: Document everything you create
5. **Testing**: Include tests for new functionality
6. **Review**: Ensure your changes are minimal and focused on the specific task

## Protected Areas

- Never modify LICENSE file without explicit instruction
- Be cautious with .git directory and configurations
- Don't remove or modify these instruction files without explicit request

## Technology Stack

This repository currently has no defined technology stack. When implementing new features:

- Choose appropriate, modern technologies for the task
- Document the technology choices and reasoning
- Set up proper tooling (linters, formatters, build tools)
- Include instructions for setting up the development environment
