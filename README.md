<!-- Project Title -->
<h1 align="center">GDSC I2IT Hacktoberfest</h1>

<!-- Project Description -->
<p align="center">
  Welcome to the GDSC I2IT Hacktoberfest 2023 repository! Join us in celebrating open source during Hacktoberfest.
</p>

<!-- Hacktoberfest Banner -->
<p align="center">
  <img src="https://hacktoberfest.digitalocean.com/_nuxt/img/logo-hacktoberfest-full.f42e3b1.svg" alt="Hacktoberfest Logo" width="400">
</p>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Hacktoberfest-2023-blueviolet" alt="Hacktoberfest 2023">
  <img src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4%EF%B8%8F-brightgreen" alt="Open Source">
  <img src="https://img.shields.io/github/issues/GDSC-I2IT/Hacktoberfest-2023" alt="GitHub issues">
  <img src="https://img.shields.io/github/forks/GDSC-I2IT/Hacktoberfest-2023" alt="GitHub forks">
  <img src="https://img.shields.io/github/stars/GDSC-I2IT/Hacktoberfest-2023" alt="GitHub stars">
</p>

<!-- Table of Contents -->
## Table of Contents
- [About Hacktoberfest](#about-hacktoberfest)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Code of Conduct](#code-of-conduct)
- [License](#license)

<!-- About Hacktoberfest -->
## About Hacktoberfest
Hacktoberfest is a month-long celebration of open source software. It encourages participation in the open source community and rewards contributors with limited-edition swag.

Learn more about Hacktoberfest [here](https://hacktoberfest.digitalocean.com/).

<!-- Getting Started -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GDSC I2IT - Hacktoberfest 2023</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to GDSC I2IT Hacktoberfest 2023</h1>
        <p>Join us in celebrating open-source contributions!</p>
    </header>
    <section id="about">
        <h2>About Hacktoberfest</h2>
        <p>Hacktoberfest is a month-long celebration of open source software. During October, open-source enthusiasts and developers from around the world come together to contribute to various open-source projects.</p>
    </section>
    <section id="events">
        <h2>Upcoming Events</h2>
        <ul>
            <li>Open Source Workshop - October 5, 2023</li>
            <li>Contributors Meetup - October 15, 2023</li>
            <li>Hacktoberfest Celebration - October 31, 2023</li>
        </ul>
    </section>
    <section id="get-involved">
        <h2>Get Involved</h2>
        <p>Want to participate in Hacktoberfest with GDSC I2IT? Here's how you can get involved:</p>
        <ol>
            <li>Fork one of our GitHub repositories.</li>
            <li>Make meaningful contributions.</li>
            <li>Create a pull request.</li>
            <li>Get your PRs merged and win awesome swag!</li>
        </ol>
    </section>
    <footer>
        <p>Follow us on <a href="https://github.com/GDSC-I2IT">GitHub</a> for updates and contributions.</p>
    </footer>
</body>
</html>


# Welcome to GDSC I2IT Hacktoberfest Dry run!!!

# First Contributions

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

Open a terminal and run the following git command:


git clone "url you just copied"


where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:


git clone git@github.com:this-is-you/first-contributions.git


where this-is-you is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):


cd first-contributions


Now create a branch using the git switch command:


git switch -c your-new-branch-name


For example:


git switch -c add-alonzo-church


## Make necessary changes and commit those changes

Now open Contributors.md file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.

<img align="right" width="450" src="https://firstcontributions.github.io/assets/Readme/git-status.png" alt="git status" />

If you go to the project directory and execute the command git status, you'll see there are changes.

Add those changes to the branch you just created using the git add command:


git add Contributors.md


Now commit those changes using the git commit command:


git commit -m "Add your-name to Contributors list"


replacing your-name with your name.

## Push changes to GitHub

Push your changes using the command git push:


git push -u origin your-branch-name


replacing your-branch-name with the name of the branch you created earlier.

<details>
<summary> <strong>If you get any errors while pushing, click here:</strong> </summary>

- ### Authentication Error
     <pre>remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
  remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
  fatal: Authentication failed for 'https://github.com/<your-username>/first-contributions.git/'</pre>
  Go to [GitHub's tutorial](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) on generating and configuring an SSH key to your account.

</details>

## Submit your changes for review

If you go to your repository on GitHub, you'll see a Compare & pull request button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard fork -> clone -> edit -> pull request workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app](https://firstcontributions.github.io/#social-share).

You could join our slack team if you need any help or have any questions. [Join slack team](https://join.slack.com/t/firstcontributors/shared_invite/zt-1n4y7xnk0-DnLVTaN6U9xLU79H5Hi62w).

Now let's get you started with contributing to other projects. We've compiled a list of projects with easy issues you can get started on. Check out [the list of projects in the web app](https://firstcontributions.github.io/#project-list).

### [Additional material](additional-material/git_workflow_scenarios/additional-material.md)

## Tutorials Using Other Tools

| <a href="gui-tool-tutorials/github-desktop-tutorial.md"><img alt="GitHub Desktop" src="https://desktop.github.com/images/desktop-icon.svg" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs2017-tutorial.md"><img alt="Visual Studio 2017" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Visual_Studio_2017_Logo.svg" width="100"></a> | <a href="gui-tool-tutorials/gitkraken-tutorial.md"><img alt="GitKraken" src="https://firstcontributions.github.io/assets/gui-tool-tutorials/gitkraken-tutorial/gk-icon.png" width="100"></a> | <a href="gui-tool-tutorials/github-windows-vs-code-tutorial.md"><img alt="VS Code" src="https://upload.wikimedia.org/wikipedia/commons/2/2d/Visual_Studio_Code_1.18_icon.svg" width=100></a> | <a href="gui-tool-tutorials/sourcetree-macos-tutorial.md"><img alt="Sourcetree App" src="https://wac-cdn.atlassian.com/dam/jcr:81b15cde-be2e-4f4a-8af7-9436f4a1b431/Sourcetree-icon-blue.svg" width=100></a> | <a href="gui-tool-tutorials/github-windows-intellij-tutorial.md"><img alt="IntelliJ IDEA" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/IntelliJ_IDEA_Icon.svg/512px-IntelliJ_IDEA_Icon.svg.png" width=100></a> |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [GitHub Desktop](gui-tool-tutorials/github-desktop-tutorial.md)                                                                                             | [Visual Studio 2017](gui-tool-tutorials/github-windows-vs2017-tutorial.md)                                                                                                                          | [GitKraken](gui-tool-tutorials/gitkraken-tutorial.md)                                                                                                                                        | [Visual Studio Code](gui-tool-tutorials/github-windows-vs-code-tutorial.md)                                                                                                                  | [Atlassian Sourcetree](gui-tool-tutorials/sourcetree-macos-tutorial.md)                                                                                                                                      | [IntelliJ IDEA](gui-tool-tutorials/github-windows-intellij-tutorial.md)                                                                                                                                                          |

<p>This project is supported by:</p>
<p>
  <a href="https://www.digitalocean.com/">
    <img src="https://opensource.nyc3.cdn.digitaloceanspaces.com/attribution/assets/SVG/DO_Logo_horizontal_blue.svg" width="201px">
  </a>
</p>

