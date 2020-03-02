---
title: My site
layout: home
header: true
permalink: ../SSF
---

# Summer Studio - Final Submission

## The SLO's
During these six weeks I actively engaged in different tasks that stood up to the different SLO's that I was tasked to carry out

### SLO1 - Engage with stakeholders to identify a problem or scope a defined problem.
During the 6 weeks I endeavored to engage with different stakeholders in order to identify problems in Cyber Security
<br>
In Week 1: 
I engaged with Matthew Brennan a Cyber Security analyst who helped us the learn some of the basics of Cyber security
<br>
In Week2: 
I engaged with two experts in the Cyber Security field: UTS IT Teacher Patrick Kelso and Security Engineering Manger Robert Mitchell who were able to give us advice in different aspects of the Cyber Security field by answering any questions we were able to come up with.
![Patrick and Robert](/assets/pat.png)
Some notes that I took
<br>
In Week 4 : 
I sought advice from my teachers into what box I should attempt to complete for this week. With there suggestions I chose to attempt the literally vulnerable box
<br>
In Week 5:
I engaged with the two representatives from Deloitte: Nathan Jones and Pieter Westein who showed us the different tools that they used to engage in red teaming operations
 ![Notes ](/assets/notes.png)
 I also sought the advice of one of my tutors for some insight into how to design a write up report. He was able to link me to a previous attempt of his from a different box.
 ![Jason ](/assets/jason.png)
<br>
In Week 6:
I engaged with several members of the Google team who participated in the ninja night CTF who were able to provide unique insight into how I should approach CTF challenges in the future.
 ![Cyber Ranger](/assets/cr.png) 
 
### SLO 2 - Apply design and systems thinking to respond to a defined or newly identified problem.  
During the six weeks I strived to apply design techniques into different forms of media as well as use system thinking to understand different forms of computer systems.
<br>
In Week1:
I made use of design and system thinking in order to understand how to deploy my website as a static site. This included me learning how git operated as a version control system and also how I could use Netlify to forward my webpage to a domain.
![Netlify](/assets/Netlify.png)
![Github](/assets/github.png)

<br>
In Week2:
I applied design and system thinking by working on my deliverable; the powerpoint.  In this research I was able to grasp how my reconnaissance tool functioned by scanning different directories of sites while alos applying design thinking by considering how my powerpoint would be designed for the presentation
![Gobuster Presentation](/assets/Gobuster2.png)
![Gobuster Speech](/assets/Gobuster.png)
<br>
In Week3:
This week I applied my design and system thinking skills in a rather similar way as last week. This week I learned how Cross Site Scripting (XSS) functioned and exploited the system in which it ran on.
![XSS Presentation](/assets/XSS1.png) 
![XSS Presentation](/assets/XSS.png) 
<br>
In Week 5:
This week I applied my design and system thinking skills by designing how I would present my write up of Open Admin.These thoughts determined how I would format my assignment by considering such thoughts as font sizes and picture placements.
<br>
In Week 6 
I Applied my design and system thinking skills by designing both write ups of Open Admin and Travexec so that they demonstrated how I achieved root access on both boxes clearly and concisely.
### SLO 3 - Apply technical skills to develop, model and/or evaluate designs. 
This Course over the six weeks have developed and enhanced my technical skills in all fields of Cyber Security by applying it in many different tasks that were assigned to me.
<br>
In Week 1:
In this week I applied my technical skills through the creation, forwarding and version control of my website.
![Jekyll](/assets/Picture1.png)
![The Git bash shell](/assets/git.png)
![Netlify](/assets/Netlify.png)
<br>
In Week 2:
This week I demonstrated technical skills through the completion of picoCTF and OTW Bandit levels
![Pico CTF challenges](/assets/picoCTF.png)  
Some of the challenges I completed
![Python](/assets/python1.png)
The Python Ceaser shifter that I made to solve some of the picoCTF problems

<br>
In Week 3:
I demonstrated technical skills this week through the completion of OTW Natas levels as well as the completion of some of the OWASP Juice Shop challenges. The OWASP challenges made me apply skills in web exploitation as well as social engineering while the Natas focused more solely on web exploitation through methods such as file traversal and http request capturing
![0 Star review](/assets/0star.png) 
![Bjorns account reset](/assets/bjorn.png)  
![Jims account reset](/assets/jim.png) 
<br>
Natas work
Level 0: Level 0 was a page where the password was hidden inside the page. From here I inspect the element due to how it contains useful information to the website. The password is found in there.
Level 1: Level 1 was a page quite similar to the first except that right clicking cannot be done. I countered this by using the f12 keybind and this allowed me to see the password.
![No Right Click](/assets/nlv1.png)
Level 2: Level 2 was a page still similar in format to the first 2. An inspection of the element did not find the password outright however there was an image in the directory of /files.  Since I know that another file coudl exist in that directory I traverse to it and find user.txt file. Accessing it reveals the password
![A file directory?](/assets/nlvl2.png)
| ![The directory](/assets/tlvl2.png) |  | ![User.txt](/assets/nlvl3.png) |

Level 3: Level 3 was a page whose element revealed did not leak information and that not even google would find it. Since google could not find it there must be a robots.txt that denies google access. By accessing this page we find a directory named s3cr3t. Accessing it reveals another user.txt that contains the password.
![Not even google](/assets/robots.png)
![The secrets](/assets/secret.png)
Level 4: Level 4 was a change of pace in previous levels. Upon accessing it, it denies me access to the password and tells me that I need to access it to level 5. Obviously I cant do that as I dont have the password for level 5 however I know since it is scanning where I am coming from it is sending out a HTTP request to my browser. By using burpsuite I am able to capture the package and change the referrer tab in the request to say i am coming from natas 5
![burp.txt](/assets/burp.png)
level 5: Level 5 was similar idea to level 4 such that it also required packet caapturing. However this one carried an actual variable set to 0. I thought it was boolean and as such changed the value to 1. THis then gave me access to the password
![burp with cookie.txt](/assets/burp2.png)
<br>
In Week 4:
This Week I demonstrated technical skills by attempting the different boxes on Vulnbox. This required me to do reconnaissance as well as attempt to find a vulnerability to exploit.
![Nmap on windows ](/assets/netscan.png) 
![File to Print](/assets/ftp.png) 
![Backup Passwords](/assets/password.png)
![Website](/assets/website.png) 
![Website with format](/assets/website2.png) 
<br>
In Week 5:
I demonstrated technical skills through my work of getting the invite code for the Hack the box registration and working through the Deloitte box as well as through the methods of my write up of the Open Admin box. The Deloitte box I was able to use some of my reconnaissance skills to find some directories not previously known
  ![XSRF attack caught ](/assets/xrsf.png)
  ![Beautified Javascript ](/assets/beauty.png)
  ![beautiful stuff ](/assets/bs.png) 
  Me working through the different things that I found interesting in the invite code retrieval. 
 <br>
 Deloitte Box
 ![netdiscover ](/assets/netscan.png)
 ![Nmap port scan ](/assets/portscan.png)
 ![Git directory ](/assets/git.png)
<br>
In Week 6:
I demonstrated my technical skills in my completed write up of both Open Admin and the Travexec boxes.
### SLO 4 - Demonstrate effective collaboration and communication skills. 
During the six weeks, I did my best to go beyond my comfort zone and work as an effective group member amongst peers.
<br> 
In Week2:
I used my collaborative skills to work as an effective group member and carry out the part of the presentation that I was tasked with completing.
![Our Gobuster Group](/assets/Gobuster3.png)
<br>
In Week3:
I made use of my collaboration skills to carry out my part of my presentation  as requested by the team.
![XSS Presentation](/assets/XSS.png)
<br>
In Week5:
This week I demonstrated communication skills by offering help to a person who needed it in order to progress in their weekly delivery.
![Collaboration ](/assets/help1.png)
<br>
In Week6:
I made use of collaboration and communication skills by not being afraid to seek advice from my peers but also in helping out in my group for the showcase by completing the task that was requested of me by my group member.
![Advice](/assets/advice.png)
![Me receiving a request from my group member](/assets/collab.png)
### SLO 5 - Conduct critical self, peer, and group review and performance evaluation.  
Over the 6 week I have had to conduct critical reflections and evaluations into the preformance of not only myself but also my peers and teachers as well. This was conducted weekly in both our stand up meeting as well as our 1 on 1 conversations with our tutors.
<br>
In Week1:
I was able to conduct a review of my actions for the week and record them in my review
<br>
In Week2:
I took on the advice of my tutors and tried to review my actions more reflectively by recording more in depth of what I had done for the week and also recording more artifacts for the submission.  
<br>
In Week 3:
I once again took the advice of my tutors and began to record both why and how I employed my technical skills with use of relative artefacts. I also began to start to redo previous submissions o that they could achieve passing quality.
<br>
In Week 4:
I took further steps in trying to replicate why I preform certain steps in order to demonstrate knowledge of technical skills in my documentation so that I demonstrate a thorough understanding of the tasks of which I am doing.
<br>
In Week5:
I continued to work on getting previous submissions up to standards that were acceptable for the class including demonstrating that I actually show technical skills while attempting the OTW natas puzzles.
 ![Added some natas explanations](/assets/natas2.png) 
In Week6:
I finish continuing to work on the previous submissions and also construct my concluding portfolio entry taking a final look on the class and all that I have gained from it. I have added some further explanations into previous submissions in order to demonstrate that I have made use of technical skills in order to solve problems.
 ![Added some picoCTF explanations](/assets/pico.png) 

### What I Learned
This class has been incredibly informative for me taking me from an absolute outsider of the Cyber Security subject to a pretty knowledgeable novice who wishes to improve his knowledge further.  It has allowed me to develop and further technical skills in the fields of Pentesting such as reconnaissance and exploitation through the research and deployment of different tools and equipment, enhanced by design and system thinking skills through research, documentation and presenting skills. It has also improved my communication and collaboration skills both with peers but also with different stakeholders by teaching me that true progress requires multiple minds to work on different issues effectively. This course has also taught me to look upon my work critically, making me reconsider the quality of my submissions and improving them thusly. This subject has far exceded my expectations set at the start of the 6 weeks teaching me many of the skills and knowledge that is essential to the Cyber Security field while also giving me contacts that I may interact with long after this class has finished to further my understanding of the subject.  Finally this subject has kindled the passion that was developing in me for the subject of IT and I hope that I am able to further this passion with future classes in the field of Cyber Security. 
By Matthew Henry