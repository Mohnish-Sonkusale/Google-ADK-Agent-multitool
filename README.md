# Google-ADK-Agent-multitool
## Prerequisites:
1.Install python \n
2.Have an IDE
Steps:

Set up the python environment
Initialize .vnev python -m venv .venv

Activate virtual env

Activate (each new terminal)

macOS/Linux: source .venv/bin/activate

Windows CMD (Git Bash): source .venv/Scripts/activate

Windows PowerShell: .venv\Scripts\Activate.ps1

pip install -r requirements.txt
Have the following project structure
parent_folder/
    multi_tool_agent/
        __init__.py
        agent.py
        .env
Defined root agent and start integrating tools and services!
Run project with adk web
Note: ElevenLabs integration will need ffmpeg

Download ffmpeg from here: https://ffmpeg.org/download.html#build-windows
Choose build, install via CLI: winget install ffmpeg
Check installation via command line: ffmpeg -version
Add ffmpeg to scripts
where ffmpeg to get installation folder
Copy files to Scripts folder
Link to generate Reddit API Key: https://www.reddit.com/prefs/apps/

