GBU 2301 Business Statistics: Getting Started


I. GitHub Desktop: Downloading lecture files


a) Download and Install: https://desktop.github.com/download/


b) Sign In: Open GitHub Desktop and sign in with your GitHub account. You may also continue without signing in when cloning a public repository.


c) Get Lectures (Clone):
1. In GitHub Desktop, go to File > Clone Repository.
2. Select the URL tab.
3. Paste: https://github.com/DROMCA/Business-Statistics
4. Pick a folder on your computer.
5. Click Clone.


d) Check for Updates (Fetch):
1. Click Fetch origin at the top-middle.
2. If updates are available, GitHub Desktop will show Pull origin.


e) Download Updates (Pull):
1. Click Pull origin to download the latest lecture files.


NOTE:
Always copy a lecture notebook before editing it. Work on your copy so later course updates do not conflict with your work.





II. Visual Studio Code: Recommended editor for lecture notebooks


a) Download and Install: https://code.visualstudio.com/download


b) Add Python and Jupyter Support:
1. Open Extensions from the left panel.
2. Install the Python and Jupyter extensions.


c) Open the Lecture Folder:
1. Go to File > Open Folder.
2. Choose the folder cloned with GitHub Desktop.
3. Confirm that the lecture notebooks appear in the Explorer panel.


d) Run a Notebook:
1. Open an .ipynb file.
2. Select a Python kernel when prompted.
3. Run a selected cell with Ctrl/Cmd + Enter.


NOTE:
Visual Studio Code is the recommended starting point for this course. It provides direct notebook support through the Python and Jupyter extensions and makes lecture files, code cells, outputs, and datasets easy to work with in one place.





III. Google Antigravity IDE: Second editor option


a) Download and Install: https://antigravity.google/product/antigravity-ide


b) Sign In: Open Antigravity IDE and sign in with your Google account.


c) Add Python and Jupyter Support:
1. Open Extensions from the left panel.
2. Install the Python and Jupyter extensions.


d) Open the Lecture Folder:
1. Select Open Folder.
2. Choose the folder cloned with GitHub Desktop.
3. Confirm that the lecture notebooks appear in the Explorer panel.


e) Run a Notebook:
1. Open an .ipynb file.
2. Select a Python kernel when prompted.
3. Run a selected cell with Ctrl/Cmd + Enter.


NOTE:
Antigravity includes an AI-assisted editor and agent. It can help explain code, diagnose errors, and work across notebooks and the terminal. Review proposed file changes before accepting them.





IV. Cursor: Third editor option


a) Download and Install: https://cursor.com/downloads


b) Sign In: Open Cursor and sign in.


c) Add Python and Jupyter Support:
1. Open Extensions from the left panel.
2. Install the Python and Jupyter extensions.


d) Open the Lecture Folder:
1. Select Open Project or Open Folder.
2. Choose the folder cloned with GitHub Desktop.


e) Run a Notebook:
1. Open an .ipynb file.
2. Select a Python kernel when prompted.
3. Run a selected cell with Ctrl/Cmd + Enter.


NOTE:
Cursor works similarly to Visual Studio Code and adds integrated AI assistance.





V. Installing the Course Packages


a) Open install.ipynb from the cloned repository.


b) If asked to select a kernel, choose the available Python option. If you installed Anaconda, choose base.


c) Run the installation cell. It installs the packages listed in requirements.txt.


d) Restart the notebook kernel after installation.


e) Run the verification cell to confirm that the required packages are available.





VI. Anaconda with Visual Studio Code: Convenient Python setup


a) Download and Install Anaconda Distribution: https://www.anaconda.com/download/success


b) Why Use Anaconda with Visual Studio Code:
1. Anaconda installs Python together with many commonly used scientific packages.
2. It provides a convenient way to maintain Python and install additional packages.
3. Its base Python installation can be selected directly as the notebook kernel in Visual Studio Code.
4. Anaconda Navigator provides a graphical interface for students who prefer not to manage Python from the command line.


c) Connect Anaconda to Visual Studio Code:
1. Open Visual Studio Code from Anaconda Navigator if it is available there. Otherwise, open Visual Studio Code normally.
2. Open the cloned lecture folder in Visual Studio Code.
3. Open a notebook and select base when asked for the Python kernel.
4. Run install.ipynb to install and verify the course packages.


NOTE:
Anaconda is not another notebook editor. It provides a convenient Python installation for use inside Visual Studio Code. This course uses Anaconda's default base setup. If you install Anaconda, a separate Python installation is normally unnecessary.
