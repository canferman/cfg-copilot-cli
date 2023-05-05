# Auto Copilot CLI
![logo](https://user-images.githubusercontent.com/70219513/236394679-7b1f4ac4-4454-4e91-97ea-41326d1df5b4.png)

[![npm](https://img.shields.io/npm/v/auto-copilot-cli)](https://www.npmjs.com/package/auto-copilot-cli) 
[![Node.js Package](https://github.com/rsaryev/auto-copilot-cli/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/rsaryev/auto-copilot-cli/actions/workflows/npm-publish.yml) 
[![MIT License](https://img.shields.io/badge/license-MIT-blue)](https://github.com/transitive-bullshit/chatgpt-api/blob/main/license)
[![auto-copilot-cli npm downloads](https://img.shields.io/npm/dt/auto-copilot-cli)](https://www.npmjs.com/package/auto-copilot-cli)

### Quick Start

1. Install Node.js v18.16.0 or higher - https://nodejs.org/en/download/
2. Run ```npx auto-copilot-cli``` or ```npm install -g auto-copilot-cli```
3. Run the CLI tool using ```auto-copilot-cli``` or ```npx auto-copilot-cli```
4. Enter your OpenAI API key - https://platform.openai.com/account/api-keys
5. Run ```npx auto-copilot-cli -V``` to check if the CLI tool is working
6. Run ```npx auto-copilot-cli <goal>``` run the CLI tool with a goal

### Options

- ```-a, --auto-execute``` - Enable auto execute mode (default: false)
- ```-m, --model <modelName>``` - OpenAI model name (default: "gpt-3.5-turbo")
- ```-h, --help``` - display help for command
- ```-V, --version``` - output the version number

### Recommendations

- Setup an alias for the ```npx auto-copilot-cli``` command, for example ```ac``` or ```copilot```
- Use npx to run the CLI tool without installing it globally ```npx auto-copilot-cli```
- Use the ```-a``` flag carefully for automatic execution of commands
- Not changing the default model is recommended

### Examples using the CLI tool
- ```auto-copilot-cli create image.png with cat and open it``` - Creates an image with a cat and opens it
- ```auto-copilot-cli create 10 empty files with names from 1 to 10``` - Creates 10 empty files with names from 1 to 10
- ```auto-copilot-cli create koa.js project``` - Creates a Koa.js project
- ```auto-copilot-cli start postgresql in docker``` - Starts PostgreSQL in Docker
- ```auto-copilot-cli create pdf file with top 10 movies``` - Creates a PDF file with top 10 movies
- ```auto-copilot-cli create js file with implementation of binary search``` - Creates a file with implementation of binary search

## Description

This CLI tool uses the ChatGPT language model to create commands. This allows you to create a list of tasks and perform them sequentially, optimizing your workflow and increasing the efficiency of repetitive actions.

### Demo

https://user-images.githubusercontent.com/70219513/236418269-0b82dbb6-4ff9-4eda-992c-c9d6f3e96ad1.mov