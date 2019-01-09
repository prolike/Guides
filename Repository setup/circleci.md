# Circle CI

Go to circle CI:

Login as Prolike for admin rights on both Github and CircleCI

Add projects --> Setup project

For self (Upload Circle CI folder(Config.yml, manuscript.yml), Module(Tiny.pm) and Play file)
paste it into the working directory
Make play file executable sudo chmod 755 
 
If you got Git Phlow installed, you can now use ```git deliver --local``` otherwise you gonna manually push it to master!

Click "Start building" after push is complete

as prolike user: permissions --> checkout ssh keys --> verify key

Generate a new token with access to repositories from here: https://github.com/settings/tokens
Save that key until you used it next!

Setup prolike github token environment variable
Add environment variable

name: GHTOKEN_PROLIKE
value: Your Token

