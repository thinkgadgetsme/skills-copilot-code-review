# Backend Development Instructions

This file provides guidelines and instructions for backend development in this repository.

## Purpose
- Ensure consistency in backend code quality and style.
- Provide best practices for using frameworks, libraries, and tools.
- Help contributors understand the backend architecture.

## Usage
- Follow the established folder structure for backend modules and routers.
- Use modern Python standards and recommended libraries.
- Prefer modular and reusable code.
- Document any custom logic or complex backend features.

## Best Practices
- Validate and sanitize all user input.
- Handle errors and exceptions explicitly.
- Optimize database queries and backend performance.
- Use environment variables for sensitive configuration.
- Write unit and integration tests for backend logic.

## Contribution
- Submit backend changes via pull requests for review.
- Include test results or coverage reports for significant backend updates.
- Report issues or suggest improvements for the backend workflow.

---
applyTo: "backend/**/*,*.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Error handling is only logged on the server. Do not propagate to the frontend.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If possible breaking changes are found, mention them to the developer.

---
For more information, refer to the main README or reach out to the maintainers.