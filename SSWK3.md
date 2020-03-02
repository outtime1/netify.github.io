---
title: My site
layout: home
header: true
permalink: ../SSW3
---



# Week3 Task Presentation


## What I did:
### OWASP
This week I completed a bunch of challenges on OWASP juice shop requiring quite a lot of technical knowledge and the understanding of systems. 

 
 


## Problems I Faced:
This week I faced a few problems regarding to the class, I had little knowledge based on Burpsuite and as such, I was required to learn how to operate the tool on the go, I also had very little knowledge regarding to the syntax of a few of the penetration attacks such as SQL or XSS, this required me to put in more time understanding how these attacks are used and how they can exploit web vulnerabilities. Another problem faced this week was regarding communication amongst our group, though better than last week, I feel that better communication can still be achieved in order to more efficiently accomplish tasks  
## Reflection on last week
I listened to the advice given to me from my tutors and tried to add more artifacts that help establish that I am adhering to the subject outlines in this class.

## How I have achieved the Subject Outcomes

### SO2
This week I was able to apply my design and system thinking skills through the development and research conducted on my presentation throughout the week. I was also able to apply my system thinking skills through the thought process that went into trying to crack some of the OWASP vulnerabilities.
<br>
 ![XSS Presentation](/assets/XSS1.png) 
 This was the slide of the presentation that I did regarding the impact of Cross Site Scripting(XSS). 

<br>
 ![XSS Presentation](/assets/XSS.png) 
 This is the Microsoft teams group where we designated our roles for the presentation  

### SO3 
  I was able to apply technical skills this week by working on the different puzzles that were presented to me on Over the Wire and OWASP.

| ![0 Star review](/assets/0star.png)  |
| I was able to leave a 0 star review on the juice shop site by considering what was stopping the button from being able to be pressed. Since i know that html buttons can have the attribute disabled applied to them I  saw by filling in the prompts usually that the attribute disabled = true was removed. By reloading the page and removing the attribute prematurely, I found it possible to submit a zero star review.  |

| ![Bjorns account reset](/assets/bjorn.png) |
| I was able to reset Bjorn's password by finding a video in which he answers his security question on his social media (doxing) and resetting his account credentials in the shop. However I am still unable to log in to his account |
| --- |
| ![Bjorns account reset](/assets/admin.png) |
| I was able to access the administrator page by finding reference to it in a java script. From there I was able to delete all 5 stars reviews using the GUI that I have. |
| --- |
| ![Jims account reset](/assets/jim.png) |
| I reset Jim's Password by finding a Star Trek reference to him in one of the reviews. By using a quick google search I was able to find him and then find his brother I then reset his password by answering the reset security question: What is his brothers middle name?. |


 I cracked viewing another users basket by logging in as two accounts, this confuses the site and registers that you are one user when you are currently acting as another.

### Over The Wire Natas 

This week, I was able to complete some Natas levels making it to level 6. 

Level 0: Level 0 was a page where the password was hidden inside the page. From here I inspect the element due to how it contains useful information to the website. The password is found in there.
Level 1: Level 1 was a page quite similar to the first except that right clicking cannot be done. I countered this by using the f12 keybind and this allowed me to see the password.
![No Right Click](/assets/nlv1.png)
Level 2: Level 2 was a page still similar in format to the first 2. An inspection of the element did not find the password outright however there was an image in the directory of /files.  Since I know that another file coudl exist in that directory I traverse to it and find user.txt file. Accessing it reveals the password.
![A file directory?](/assets/nlvl2.png)
| ![The directory](/assets/tlvl2.png) | ![User.txt](/assets/nlvl3.png) |

Level 3: Level 3 was a page whose element revealed did not leak information and that not even google would find it. Since google could not find it there must be a robots.txt that denies google access. By accessing this page we find a directory named s3cr3t. Accessing it reveals another user.txt that contains the password.
![Not even google](/assets/robots.png)
![The secrets](/assets/secret.png)
Level 4: Level 4 was a change of pace in previous levels. Upon accessing it, it denies me access to the password and tells me that I need to access it to level 5. Obviously I cant do that as I dont have the password for level 5 however I know since it is scanning where I am coming from it is sending out a HTTP request to my browser. By using burpsuite I am able to capture the package and change the referrer tab in the request to say i am coming from natas 5.
![burp.txt](/assets/burp.png)
level 5: Level 5 was similar idea to level 4 such that it also required packet caapturing. However this one carried an actual variable set to 0. I thought it was boolean and as such changed the value to 1. THis then gave me access to the password.
![burp with cookie.txt](/assets/burp2.png)
### SO4 
This week I demonstrated collaboration and communication skills through the group work that we were assigned, it was through the creation of our own Microsoft Teams group that we ensured efficient communication amongst ourselves. It was through our designation of how the task that would be completed that we demonstrated our collaboration skills creating a system for the presentation that was fair as well as balanced amongst students. 

### SO5
This week I conducted critical review over our group and myself by adding sections to this reflection demonstrating the pitfalls and struggles we faced during this week. It is my belief that this will allow me to review my weekly actions more critically and ensure that I learn from my past mistakes. I also received criticism from tutors during our 1 on 1's allowing me to better preform for the future weeks.

