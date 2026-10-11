---
title: "Improving the documentation"
---

This documentation is written and maintained by the Battery Emulator community. If you spot a mistake, find something outdated, or know a detail that is missing, you can fix it yourself, right in your browser. No software to install and no git knowledge needed.

!!! info "What you need"
    A free [GitHub account](https://github.com/signup). Sign in to GitHub before you start.

## Step 1: Click "Edit this page"

Every page on this site has an **Edit this page** button: the pencil icon in the top right corner, next to the page title. Go to the page you want to improve and click it.

<img width="825" height="326" alt="Edit this page button" src="https://github.com/user-attachments/assets/af26453c-2dcf-480c-8476-7e6df9c2d1e6" />

This takes you to the source file of that page on GitHub.

## Step 2: Open the editor

GitHub shows the source of the page. Click the pencil icon (**Edit this file**) above the file contents.

<img width="525" height="224" alt="Edit this file on GitHub" src="https://github.com/user-attachments/assets/81548c4f-4b55-4610-89bd-bd117aa32530" />

## Step 3: Fork the repository

Since you don't have write access to the documentation repository, GitHub asks you to make your own copy of it first (a *fork*). Click **Fork this repository** button:

<img width="647" height="202" alt="Fork this repository" src="https://github.com/user-attachments/assets/cb616f01-1510-4cd7-9e1c-563b3c06b692" />

Your changes will be saved in your fork, and from there you ask the project team to take them over. **This is needed only the first time**: next time GitHub reuses your existing fork.

## Step 4: Make your changes

The editor opens with the text of the page in Markdown format. Make the changes needed, and use the **Preview** tab for a partial syntax check.

<img width="684" height="660" alt="Editing the page" src="https://github.com/user-attachments/assets/b323ae84-adfc-4ae8-8cc0-779bb92d65f6" />

!!! note
    GitHub's preview is close to, but not the same as, this site. Boxes like this one, image sizes and icons only show up correctly once the site is built. When unsure, look at how other pages do it and keep the existing formatting.

Keep a change focused on one topic. A few small, separate changes are easier to review than one big one.

!!! tip
    Need to add a new picture? Just paste the image anywhere you'd like to have it displayed in the page!

## Step 5: Commit (save) your changes

Click the green **Commit changes...** button at the top right when you're done. In the dialog, write a short summary of what you changed in **Commit message**. Add more details in **Extended description** if needed, then click **Propose changes**.

<img width="480" height="433" alt="Commit changes dialog" src="https://github.com/user-attachments/assets/58364c8d-0ee6-4703-b6ed-16ef1d56497b" />

## Step 6: Send in the pull request

GitHub shows an overview of your changes. Click **Create pull request** button:

<img width="732" height="483" alt="Create pull request" src="https://github.com/user-attachments/assets/e165ba62-1fd5-484b-af80-67804af4cace" />

The pull request form opens with a template already filled in. Complete it:

- **Description**: what you changed and why.
- **Related issue**: link the issue this fixes, if there is one, otherwise delete the line.
- **Pull request in Battery Emulator**: if your change documents a software change, link that pull request here.
- **Types of changes**: tick the boxes that apply, by replacing `[ ]` with `[x]`.

Then click **Create pull request** to send it in:

<img width="843" height="111" alt="Create pull request go" src="https://github.com/user-attachments/assets/c5c5a47a-ffa6-45de-bc20-3530c6688674" />

## Step 7: Review and merge

The project team admins review the changes you suggested. They may merge them right away, or ask questions or request changes in the comments of the pull request. GitHub notifies you about these by e-mail and under the bell icon :material-bell-outline: on GitHub.

Once merged, your changes are published on the live site.

### Coming back to your pull request

Your pull request lives in the documentation repository, not in your fork. To find it later, open the [Pull requests](https://github.com/dalathegreat/Battery-Emulator-Wiki/pulls?q=is%3Apr+author%3A%40me) tab of the documentation repository. This link lists only the pull requests you opened.

<img width="947" height="350" alt="Branch of the pull request in your fork" src="https://github.com/user-attachments/assets/d8338494-60f2-42dd-9ec8-f90f4435299e" />

Click on your pull request. At the top of the pull request there's a line like *yourname wants to merge 1 commit into `dalathegreat:main` from `yourname:patch-1`*. The part after "from" is the branch in your fork that holds your changes. Click it to open that branch.

<img width="746" height="174" alt="Branch of the pull request in your fork" src="https://github.com/user-attachments/assets/7b6c0cb6-0a56-4e6c-9a4c-fdf69b23d725" />

This is your fork, with the changes in your unique branch! To change a file again, for example when the reviewers ask for it:

1. On your branch, navigate to the file. The files are in the `docs` folder, following the addresses of the site: for example the page `.../setup/software/mqtt/` is the file `docs/setup/software/mqtt.md`.
2. Click the pencil icon and make your changes.
3. Click **Commit changes...** and write a short summary. Make sure **Commit directly to the `patch-1` branch** is selected, then click **Commit changes**.

This will save the changes in your already existing branch, and will update the pull request with your additional changes.

!!! note "Warning"
    Once you pull request has been merged, and the changes appeared on the live site, that branch won't be used anymore. For further changes, you need to start editing the file again from scratch.

Thank you for helping improve the documentation!
