# Template Repository Guide

This guide walks you through the process of cloning, setting up, and collaborating on a GitHub repository based on this template.

## Cloning the Repository

1. **Start with the Template:** Click **Use Template** in the top right corner of this repository page. Ensure the repository is public to facilitate collaboration.

   ![Screenshot 2024-04-05 123446](https://github.com/InteracionLabWorkshopTeam/repository-template/assets/74628574/42081397-92eb-43df-a131-9b95dc80bdd3)

2. **Prepare Your Environment:**
   - Ensure you have the correct version of Git installed on your computer. [Download Git Here](https://git-scm.com/downloads).
   - Open Git Bash or Terminal in a folder of your choice:
     - **Windows:** Open the folder in explorer, right-click, select *Show more options*, then *Git Bash here*.
     - **Mac:** Open the folder in Finder, control-click the path bar, choose *Open in Terminal*.

3. **Clone the Repository:** Use the command `git clone <your repository url>` to clone your new repository to your computer.

---

## Setting Up Your Local Repository

1. **Create a File:** Inside the cloned repository folder, create a `filename.txt` file and save it.
2. **Commit and Push:**
   - Open Git Bash/Terminal again.
   - Stage your new file with `git add filename.txt`.
   - Commit your changes using `git commit -m 'your commit comment'`.
   - Push your changes with `git push`.

Refreshing your GitHub repository page should now show the `filename.txt` file.

---

## Collaboration and Branching

### Initial Setup

1. **Collaboration:** Pair up in groups of 2 or 3. Add each other as collaborators under Settings > Collaborators and Teams > Add People, granting write access.

   ![Collaboration Image](https://github.com/InteracionLabWorkshopTeam/repository-template/assets/74628574/d965c17c-5388-4283-8da7-3ed8e2a6924e)

### Creating a Branch

1. **Branch Out:** Now that you have access to each other's repositories, it's time to create a branch. A branch creates a 1:1 copy of the repository, allowing you to make changes without affecting the main branch directly.

2. **Development:** Clone the branch, commit, and push changes as you would with the main repository. This method allows simultaneous development and careful integration of changes.

   ![Git Branching](https://github.com/InteracionLabWorkshopTeam/repository-template/assets/74628574/33e9961d-893e-45ac-8e8f-e050dda9a492)

Branching is essential for collaborative development, allowing for safe testing and gradual integration of new features or changes.
