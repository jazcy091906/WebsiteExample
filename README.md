# WebsiteExample

## How to connect this website to your GitHub account
init
### Option 1: Using Git Commands

1. **Create a repository on GitHub**
   - Go to [GitHub](https://github.com) and click "New" to create a repository (e.g., "WebsiteExample").
2. **Install Git if needed**
   - If you see an error like `'git' is not recognized as an internal or external command`, install Git from [git-scm.com/downloads](https://git-scm.com/downloads).
   - Choose the installer for your operating system:
     - **Windows:** Download and run the Windows installer.
     - **Mac:** Download the macOS installer or use Homebrew (`brew install git`).
     - **Linux:** Use your package manager (e.g., `sudo apt install git` for Ubuntu).
   - Restart your terminal after installing.
3. **Open a terminal in your website folder**
   - Navigate to your project folder.
4. **Initialize Git**
   - To use the default branch name (`main`):
     ```sh
     git init -b main
     ```
   - Or, to use a different branch name (e.g., `master`):
     ```sh
     git init -b master
     ```
5. **Add and commit your files**
   ```sh
   git add .
   git commit -m "Initial commit"
   ```
6. **Connect to your GitHub repository**
   ```sh
   git remote add origin https://github.com/YOUR_USERNAME/WebsiteExample.git
   ```
   - Replace `YOUR_USERNAME` with your GitHub username.
7. **Push your code**
   - If you used `main`:
     ```sh
     git push -u origin main
     ```
   - If you used `master`:
     ```sh
     git push -u origin master
     ```

---

### Option 2: Using Visual Studio Code

1. **Open Visual Studio Code**
   - Go to `File > Open Folder` and select your website folder.
2. **Make sure Git is installed**
   - If not, install Git as described above.
3. **Initialize the repository**
   - Click the Source Control icon (or press `Ctrl+Shift+G`).
   - Click "Initialize Repository" if prompted.
4. **Make your first commit**
   - Type a commit message (e.g., "Initial commit") and click the checkmark to commit.
5. **Publish to GitHub**
   - Click "Publish to GitHub" or use the "Remote" section to add your GitHub repository.
   - Sign in to GitHub if prompted.
   - Select or create a repository.
6. **Done!**
   - Your folder is now connected and pushed to your GitHub account.
   - You can manage and push changes directly from Visual Studio Code.

---

You can use either method. Visual Studio Code makes it easy with a graphical interface, while Git commands give you more control.
