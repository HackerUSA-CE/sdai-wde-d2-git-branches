# Lab 1: Understanding Git Branches and Creating Initial Wireframe

---

## Activity Title - Build the Initial Wireframe

---

## Description 📄
This lab will guide you through creating an initial wireframe for a webpage using HTML and Git branches. You'll create a branch for the header section, add the header, and merge it back into the main branch.

---

## Acceptance Criteria 📋
1. **Create a repository:** Initialize a new Git repository locally.
2. **Main branch:** Set up the main branch with the basic structure.
3. **Feature branch:** Create a separate branch for the header section.
4. **HTML structure:** Add the header structure to the feature branch and merge it into the main branch.
5. **Upload to GitHub:** Upload the repository to GitHub.

---

## ToDo list ✅
**Attention**: When you complete a task, put an `x` in the middle of the brackets to mark it off your ToDo list.

- [ ] Initialize a new Git repository:
  1. Open your terminal or Git Bash.
  2. Navigate to where you want your repository to reside: `mkdir project-name` (replace "project-name" with your project name). Ensure all repository names are lowercase and use dashes between words.
  3. Change into the directory you just created: `cd project-name`.
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
  1. Create and switch to the `feature-header` branch: `git checkout -b feature-header`.
  2. Add a header element to `index.html` on the `feature-header` branch.
  3. Add and commit the changes: `git add index.html`, `git commit -m "Added header"`.
  4. Push the changes to GitHub: `git push origin feature-header`.
- [ ] Create a pull request to merge the `feature-header` branch into the `main` branch:
  1. Go to your GitHub repository.
  2. You should see a button that says "Compare & pull request". ![Compare & Pull Request button](/assets/images/prs-github.png)
  3. Click the button.
  4. On the "Open a pull request" page, check the following:
     1. **Red box** - Ensure the `main` branch is compared with the `feature-header` branch. 
     2. **White box** - Verify if it is able to be merged with the `main` branch.
     3. **Green box** - Add any notes you want to include.
     4. **Purple box** - Click the "Create pull request" button. ![Pull request page](/assets/images/create-pr.png)
- [ ] Merge the pull request:
  1. On the "Merge pull request" page, check the following:
     1. **Red box** - Ensure the branch does not contain conflicts.
     2. **Blue box** - Click the "Merge pull request" button and then close the request. ![Merge PR page](/assets/images/merge-pr.png)

🎊 **Fantastic work! You just finished your first HTML coding lab.** 🎊

---