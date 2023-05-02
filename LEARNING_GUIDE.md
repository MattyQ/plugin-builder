Learning Document: ChatGPT Plugins

Overview:
- This document provides learning instructions on the topic of "ChatGPT Plugins."
- It is organized into sections, each covering a specific aspect of ChatGPT plugins.
- Additional details on specific topics can be found in the linked documents provided.
- ChatGPT plugins enhance the model's capabilities by connecting it to external services.

Table of Contents:
1. Introduction
2. Plugin Manifest (See: Plugin Manifest Details)
3. OpenAPI Definition (See: OpenAPI Definition Details)
4. Writing Descriptions
5. Best Practices

Introduction:
- ChatGPT plugins are extensions that connect ChatGPT to third-party applications.
- They enhance ChatGPT's capabilities by allowing it to interact with external APIs.
- Plugins can retrieve real-time information, access knowledge bases, and perform user actions.

Plugin Manifest:
- Every plugin requires an "ai-plugin.json" file hosted on the API's domain.
- The manifest file contains metadata, authentication details, and an OpenAPI specification.
- The file should be accessible at "https://example.com/.well-known/ai-plugin.json".

OpenAPI Definition:
- The OpenAPI specification documents the plugin's API and its functionality.
- It defines available endpoints, parameters, and descriptions.
- The model uses the OpenAPI specification to understand how to use the plugin.

Writing Descriptions:
- Descriptions guide the model on how to use the plugin effectively.
- They should be clear, concise, and written in natural language.
- Avoid prescribing specific triggers or controlling the model's behavior.

Best Practices:
- Keep descriptions and responses concise due to the model's limited context window.
- Avoid encouraging the model to use the plugin when not explicitly requested by the user.
- Return raw data in API responses; ChatGPT will generate its own natural language response.

Summary:
- ChatGPT plugins enhance the model's capabilities by connecting it to external services.
- Developers create a manifest file and OpenAPI specification to define the plugin.
- Descriptions and best practices guide the model's interaction with the plugin.

Connected Documents:
- Plugin Manifest Details: A detailed guide on creating and configuring the plugin manifest file.
- OpenAPI Definition Details: An in-depth explanation of the OpenAPI specification for ChatGPT plugins.
