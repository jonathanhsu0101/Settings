# Install Chrome

search & download & install "chrome beta" from FireFox

# Chinese input

System Settings > Input Method > choose "iBus" > Traditional Chinese > + Chewing

# Move Panel (Taskbar) from bottom to left

right-click on Panel > Modify Panel > Move Panel

# Modify ~/.bashrc

don't use root

open "Folder" > View > Show Hidden Files > open ".bashrc" with "Text Editor"

find "if [ "$color_prompt" = yes ], " > insert '\n' before '\\$'

# switch to root

$ sudo -s

# Install Snapd

$ apt update

$ apt upgrade

$ apt install snapd

https://www.addictivetips.com/ubuntu-linux-tips/enable-snap-package-support-linux-mint/

# Snapd update

$ sudo snap refresh

# Git

$ sudo apt install git

$ sudo git config --global user.name "Your Name"

$ sudo git config --global user.email "youremail@domain.com"

https://help.github.com/en/articles/connecting-to-github-with-ssh

don't use root account

Generating a new SSH key and adding it to the ssh-agent

Adding a new SSH key to your GitHub account

# Install VSCode

$ sudo snap install --classic code

Extensions --> Install Settings Sync --> Login with GitHub --> Shift + Alt + D (download all settings and extensions)

Keyboard Shortcuts > Go to Next Problem in Files --> Ctrl + F8, cursorLineEnd --> F8, Copy Line Down --> Ctrl + Alt + DownArrow, Copy Line Up --> Ctrl + Alt + UpArrow

# Install Postman

$ sudo snap install postman

# create VS Code & Postman icons

$ which code (or postman)

right click Menu > Configure > Menu > Open the menu editor (click on rocket icon to change icon)

# remove unwanted favorites icon from menu (and put it in)

drag it out

drag it in

# disable alt-ctrl-up and alt-ctrl-down hijack

System Settings > Keyboard > Shortcuts > General --> Go to "Show the window selection screen" and "Show the workspace selection screen", double click the shortcuts, remove them using backspace.

# Node & npm

$ sudo snap install node --classic --channel=8

# MongoDB

must follow https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/

but use "$ sudo apt-get install -y mongodb"

don't use "$ sudo apt-get install -y mongodb-org"

# java

$ sudo apt install openjdk-11-jdk

---------------------------------------------------------------------------------------------------

# docker

https://computingforgeeks.com/install-docker-and-docker-compose-on-linux-mint-19/

# @vue/cli

$ sudo npm install -g @vue/cli

# nodemon, express, cors, body-parser, morgan, monk, joi

Must be installed in ./server folder

$ npm install $$$$ --save

# use Vue to create App

$ vue create "App name" (e.g. ./client) (DON'T CHOOSE "Linter / Formatter")

# Svelte, npx, degit

$ npx degit sveltejs/template my-svelte-project

$ cd my-svelte-project

$ npm install --no-optional

$ npm run dev

--------------------------------------

$ sudo npm i -g npx

$ sudo apt install degit

---------------------------------------

/home/steven/Documents/GitHub/project -->

/home/steven/Documents/GitHub/project/emoji-weather
/home/steven/Documents/GitHub/project/message-board
/home/steven/Documents/GitHub/project/Othello
/home/steven/Documents/GitHub/project/reddit-clone
/home/steven/Documents/GitHub/project/restful-shop
/home/steven/Documents/GitHub/project/sandwich
/home/steven/Documents/GitHub/project/score-counter
/home/steven/Documents/GitHub/project/svelte-shopping-app
/home/steven/Documents/GitHub/project/to-do-list

/home/steven/Documents/GitHub/react-class -->

/home/steven/Documents/GitHub/react-class/http-blog
/home/steven/Documents/GitHub/react-class/react-complete
/home/steven/Documents/GitHub/react-class/react-complete-guide
/home/steven/Documents/GitHub/react-class/react-complete-guide-106
/home/steven/Documents/GitHub/react-class/react-complete-guide-144
/home/steven/Documents/GitHub/react-class/react-complete-guide-213
/home/steven/Documents/GitHub/react-class/react-complete-guide-using-hooks
/home/steven/Documents/GitHub/react-class/routing--assignment-problem
/home/steven/Documents/GitHub/react-class/Fabonacci
/home/steven/Documents/GitHub/react-class/lifecycle-creation-learning-card.pdf
/home/steven/Documents/GitHub/react-class/lifecycle-update-external-learning-card.pdf
