# Circle CI

Go to circle CI:

Login as Prolike for admin rights

Add projects --> Setup project

For self (Upload Circle CI folder(Config.yml, manuscript.yml), Module(Tiny.pm) and Play file)
paste it into the working directory
Make play file executable sudo chmod 755 

Git phlow does not work yet, as the setup isn't complete, therefore use push.

Click "Start building" after push is complete

as prolike user: permissions --> checkout ssh keys --> verify key

Setup prolike github token environment variable
Add environment variable

name: GHTOKEN_PROLIKE
value: 93f53aa4ba34407a7a8368276f6f0ea78d303ae3

