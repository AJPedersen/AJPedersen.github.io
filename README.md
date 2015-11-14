# AJPedersen.github.io
AlexJP.com portfolio site.

This is my personal portfolio website-a business card on the web. I created this with HTML and CSS as a place to track and show off my journey to web development. As I learn more this site will change and grow. I plan on adding a blog made with Jekyll, incorporating JavaScript as I learn more, and hopefully linking to all the cool apps and projects I create.

INDEX:

-CNAME <br>
	*Redirects ajpedersen.github.io to alexjp.com

-README.md <br>
	*This file. Used to keep track of my development of the site. I will most likely use the notes here to flesh out some blog posts in the future.

-index.html <br>
	*My placeholder html file while I work on getting my site up.

-main.html <br>
	*My main html file for the site. Will rename to index.html when I am done building the site.

-normalize.css <br>
	*The normalize.css file to "provide better cross-browser consistency in the default styling of HTML elements."

-stylesheet.css <br>
	*The css stylesheet for index.html.

-stylesheetmain.css <br>
	*The css stylesheet for main.html.


I used <a href="http://www.curtismlarson.com/blog/2015/04/12/github-pages-google-domains/">this</a> tutorial to redirect my domain to my github page. I really like Google domains since they provide private WHOIS service in the price of the domain, which was an affordable $12!

<a href="http://sixrevisions.com/css/css-tips/css-tip-1-resetting-your-styles-with-css-reset/">This</a> explanation of reset.css really helped me understand why and how to use a reset.css file. In my use case I will use a separate reset.css file called before my stylesheet.css. For some reason Eric Meyer's reset.css did not work for me; it messed up my margins and padding. Most likely this is because I did not take the time to edit it for my use case. I actually ended up using normalize.css, <a href="http://nicolasgallagher.com/about-normalize-css/">check it out.</a>

I got tired of typing: <br>
<em>git add .<br>
[enter]<br>
git commit -m "Initial commit"<br>
[enter]<br>
git push<br>
[enter]<br>
</em>
So I edited my bash_profile file with <em>touch ~/.bash_profile; open ~/.bash_profile</em> to include:

<em>function acpgit() {<br>
    git add .<br>
    git commit -a -m "$1"<br>
    git push<br>
}<br>
</em>

This way all I have to type in my terminal is acpgit to execute my add, commit, and push commands. I also went ahead and added a cdajp command that allows me to type cdajp to cd straight to this repo on my local machine. These two things are very convenient. In this process I learned how to edit my bash_profiles file to customize my terminal and speed up my work, yay! I'm sure I will add to this file in the future.

