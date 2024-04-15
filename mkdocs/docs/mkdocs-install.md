MkDocs on Windows: Serving & Building
=======================
Important Note: The instructions on this page are applicable only if you intend to modify the content of this documentation website. Please proceed with caution and make sure to follow our guidelines for making contributions.

Installation
------------

1. **Install Github Desktop**: [Follow the instructions provided by Github](https://github.com/desktop) to install Github Desktop on your Windows PC.
2. **Clone the Docs Repo**: Using Github Desktop, clone the documentation repository to a location on your computer.
3. **Install Python**: [Download and install Python](https://www.python.org/downloads/) from the official website. Make sure to follow the installation instructions for Windows.
4. **Verify Python Installation**: Open a Powershell terminal (run as administrator), and type `python --version` to confirm that Python is installed correctly.
5. **Install pip**: Use PowerShell to install pip by running the command: `py -m ensurepip --upgrade`. Verify the installation by typing `pip --version` in Powershell.
6. **Install mkdocs**: Open a Powershell terminal, and run `pip install mkdocs` to install mkdocs on your system.

Usage
-----

1. Fetch the latest version of the documentation repository using Github Desktop.
2. Open a [Powershell](https://en.wikipedia.org/wiki/PowerShell) or VS Code terminal, navigate to the root directory of the `mkdocs` repository (e.g., `cd C:\Github\thefield\docs\mkdocs`).
3. Run the command `mkdocs serve`. Open your browser and visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to view your documentation.
4. Add, delete, or edit `.md` files within the `mkdocs/docs` directory to reflect your desired changes. Verify these updates in your browser.
5. Once you're satisfied with your modifications, run the command `mkdocs build` to generate updated static files. Commit these changes using Github Desktop, ensuring that your work is pushed to the repository.

Please let us know if you encounter any issues or have suggestions for improvements!