# Pinia crash course

## Setup for local development

### First time setup

Clone the repository to your device and cd into it
``` bash 
git clone https://github.com/Ismail020/Pinia-crash-course.git && cd "$(basename "$_" .git)"
```

Download packages and dependencies
```bash
npm install
```

Run dev script
```bash
npm run dev
```

Install package to run a fake REST API
```bash
npm install -g json-server 
```

Set up json file as server
```bash
json-server -w ./data/db.json  
```