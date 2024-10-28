

<h1 align="center">Contributors Guide⚡ </h1>
<h3 align="center">Welcome to our open-source project! 😍<br> We appreciate your interest in contributing.😊 <br>This guide will help you get started with the project and make your first contribution.</h3>

  # Project Structure 📂

```bash

SPROCTOR/
├── .github/                  # GitHub-related files
│   ├── workflows/            # CI/CD workflows
│   └── ISSUE_TEMPLATE/       # Issue templates for GitHub
├── Assets/                   # Project assets (images, icons, etc.)
│   ├── image.png             # Image file
│   ├── GSSoC-Ext.png         # Image for GSSoC
│   └── heatmap_combined_20241009_144503.png # Heatmap image
├── Backend/                  # Backend code
│   ├── SQLFILE.sql           # SQL database file
│   ├── audio.py              # Audio processing script
│   ├── detection.py          # Detection algorithms
│   ├── face-rec.py           # Face recognition script
│   ├── graph.py              # Graph-related functionalities
│   ├── head_pose.py          # Head pose estimation script
│   ├── login.py              # User login handling
│   ├── peer_comparison_tool.py # Peer comparison tool
│   ├── processes.py          # Various processes
│   ├── pyaudio_test.py       # PyAudio testing script
│   └── run.py                # Main execution file
├── GUI/                      # Graphical User Interface files
│   ├── active.html           # Active user interface
│   ├── copypaste.html        # Copy-paste interface
│   ├── windowClose.html       # Window close interface
├──calendarApp/
|       ├── calendar.html   
├──contributor/           # Contributor-related files
│       ├── contributor.html   # Contributor page
│       ├── contributor.css    # Contributor styles
│       └── contributor.js     # Contributor scripts
├── .gitignore                # Git ignore file
├── CODE_OF_CONDUCT.md        # Code of conduct
├── CONTRIBUTING.md           # Contribution guidelines
├── LICENSE                   # License file
├── PROJECT_STRUCTURE.md      # Project structure documentation
├── README.md                 # Main README file with project details
├── logic.xlsx                # Logic spreadsheet
├── requirements.txt          # Project dependencies
└── repo_structure.txt        # Repository structure documentation

```


# :zap: First Pull Request ✨

1. **Star this repository**
    Click on the top right corner marked as **Stars** at last.

2. **Fork this repository**
    Click on the top right corner marked as **Fork** at second last.                  

3. **Clone the forked repository**                   

```bash
git clone https://github.com/<your-github-username>/SPROCTOR.git
```
  
4. **Navigate to the project directory**

```bash
cd SPROCTOR
```

5. **Create a new branch**

```bash
git checkout -b <your_branch_name>
```

6. **To make changes**

```bash
git add .
```

7. **Now to commit**

```bash
git commit -m "add comment according to your changes or addition of features inside this"
```

8. **Push your local commits to the remote repository**

```bash
git push -u origin <your_branch_name>
```

9. **Create a Pull Request**

10. **Congratulations! 🎉 you've made your contribution**

<br>

# :zap: Alternatively contribute using GitHub Desktop 🖥️

1. **Open GitHub Desktop:**
   Launch GitHub Desktop and log in to your GitHub account if you haven't already.

2. **Clone the Repository:**
   - If you haven't cloned the repository yet, you can do so by clicking on the "File" menu and selecting "Clone Repository."
   - Choose the repository from the list of repositories on GitHub and clone it to your local machine.

3. **Switch to the Correct Branch:**
   - Ensure you are on the branch that you want to submit a pull request for.
   - If you need to switch branches, you can do so by clicking on the "Current Branch" dropdown menu and selecting the desired branch.

4. **Make Changes:**
   Make your changes to the code or files in the repository using your preferred code editor.

5. **Commit Changes:**
   - In GitHub Desktop, you'll see a list of the files you've changed. Check the box next to each file you want to include in the commit.
   - Enter a summary and description for your changes in the "Summary" and "Description" fields, respectively. Click the "Commit to <branch-name>" button to commit your changes to the local branch.

6. **Push Changes to GitHub:**
   After committing your changes, click the "Push origin" button in the top right corner of GitHub Desktop to push your changes to your forked repository on GitHub.

7. **Create a Pull Request:**
   - Go to the GitHub website and navigate to your fork of the repository.
   - You should see a button to "Compare & pull request" between your fork and the original repository. Click on it.

8. **Review and Submit:**
   - On the pull request page, review your changes and add any additional information, such as a title and description, that you want to include with your pull request.
   - Once you're satisfied, click the "Create pull request" button to submit your pull request.

9. **Wait for Review:**
    Your pull request will now be available for review by the project maintainers. They may provide feedback or ask for changes before merging your pull request into the main branch of the repository.

<br>


# :zap: Good Coding Practices 🧑‍💻

1. **Follow the Project's Code Style**

   - Maintain consistency with the existing code style (indentation, spacing, comments).
   - Use meaningful and descriptive names for variables, functions, and classes.
   - Keep functions short and focused on a single task.
   - Avoid hardcoding values; instead, use constants or configuration files when possible.

2. **Write Clear and Concise Comments**

   - Use comments to explain why you did something, not just what you did.
   - Avoid unnecessary comments that state the obvious.
   - Document complex logic and functions with brief explanations to help others understand your thought -process.

3. **Keep Code DRY (Don't Repeat Yourself)**

   - Avoid duplicating code. Reuse functions, methods, and components whenever possible.
   - If you find yourself copying and pasting code, consider creating a new function or component.

4. **Write Tests**

   - Write unit tests for your functions and components.
   - Ensure your tests cover both expected outcomes and edge cases.
   - Run tests locally before making a pull request to make sure your changes don’t introduce new bugs.

5. **Code Reviews and Feedback**

   - Be open to receiving constructive feedback from other contributors.
   - Conduct code reviews for others and provide meaningful suggestions to improve the code.
   - Always refactor your code based on feedback to meet the project's standards.

<br>

# :zap: Pull Request Process 🚀

When submitting a pull request, please adhere to the following:

1. **Self-review your code** before submission. 
2. Include a detailed description of the functionality you’ve added or modified.
3. Comment your code, especially in complex sections, to aid understanding.
4. Add relevant screenshots to assist in the review process.
5. Submit your PR using the provided template and hang tight; we'll review it as soon as possible! 🚀

<br>          

## 🏆 Contribution Points

All tasks will be assigned various levels based on complexity and required skills. Each level provides different points:

- **🥇 Level 1:** 10 Points  
- **🥈 Level 2:** 25 Points  
- **🥉 Level 3:** 45 Points

<br>

# :zap: Issue Report Process 📌            

To report an issue, follow these steps:                   				 
1. Navigate to the project's issues section :- [Issues](https://github.com/tanishaness/SPROCTOR/issues)
2. Provide a clear and concise description of the issue.
3. **Avoid spamming** to claim an issue. Patience is key! 
4. Wait until someone looks into your report.
5. Begin working on the issue only after you have been assigned to it. 🚀

<br>

# Thank you for contributing 💗

We truly appreciate your time and effort to help improve our project. Feel free to reach out if you have any questions or need guidance. Happy coding! 🚀

##


