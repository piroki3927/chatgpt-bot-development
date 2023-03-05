# chatgpt-bot-development

## introduction

Challenging ChatBot that runs on Lambda with reference to the ChatGPT document.

## Required

- node.js: 18.14.2
- you shuld get [OPENAI_API_KEY](https://platform.openai.com/account/api-keys)

## usage

### install & setting

```
cd chatgpt-bot-development
npm install
cp .env.local .env
vi .env 
```
You can set your API key in the environment variable "OPENAI_API_KEY"

### run

```
node index.js
```

## Challenge Goals
- [x] Create Project
- [ ] Connect to Teams
- [ ] (and Connect to Slack)
- [ ] Generate JP to EN, and EN to JP (for Speed up test)
- [ ] Combine with other tools or AI tools (ex. stable diffision, canva, Whisper...)

