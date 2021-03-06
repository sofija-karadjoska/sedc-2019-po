# Project Organizaion 2019

SEDC Web Design Official Repository for Project Organization Course

Trainer: Boban Radeski  
E-mail: radeski.boban@gmail.com

## Install Git on Windows

1. Download the required version(32/64bit) of Git on the following URL, https://git-scm.com/download/win  
2. Follow the next steps 
3. Configuring the terminal emulator to use with **Git bash -> Use Windows' default**
4. Run `git --version` in the command prompt to check if the installation is successful
5. Configure GIT for usage, https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup, the first thing you should do when you install Git is to set your user name and email address. This is important because every Git commit uses this information, and it’s immutably baked into the commits you start creating:
  ```
  git config --global user.name "John Doe"
  git config --global user.email johndoe@example.com
  ```

## Install SourceTree client for git
https://www.sourcetreeapp.com/

## Install Kdiff3 merge tool
http://kdiff3.sourceforge.net/

Open SourceTree app -> `Tools -> Options -> Diff -> Merge tool -> Kdiff3`

## Materials and Resources From the Class

On this repository I will push all the materials.
Download as zip or clone the repository to have the latest version of the materials we use such as presentaions or code directories/files. On the downloaded directory **Project Organization Classes** you will find the `assets` and `classXX.html`, open the `classXX.html` in your browser to preview the presentation.

## Additional Resources for Learning Git

1. https://learngitbranching.js.org/
2. https://git-scm.com/
3. https://gitexplorer.com/


## Homework 01
- create new repo, name: **sedc-po-2019-hm-01**
- implement the basic HTML and style in `index.html` and `style.css` into the **master branch**
- create new branch, name: **implement-header**
- checkout to the new branch **implement-header** and implement the header in it
- push the new branch to the REMOTE REPOSITORY

## Workshop (team|dream work)
### One team lead, 2 or 3 team members

1. create a new Remote Repository on GitHub
2. clone, pull - the other team members
3. **master** should be the source of truth, always stable 

3.1. **implement-sidebar** branch for HTML and CSS code

	3.1.1 List of page links (optional)
	3.1.2 image of the (optional) 
	3.1.3 display date and time (optional)
	3.1.4 display weather information (optional)
	
3.2  **implement-contact-form** branch for HTML and CSS code

	3.2.1  push local branch to remote repository
4. rebase 
5. merge
6. delete branches(wait for confirmation) 

files to use: 
`index.html`
`contact.html`
`style.css`
