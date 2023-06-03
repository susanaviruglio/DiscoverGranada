# Discover Granada

## User Centric Frontend Development Milestone Project by Susana Viruglio

Discover Granada is a fictional tourist website that offers information about Granada: places to visit, book activities, places to eat, what to do and information. The idea of the decoration project came to me while I was actually visiting Granada on my holidays, I thought it could be a great idea to bring my personal experience to life. As I was visiting this city I was collecting ideas for the project from every place I was visiting.
My principal goal is interested in attracting and retaining tourists so they can book activities.
Some potencial features to include are:

1. Photos ( views of places to go, places to visit,...).

2. Provide information on places to go with the proper addresses, opening hours, booking activities.

3. A map of Granada with information about how to get there, transport.

## UX AIMS

* To attract users between 25 and 45 years old who want to travel and get to know Granada, Spain.
* To convince users to stay longer by providing images and an actractive design.
* To provide users with an easy and quick interaction website with all the information.
* To create a fully responsive design for several devices as desktop, tablets and phones, etc.

## USER STORIES

1. What can I do in Granada?
2. How can I book tickets to go to La Alhambra?
3. How can I see the city if I don´t have enought time?
4. How do I get to the city centre? which vehicle i can use?
5. Where can I go to eat? Do you recommend nice views?
6. Do you recommend any show?

## DESIGN EVOLUTION

### Home

[2023-05-27 (1)](https://github.com/susanaviruglio/Milestone-project-1/assets/127688431/f99842a6-7dc5-496d-aa94-5acefee3101d)
My first wireframe for desktop.

#### Header

In my first page you will find the home page (header) where I described the purpose of this website with an introductory paragraph. I have added the principal header with a background picture. Beneath the principal image, I created the navigation menu with links of the three different web pages: what to do (information of places to go and what to eat) contact or about us (information about how to get there and a form if the user has any enquiry).

#### Section 1

Underneath I will have my first section(h2) Welcome to Granada! with a paragraph description of the website and introduction attracting the user to know more about it.

#### Section 2

In my section area I have provided the user with some interesting activities to book in Granada. I have used Bootstrap to create the layout and some pictures.

#### Footer

Finally I have created the footer where some link in social media and a copyright sign.


## CODE ISSUES

### Bugs discover
* Navigation menu: I wanted my menu bar translucent with a bit of color, but when I was trying to do it with the Hex Value I could not change the opacity. So after trying and doing some researchs I tried to use RGB.
* Section 1 general issue: once I created my navigation menu and the background for my header I wanted to create my first section ,but it did not appear beneath it. I checked my code and I found out that I had had set the background to position absolute, so I deleted and everything was working fine.
* Section 1 image issue: I had my own picture ,but it seemed to be broken everytime I doing the code. I found my mistake in my html area because I forgot the slash in front of the route link.
* 

### Command issues 

#### First Issue
I have had two issues with my commands several times when I was trying to pull and push my work.
I was stuck with the commands I asked for help Code Institute Tutors Assistants. I followed these steps:
* git push origin HEAD:main
* git rebase --abort

My tutor informed that sometimes there are conflicts between your github repository and your local one. This can happen because I have made a change directly on github.  Here is how to do a git pull and fix and merge conflicts:
1.  git config pull.rebase false # merge
2.  git pull
3.  git status to see which files have a conflict that needs fixing
4.  then check those files and look for places marked with #### or <<<<. These are the areas that differ between your local files and the Github ones. Correct these areas until the code is how you need it to be. Save all the files you changed.
5. git add .  (don't forget the . that will add all the files changed since the last time they were committed.
6. git commit -m "fixed merge conflict"  You will know the merge is complete because (main | MERGING)  will return to just (main)  in the terminal
7. Finally git push origin main so all your files are synced up.

Then it worked and I could merge to my main branch. 
#### Second Issue
My second issue was very similar to my previous one ,but this time I could fix it by myself using the step above. I have realise that if I edite any file from my Github it will diverge the branch from the main.

## CREDITS

### CODE

All the code that I have used to create this website was taken from Code Institute learning platform a part from the next following sources:
* [BOOTSTRAP](https://getbootstrap.com/)

### IMAGES

### FONTS
