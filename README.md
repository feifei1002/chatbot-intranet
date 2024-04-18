# Cardiff University Chatbot

Main repository: https://git.cardiff.ac.uk/c21089970/chatbot-intranet

Link to the deployed application: https://cu-chatbot.kavin.rocks/



## Running the Application

#### In order to run the application, please prepare the API keys for the following tools:
* OpenAI
* TogetherAI
* ClaudeAI
* Cohere
* Deepgram
* Newrelic

### In the Frontend
- Clone the repository: https://git.cardiff.ac.uk/c21089970/chatbot-intranet-ui
- Install pnpm by opening windows powershell and typing ```iwr https://get.pnpm.io/install.ps1 -useb | iex```
- Open a terminal in the repository
- Run ```pnpm install```
- Run ```pnpm run dev``` for development

### In the Backend
- Clone the repository: https://git.cardiff.ac.uk/c21089970/chatbot-intranet-api
- Add the api keys to environment variables
- Open a terminal
- Run ```pip install```
- Run ```uvicorn main:app --reload```




## How to Maintain the Project in the Future

The current setup uses Docker compose files but for ideal production Kubernetes could be used, which involved docker images. (Check that this is correct)
