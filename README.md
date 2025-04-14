# FinalProject_QTM151

## Environment Setup and Guidelines

This project requires Python 3.12.7 and several key libraries for data analysis and visualization. We recommend using [Conda](https://docs.conda.io/en/latest/) to manage your environment. Follow these steps to set up the project:

1. **Install Conda:**  
   If you don’t have Conda installed, download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution).

2. **Create a New Conda Environment:**  
   Open your terminal and create a new environment named `qtm151` (or a name of your choice) with Python 3.12.7:
   ```bash
   conda create -n qtm151 python=3.12.7

3. Activate the Environment:
   ```bash
   conda activate qtm151

4. Install Required Libraries:
   ```bash
   conda install pandas numpy matplotlib seaborn

## GitHub Branching and Collaboration Guidelines

To ensure a stable main branch and smooth collaboration, please follow these rules:

1. **Do Not Work Directly on the Main Branch:**  
   All work should be done in individual feature branches. This helps avoid conflicts and ensures that the main branch remains stable.

2. **Create Your Own Branches in VS Code:**  
   - Open the Source Control panel in VS Code (Ctrl+Shift+G or Cmd+Shift+G).
   - Click the current branch name in the bottom-left corner.
   - Select **"Create new branch"**, then name your branch appropriately (e.g., `yourname`).
   - VS Code will switch to your new branch automatically.

3. **Commit Message:**  
   As you make changes, commit them often with clear, descriptive messages. This keeps your work organized and makes it easier to track progress.

4. **Push Your Branch:**  
   Once you've committed your changes, push your branch to GitHub using the **"Push"** command from the Source Control panel or the Command Palette (Ctrl+Shift+P / Cmd+Shift+P → "Git: Push").

5. **Create a Pull Request:**  
   After pushing, open a pull request to merge your branch into the main branch. Use the GitHub website or the GitHub extension in VS Code to create and manage your pull requests.

6. **Code Review and Conflict Resolution:**  
   Your pull request must be reviewed by the team to check for any conflicts or issues before merging. Address any feedback or conflicts as needed. Only after a successful review should your branch be merged into the main branch.

Following these guidelines will help maintain a clean and conflict-free codebase while enabling efficient collaboration on our project.
