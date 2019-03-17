# Installation
More details to follow

## Background
More details to follow
Kieran is a pain in the ass


## Commands
```
…or create a new repository on the command line
echo "# iaac-docs" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/bissessr/iaac-docs.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/bissessr/iaac-docs.git
git push -u origin master


…Git Hub Pages


PS C:\Users\Raj\Documents\_LAB\_PROJECTS\iaac-docs> mkdocs gh-deploy
INFO    -  Cleaning site directory
INFO    -  Building documentation to directory: C:\Users\Raj\Documents\_LAB\_PROJECTS\iaac-docs\site
WARNING -  Version check skipped: No version specificed in previous deployment.
INFO    -  Copying 'C:\Users\Raj\Documents\_LAB\_PROJECTS\iaac-docs\site' to 'gh-pages' branch and pushing to GitHub.
INFO    -  Your documentation should shortly be available at: https://bissessr.github.io/iaac-docs/
PS C:\Users\Raj\Documents\_LAB\_PROJECTS\iaac-docs>

```

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
