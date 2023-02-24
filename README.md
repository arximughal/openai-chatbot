# openai-chatbot
Chatbot like Chat-GPT3 with openai package.

## Folder structure
The folder contains two sub folders
- client: contains the React app with a Chat UI build using Tailwind CSS
- server: contains the Express app that consumes Open AI API

### Create a .env file in 'server' folder:
The file should contain the following entries:
  - PORT: The port on which application will run
  - OPENAI_API_KEY: Your own OPENAI API Key, Check the steps mentioned here to generate the API key for your account:
  https://platform.openai.com/docs/api-reference/authentication


### To Run the Project:
- cd into client folder and run `yarn && yarn dev`
- cd into server folder and run `yarn && yarn dev`
