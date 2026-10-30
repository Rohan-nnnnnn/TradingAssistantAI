# Trading Assistant AI – AI-Powered Market Analysis System

Trading Assistant AI is an automated market analysis workflow built using **n8n, AI models, and market data APIs**. It analyzes stock market information, evaluates technical indicators and market momentum, and generates AI-assisted trading insights with risk assessments.

The system also includes error-handling paths for market data retrieval and AI processing failures.

## Features

- **Automated Market Data Retrieval:** Fetches stock market information through configured market data APIs.
- **Technical Analysis:** Evaluates technical signals to understand market conditions.
- **Momentum Analysis:** Analyzes market momentum to support decision-making.
- **AI-Powered Insights:** Generates structured market analysis using AI.
- **Risk Assessment:** Provides risk levels alongside analysis results.
- **Trading Signals:** Generates signals such as BUY, SELL, or HOLD based on the analysis.
- **Error Handling:** Includes separate handling paths for market data failures and AI processing failures.

## Technology Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation and orchestration |
| Market Data API | Stock market information retrieval |
| AI / LLM | Market analysis and insight generation |
| HTTP Request | API communication |
| Workflow Error Handling | Failure management |

## Workflow

1. The workflow receives a stock symbol as input.
2. Market data is retrieved through the configured API.
3. Retrieved information is processed for analysis.
4. Technical indicators and market momentum are evaluated.
5. AI processes the analysis information.
6. The system generates a trading signal and risk assessment.
7. Structured analysis results are returned.
8. Market data failures and AI failures are handled through dedicated error paths.

## Analysis Output

The workflow generates structured analysis containing information such as:

- Stock symbol
- Trend summary
- Momentum summary
- Technical signal
- Risk level
- AI-generated market insights

## Error Handling

Trading Assistant AI includes dedicated failure-handling paths for:

- Market data API failures.
- AI processing failures.

This helps prevent unsuccessful processing from being treated as a valid analysis result.

## Setup Requirements

Before running the workflow, ensure you have:

- n8n installed and running.
- Access to the configured market data API.
- Required API credentials.
- The AI model or LLM service configured in n8n.
- The Trading Assistant AI workflow imported or created.

## How to Use

1. Open the Trading Assistant AI workflow in n8n.
2. Provide a valid stock symbol.
3. Execute the workflow.
4. Allow the market data retrieval and analysis steps to complete.
5. Review the generated technical signal, risk level, and market summaries.
6. Check the execution output for any errors.

## Important Disclaimer

Trading Assistant AI is an experimental market analysis and automation project. Its outputs are AI-assisted insights, not guaranteed predictions or financial advice. Users should independently verify market information before making investment decisions.

## Project Objective

The objective of Trading Assistant AI is to demonstrate how workflow automation, market data integration, technical analysis, and AI-generated insights can be combined into an automated stock market analysis system.

## Author

**Rohan Narlawar**

- GitHub: [Rohan-nnnnnn](https://github.com/Rohan-nnnnnn)
- LinkedIn: [linkedin.com/in/rohan-narlawar-149291354](https://www.linkedin.com/in/rohan-narlawar-149291354)
- Email: [rohannarlawar31@gmail.com](mailto:rohannarlawar31@gmail.com)
