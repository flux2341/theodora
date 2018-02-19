# theodora
a light-weight markdown wiki


Markdown's syntax is simple enough that you can focus on writing and not be over-burdened by formatting. By offloading file management on git, we can keep the application small and simple and you have control over your content. You can host it wherever you like and use whatever editor you like. It can be used as a boilerplate or as a drop-in solution.


# todo
- prototype angular front-end
  - table of contents, file list
  - history, location (time and space) - able to switch between them with hourglass and tree
- serve any non-markdown files statically (images, pdfs, etc)
- at least some primitive way of syncing the writing repo
  - run a script, sparse checkout
  - delete and re-clone, rather than pulling
  - periodic sync, a guide for setting up a cron
- only one admin, no other users
  - admin and username are stored in settings
  - edit name/value pairs for settings
  - trigger a re-clone of the writing repo
  - have a special login that's otherwise unlinked to the rest
- themes folder, separate css files
  - allow admins to set a default theme
  - allow admins the to allow users to pick their own theme
  - when a user selects a theme, store in a cookie
- better looking scrollbar
  - https://codepen.io/akinjide/pen/BpggrZ
- search
- installation guide
  - setting up a repo
  - creating a virtual server (digital ocean + ubuntu)
  - installing and configuring theodora

# maybe
- user and login system
  - git info stored with user
  - admin and editor roles
  - admin - edit users, git settings
- markdown editor
- css/theme editor



