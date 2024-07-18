# Template Description
This template has the basic file structure for a lesson plan that builds a GitBook.

## Files
Here is a breakdown of the files in this repository:

- [**.github/workflows/BuildGitBook.yml**](.github/workflows/BuildGitBook.yml): This file describes the GitHub action to build the GitBook from this repository. It places the code in a branch named `gh-pages`, which GitHub Pages can use to render the book online.
- [**styles/website.css**](styles/website.css): This file adds custom styles to the GitBook.
- [**.gitignore**](.gitignore): This file lists files that should be ignored by Git.
- [**book.json**](book.json): This file contains configuration information for the GitBook.
- [**TemplateDescription.md**](TemplateDescription.md): This is this file. It contains information about the lesson plan template.
- [**AdditionalPage.md**](AdditionalPage.md): This is an example file that will become a page of the published GitBook.
- [**README.md**](README.md): This file is the landing page for the repository. It should be the primary document for the lesson plan. It will not be published on the GitBook, and is designed for internal instructor reference only.
- [**BookHomePage.md**](BookHomePage.md): This file will be the landing page of the GitBook when it is published. It serves as the lesson homepage for students.
- [**SUMMARY.md**](SUMMARY.md): This file outlines the pages to be published on the GitBook.

## Getting Started
To use this template, follow these instructions:

1. Click the green "Use this template" button when [viewing this repository on GitHub](https://github.com/hylandtechoutreach/lesson-plan-template/)
1. Fill out a Repository name and Description
1. Click the green "Create repository" button
1. In **Settings**, in the **Code and automation section**, under **Actions -> General**, under **Workflow permissions**, select the **Read and write permissions** option 
1. On the new repository, wait for the GitHub action to complete
    - This action will create the `gh-pages` branch
1. When the action is done, click on "Settings"  
    - It may be necessary to push a change to the repository to re-trigger the action
1. On the "Settings" page, on the left, click on "Pages"
1. In the "Build and deployment" section, click the dropdown under "Branch"
1. Select `gh-pages` as the branch
1. Click the "Save" button
1. Wait for a little while, and then refresh the "Pages" page
1. Click the link to the deployment - the GitBook should be published!

After the GitBook is up, all that's left is to actually create the lesson plan in the repository. This file can be removed.
