# Cardiff University Chatbot

Main repository: https://git.cardiff.ac.uk/c21089970/chatbot-intranet

Link to the deployed application: https://cu-chatbot.kavin.rocks/ (blocked on eduroam)

## Running the Application

### Please prepare the API keys for the following tools:

-   OpenAI
-   TogetherAI
-   AnthropicAI
-   Cohere
-   Deepgram
-   Newrelic

## Prepare a SearXNG instance with JSON format enabled.

You can set the SEARX_URL environment variable to the URL of the SearXNG instance.

#### Prepare a Qdrant cluster or instance.

Set the QDRANT_URL, and QDRANT_API_KEY environment variables.

### In the Frontend

-   Clone the repository: https://git.cardiff.ac.uk/c21089970/chatbot-intranet-ui
-   Install pnpm following the documentation: https://pnpm.io/installation
-   Open a terminal in the repository
-   Run `pnpm install`
-   Run `pnpm dev` for development

### In the Backend

-   Clone the repository: https://git.cardiff.ac.uk/c21089970/chatbot-intranet-api
-   Add the API keys and instances to environment variables
-   Open a terminal
-   Run `pip install`
-   Run `uvicorn main:app --reload`

## How to Maintain the Project in the Future

The current setup uses Docker compose files but for an ideal production deployment, Kubernetes could be used, with the help of the Docker files.
