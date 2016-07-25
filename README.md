# The Sass Project
The Sass Project is a guide to get you up && running quickly to compile your CSS using nothing but your command line and/or terminal. Once I discovered a few commands, finally able to navigate myself gently around the terminal - what I discovered was, that, using the command line, I was able to start coding faster, easier, and with less errors. It was m a g i c a l. These are the simple things I made notes of that helped me make the transition from 3rd party apps _(codekit && prepos)_ to only my terminal.

###Install Sass

Step 1—

This is the first-timer install section. To get started, we need to first find the terminal. On a mac, type ```cmd+spacebar``` and search for _"terminal"_. Once you're in the terminal, we need to do 1 -of- 2 things. A. If this is your first time, you need to install Sass on your machine. Otherwise, B, you need to update it.

For Newbs, please type the command ```sudo gem install sass```. This will go out and fetch the gem Sass and install it on your machine. Intially, it'll ask for your password; this will just be your cpu's start up credentials.

Those of you who have already installed Sass but need to get up && running on a new/current project, update Sass by typing ```sudo gem update sass```.

Finally, if you would just like to check the current version or simply make sure it's installed, type ```sass -v``` for version.

1. Intial Installation of Sass ```sudo gem install sass```
2. Update Sass ```sudo gem update sass```
3. Check Sass version ```sass -v```


###Using Sass

Step 2—

To get the Sass compiler up && running, watching our project, we will need to use the ```--watch``` command so that it can begin looking for changes in our project folder _(directory)_.

First things, first. We need to make sure we're in the correct directory of or project. Here are some helpful commands in order to get us to that point.

1. Change directory to desktop > folder ```cd desktop/project-name```
2. If you're already on desktop, simply ```cd project-name```
3. Shows you where you're at ```pwd```
4. Shows the files & folders in the current directory ```ls```
5. Stop Sass from watching ```ctrl-c```


Step 3—

Once you know you're in the correct location/file/directory of the project you're going to be working on - it's probably best to keep your CSS & Sass in separate folders. Therefore, we'll want to use the command ```sass --watch sass:css```. This is saying, _"Hey Sass, watch all the files in the 'Sass' folder for any changes and update the stylesheet in the 'CSS' folder."_ A few more tips include;

1. Start watching & compiling Sass to CSS ```sass --watch sass:css```
2. Compress and minify code by using ```sass --watch --style compressed sass:css```
3. Compile an single file, ```sass --watch --style compressed file-name.sass:file-name.css```
