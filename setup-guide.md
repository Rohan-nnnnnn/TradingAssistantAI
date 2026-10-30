TRADING ASSISTANT AI – SETUP GUIDE

Overview

This guide explains how to configure and execute Trading Assistant AI using n8n, a market data API, and an AI model or LLM service.

Prerequisites

Ensure you have:

- n8n installed and running.
- Access to the configured market data API.
- A valid market data API key, if required.
- The AI model or LLM service configured in n8n.
- Required credentials configured in n8n.
- The Trading Assistant AI workflow imported or created.

1. Configure Market Data API

Open the market data API configuration used by the workflow.

Verify that:

- The API endpoint is correct.
- Required authentication credentials are configured.
- The request parameters accept the stock symbol.
- The API returns the market information required by the analysis workflow.

2. Configure AI Processing

Open the AI-related nodes in n8n.

Verify that:

- The required AI model or LLM service is available.
- Credentials are configured if required.
- The prompts receive the expected market data.
- The output follows the expected structured format.

3. Configure Workflow Input

Check the workflow's input configuration.

Ensure that a stock symbol can be provided and passed to the market data retrieval stage.

4. Verify Workflow Connections

Inspect the workflow connections.

Confirm that:
- Market data retrieval feeds the analysis stages.
- Technical and momentum analysis receive the required information.
- AI processing receives the analysis context.
- The final output contains the expected analysis fields.
- Market data failures follow the configured error path.
- AI failures follow their dedicated error path.

5. Execute the Workflow

1. Start n8n.
2. Open the Trading Assistant AI workflow.
3. Provide a valid stock symbol.
4. Execute the workflow.
5. Inspect the market data retrieval result.
6. Review the technical and momentum analysis.
7. Check the generated trading signal and risk level.
8. Verify the final structured output.

Troubleshooting

Market Data API Failure

- Verify the API endpoint.
- Check the API credentials.
- Confirm the stock symbol is valid.
- Inspect the HTTP Request node response.

AI Processing Failure

- Verify the AI service is accessible.
- Check model availability and credentials.
- Inspect the AI node input and output.
- Review the configured error-handling path.

Unexpected Analysis Output

- Verify the market data received by the workflow.
- Check the analysis node inputs.
- Confirm the AI prompt and expected output structure.

Notes

- Market data availability depends on the configured provider.
- AI-generated analysis may contain inaccuracies.
- API limits and service availability may affect execution.
- Trading Assistant AI is an analysis project, not a financial advisory service.
