# Mkdocs usage Windows

## Installation

1. Install Github Desktop
2. Using Github Desktop, clone the docs repo to a location on your pc
3. [Download](https://www.python.org/downloads) and install Python
4. Verify Python was installed correctly: Run powershell as admin and run ```python --version```
5. Install pip using Powershell: ```py -m ensurepip --upgrade```
6. Verify pip is installed: ```pip --version```
7. Install mkdocs: ```pip install mkdocs```

---

## Usage

1. Fetch the latest version of the docs repo with Github Desktop.
2. Using Powershell navigate to the mkdocs repo. Example: ```cd C:\Github\thefield\docs\mkdocs```
3. Run mkdocs: ```mkdocs serve``` and in your browser open <http://127.0.0.1:8000>
4. Add, delete or edit .md files  in ```mkdocs/docs``` and verify your changes in your browser.
5. When done run ```mkdocs build``` and push the changes to the repo with Github Desktop