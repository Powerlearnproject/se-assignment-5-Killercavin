# Installation of VS Code

## Steps to Download and Install Visual Studio Code on Windows 11

### Download VS Code
1. Visit the official Visual Studio Code website: [Visual Studio Code](https://code.visualstudio.com/).
2. Click on the "Download for Windows" button to download the installer.

### Run the Installer
1. Locate the downloaded installer file (usually in the Downloads folder) and double-click it to run.
2. If prompted by the User Account Control (UAC), click "Yes" to allow the installer to make changes to your device.

### Install VS Code
1. Follow the setup wizard instructions:
   - Accept the license agreement.
   - Choose the installation location.
   - Select any additional tasks (e.g., creating a desktop icon, adding to PATH).
2. Click "Install" to begin the installation process.
3. Once the installation is complete, click "Finish" to launch Visual Studio Code.

### Prerequisites
- Ensure that your system meets the minimum requirements for VS Code.
- It's recommended to have the latest version of Windows 11 and necessary updates installed.

## First-time Setup

### Initial Configurations and Settings

#### Install Essential Extensions
1. Launch VS Code.
2. Click on the Extensions icon in the Activity Bar (or press `Ctrl+Shift+X`).
3. Search for and install extensions like "Python", "Prettier - Code formatter", "ESLint", etc., based on your development needs.

#### Adjust Settings
1. Go to `File > Preferences > Settings` or press `Ctrl+,`.
2. Important settings to adjust:
   - **Theme:** Change the color theme under `Appearance > Color Theme`.
   - **Font Size:** Adjust the editor font size under `Text Editor > Font`.
   - **Format on Save:** Enable `Editor: Format On Save` to auto-format code on save.

#### Set Up Git Integration
1. Ensure Git is installed on your system.
2. Configure Git in VS Code by navigating to `File > Preferences > Settings` and searching for `Git`.

## User Interface Overview

### Main Components of the VS Code User Interface

#### Activity Bar
- Located on the far left.
- Contains icons for different views like Explorer, Search, Source Control, Run and Debug, and Extensions.

#### Side Bar
- Displays the content of the selected view from the Activity Bar.
- For example, the Explorer view shows a file and folder structure.

#### Editor Group
- The main area where files are opened and edited.
- Supports multiple tabs and split views for editing multiple files simultaneously.

#### Status Bar
- Located at the bottom.
- Shows information like current file encoding, line and column numbers, Git branch, and errors and warnings.

## Command Palette

### What is the Command Palette and How to Access It
- The Command Palette is a powerful tool to access VS Code commands.
- Access it by pressing `Ctrl+Shift+P` or `F1`.

### Examples of Common Tasks
- Open a file: Type `>Open File`.
- Change color theme: Type `>Preferences: Color Theme`.
- Install extensions: Type `>Extensions: Install Extensions`.

## Extensions in VS Code

### Role of Extensions and How to Manage Them

#### Role
- Extensions add functionality to VS Code, such as language support, debuggers, and tools.

#### Finding and Installing Extensions
1. Click the Extensions icon in the Activity Bar (or press `Ctrl+Shift+X`).
2. Search for the desired extension and click "Install".

#### Managing Extensions
- Manage installed extensions through the Extensions view by enabling, disabling, or uninstalling them.

### Essential Extensions for Web Development
- "Live Server" for live preview.
- "ESLint" for JavaScript linting.
- "Prettier" for code formatting.

## Integrated Terminal

### Opening and Using the Integrated Terminal
- Open the terminal by going to `View > Terminal` or pressing `` Ctrl+` ``.

### Advantages
- Integrated terminal allows you to run command-line tasks without leaving VS Code.
- Supports multiple terminal instances and shells (e.g., PowerShell, Git Bash).

## File and Folder Management

### Creating, Opening, and Managing Files and Folders

#### Creating Files/Folders
- Right-click in the Explorer view and select "New File" or "New Folder".

#### Opening Files/Folders
- Double-click a file in the Explorer view to open it.

#### Navigating
- Use the file tabs for open files.
- Switch between files using `Ctrl+Tab` or the file explorer.

## Settings and Preferences

### Finding and Customizing Settings
- Access settings via `File > Preferences > Settings` or `Ctrl+,`.

### Examples
- **Theme:** `Appearance > Color Theme`.
- **Font Size:** `Text Editor > Font`.
- **Keybindings:** `Keyboard Shortcuts` under `File > Preferences > Keyboard Shortcuts`.

## Debugging in VS Code

### Setting Up and Starting Debugging
1. Open the file you want to debug.
2. Set breakpoints by clicking in the gutter next to the line numbers.
3. Open the Run and Debug view from the Activity Bar.
4. Click on "Run and Debug" and select the appropriate environment.

### Key Debugging Features
- Breakpoints, step over/into/out, watch variables, call stack, and debug console.

## Using Source Control

### Integrating Git with VS Code

#### Initializing a Repository
1. Open a project folder.
2. Initialize a repository by clicking on the Source Control icon and clicking "Initialize Repository".

#### Making Commits
- Stage changes by clicking the `+` icon.
- Commit changes with a message in the commit input box and press `Ctrl+Enter`.

#### Pushing to GitHub
1. Set the remote repository URL:
   ```sh
   git remote add origin https://github.com/YourUsername/YourRepo.git
### References
## Visual Studio Code Official Documentation:
- [Download and Installation](https://code.visualstudio.com/docs/setup/setup-overview)
- [First-time Setup and Settings](https://code.visualstudio.com/docs/getstarted/settings)
- [User Interface Overview](https://code.visualstudio.com/docs/getstarted/userinterface)
- [Command Palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette)
- [Extensions](https://code.visualstudio.com/docs/editor/extension-marketplace)
- [Integrated Terminal](https://code.visualstudio.com/docs/editor/integrated-terminal)
- [File and Folder Management](https://code.visualstudio.com/docs/editor/codebasics)
- [Settings and Preferences](https://code.visualstudio.com/docs/getstarted/keybindings)
- [Debugging](https://code.visualstudio.com/docs/editor/debugging)
- [Source Control](https://code.visualstudio.com/docs/editor/versioncontrol)

## GitHub Documentation:
- [Getting Started with GitHub](https://docs.github.com/en/get-started)
- [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)

## YouTube Tutorials:
- [YouTube](https://www.youtube.com)
## Artificial Intelligence Prompts
- ClaudeAI
- Gemini
- GitHub Copilot
- Microsoft Copilot
- ChatGPT etc
