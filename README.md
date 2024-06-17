[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15276441&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.


   __Steps to Download and Install Visual Studio Code on Windows 11:__

1. **Download VS Code Installer:**
   - Visit [https://code.visualstudio.com/](https://code.visualstudio.com/).
   - Click "Download for Windows" to get the installer.

2. **Run the Installer:**
   - Locate and double-click the downloaded `.exe` file.

3. **Install Visual Studio Code:**
   - Follow the installer prompts.
   - Accept User Account Control (UAC) if prompted.
   - Choose the destination folder and click "Next".

4. **Select Additional Tasks (Optional):**
   - Choose options for shortcuts and click "Next".

5. **Install VS Code:**
   - Click "Install" and wait for the process to complete.

6. **Finish Installation:**
   - Click "Finish" when the installation completes.

7. **Launch Visual Studio Code:**
   - Open VS Code via the desktop shortcut or Start menu.

   


2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.



   ### Initial Configurations:
1. Theme and Appearance
2. Auto Save
3. Tab and Indentation Settings
4. Integrated Terminal
5. Editor Configurations

### Essential Extensions:
1. Language Support
   - Python
   - Prettier
2. Code Formatting
   - Prettier - Code formatter
3. Version Control
   - GitLens
4. Snippets and Autocompletion
   - Path Intellisense
5. Debugging
   - Debugger for Chrome
6. Utilities
   - Bracket Pair Colorizer
   - Live Server




3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.


### Main Components of Visual Studio Code UI:

1. Activity Bar: Left side, access views.
2. Side Bar:Next to Activity Bar, shows tools/info.
3. Editor Group: Center, main coding area.
4. Status Bar: Bottom, displays file/workspace info.



4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   ### Command Palette in Visual Studio Code
   The Command Palette makes it easy to access and execute a wide variety of tasks efficiently, enhancing productivity and streamlining the development workflow.
- **Access:**
  - `Ctrl+Shift+P` or `F1`
### Common Tasks:
1. **Open File:** Quickly open files.
2. **Git Commands:** Commit, push changes.
3. **Search and Replace:** Find/replace text.
4. **Extensions:** Install extensions.
5. **Change Language Mode:** Switch file language.
6. **Format Document:** Auto-format code.
7. **Toggle Terminal:** Open/close terminal.
8. **Run and Debug:** Start debugging.
9. **Snippets:** Insert code snippets.
10. **Settings:** Adjust preferences.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   ### Visual Studio Code Extensions

- **Role:** Extend VS Code's functionality with language support, debugging tools, themes, and more.
- **Finding Extensions:** Access via Extensions view , search or browse.
- **Installing Extensions:** Click `Install` in Extensions view or via Command Palette .
- **Managing Extensions:** Enable, disable, update, or uninstall directly from Extensions view.
  
### Essential Web Development Extensions

- **JavaScript**
  - ESLint: Linting for JavaScript/TypeScript.
  - Prettier: Code formatting.

- **HTML/CSS:**
  - HTML CSS Support: Enhanced editing.
  - Live Server: Local server with live reload.

- **Version Control:**
  - GitLens: Advanced Git features.

.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?


   ### Integrated Terminal in VS Code

- **Opening:** `View` > `Terminal`.
- **Switch Shell:** Select from default or custom shells.
- **Customization:** Configure settings via `Terminal > Configure Terminal Settings`.
  
### Advantages Over External Terminals

- **Integration:** Seamless workflow within VS Code.
- **Context:** Opens at workspace root for project-specific commands.
- **Productivity:** Reduces window switching, speeds up development.
- **Customization:** Adjust settings, themes, and shell configurations.
- **Extension Support:** Integrates with VS Code extensions for enhanced functionality.



7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?


   ### Managing Files and Folders in VS Code

- **Creating:** Right-click in Explorer > New File/Folder.
- **Opening:** Double-click file in Explorer 
- **Managing:**
  - **Renaming:** Right-click > Rename.
  - **Deleting:** Right-click > Delete (irreversible action).
  - **Moving:** Drag and drop within Explorer panel.
  
### Navigating Efficiently

- **Switching Files:**  click file tabs.
- **Navigating Directories:** Use Explorer panel (`Ctrl+Shift+E`).
- **Searching:** `Ctrl+P` for Quick Open.



8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.


### Finding and Customizing Settings in VS Code
- **Finding Settings:**
  - Access via `Settings` (`Ctrl+,`)
  
- **Customizing Settings:**
  - Change Theme: `File` > `Preferences` > `Color Theme`.
  - Adjust Font Size: Search for "Font Size" in Settings UI.
  
### Examples
- **Change Theme:** Select "Dark+" or "Light+" themes.
- **Adjust Font Size:** Modify "Editor: Font Size".



9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   ### Debugging in VS Code

#### Setup and Starting Debugging:

1. **Install Extensions:** Get necessary debugging tools from Extensions Marketplace (`Ctrl+Shift+X`).

2. **Open Project:** Open your project folder in VS Code (`File` > `Open Folder...`).

3. **Configure `launch.json`:** Customize how your program launches by editing `launch.json` in the Debug view (`Ctrl+Shift+D`).

4. **Set Breakpoints:** Click in the left margin of your code or press `F9` to pause execution at specific lines.

5. **Start Debugging:** Press `F5` to begin debugging or use the Debug view (`Start Debugging` button).

#### Key Debugging Features:

- **Breakpoints:** Pause execution to inspect variables and code flow.
- **Watch and Variables:** Monitor variable values in real-time.
- **Call Stack:** Visualize the path through nested function calls.
- **Debug Console:** Interact directly with your running code using a command line interface.
- **Run Control:** Step through code (`F10` for step over, `F11` for step into), restart (`Ctrl+Shift+F5`), stop (`Shift+F5`).
- **Conditional Breakpoints:** Pause execution based on specific conditions.
- **Exception Handling:** Configure how to handle errors and exceptions.
- **Multi-session Debugging:** Debug multiple programs concurrently for complex scenarios.





10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    ### Using Git Bash with VS Code

#### Steps:

1. **Initialize Repository:**
   - Open your project folder in VS Code.
   - Open Git Bash terminal in VS Code by clicking `Terminal` > `New Terminal`, then select Git Bash.
   - Run `git init` in Git Bash to initialize the repository.

2. **Make Commits:**
   - Stage changes: `git add .` to stage all changes.
   - Commit changes: `git commit -m "Your commit message"`.

3. **Push to GitHub:**
   - Link GitHub repository: `git remote add origin <repo-url>`.
   - Push changes: `git push -u origin main` (or `master`).

#### Summary:

1. **Initialize Repository:**
   - Open project folder.
   - Use Git Bash in VS Code, run `git init`.

2. **Make Commits:**
   - Stage with `git add .`.
   - Commit with `git commit -m "message"`.

3. **Push to GitHub:**
   - Add remote: `git remote add origin <repo-url>`.
   - Push with `git push -u origin main`.



 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

