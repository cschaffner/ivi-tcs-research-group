# homepage of research group Theory of Computer Science (TCS) at University of Amsterdam 

set up in March 2023 by [Christian Schaffner](https://staff.science.uva.nl/c.schaffner/)
online at https://ivi.fnwi.uva.nl/tcs/

based on [Hugo Research Group Theme](https://github.com/wowchemy/starter-hugo-research-group)

## Building this website from scratch locally

### on Mac/Linux

1. Install [Hugo and its dependencies](https://wowchemy.com/docs/getting-started/install-hugo-extended/)

2. Clone this repo:

```bash
git clone git@github.com:cschaffner/ivi-tcs-research-group.git
```

3. Start Hugo server to see the site live locally at http://localhost:1313/ (or at whatever the hugo server tells you)!

```bash
cd ivi-tcs-research-group
hugo server
```

4. Edit the [markdown source files](https://wowchemy.com/docs/content/writing-markdown-latex/) with ending .md in the [/content/](https://github.com/cschaffner/ivi-tcs-research-group/tree/main/content) subdirectory to make changes to the site. As long as the hugo server is running, your changes should be visible immediately at http://localhost:1313/.

5. Using a suitable editor like [Atom](https://atom.io/) or [Visual Studio Code](https://code.visualstudio.com/) allows to easily search across all source files, and will help finding the correct file to edit if you want to make specific changes.

6. Add new researchers by duplicating a similar subfolder in [/content/authors/](https://github.com/cschaffner/ivi-tcs-research-group/tree/main/content/authors) and adjusting the .md content and replacing the avatar picture.

7. Add news items to [/content/post](https://github.com/cschaffner/ivi-tcs-research-group/tree/main/content/post)

8. Add projects to [/content/project](https://github.com/cschaffner/ivi-tcs-research-group/tree/main/content/project)

8. When you are happy with the result, run ```hugo``` to compile create an updated ```public``` directory, and commit the changes to the master branch. Ask Chris to deploy the updated site to the UvA server.

### on Windows
1. Install 
- [Github Desktop](https://desktop.github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Hugo and its dependencies](https://wowchemy.com/docs/getting-started/install-hugo-extended/#windows), including PowerShell and Scoop.

2. do this and that (@Feline, please edit)



## Troubleshooting
This [information](https://wowchemy.com/docs/hugo-tutorials/troubleshooting/) might be useful. Sometimes, you might have to [delete Hugo's default cache folder](https://wowchemy.com/docs/hugo-tutorials/troubleshooting/#error-failed-to-resolve-output-format).

For more information, try the search function on the [wowchemy website](https://wowchemy.com/).