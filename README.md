# google-homepage

Project: HTML\CSS : First Project Odin

Link: http://www.theodinproject.com/web-development-101/html-css



This is my first time starting a project on GitHub so I'm checking out some features. 
This is the designated ReadMe... I may try to take notes on this lesson here if that's practical. 


Starting a project with git :

1.git init
2.git config user.name "Ace"
3.git config user.email "apacking@gmail.com"
// recently changed to the "staging area" (ie. they're "ready to commit")
4. git add -A
// commits all the "staged" files into your local repository
5. git commit -m "update README"
// pushes your local repository up to your remote one on Github
6. git push origin master


Lesson Objective:
Create a copy of the Google Welcome page using only HTML and CSS (JS and Jquery not allowed).

Current Work:
Alignment on nav bar items is a little off; specifically the last image is too high.

Create footer.


Obstacles / Solutions:
1: Trying to align the nav bar on the right side of the page.
	My image css from the body section was effecting the image in the nav bar. 
S: Create class to specify css for nav bar images

2: Footer won't stay at the bottom of the page.
S: Set Div CSS position: absolute and left, right , bottom : 0

