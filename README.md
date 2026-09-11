# DevDen
# DevDen

DevDen is a lightweight local development workspace and desktop IDE built in Python. Create projects, browse their real files, edit code, run programs, use a terminal, and publish selected files to GitHub.

## Features

- First-run projects directory setup
- Recent projects dashboard
- Real filesystem Explorer with folder navigation
- Separate Explorer and Editor pages
- Multi-tab code editor using Consolas
- Syntax highlighting for Python, JavaScript, TypeScript, Java, C, C++, C#, Go, Rust, Kotlin, Swift, PHP, Ruby, HTML, CSS, SQL, Bash, JSON, and Markdown
- Create scripts and folders inside the selected project folder
- Double-click files to open them in the Editor
- Upload images into the selected project folder
- Delete files and folders through the operating system recycle bin
- Save, close, find, and reload project files
- Asynchronous project runner for Python and Node.js
- Integrated shell command panel
- Dark and light themes
- GitHub repository publishing with:
  - Repository name
  - Description
  - Public or private visibility
  - Individual file selection
  - Automatic README generation
  - Release creation
  - Release tag, title, and notes
- About page and error-reporting contact
- Windows executable build support

## Requirements

- Windows, macOS, or Linux
- Python 3.10 or newer
- Optional runtimes for running projects, such as Python or Node.js
- Git and GitHub CLI for GitHub publishing


On the first launch, choose the directory where new projects should be stored.

## GitHub Publishing

Install and authenticate GitHub CLI:

```powershell
winget install GitHub.cli
gh auth login
```

Open a project in DevDen and select **Publish to GitHub**. Choose the repository settings, release information, and the exact files to include. DevDen always generates and includes a `README.md` containing the repository name.

When `DevDen.exe` is available beside the application, DevDen automatically attaches it to the GitHub release as the downloadable Windows installer. Users can download the executable from the release page without installing Python or the development dependencies.



## Support

For errors or problems, email:

akshaj.k32411@outlook.com

## Copyright

(c) 2026 MANEX. All Rights Reserved.

