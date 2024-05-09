# Environment Setup for HTML5/CSS3 Development (Windows10)

## Setup Folder Structure

- Create the following folder in the C drive:
  - C:\COMP1017

---

## Download Git

- [Git Website](https://git-scm.com/)

- Download the latest version. Allow all the defaults on download. The path should be updated automatically, so that `git` is available from any directory.
- Open a PowerShell or CMD terminal. In the shell run `git --version` to make sure that git is installed and accessible from this directory. Note that it is two minus bars before version. If a version number is not returned, the path must be set so that `git` is available from any directory. To set the path, in the search area at the bottom of the windows task bar type `env` and select `Edit Environment Variables for your Account`. Then edit the `PATH` and add new `C:\Program Files\Git\cmd`. You could add this to the system environments alternatively. Now you can run the `git` command from a terminal anywhere.

---

## Download Visual Studio Code

- [Visual Studio Code Website](https://code.visualstudio.com)
- From VS Code install the extension `live server`.

---

## Clone My Demos to Your Machine

- [My Demos Repo on GitHub](https://github.com/RobbinLawHTMLCSS/html-css-1-demos)
- From the link above, clone my repo to your machine.
  - from the green dropdown copy the link to your clipboard.
  - in VSCode run the command `View/CommandPallet/Git:Clone`
  - clone the repo to `C:\COMP1017`

---

## Test Drive Tool Chain

- Test drive our tools by running the code in the `src` folder with `live server`.

---

## Create a Netlify Account

- [Netlify Website](https://netlify.com)

---
