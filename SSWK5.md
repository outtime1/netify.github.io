---
title: My site
layout: home
header: true
permalink: ../SSW5
---
# Week5 Hack the Box Write Up


## What I did:
### Hack The Box
This week I was able to access the user on a Hack the Box though a variety of different methods that led me to gaining remote access and then elevating myself to the role of a user. Root access however still aludes me. I also attempted to attack the box that Deloitte had prepared for us.

 
 


## Problems I Faced:
This week I struggled with the boxes that we were assigned to hack this week. I did my best in using the methods that I had previously known and also tried researching new methods 
## Reflection on last week
This week I have done my best to explain my actions as I show how I have demonstrated the subject outlines for the week. I have continued attempting to resolve the criticism of a lack of relevant artifacts by making sure that there  are plenty of relevant artifacts for the week.

## How I have achieved the Subject Outcomes

### SO1
This week I demonstrated communication with stakeholders by engaging with Nathan Jones and Pieter Westein two members from the Deloitte security group. It was through there lecture that I gained knowledge into some of the attack vectors used for red teaming. This is crucial for us to learn as it allows us to better understand and prepare for security threats and intruders.
 ![Notes ](/assets/notes.png)
 The rather crude but quick notes taken in class to keep up with the speed of the presentation.
I sought advice from my tutor Jason how I should format such a document and he was able to provide me with a previous write up that he had done for a box.
  ![Jason ](/assets/jason.png)
### SO2 
This week I was able to work on my design skills by considering how I would approach setting up my write up deliverable for this week. This week I used Microsoft Word due to its ease of positioning pictures around text as well as being a simple tool.  a template on which I could base my work. This helped me understand the formatting of a write up better.

### SO3 

This week I demonstrated my technical skills in my attempts to Hack the Box both with the log in challenges and the box that I assigned myself, these skills are demonstrated in the write up that I have created. The box that Deloitte had given us allowed me to revise some skills used previously.
#### The Hack The Box Invite Challenge
This week I was able to gain access to the hack the box registration page, it took a lot of new skill learning including how to send post methods, how to beautify javascript and how to decipher codes.

When I had reached the invite code page I had seen many different kinds of keys, I had got in slight trouble as the site picked up on me trying to both XSS attack as well as try and Cross Ste Request Forge(CSRF) attack the site and attempted to block me. This was all as I had wanted to call. 
 ![XSRF attack caught ](/assets/xrsf.png)
 
 However I soon got on the right track when I had beautified a Javascript which was capable of creating a invite code as its function name was literally makeInviteCode() .
 ![Beautified Javascript ](/assets/beauty.png)
 
 It just became a matter of submitting a post request so that I was able to call the function.  Something I had never heard of doing before. It took time but I stumbled upon a site in which I could submit post requests.
  ![beautiful stuff ](/assets/bs.png)
 By doing this I got a string of characters,  an encrypted string I thought probably base 64, after decoding I get told to submit another post request to api/generate. Afterwards it gives me another encrypted set of characters, finally decoding it in base 64 gives you the invite code.
#### The Deloitte Box
When attempting the box I used Netdiscover as it allows me to find the boxes IP so that I may begin the information gathering stage of hacking the box.
 ![netdiscover ](/assets/netscan.png)
Then I used nmap so that I could find what ports were available and thus where it could be potentially vulnerable.
 ![Nmap port scan ](/assets/portscan.png)
I saw that the ports 22 and 4567 were open, I knew that 4567 was a webserver that also had a git repository, this became useful as I thought that I could potentially download the repository so that I could see for hidden files that maybe could clue me into how I could get access into the  however no matter what tools i could use such the git extractor or wget, I was unable to reveal any new information.
 ![Git directory ](/assets/git.png)


### SO4 
This week I collaborated with the class in order to help attack both the boxes that were attempted. This collaboration sped up the rate at which we were able to find the different parts required to further progress through the boxes.
 ![Collaboration ](/assets/help1.png)
### SO5
This week had challenged me to revise former parts of my portfolio in order for them to reach the standard that was required for this class. As such I had edited some parts of my previous portfolios in order to answer in better depth why I am taking such steps. This can be seen with my rewritten part in wk 3 where I revised how I explained my 0 star review documentation.  I have also restarted from week one and began to more throughly explain my actions when attempting to address the Student Outlines for the week.
This week I was rather happy with the effort that I put in with my documentation. I believe that I have taken major strides since the start of the class in order to reach a passing standard. I can only hope that I can maintain this standard across the whole of my documentation now.
