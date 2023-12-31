# DODA

![screenshot.png](/screenshot.png)

DODA Offers Developer Assistance.

It is an experiment using the OpenAI Assistants API to control your command line and development environment.

Based on Deno + Electron in order to provide a ChatUI that can run as a website on a remote server or as a desktop app.

## Current Functions
* Creating files
* Executing CLI commands
* Getting environment and system info
* Running scripts

⚠️🔥 The agent can run REAL code locally and WILL execute any command you tell it to. Be careful. 🔥⚠️

## Setup
* install node/deno
* add your OPENAI_API_KEY 
* customize the doda_agent/assitantConfig.json ( optional )

## Usage

# run the agent
```
cd doda_agent
deno run --allow-all server.ts
```

# run electron
```
cd doda_electron
npm start
```

# or both at once:
```
chmod +x start.sh
./start.sh
```

You can kill the proc with `kill $(lsof -t -i:1337)`

Contributions are welcome! Fork the repo and submit pull requests. 🍻