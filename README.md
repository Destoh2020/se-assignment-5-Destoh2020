[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15279194&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

Installation and Navigation of Visual Studio Code (VS Code)
Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

Questions:

1. Installation of VS Code:

   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
     (i). Open your web browser and navigate to the Visual Studio Code official website.
     (ii). On the homepage, click the "Download for Windows" button. This will automatically download the installer for the latest stable version of Visual Studio Code compatible with Windows.
     (iii). Once the download is complete, locate the downloaded file (usually in the "Downloads" folder) named something like VSCodeUserSetup-x64-1.x.x.exe.
     (iv). Double-click the installer file to run it.
     (v). In the installation wizard that appears, read and accept the license agreement by checking the "I accept the agreement" box, then click "Next".
     (vi). Choose the installation location. The default path is typically C:\Program Files\Microsoft VS Code\. You can change it if necessary, then click "Next".
     (vii). Choose any additional tasks you want the installer to perform, such as:
     - Adding "Open with Code" to the context menu for file and directory.
     - Creating a desktop icon.
       Click "Next" after making your selections.
       (viii). Click the "Install" button to begin the installation process. The installer will copy the necessary files to your computer.
       (ix). Once the installation is complete, you can choose to launch Visual Studio Code immediately by checking the "Launch Visual Studio Code" box and clicking "Finish".

2. First-time Setup:

   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
     (i). Install essential extensions like
     prettier - for code formating.
     ESLint or TSLint- for linting Javascript or typescript.
     GitLen - for enhancing git integration
     Live Server - for live preview of HTML/CSS changes
     VSCode Icons - for icons to file explorer.
     (ii). User and workspace setting like
     default code formaters, font size and family, line numbers, word wrap
     (iii). Theme and icon: choose a theme that is aesy on the eyes like the dark theme -> file...preferences...color theme...Dark+
     file icon theme -> file...preferences...file icon theme...VScode Icons
     additional themes can can be installed from the marketpalce
     (iv).Keybindings: customize keybindings to match workflow through -> file...preferences...keyboard shotcuts or (ctrl+ k ctrl+s)
     (iv). Version Control Integration: git can be configure through (ctrl+, json on the topright corner)
     set the json to "git.enableSmartCommit": true,
     "git.autofetch": true

3. User Interface Overview:

   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   (i). Activity bar - Located on the left edge of the window. It allows for switching between different views and provides access to various features and extensions.it has the following key icons; Explorer displays the explorer view, Search allows for searching of files and replace text withing the project. Source Control integrates with version control system like git showing changes, branches and repositories. Run and Debug provides tools to run and debug your code. Extension allows for access to extensions marketplace to install and manage extensions.
   (ii). Side Bar - Located on the right of the activity bar. it is changes based on the selected view in the activity bar, providing detailed navigation and control for that particular view. It has the following key panels - Explorer for showing the project directory structure, allowing for navigation ana management of files and folders. Search displays serach results within the project. Source Control Shows changes, staged files, and provides commit functionality. Run and Debug lists configurations and debugging options. Extensions lists installed extensions and recommendations for additional ones.
   (iii). Editor Group located at the center of the window. it's the main area where we write and edit our code. It has the following key features - tabs represents each open file at the top of the editor group. Split View allows one to split the editor into multiple panes to view and edit multiple files side by side. Minimap a small overview of your code on the right edge of the edito, provides a quick way to navigate long files. Syntax Hightlighting colors different parts of the code according to their syntactic meaning enhancing readability.
   (iv). Status Bar located at the bottom edge of the window. it provides useful information and quick access to certain settings related to the current workspace and file. it has the folloeing key indicators: Branch shows the current git branch. Errors and warning displays the number of errors and warnings in the current file or workspace. Encoding and line endings indicates the character encoding and line ending format of the cuurent file. Language Mode displays and allows changing the language mode (syntax highlighting) of the current file. Line and Column shows the current cursor position in terms of line and column number.

4. Command Palette:

   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
     A command Palette is a powerful feature that provides quick access to a wide range of commands and settings. It allows you to perform various tasks without having to navigate through menus or remember keyboard shortcuts.
     To access the command Palette we can use the Keyboard shortcut by pressing ctrl+Shift+p or thought the menu by going to view > Command Palette.
     The command palette can be used to perform the following tasks:
     (1). Opening and managing files - opening files, saving files and close window
     (2). Version Control - git commit, git pull, git push
     (3). Editing - format document, go to line, toogle comment
     (4). View and Layout - toogle sidebar visibility, split editor, toogle zen mode.
     (5). Extensions - Install extensions, Disable extensions
     (6). Debbuging - start debugging, add configuration.
     (7). Setting and preferences - open settings, change color, configure language specific settings

5. Extensions in VS Code:

   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
     Extensions are small software programs that add new features and functionalities to VS Code. This allows for a highly customizable development experience tailored to your specific needs.
     To find extensions
     - Open the Extensions view (Ctrl+Shift+X or click the Extensions icon in the Activity Bar)
     - Browse the curated list or search for specific functionalities.
     - Click on an extension to view its details, ratings, and features.
     - Click "Install" to add the extension to VS Code
       To manage Extensions
     - The Extensions view displays all installed extensions.
     - You can disable, enable, or uninstall extensions from this view.
       Essential extensions for web developmnet
     - ESLint: Identifies and highlights potential errors and stylistic issues in your JavaScript code.
     - Prettier: Automatically formats your code according to a consistent style guide.
     - Debugger: Allow you to debug your web applications directly within VS Code.
     - GitLens: Enhances the built-in Git integration with features like visual commit history and blame annotations
     - Live Server: For live preview of HTML/CSS changes

6. Integrated Terminal:

   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
     To open the integrated terminal you can use the keyboard shotcut (ctrl+` "bacltick key before 1 on the keyboard") or through the Menu view > terminal or through the command palette open the command palette (ctrl+Shift+p) > and type terminal:toogle terminal.
     The advantages of using integrated terminal comared to external terminal are:
     1. Convinience - havinng a terminal directly within VSCode eliminates the need to switch between windows.
     2. Integration - benefits from features like clickable links in terminal output and decorations related to code, improved workflow efficiency
     3. Focus - Keeping the terminal within VSCode helps maintain focus on your project and avoid distractions from other apllications.

7. File and Folder Management:

   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
     - To create a file: New file: In the Menu
       Go to File > New File.
       Keyboard Shortcut: Ctrl + N.
       New Folder. In the Menu
       Go to File > New Folder.
       Keyboard Shortcut: Ctrl + Shift + N
     - To open a file:
       Double-Click: In the Explorer view, double-click on a file to open it in the editor.
       Keyboard Shortcut: Use the Go to File functionality: Ctrl + P.
     - To manage files and folders:
       Explorer View: The Explorer view (on the left side by default) displays all files and folders within your workspace. You can use it to navigate, rename, delete, and move files/folders. Drag and Drop: Drag and drop files/folders within the Explorer view to rearrange them. Context Menu: Right-click on a file or folder to access various options for renaming, deleting, copying, cutting, pasting, and more. Keyboard Shortcuts: Learn keyboard shortcuts for common perations like renaming (F2) and deleting (Delete).
     - To navigating efficiently:
       Go to File (Ctrl + P): This is a powerful way to quickly open any file in your project by name.
       Recent Files: VS Code maintains a list of recently opened files. Access it by going to File > Open Recent.
       File History: VS Code keeps track of recently edited files. Access the history using the Go to File functionality and typing "@" to see the list.
       Breadcrumbs: The breadcrumbs at the top of the editor indicate the current file location. Click on any folder name to navigate up the directory structure.
       Symbols: The Symbols panel (Ctrl + Shift + O) helps navigate to specific functions, variables, or classes within your codebase.

8. Settings and Preferences:

   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
     To access settings in VSCode
     - In the Menu: Go to File > Preferences > Settings.
     - Keyboard Shortcut: Ctrl + ,
     - Command Palette: Open the Command Palette (Ctrl + Shift + P) and type "Settings" or "Preferences". Select the appropriate option to open the Settings editor.
       To change theme
     - Search for "Color Theme" or "Theme".
     - Select a theme from the built-in options or click "Browse Themes" to install themes from the VS Code Marketplace.
       To change font size
     - Search for "Font Size".
     - Use the slider or enter a specific pixel value to adjust the font size.
       Keybindings
     - Search for "Keyboard Shortcuts".
     - Here you can see a list of all default keybindings.
     - You can search for specific commands or browse by category.
     - Click on a keybinding to modify it or set a new shortcut using the keyboard

9. Debugging in VS Code:

   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
     (1). To set up and start debugging ensure you have supported Language extensions installed for your programming language (e.g., Python extension for Python code).
     (2). Set breakpoint: Open the source code file in the editor. - Click on the line number where you want to pause execution during debugging. - A red dot appears next to the line number, indicating a breakpoint.
     (3). Open the Run and Debug view (Ctrl + Shift + D). - Select the appropriate launch configuration (if multiple exist). - Click the Start Debugging button (play icon) or use the keyboard shortcut (F5 by default).
     (4). Once your program starts running, VS Code enters debug mode, offering various features:
     Stepping Through Code - Step Over (F10): Executes the current line and continues to the next line. - Step Into (F11): Steps into function calls, pausing at the first line of the called function. - Step Out (Shift + F11): Steps out of the current function, continuing execution until the function returns.
     Variable Inspection - The Variables panel displays the values of variables at the current breakpoint. - You can inspect their values and modify them if necessary.
     Call Stack - The Call Stack panel shows the sequence of function calls leading to the current point in execution. This helps you understand the program flow.
     Console - The integrated terminal allows you to interact with your program while debugging, printing messages or inspecting variables using language-specific commands.
     Stopping Debugging - Once you've finished debugging, click the Stop Debugging button (square icon) or press Shift + F5.

10. Using Source Control:

    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

      - For a user to integrate git with VSCode ensure you have git installed or download git from (https://www.git-scm.com/downloads).

      - Initialize a Git Repository
        - Open your project folder in VS Code.
        - Go to the Source Control view (Ctrl + Shift + G).
        - If Git isn't detected, VS Code will prompt you to initialize a repository.
        - Click on "Initialize Repository". This creates the necessary Git metadata files in your project folder.
      - Staging Changes and Making Commits
        - After making code changes, you'll see them reflected in the Source Control view with different icons indicating their status
        - Untracked - New files not yet added to Git.
        - Modified - Existing files with changes.
      - Stage Changes
        - Select the files you want to include in your next commit and stage them using the "+" button or right-click context menu options.
        - Staging tells Git which specific changes you want to track.
      - Commit
        - Once you've staged your changes, type a meaningful commit message describing the changes made.
        - Click on the checkmark icon or use the keyboard shortcut (Ctrl + Enter by default) to commit the staged change
      - Pushing Changes to GitHub (Remote Repository):
        - Remote Repository Setup: You'll need a remote repository to push your local commits.
        - GitHub is a popular option, but other Git hosting services work similarly.
        - Create a new repository on GitHub or link your local repository to an existing one.
      - Push to Remote
        - In the Source Control view, click on the "..." menu and select "Publish to GitHub" (if you haven't linked your account yet) or choose "Push". This will push your local commits to the remote repository on GitHub.

Submission Guidelines:

- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July
