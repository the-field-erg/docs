**MkDocs on Windows: Serving & Building**
=====================================

**Important Note:** These instructions are applicable only if you intend to modify the content of this documentation website. Please proceed with caution and make sure to follow our guidelines for making contributions.

---

## Installation

1. **Install Python**: Download and install Python from the official website. Follow the installation instructions for Windows.
2. **Verify Python Installation**: Open a PowerShell terminal (run as administrator) and type `python --version` to confirm that Python is installed correctly.
3. **Install pip**: Use PowerShell to install pip by running the command: `py -m ensurepip --upgrade`. Verify the installation by typing `pip --version` in PowerShell.
4. **Install mkdocs**: Open a PowerShell terminal, and run `pip install mkdocs` to install mkdocs on your system.

---

## Usage

1. Fetch the latest version of the documentation repository using GitHub Desktop or Git Bash.
2. Open a PowerShell or VS Code terminal, navigate to the root directory of the `mkdocs` repository (e.g., `cd C:\Github\thefield\docs\mkdocs`).
3. Run the command `mkdocs serve`. Open your browser and visit [http://127.0.0.1:8000](http://127.0.0.1:8000) to view your documentation.
4. Add, delete, or edit `.md` files within the `mkdocs` directory (e.g., `cd C:\thefield\mkdocs`) to reflect your desired changes. Verify these updates in your browser.
5. Run the command `mkdocs build` to generate the html files that include the recent changes and push these changes to the Github repository.

---

## Troubleshooting

### Error: "pip is not recognized as an internal command"

If you encounter this error, it's likely because pip was not installed correctly during the Python installation process.

#### Verify Python Installation

Run `python --version` in PowerShell to confirm that Python is installed correctly. Check if pip is listed as a dependency or included with the Python installation.

#### Add Environment Path for pip (if necessary)

If pip is not recognized, you may need to add an environment path for pip:

1. Right-click on "Computer" or "This PC", select "Properties", then click on "Advanced system settings".
2. Under "System Variables", scroll down and find the "Path" variable, then click "Edit".
3. Click "New" and add the path to the Pip directory (usually `C:\Python39\Scripts` or similar).
4. Click "OK" to close all the windows.

After adding the environment path, try running the command again to verify that pip is recognized correctly.

### Error: "mkdocs serve" does not start the server 

Ensure that you are running PowerShell or VS Code as an administrator, and that the directory path is correct.

---

## Updating MkDocs

To keep your documentation up-to-date, it's essential to update mkdocs regularly. Here's how:

1. Open a PowerShell terminal and run `pip install --upgrade mkdocs` to upgrade mkdocs.
2. Verify the installation by running `mkdocs --version`.
3. Update any dependencies or plugins as needed.

---

## Additional Tips

### Consistent Naming Convention

Use a consistent naming convention (e.g., lowercase letters and underscores) when creating new files or directories to avoid confusion.

### Organizing Your Content

Organize your content using clear headings, subheadings, and sections to make it easy for users to navigate. This will also help you maintain a logical structure for your documentation.

### Testing Changes

Before committing any changes, test them by running `mkdocs serve` and verifying that the updates are reflected in your browser. This ensures that your changes are accurate and functional.

### Keeping mkdocs Up-to-Date

Regularly update mkdocs to ensure you have access to the latest features and bug fixes. You can do this by running `pip install --upgrade mkdocs` in a PowerShell terminal.

