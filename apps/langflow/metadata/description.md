
# Langflow

Langflow is a powerful UI for building, debugging, and deploying LLM flows with a visual interface.

This app runs Langflow with a persistent PostgreSQL database for storing flows, users, and settings.

## Features

- Visual flow builder for LLM applications
- Persistent PostgreSQL database
- Support for multiple AI models and integrations
- Flow templates and components
- API endpoints for programmatic access

## Access Information

- **Web UI:** Available through Runtipi dashboard or direct port access
- **Default Port:** 7860
- **Database:** PostgreSQL 16 with persistent storage
- **Authentication:** No default authentication (configure as needed)

## Data Persistence

- **Langflow data:** Stored in `/app/langflow` directory
- **Database data:** PostgreSQL data persisted separately
- **All data is preserved** across container restarts

For more information, see [Langflow documentation](https://docs.langflow.org/).
