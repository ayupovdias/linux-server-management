## Project Purpose

This project is a Linux server management tool. It helps users check system information, disk usage, memory, and services.

## Project Structure

The project contains Go source code, tests, and documentation.

```text
cmd/          - main application
internal/     - project logic
docs/         - documentation
tests/        - tests
README.md     - project information
```

## Development Workflow

Developers create a new branch, write and test their code, commit the changes, and create a Pull Request. Another developer reviews the code before it is merged into `main`.

## Branching Strategy

The `main` branch contains stable code. New features and changes are developed in separate branches.

Example:

```text
main
 └── feature/health-check
```

## Contribution Process

1. Create a new branch.
2. Make your changes.
3. Test the changes.
4. Commit and push the branch.
5. Create a Pull Request.
6. Fix review comments if needed.
7. Merge after approval.

## Testing Process

Go tests are used to check the application.

Run:

```bash
go test ./...
```

The application is also tested manually on a Linux server.

## Troubleshooting Process

When a problem occurs, check the error message, logs, configuration, and system status. The `docs/troubleshooting.md` file contains common problems and their solutions.
