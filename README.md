# A basic guide to Next.js AI SDk using openai as the provider and gpt-4.1-nano as the model
Follow the steps below

## Steps
- create a next js project
  ```bash
  npx create-next-app@latest
  cd project dir
- install the next js AI SDK
  ```bash
  npm install ai @ai-sdk/openai @ai-sdk/react zod
  // ai package is the core sdk package
  // @ai-sdk/openai connects to the openai model
  // @ai-sdk/react contains React-specific hooks to aid AI integration
  // zod creates type-safe schemas used in the project
- Create an openai API key on the [openai dev platform](https://platform.openai.com)
- Store the key in your env.local file as
  ```bash
  OPENAI_API_KEY="your openai api key"


### Note
The openai API key isn't free and you can make the model global placing it in your env file and change it to your preferred model
