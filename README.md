# 2023cookbook
## https://github.com/chezmarcbrown/2023cookbook.git

This repo contains a crowd-sourced cookbook with contributions by students in UAA490, Fall 2023.

The purpose is to give you a chance to write some HTML and to use git. As a freebie benefit, your classmates will get to learn a bit about you! 

Your job is to add to this repo an HTML page with a recipe that speaks to you. Add images to the folder *images*, and add a link to your recipe page in the file *index.html*. You can see what I did in https://uaa490.org/2023cookbook/recipe-salsa.html; you can start with a copy of that file or start with a copy of https://uaa490.org/2023cookbook/recipe-starter.html or start bare-bones. The skeleton of your html page will be the following:

```
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" href="https://cdn.simplecss.org/simple.css">
    <title>...</title>
  </head>
  <body>
  ...
  </body>
</html>
```

The line that starts with the `link` tag adds some beauty to the page using a library called "simplecss" (https://simplecss.org/). You can see the beauty it adds by deleting that line. 

A straighforward way for you to add your files and the modify *index.html* file is for you **fork** this repo, **clone** it and make your changes to your clone, **commit** the changes, and then issue a **pull request** (resolve all **merge conflicts** before the PR!). I'll handle the PR and then push the updated repo to https://uaa.org/2023cookbook. Include your first name in the name of your new files, so there are no conflicts with classmates who also want to post a page with a recipe for Brownies. For example, a better name for recipe-salsa.html would be recipe-marc-salsa.html.

If you don't understand the previous paragraph, then you need to read up on using **git**. Here's a short and sweet YouTube intro to get you started: https://www.youtube.com/watch?v=i_23KUAEtUM. Here's a nice read on cloning and forking: https://www.freecodecamp.org/news/how-to-fork-a-github-repository/

(Note that I removed the `<nav>` tag from the files that were shown in the ppt for the class. Keeping that tag as the table of contents for pages would have required modification to all pages in our website each time a new recipe was added.)

