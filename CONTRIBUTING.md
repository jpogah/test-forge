# Contributing Guidelines

Thank you for your interest in contributing to this project! Here's how you can help.

## Prerequisites

- [Go](https://go.dev/) 1.18 or later
- Git

## Getting Started

1. Fork the repository.
2. Clone your fork locally:
   ```bash
   git clone https://github.com/<your-username>/forge-hello-world.git
   cd forge-hello-world
   ```
3. Verify the project builds and runs:
   ```bash
   go run main.go
   ```
4. Create a new branch for your work:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Development Workflow

1. Make your changes.
2. Format your code with `gofmt`:
   ```bash
   gofmt -w .
   ```
3. Run `go vet` to catch common issues:
   ```bash
   go vet ./...
   ```
4. Test the server locally:
   ```bash
   go run main.go
   curl http://localhost:8080/
   ```

## Making Changes

- Keep changes focused and limited to a single issue or feature per branch.
- Write clear, descriptive commit messages.
- Follow existing code style and conventions.
- Run `gofmt` before committing to ensure consistent formatting.
- Add or update tests for any new or changed functionality.

## Submitting a Pull Request

1. Push your branch to your fork.
2. Open a pull request against the `main` branch.
3. Provide a clear description of what your changes do and why.
4. Reference any related issues (e.g., "Fixes #123").
5. Ensure your code passes `go vet` and is formatted with `gofmt`.

## Reporting Issues

- Search existing issues before opening a new one.
- Include steps to reproduce the problem.
- Provide details about your environment (OS, Go version, etc.).
- Use a clear, descriptive title.

## Code of Conduct

- Be respectful and constructive in all interactions.
- Welcome newcomers and help them get started.
- Focus on what is best for the community and the project.
