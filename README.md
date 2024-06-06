# SE-Assignment-5

## Installation and Navigation of Visual Studio Code (VS Code)

### Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

#### Questionsss:

#### 1. Installation of VS Code:
**Steps to download and install Visual Studio Code on Windows 11:**
1. **Visit the Official Website**: Go to [Visual Studio Code's official website](https://code.visualstudio.com).
2. **Download the Installer**: Click on the download button for Windows to get the installer.
3. **Run the Installer**:
   - Locate the downloaded file (usually in your Downloads folder).
   - Double-click the installer to run it.
   - Follow the on-screen prompts to complete the installation.
   - Optionally, check the box to add VS Code to your PATH for easier command-line access.
4. **Complete Installation**: After installation, launch Visual Studio Code from the Start Menu or desktop shortcut.

**Prerequisites:**
- Windows 11 operating system
- Internet connection to download the installer

**Sources:**
- [VS Code Official Download Page](https://code.visualstudio.com)

#### 2. First-time Setup:
**Initial Configurations and Settings:**
1. **Install Popular Extensions**:
   - **Live Server**: Launch a local development server with a live reload feature for static & dynamic pages.
   - **Prettier - Code formatter**: Enforces a consistent style by parsing your code and re-printing it.
   - **ESLint**: Integrates ESLint JavaScript into VS Code.
2. **Adjust Theme and Font Size**:
   - Navigate to `File > Preferences > Color Theme` to choose a theme (Dark themes are preferred by many developers).
   - Adjust the font size by going to `File > Preferences > Settings`, then searching for "font size".
3. **Configure Autosave and Format on Save**:
   - Enable autosave by setting `"files.autoSave": "afterDelay"` in the settings.
   - Enable format on save by setting `"editor.formatOnSave": true`.
4. **Indentation**:
   - Configure indentation settings (spaces or tabs) under `File > Preferences > Settings` by searching for "indentation".

**Sources:**
- [VS Code First Steps](https://code.visualstudio.com/docs/introvideos/basics)

#### 3. User Interface Overview:
**Main Components of the VS Code User Interface:**
1. **Activity Bar**: Located on the far left, it allows navigation between views such as Explorer, Search, Source Control, Run & Debug, and Extensions.
2. **Side Bar**: Displays different views like Explorer (file and folder structure), Source Control, and Extensions.
3. **Editor Group**: The main area where code files are opened and edited. Multiple files can be opened in tabs.
4. **Status Bar**: Positioned at the bottom, it shows information about the current file, such as line number, column, file encoding, and active branch.

**Sources:**
- [VS Code User Interface](https://code.visualstudio.com/docs/getstarted/userinterface)

#### 4. Command Palette:
**What is the Command Palette and How to Access It:**
The Command Palette is a powerful feature in VS Code that allows you to access and execute various commands quickly. It can be accessed using the shortcut `Ctrl + Shift + P` or by navigating to `View > Command Palette`.

**Examples of Common Tasks:**
- Open a file: Start typing the file name and select it from the list.
- Install an extension: Type "Install Extensions" and select from the options.
- Change settings: Type "Preferences: Open Settings (JSON)" to edit settings directly.

**Sources:**
- [VS Code Command Palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette)

#### 5. Extensions in VS Code:
**Role of Extensions and How to Manage Them:**
Extensions add new features and enhance the functionality of VS Code.

**Finding, Installing, and Managing Extensions:**
- Go to the Extensions view by clicking the Extensions icon in the Activity Bar or pressing `Ctrl + Shift + X`.
- Search for the desired extension in the search bar.
- Click "Install" to add the extension to your VS Code.

**Essential Extensions for Web Development:**
- **Live Server**: Launches a local development server.
- **Prettier**: Code formatter.
- **ESLint**: Linter for identifying and reporting on patterns in JavaScript.

**Sources:**
- [VS Code Extensions](https://code.visualstudio.com/docs/editor/extension-gallery)

#### 6. Integrated Terminal:
**How to Open and Use the Integrated Terminal:**
Open the integrated terminal using the shortcut `Ctrl + `` ` (backtick) or by navigating to `Terminal > New Terminal`.

**Advantages:**
- **Convenience**: Run commands and scripts without leaving the editor.
- **Context Awareness**: Automatically opens in the workspace directory.
- **Integrated Tools**: Use tools like Git directly in the terminal.

**Sources:**
- [VS Code Integrated Terminal](https://code.visualstudio.com/docs/editor/integrated-terminal)

#### 7. File and Folder Management:
**Creating, Opening, and Managing Files and Folders:**
- **Create a Folder**: Use the terminal command `mkdir <folderName>`.
- **Create a File**: Use the terminal command `touch <fileName>`.
- **Change Directory**: Use the terminal command `cd <directoryName>`.
- **Navigate Files**: Use the Explorer view in the Side Bar to open and switch between files and folders.

**Sources:**
- [VS Code File and Folder Management](https://code.visualstudio.com/docs/editor/codebasics)

#### 8. Settings and Preferences:
**Customizing Settings:**
- **Access Settings**: Go to `File > Preferences > Settings`.
- **Change Theme**: Search for "Color Theme" and select your preferred theme.
- **Adjust Font Size**: Search for "Font Size" and set your preferred size.
- **Keybindings**: Search for "Keyboard Shortcuts" to customize keybindings.

**Sources:**
- [VS Code Settings](https://code.visualstudio.com/docs/getstarted/settings)

#### 9. Debugging in VS Code:
**Setting Up and Starting Debugging:**
1. **Open Debug View**: Click the Run icon in the Activity Bar or press `Ctrl + Shift + D`.
2. **Configure Debugger**: Add a configuration file by clicking on `create a launch.json file` and selecting the environment.
3. **Start Debugging**: Click the green "Start Debugging" button or press `F5`.

**Key Debugging Features:**
- **Breakpoints**: Set breakpoints by clicking in the gutter next to the line number.
- **Variable Inspection**: Hover over variables to see their values.
- **Step Through Code**: Use the debug toolbar to step into, over, or out of functions.

**Sources:**
- [VS Code Debugging](https://code.visualstudio.com/docs/editor/debugging)

#### 10. Using Source Control:
**Integrating Git with VS Code:**
1. **Initialize a Repository**: Click on the Source Control icon in the Activity Bar and click "Initialize Repository".
2. **Making Commits**:
   - Stage changes by clicking the "+" next to the files in the Source Control view.
   - Write a commit message in the input box and click the checkmark to commit.
3. **Pushing to GitHub**:
   - Open the terminal and use `git push origin main` to push changes to a remote repository.

**Sources:**
- [VS Code Source Control](https://code.visualstudio.com/docs/editor/versioncontrol)

### Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July.
