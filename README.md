# github-project

## How to clone the Repository:

1. Go to Github, click on your profile/account and open up your Repositorties.
2. Start a new Repository but clicking the "New" button and create one.
3. Once the Repositiory has been made, go to the main page of where all of your Repositiories are and click "code".
4. From there copy the URL of the Repositorty you want to copy under HTTPS.
5. Open Terminal.
6. Change the current working directory to the location where you want the cloned Repositorty to go.
7. Once you are in the directory that you want, simply type "git clone" and paste the URL of your Repository.
8. Press Enter to create your local clone.

## How to make changes:

### Chnages in Github:

1. In your repository, browse to the file you want to edit.
2. In the upper right corner of the file view, click to open the file editor.
3. In the text box, make any changes you need to the file.
4. Above the new content, click Preview to see the changes you made.
5. Once you are done that, click Commit changes.

### Changes in VSC:

1. Open the file that you plan to make the changes on.
2. Make changes to the file and then save it.
3. Once you have made the chnages, open up your terminal in VSC.
4. Type "git add .", "git commit -m", "git push".

## How do you submit pull requests:

1. Make Your Changes

- Edit your files and save your changes in your branch.

2. Commit Your Changes

- Open the Source Control view by clicking the Source Control icon or using Ctrl + Shift + G.

- Type a commit message in the input box.

- Click the checkmark (✓) icon to commit your changes.

3. Push Your Branch

- Open the terminal in VS Code (View > Terminal or Ctrl + `).

- Push your branch to the remote repository using the command git push origin your-branch-name

4. Open the Pull Request

- After pushing, you can typically find an option to "Create Pull Request" directly in VS Code if you're using the GitHub extension. You may see a prompt or notification after the push.

- Alternatively, you can open your repository on GitHub in your web browser. GitHub usually shows a banner for creating a pull request immediately after pushing a new branch.

5. Fill Out the Pull Request Form

- On GitHub, you’ll see a form to fill out for your pull request:
- Title: Provide a clear and concise title.
- Description: Explain the changes made, why they were made, and any other relevant details.

6. Create the Pull Request

- Once you’ve filled out the necessary information, click the “Create Pull Request” button.

## How to create Branches:

1. Open your Terminal and type "git branch (name of your branch)"
2. Type "git checkout (name of the branch)" in order to switch over to it.
3. Shortcut: Instead of do steps 1 and 2 you can type in "git checkout -b (name of branch)" to not only create a branch but also to switch over to it.

## How to merge Branches:

1. Open your Terminal and type "git branch (name of your branch)" in order to create one.
2. Type "git checkout (name of the branch)" in order to switch over to it.
3. Commit the change but do not push.
4. Checkout back to the main branch using "git checkout (name of the branch)"
5. Merge the new branch into the main using "git merge (name of branch)
