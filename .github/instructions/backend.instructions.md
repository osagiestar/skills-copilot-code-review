---
applyTo: "backend/**/*,*.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Error handling is only logged on the server. Do not propagate to the frontend.
- Ensure all APIs are explained in the documentation.
