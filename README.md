# Streamlit

Streamlit is an open-source Python framework that makes it easy to build and share beautiful, custom web apps for machine learning and data science. Turn data scripts into shareable web applications in minutes without front-end experience. Streamlit Community Cloud provides free hosting directly from GitHub repositories.

**Human URL:** [https://streamlit.io](https://streamlit.io)  
**API Reference:** [https://docs.streamlit.io/develop/api-reference](https://docs.streamlit.io/develop/api-reference)

## Links

- [Documentation](https://docs.streamlit.io)
- [GitHub](https://github.com/streamlit/streamlit)
- [Community Forum](https://discuss.streamlit.io)
- [Blog](https://blog.streamlit.io)
- [App Gallery](https://streamlit.io/gallery)
- [Changelog](https://docs.streamlit.io/develop/quick-reference/changelog)
- [PyPI](https://pypi.org/project/streamlit/)
- [Terms of Service](https://streamlit.io/terms-of-use)

## APIs

### Streamlit Python API

The core Streamlit Python library providing functions for displaying data, input widgets, layout, media, charts, performance caching, and database connections.

- [Documentation](https://docs.streamlit.io/develop/api-reference)
- [GitHub](https://github.com/streamlit/streamlit)

### Streamlit Community Cloud API

Programmatic access for deploying and managing Streamlit apps on Community Cloud from GitHub repositories.

- [OpenAPI Spec](openapi/streamlit-cloud-openapi.yml)
- [Documentation](https://docs.streamlit.io/deploy/streamlit-community-cloud)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [streamlit-cloud-openapi.yml](openapi/streamlit-cloud-openapi.yml) | Community Cloud API — app deployment, secrets, workspaces |

### JSON Schema

| File | Description |
|---|---|
| [streamlit-app-schema.json](json-schema/streamlit-app-schema.json) | JSON Schema for Streamlit Community Cloud app objects |

### JSON Structure

| File | Description |
|---|---|
| [streamlit-app-structure.json](json-structure/streamlit-app-structure.json) | Field structure for Community Cloud app objects |

### JSON-LD Context

| File | Description |
|---|---|
| [streamlit-context.jsonld](json-ld/streamlit-context.jsonld) | JSON-LD context mapping Streamlit vocabulary to schema.org |

### Examples

| File | Description |
|---|---|
| [streamlit-list-apps-example.json](examples/streamlit-list-apps-example.json) | List deployed Streamlit apps |
| [streamlit-deploy-app-example.json](examples/streamlit-deploy-app-example.json) | Deploy a new app from GitHub |

### Spectral Rules

| File | Description |
|---|---|
| [streamlit-rules.yml](rules/streamlit-rules.yml) | Spectral ruleset for Streamlit Cloud API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/cloud-api.yaml](capabilities/shared/cloud-api.yaml) | Community Cloud API — apps, secrets, workspaces |

#### Workflow Capabilities

| File | Description |
|---|---|
| [capabilities/app-deployment.yaml](capabilities/app-deployment.yaml) | App deployment and management workflow (8 tools) |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/streamlit-vocabulary.yml](vocabulary/streamlit-vocabulary.yml) | Streamlit domain vocabulary and framework terminology |

## Tags

- Data Science
- Machine Learning
- Open Source
- Python
- Web Applications

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
