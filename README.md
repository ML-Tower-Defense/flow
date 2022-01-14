# Flow

This repo contains an example guide on what our workflow (based on [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow)) might look like for project development and collaboration.

## Steps

1. In GitHub Desktop, click the `Current branch` button to open the branch menu. The `main` branch is our default master branch. Click the `New branch` button to create a new branch. The branch name can be based off of the task that you're working on. For example if you're working on implementing a basic map, the branch can be named `implement-basic-map`. The new branch allows you to make whatever changes for your task without affecting the `main` branch.

![Image 01][image01]

![Image 02][image02]

2. Whenever you make changes, the file differences will appear under the `Changes` tab. You can choose which files to commit by checking or unchecking the box next to each file. In the bottom left corner, describe your commit changes by typing into the message box. Click the `Commit to ...` to make the commit. You can publish the branch to push it to the repo.

![Image 03][image03]

![Image 04][image04]

3. When you are done with implementing the task, click the `Create Pull Request` button. This will open a page in the browser. You can name the pull request based off of your task and describe what changes you made in the `Write` box. Click the `Create pull request` button to publish it. This page will show all of the commits that you made on the branch.

![Image 05][image05]

![Image 06][image06]

4. If your pull request is ready for review, you can drop the link to it in Discord and have someone look it over. If everything has been addressed and it is approved, click the `Merge pull request` button. This will merge your branch into the `main` branch which will carry your changes over.

![Image 07][image07]

5. After the pull request has been merged, you can delete the branch.

6. Whenever changes are made to the `main` branch and you want to update it, make sure the `main` branch is selected as the `Current branch` and click the `Pull origin` button to sync it with the latest changes.

![Image08][image08]

[image01]: docs/images/image01.png
[image02]: docs/images/image02.png
[image03]: docs/images/image03.png
[image04]: docs/images/image04.png
[image05]: docs/images/image05.png
[image06]: docs/images/image06.png
[image07]: docs/images/image07.png
[image08]: docs/images/image08.png
