# Getting Started

## Create an environment variable file

Create a .env file in the project root directory and add the following content (note that the variable name must start with VITE\_, otherwise Vite will not expose them to the client code):

```
VITE_ANTHROPIC_API_KEY=your_anthropic_api_key_here
VITE_HF_ACCESS_TOKEN=your_hf_access_token_here
```

## Install the dependencies and run the project

```
npm install
npm start
```

Head over to https://vitejs.dev/ to learn more about configuring vite

Happy Coding!
