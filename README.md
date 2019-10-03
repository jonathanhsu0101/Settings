# Chinese input

System Settings > Input Method > choose "iBus" > Traditional Chinese > + Chewing

# Move Panel from bottom to left

right-click on Panel > Modify Panel > Move Panel

# vi ~/.bashrc

find if [ "$color_prompt" = yes ], insert '\n' before '\\$'

# switch to root

$ sudo -s

# Install Chrome

search & download & install "chrome beta" from FireFox

# Install Snapd

$ apt update

$ apt upgrade

$ apt install snapd

https://www.addictivetips.com/ubuntu-linux-tips/enable-snap-package-support-linux-mint/

# Snapd update

$ sudo snap refresh

# Install VSCode

$ sudo snap install --classic code

Extensions --> Install Settings Sync --> Login with GitHub --> Shift + Alt + D (download all settings and extensions)

Keyboard Shortcuts > Go to Next Problem in Files --> Ctrl + F8, cursorLineEnd --> F8, Copy Line Down --> Ctrl + Alt + DownArrow, Copy Line Up --> Ctrl + Alt + UpArrow

# disable alt-ctrl-up and alt-ctrl-down hijack

System Settings > Keyboard > Shortcuts > General --> Go to "Show the window selection screen" and "Show the workspace selection screen", double click the shortcuts, remove them using backspace.

# Node & npm

$ sudo snap install node --classic --channel=8

# Install Postman

$ sudo snap install postman

# create VS Code & Postman icons

$ which code (or postman)

right click Menu > Configure > Menu > Open the menu editor (click on rocket icon to change icon)

# MongoDB

must follow https://docs.mongodb.com/manual/tutorial/install-mongodb-on-ubuntu/

but use "$ sudo apt-get install -y mongodb"

don't use "$ sudo apt-get install -y mongodb-org"

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

# Git

$ apt install git

$ git config --global user.name "Your Name"

$ git config --global user.email "youremail@domain.com"

https://help.github.com/en/articles/connecting-to-github-with-ssh

don't use root account

Generating a new SSH key and adding it to the ssh-agent

Adding a new SSH key to your GitHub account

# java

$ sudo apt install openjdk-11-jdk

# docker

https://computingforgeeks.com/install-docker-and-docker-compose-on-linux-mint-19/

