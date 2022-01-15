# Flow

This repo contains an example guide of what our workflow (based on [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow)) might look like for project development and collaboration.

## Steps

1. In GitHub Desktop, click the `Current branch` button to open the branch menu. The `main` branch is our default master branch that we will branch off of when starting on a new task. Click the `New branch` button to create a new branch. When choosing a branch name, you can refer to the task that you're working on. For example if you're working on implementing a basic map, you could name the branch `implement-basic-map`. The new branch allows you to make whatever changes for your task without affecting the `main` branch. After naming the branch, click the `Create branch` button.

![Image 01][image01]

![Image 02][image02]

2. Whenever you make changes locally, the file differences will appear under the `Changes` tab. You can choose which files to commit by checking the box next to each file. If there are files that you don't want to include in the commit, you can uncheck the box for those files. In the bottom left corner, describe your commit changes by typing into the message box. Click the `Commit to ...` to make the commit. You can publish the branch to push it to the repo.

![Image 03][image03]

![Image 04][image04]

3. After you have completed your work on the task, click the `Create Pull Request` button. This will open a page in the browser. You can name the pull request based off of your task and describe the changes you made in the `Write` box. Click the `Create pull request` button to publish it.

![Image 05][image05]

![Image 06][image06]

4. If your pull request is ready for review, you can drop the link to it in Discord and have someone look it over. If everything has been addressed and it is approved, click the `Merge pull request` button. This will merge the changes from your branch into the `main` branch.

![Image 07][image07]

5. After the pull request has been merged, you can click the `Delete branch` button to indicate that the work on that branch is done.

![Image 09][image09]

6. Whenever changes are made to the remote `main` branch, you'll need to pull the changes to update your local version of the `main` branch. To do this, make sure the `main` branch is selected as the `Current branch` and click the `Pull origin` button to sync it with the latest changes.

![Image 08][image08]

[image01]: docs/images/image01.png
[image02]: docs/images/image02.png
[image03]: docs/images/image03.png
[image04]: docs/images/image04.png
[image05]: docs/images/image05.png
[image06]: docs/images/image06.png
[image07]: docs/images/image07.png
[image08]: docs/images/image08.png
[image09]: docs/images/image09.png
