# The Sass Project
The Sass Project is a guide to get you up && running quickly to compile your CSS using nothing but your command line and/or terminal. Once I discovered a few commands, finally able to navigate myself gently around the terminal - what I discovered was, that, using the command line, I was able to start coding faster, easier, and with less errors. It was m a g i c a l. These are the simple things I made notes of that helped me make the transition from 3rd party apps _(codekit && prepos)_ to only my terminal.

###Install Sass

Step 1—

This is the first-timer install section. To get started, we need to first find the terminal. On a mac, type ```cmd+spacebar``` and search for _"terminal"_. Once you're in the terminal, we need to do 1 -of- 2 things. A. If this is your first time, you need to install Sass on your machine. Otherwise, B, you need to update it.

For Newbs, please type the command ```sudo gem install sass```. This will go out and fetch the gem Sass and install it on your machine. Intially, it'll ask for your password; this will just be your cpu's start up credentials.

Those of you who have already installed Sass but need to get up && running on a new/current project, update Sass by typing ```sudo gem update sass```.

Finally, if you would just like to check the current version or simply make sure it's installed, type ```sass -v``` for version.

1. ```sudo gem install sass``` - Intial Installation of Sass 
2. ```sudo gem update sass``` - Update Sass 
3. ```sass -v``` - Check Sass version


###Using Sass

Step 2—

To get the Sass compiler up && running, watching our project, we will need to use the ```--watch``` command so that it can begin looking for changes in our project folder _(directory)_.

First things, first. We need to make sure we're in the correct directory of or project. Here are some helpful commands in order to get us to that point.

1. ```cd desktop/project-name``` - Change directory to desktop > folder
2. ```cd project-name``` - If you're already on desktop, simply
3. ```pwd``` - Shows you where you're at
4. ```ls``` - Shows the files & folders in the current directory
5. ```ctrl-c``` - Stop Sass from watching


Step 3—

Once you know you're in the correct location/file/directory of the project you're going to be working on - it's probably best to keep your CSS & Sass in separate folders. Therefore, we'll want to use the command ```sass --watch sass:css```. This is saying, _"Hey Sass, watch all the files in the 'Sass' folder for any changes and update the stylesheet in the 'CSS' folder."_ A few more tips include;

1. ```sass --watch sass:css``` - Start watching & compiling Sass to CSS 
2. ```sass --watch --style compressed sass:css``` - Compress and minify code by using 
3. ```sass --watch --style compressed file-name.sass:file-name.css``` - Compile a specific file only

Step 4—
Dw will ask you anytime a Sass file has been changed that _"The file has been modified outside of Dw would you like to update/save those changes"_ and you want to be sure to click ```yes``` so that it'll stop asking you.

Lastly, here are a few general command tips to help you level up. Enjoy!

1. ```shift+command+period``` - Shows files again? idrk
2. ```cd ../``` or ```cd -``` - Go back to previous directory
3. ```open file-name.html``` - Open that file in a browser. Cute, huh?
3. ```cd my\ directory\``` - use the ```\``` to deal w/ spaces in directory names...