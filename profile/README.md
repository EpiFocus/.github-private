# 1. Welcome to EpiFocus' GitHub 👋.
Welcome to the team's GitHub. It might be your first time using GitHub. No worries! Below you'll find guides on key GitHub features that will help you get started with the projects.

## What is GitHub?
You can see GitHub as a OneDrive that specifically serves for code and data purposes. A **repository** is the core of GitHub, and it's where your project resides. It can contain all sorts of items, from code files and images to data sets and documentation. <br>

# 2. GitHub basics
## 2.1. Adding files to repositories
Navigate to Your Repository: Go to the GitHub repository that hosts your GitHub Pages site.
- To **upload** a file, click on the "Add file" button and select "Upload files." Drag and drop your file or browse to select it. Then, commit the file.
- To **create** a new file directly on GitHub, click on the "Add file" button and select "Create new file." Write or paste your content, name your file appropriately, and commit the new file.
After that, it might be handy to use a Commit Message, that describes the addition of your file. For example, "Modification of inclusion criteria in SAP".

Commit: You can either commit directly to the main branch or create a new branch and start a pull request. You'll see what are those terms after.

## 2.2. Creating a GitHub Page
Creating a GitHub Page provides a way to share your project's results or documentation with the world. Here's how to set one up:
1. **Navigate to your repository** on GitHub.
2. **Go to the 'Settings' tab**, and then find the 'Pages' section in the menu on the left.
3. **Choose a source** for your GitHub Page. Typically, this is either your main branch or a `/docs` folder in your repository.
4. **Click 'Save'**. GitHub will provide you with a URL to access your new GitHub Page.


## 2.3. Data protection
Please ensure no password or personal data is uploaded to GitHub. You'll see some repos may have a .gitignore file to prevent this, but please refrain from doing so.


# 3. Working code essentials: Cloning, Branches and Pull Requests
If you want to change parts of a Stata do-file or a R script, one the best ways to track all the changes and work collaboratively is GitHub. However, it may be difficult at the beginning. Please see some of the most used terms:
- **Cloning**: By cloning a repository, you make a local copy of the repository on your computer. This is essential for working on the project offline, for example with your Stata do-file.
- **Main branch and other branches**: Branches are a way to work code in your personal computer without affecting the "master branch" (or main). This allows each one to work individually without interfering with the main project's flow. It allows multiple features or fixes to be developed in parallel, which hopefully will end in a Pull Request (which essentially means: "guys, let's discuss whether these changes should be in the main project)." 
- **Commits**. Each change of the code in a branch can either be "staged" or "discarded" locally, and then should be committed to save it in your branch.
- **Pull Requests** (or PR) lets others know about your changes in your branch, facilitating discussion and review before integrating your work into the main branch. If you haven't done this before, you can see this exercise: https://docs.github.com/en/get-started/start-your-journey/hello-world
- **Permalinks**. During code reviews and discussions, it's crucial to reference specific lines of code or files at a particular point in time, regardless of any future changes. Permalinks make this possible, ensuring that comments and discussions are always relevant to the code version they were originally made about, preventing confusion as the codebase evolves.

Happy collaborating!
