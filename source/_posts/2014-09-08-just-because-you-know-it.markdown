---
layout: post
title: "Just because you know it, doesn't make it easy to learn"
date: 2014-09-08 12:32:03 -0400
comments: true
categories: Code
---

####Or what I've learned while teaching an introduction to HTML and CSS class.

I'm on my fifth year now teaching an intro to website development at a local college and am always looking for new ways to teach the material. I initially started out teaching the course online. The class was structured with students reading the assigned book and completing their assignments while I served as a mediator to help answer questions and guide them along the way.

Starting last spring, I'm now teaching the course in the classroom which allows me to demostrate coding, have the students work hands-on and most importantly, get to know the students to determine their strengths and weaknesses. I've currently started my third semester of this course and I encounter new issues every time that really shows how differently people look at coding for the first time.
<!--more-->

I always run into the same issues every semester that fall outside of the material itself. A few students that either show up late or miss class altogether, don't complete assigned reading or assignments and generally are not interested in the subject matter. Not much I can do on the first two parts but I do try my best to get them involved to at least give coding a shot.

The section I'm teaching in is a graphic design program with a mixture of print and interactive students. This course is a requirement for students in the program so it is always a fun challenge to get students majoring in print to show them this other creative industry. I think its great for designers to have some background in code to help understand the limitations and think of ways to approach projects. It has always been rewarding for me when it finally clicks for those students that were not interested in the material to enjoy building web pages and start to gain their confidence.

When I first started teaching this course, I always envisioned that grasping the HTML tags and CSS syntax, especially layouts, would cause the most issues. The real issues that I encounter typically fall into these specific areas.

###Computer Experience
I've been using some form of a computer, whether a Windows or a Mac, over the past 18 years. Yes, I'm old. Most of the functions getting around in the OS and knowing what tools are available has become second nature to me. I have students' experiences range from little knowledge of using a computer to being pretty well apt in using a Mac. So the real test is trying to keep the pace of the class demos that benefits everyone which is pretty difficult.

I've had a few repeat scenarios where students complain of changes they make to their html file never showing in the browser. After stopping my demonstration to take a look, it typically comes down to them not working on or viewing the correct file. I'm not sure if its the pace I'm demonstrating at or having students not paying attention to where they are saving files or maybe a combination of both. I try to take a step back and think if I was the student that I would find this frustrating. Right off the bat, I'm not sure what has gone wrong or where to start on fixing the problem.

###Naming files and file paths
I'm still trying to figure the background on this issue but it seems to always come up throughout the semester with how students name their files. I believe it's due to the fact that you can pretty much name a file whatever you want on your computer. Uppercase, spaces, all caps, no file extension, you name it. It really hasn't mattered up until this point when working with art files, etc.

We start with naming all of homepage files as index.html for assignments as well as in-class demos. After discussing the file naming and actually typing them out in the class for all to view on the projector, I get files named Index.html, My Assignment.html, Class project. The same applies to folder names and asset files. I know this falls on me as I'm not clearly communicating the importance of file naming. On the upside, most of these issues are resolved by the end of the semester as I reinforce the naming protocol with each assignment.

Another issue that arises with filenames and especially linking, deals with the URl paths to images and links to other pages. I have yet to find a way to best visually illustrate how it works and help them determine which way to go either up or down a directory. Currently I open a finder window to show the folders while typing out the links in the document to bring the two together. This is one of those issues where I think once you have the syntax down, everything else falls into place. I'm always trying to come up with some association to the "../" that would represent going up a directory along with "/" going down a directory.

###Text editors
An ideal world would have all of the students using a consistent text editor throughout the semester. We use Macs in our classroom and most recently had Sublime Text installed on all of the computers. Previously we were using TextWrangler which was a step in the right direction over using TextEdit which I believe before had been the default on the classroom computers. It's great to have the students use a true editor for coding that combines color syntax and hints to help them get familiar with the markup.

My only issue I'm trying to resolve now is getting Sublime Text to default to the HTML file type versus plain text when creating a new document. It adds that extra step in class that I'm hoping doesn't add to the frustration for new students. I've had situations where I'm on step five of a demonstration while one or two students aren't seeing any changes as their file type is still set as plain text.

So we have the classroom environment set to be pretty consistent, the next issue is when the students work outside of the classroom at home on their computers. Now we are adding Windows computers to the mix along with different text editors. Sure the students can use the lab but it is a lot more convenient to have them do the assignments on their own schedule and location. They are pretty open on what text editor they can use outside of Word or Dreamweaver.

That is where the problem starts with the different text editors. Each has their own settings and defaults which may have to be changed specifically for them to use it for coding HTML and CSS. TextEdit by default will actually display the page versus the markup, encoding is on the wrong setting, file extensions are non-existent or something besides .html, etc. The list goes on.

###Roadblocks along the way
I can only imagine some of the frustration for students as they get started on programming a web page for the first time. A case in point, I had a student that ran into an issue when coding out their first page outside of class in the required reading for the week. I'll name him John for the sake of the story.

John is referencing the book in the first chapter to build out a page with a heading tag and a couple of paragraphs. Each line is broken down on what it does and he goes through and types out the code line by line in his code editor. John tests the page in the browser and everything works great. Next steps for this same page involve adding some styling to the body. The book starts with adding the style tag to the heading and setting some properties such as background color, margin and font sizing. That is the point where everything breaks down.

John emails me some questions regarding his work on this page but they are vague as to what the issue might be. He is already expressing frustration after spending some time on building this page out but has hit a stopping point.

After a bit of back and forth questions, I finally ask him to send over what he has built so far. The latest problem he brings up is the fact that none of the styling he has added to the page is appearing. I take a look at the page he has constructed and everything looks up to par with the right html markup in place. I look at the styling and then I notice a typo with background-color declaration misspelled. Ah ha! I've found the problem. But then I notice a missing colon there, a missing semicolon there and realize the issues stack up.

I send him my notes to make those fixes which he puts into place. I get a message back saying he still isn't seeing the styling display on the page. Hmmmm. Let me take another look. Then I see it. In the style tag in the heading, there are smart quotes being used versus regular quotes for the attribute to set the type as text/css. The culprit? TextEdit with a default setting of using Smart Quotes selected.  How is someone new to all of this supposed to figure this out? I'm sure there are just too many scenarios to try and cover every situation.

 The book we are currently using for class, Head First HTML, is in my opinion a great intro to the material and helps keep the source materials somewhat fun in its writing style. The main downfall with this book and many other tutorials out there, what happens when things go wrong? Nine times out of ten for me, and I can only assume others, follow that same pattern of going to Google searching for help on what might be causing your code not to work. Based on the same scenario, one can only hope that you even know what to search for to help fix your problem.

 I find myself going back to this great post written by Cecily Carver on [Things I Wish Someone Had Told Me When I Was Learning How to Code](https://medium.com/learning-to-code/things-i-wish-someone-had-told-me-when-i-was-learning-how-to-code-565fc9dcb329) which was inspiration for me to write my thoughts in this post.

 I'm going to keep taking notes and working on ways to try and improve this learning curve for all of my students. I'm curious if anyone else has run into the same issues when learning to code or would like to provide an ideas on what might help solve any of my current problems.
