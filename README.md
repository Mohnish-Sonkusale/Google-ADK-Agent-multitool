# Prerequisites: 
1. Install python
2. Have an IDE

# Quickstart¶

This quickstart guides you through installing the Agent Development Kit (ADK), setting up a basic agent with multiple tools, and running it locally either in the terminal or in the interactive, browser-based dev UI.

This quickstart assumes a local IDE (VS Code, PyCharm, etc.) with Python 3.9+ and terminal access. This method runs the application entirely on your machine and is recommended for internal development.

Steps:
1. Set up the python environment

- Initialize .vnev `python -m venv .venv`

- Activate virtual env

    - Activate (each new terminal)

    - macOS/Linux: source .venv/bin/activate

    - Windows CMD (Git Bash): source .venv/Scripts/activate

    - Windows PowerShell: .venv\Scripts\Activate.ps1


2. `pip install -r requirements.txt`
3. Have the following project structure
```
parent_folder/
    multi_tool_agent/
        __init__.py
        agent.py
        .env
```
4. Defined root agent and start integrating tools and services!
5. Run project with `adk web`

Note: ElevenLabs integration will need ffmpeg
1. Download ffmpeg from here: https://ffmpeg.org/download.html#build-windows
2. Choose build, install via CLI: `winget install ffmpeg`
4. Check installation via command line: ffmpeg -version
5. Add ffmpeg to scripts
- `where ffmpeg` to get installation folder
- Copy files to Scripts folder


Link to generate Reddit API Key: https://www.reddit.com/prefs/apps/

