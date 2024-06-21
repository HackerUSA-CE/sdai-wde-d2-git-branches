# Lab 1: Understanding Git Branches and Creating Initial Wireframe

---

## Activity Title - Build the Initial Wireframe

---

## Description 📄
This lab will guide you through creating an initial wireframe for a webpage using HTML and Git branches. You'll create branches for each part of the wireframe.

---

## Acceptance Criteria 📋
1. **Create a repository:** Initialize a new Git repository and upload it to GitHub.
2. **Main branch:** Set up the main branch with the basic structure.
3. **Feature branches:** Create separate branches for the header, footer, and main content sections.
4. **HTML structure:** Each branch should contain the corresponding HTML structure.

---

## ToDo list ✅
**Attention**: When you complete a task, put an `x` in the middle of the brackets to mark it off your ToDo list.

- [ ] Initialize a new Git repository:
  1. Open your terminal or Git Bash.
  2. Using command line, navigate to where you want your repo to reside, then use `mkdir project-name` with the project name of your choice.
   
   **All repository names must be a folder or directory with a title that only has lowercase letters and dashes between words**

  3. Using `cd`, go into the directory you just made.
  4. Initialize a new Git repository: `git init`.
  5. Create a README file: `echo "# Project Title" >> README.md`.
  6. Add the README file to staging: `git add README.md`.
  7. Commit the README file: `git commit -m "Initial commit with README"`.
- [ ] Create a new repository on GitHub:
  1. Go to GitHub and log in to your account.
  2. Click the "New" button to create a new repository.
  3. Enter a repository name and description.
  4. Choose the "Public" option.
  5. Do not initialize with a README (you already have one).
  6. Click "Create repository".
- [ ] Push your local repository to GitHub:
  1. Follow the instructions provided by GitHub to push an existing repository from the command line:
     ```
     git remote add origin https://github.com/your-username/your-repository-name.git
     git branch -M main
     git push -u origin main
     ```
- [ ] Create and switch to the `main` branch:
  1. Ensure you are on the `main` branch: `git checkout main`.
- [ ] Create a basic HTML file (`index.html`) with the doctype and root elements:
  1. Create `index.html` in your project directory.
  2. Add the boilerplate HTML structure using the `!` cheat. 
  3. Add and commit the changes: `git add index.html`, `git commit -m "Added basic HTML structure"`.
  4. Push the changes to GitHub: `git push origin main`.
- [ ] Create a branch for the header section:
  1. Create and switch to the `header` branch: `git checkout -b header`.
  2. Add a header element to `index.html` on the `header` branch:
     ```html
     <body>
         <header>
             <h1>Header Section</h1>
         </header>
     </body>
     ```
  3. Add and commit the changes: `git add index.html`, `git commit -m "Added header"`.
  4. Push the changes to GitHub: `git push origin header`.
- [ ] Repeat steps 4-6 for the footer (`footer` branch) and main content (`main-content` branch):
  1. For the footer branch: `git checkout -b footer`, add the footer element, commit, and push.
  2. For the main-content branch: `git checkout -b main-content`, add the main content elements, commit, and push.
5. [ ]  Check your GitHub repository on the site. You should see three buttons that say `Compare & pull request`.

![GitHub pull request image](/assets/images/prs-github.png)

6. [ ] Now if you click on the 'branches' section of your codebase, you'll see this.

![GitHub pull request image](/assets/images/branches-github.png)

**🛑 Do not do anything else from this point 🛑**
   

🎊 **Fantastic work! You just finished your first HTML coding lab.** 🎊

---

## Solution codebase 👀
🛑 **Only use this as a reference** 🛑

💾 **Not something to copy and paste** 💾

**Note:** This lab references a solution file located [here]() (link not shown).