

NOT DONE YET COME BACK LATER 


### STUCK? 

**Purpose** This document is a collection of tips intended to help beginner web development or programmers to "learn how to [get unstuck] fish" not just be told an answer to questions such as "my code is broke what now or how do I ...?" If that is ever you keep reading and it will be you LOL. 

**Intro** First of all, I would hope that you always feel free to ask anyone and everyone for help by doing so you can and likely will learn cool new stuff regardless of what tips are in this docs b/c its not comprehensive its just a great start. But what if you could summarize all the answers ever given and note the principles or common answers? I would say in large part yes. And if you Google how to get unstuck  or advice to new porgrammers this is the type of info that is useful to you to get to pro level fast which is why you chose a "bootcamp." What if you could have a mentor sitting next to you at all times to ask things when you get stuck (hence the name of this document STUCK.md)? This is why I wrote this article. So before asking a TA or instructor for help just run through some or all of these tips -  BUT if it become a habit of asking and you are NOT doing all this then at least master these skils first then ask all you want after that cause asking is awesome. Its just likely one of these skills/tips will be used in the answer to "my code is broke, what now or how do I ...?".

**WARNING & WHY another DOCS?** : This document is to be read over and over again until all these skills are mastersted kinda like the 7 habits of highly successful people in a way. **check this para graog and so it does not get lost If you think you don't need to be reminded of this stuff you're probably wrong. It may seem boring and I have read it all but these are Trust me this has to be said by the numerous students asking the same questions getting stuck in the same spots and for the same reasons. And YES I was one of those students.  BUt hat being said there is always a chance you know all this perfectly. I have seen it before or CODING SKILLS or HABITS - you will be a very quick learner and read once and get it down if that is you GREAT JOB.Essentailly this is just a safe palce to keep all the great adivece for new programmers and please read this once everyday for first 2 weeks or more. At least until node or Javascript is done WHEN all this is HABIT - we all know habits are not formed overnight or one time. 


## It Starts with the Right Attitude - just a reminder
In this section I purposefully am repeating some of the pre course work material ideas and concpets due to our nature to forget fast and to be honest I see too many students just not doing this stuff especially since when they ask for help I repeat this stuff. 

**KEY attitude 1**
- Learning takes humilty.

Naturally if you are stuck you will be getting feedback. Understand and accept that you will make mistakes. The point is to find them early, before they make it into production. Fortunately, except for the few of us developing rocket guidance software at a place like DragonX or NASA, mistakes are rarely fatal in our industry, so we can, and should, learn, laugh, and move on. You are not your code. Also remember to treat others asyou would be treated. Critique code instead of people-be kind to the coder, not to the code. It was hard for me at first to take critical feedback - I felt defensive - don't do that. It's just code it's not you. A humble learner is the readiest learner.

**KEY attitude 2**
- Learning to code is very hard thus learning to code/program [web dev] takes patience and determination.

You can never learn everything at once, NEO in the Matrix could do stuff like that BUT we have not left the MATRIX ... Just kidding.
"Put in the Hard Hours, at Least 20 Hours, outside of class. According to author Malcolm Gladwell, successful people put in a minimum of 10,000 hours of deliberate effort to master their craft. As newcomers to the field of web development, be ready to put in your share of hours. While the bare minimum to survive this program is 10 hours of outside class time, we've consistently found that those most successful put in closer to 20 hours of outside effort per week. At times, this number might even need to go upwards of 30 or 40 hours per week during more challenging topics. Simply said, there is no substitute for long, hard hours." (see pre work)


### SKILLS/HABITS for getting UNSTUCK!
1. Debugging
2. Google-FU aka Googling or Google it!
3. Be a Problem Solver : "Thinking Like a Programmer" & Pseudocode
4. Getting Outside Help
5. Master Your Workflow Tools Better & General Tips
6. Learn [how to code] Duh! aka Learn How to Learn

**Skill 1: Debugging** 
Warning: Debugging back end and front end is differnt at times and exp can be a little different for each particualr lanaguage this will focus on Node and Jeruy Javascript type of stuff. 

At times, it might even feel like fixing an issue is taking 3–4 times as long as conceiving the original solution.Know in advance that this is completely normal.
For novices and experts alike, fixing code is often the most time-consuming task of all. Instead of seeing these spent hours as a distraction, learn to see them as a critical part of the learning process. Each bug you pursue is a lengthy lesson that adds to your arsenal of understanding. Also it is an emloyable skill I have seen many times on job postings. 

- "Precursor to a BUG" Yeah I said it : Writing Cleaner More Efficient Maintainable Code  It has been said this is the key to sqauishing bugs in our code jsut dont' write bugs in the first place. Much has been said about this as a precursor to debugging so that in the future you will have less bugs. It should be your goal to CARE about your code. Furthermore, many a job posting has the reuiqured skill of Write Cleaner Code and avoid bugs. It was said in a recent retrospective of a group of university bootcamp students that they wished they wished they had focused more on things like code style/conventions which would have led to less confusion which in this case is from a group working on the same project. To fully support this we read in "The Art of Readable Code” by Boswell&Foucher,  "The fundamental theorem of readability : code should be written to minimize the time it would take for someone else to understand it !" I paraphrase firther advice from the book: Things you can do to imporve your code: picking good names,(semantic meaningful names for varibles, functions etc) writing good comments, formatting your code neatly (clean use of whitespace). NOTE: Linting code is a topic for later discussion once you have good habits for wriitn clean code. ESLint/Prettier/Beautify tools for JS can check and fix syntax errors but if you don't learn on your own first it will alwasy be a crutch and you may get caught in a pickle someday do use linters like ES lint later after like 4 months or so. Preventing BUGS is also related to testing code but will not be covered in this DOCS. 

Handy tools 
JS hint http://jshint.com/
JSON pretty print 
CS lint
HTML validator 

Error reading - Undersatidng how Javascript is run this cannot be fully covered here so all can say is the computer (nodejs/bash terminal, or chrome V8 engine - the code runner/executor) is going to complie the code. The first goals is to find the point in the code at which the Error was instantiated. Node Bash console may tell you or Chrome/Moxialla tools in the console. 


Check for typos its a common mistake for beignners jsut make sure to spell check each and every word and espeicialy quotes multiple times beofre giving up esp if you think you did everything right 

ReferenceError: Sytnax error fatal erros read debug code error 
run code after each function to maek sure that peice works - hard to pinpint if you wrote 10 fucnitons and sof orth 

What line the code stopped on. Code reader computer reads the code from top to bottom. Code will not even run if there is what is known as a fatal error meaning there is a syntax error . So the code comiles first then runs. Lanuages are differnt but inhjavascript this is hwo it works.
Click on the error in the yellow or red big error message in Chrome and it wil jump you right to the error in the code in at least VS Code and I think Sublime . I t can also show a list of funcitons that were fired that were all tied together and where it finally broke. 
Stack Trace 
try {
    Block of code to try
}
catch(err) {
    Block of code to handle errors
}
https://www.w3schools.com/js/js_errors.asp
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error
NOde https://nodejs.org/api/errors.html
Rollbar is a much used super cool and one of many many tools that try to catch bugs in production code and they have comiled a list of common errors . I can say with certainty the very first answer brought a big smile b/c YUP that is an error I have had hundreds of times 1. Uncaught TypeError: Cannot read property read more here. 1, 6,7, and 8 are very applicable to javascript fullstack devs and guaraenteed you will see them in the future unless youa re that rocket science guy or use super powerful linting tools. https://rollbar.com/blog/top-10-javascript-errors/ - these won't make sense to you know _ so I am going to hope you come back and back to this till its a mastered skill. Error reading

My most common errors fro boot campers and beginners 
Debugging Checklist - just do all these steps several times to be sure before giving up and then never give up 
This mainly pertains to JavaScript or other code - HTML and CSS is a little different
1. Check for spelling typos everything HAS to be exact - even file names etc. most common one for beginners I would say inlcidig me.  many frustatring hours spent till you fianlly learn spell everythig exact already. Most the time someone else has to look at it to be honest casue you cant see your won spelling errors. then someone else takes one look and says hey that is spelled wrong  cnoutless times this has happened . 
2. Check for undefined variables, log all closely related variables 
3. Check to see if loops are correctly used logically i.e. (let i = 0 ; i< arr.length; i++) operator is in the right direction. are you starting at a logical starting point, is the middle piece condition really a number many times you will be looping over an object or soemthing that is not a number. hence no workey.
4. check conditionals to see if they are true or false or what they are and/or log immedialtey inside the loop or codintional and if the log logs to the console lat least you know the loop or coidiotnal is true and loop works at least once.
if you don't know what line the code is broke on you have to use the VS Code/NOde/JS debugger tools or Chrome dev tools under SOURCES for break points OR you can jsut console log my faviroet ( hello 1 ) (hello 2 ) or more descriptive phrase like (insdie for loop:)
5. Reference Working Code even pull up side by side of a working example 
6. Take a quick break come back with fresh eyes or even better get some other eyes on it especially iwth typos.
The reason that is needinfg to be said is that the very first hrdle to jump over is that code must be essentially perfect to work or run so typos will kill ya. 
7. Check file paths to linked css and JS files KEY trust me and exact spelling of said paths 
8. check to make sure the file is even linked if nothing is happening at all. JS particuarly again countless times student have no diea why the code is not working - its not linked up - this is so key it was acutally an interview question two times to why is this code not working 

9. For HXR requests the network tabs in Chromse tools is very useful . Also console logging any repsonses immedaley is key to know how deply nested your data is. before using it. Objects in general

If none of this helps YUP read elsewhere. Here are articles you may have read but may need to review AND/OR Google and read more just like them.
https://remysharp.com/2015/10/14/the-art-of-debugging
https://news.ycombinator.com/item?id=11729806
https://developers.google.com/web/tools/chrome-devtools/debug/?hl=en

With HTML 
use the Chrome debugger tools after validating it . check closign tags like in React IMG and BR HR tags all have to be closed. For our purposes VS code will catch almsot all HTML errors and Chrome inpector tools are awesome hittign f12 to view source code to see HTML in action. 
elements and selector tool click into the DOM tree and click drop downs to dig deeper into the page . take a fre youtube Chrome tools tutorials which could be my answer to anything . If not answered her google more. Hoenlsty jsut go to a cool site and lcik around yes clikc eveeryting and everywhere to see what happens hover over stuff click it hover it and back and forth. its veyr inturtiive for most.  
CSS> jsut play with the Chrome tools - up and down arrows on keyboard to play with ppxiels and percents . you can delete elements add stuff in change stuff. jsut get it right then copy paste sytyles into your code editor and refresh the page. 
layout issues float issues. only answer study good sites and see how they do it and take another tutorial then Practice practice practice is the best answer for that. X path advacned stuff. 
CONSOLE (alerts or whatever works too)
. 
What line of code did it stop on.? console log and variables in the viciinty - check for loops and if statemetns 
console. back end front end dev tools in Chormoe or firefox whatever and backend in the node or bash terminal 


 after you have exahsuted the checklist you are ready to Google it - turst me that list helps Google aint going to sovle you typos BUT it might tell you someone else had a typo and then fixed their typos to fix said error. so either way it sgets done. So onto Google. Continued below... 

**Skill 2: Google-FU** 
Programming is also one of the most frustrating things you will ever do.working through that frustrating feeling.there is almost certainly a solution out there. aftr hours of digging I have found help for very tough complex problems 
3.You will hear ofhten form TAs and Teachers just Gogle it but this doc is for expounding on that a bit.
 google can be intimidating.

 Now copy and paste the error message and google it looking for stack overlflow type articles - then share or bookmark it to never have to google it again and save others the same frustation
be sure to stripe out your local info and jsut google the generic error. with liek our file name etc. cause no one on Google has the eact file naem or at least less people.
Your answer could be in a video it could be in a git hub issues post, it coudl be on reddit. 80% for me are on Stack overflow and 15 percent in the git hhub isseus threads. this is more comon with pacakges cause that is where people complain about the package qnd the aurthores repsoind. and 7% just out there. 8% in cool tutorials in medium or similar ariticles.

how to scan stack overflow fast look for how many votes ALWASY read the comments below I have solved many problems with those EVEN if they have lots of upvotes 
green check mark and title of the post 

If following someones read me turotial try to clone the repo and get it working all by itseld exactly as intended by the author but on your machine then once that is done you can try to move pieces of it or all of it into your project. 

CAUTION and TIPS from the HOT SHOT PROs - Stephen Grider tips 25000 students (good for MERN stack so pleasec chehc all his courses out wwell worth it in my opion and I dont get paid to say that).
Never write a line of code you never FULLY understand - at first this is obvsioly too much to ask but as time goes on make sure you know and can explin out loud every single detail of every characer or line of cod.e I have asked many studtnes what is taht or what does this mean exaclty and they say they know but can't explainit.  CEO code smith says world class enginners aster the skil of technical communication and you will be asked by employers to exmpalin code so get to it.Try pair programming for a bit with someone so you can see how others think and you wil grow a lot.  
Don't ever take any code snippets you find online if you don't understand how they work.
Remember once As a result, any problem you've already solved will get a lot easier to solve next time.

You have already read this article in the prework but here it is again jsut so you can re read or Google another one like it to learn even more. 
[Googling better](http://www.informit.com/articles/article.aspx?p=1315437)
google fu also google more articles like this one how to google fu or how to google for developers or many others 

Hint 1 - first and foremost Google the entire "thought" or "question" you have exaclty as you thoguht it - and add words like examples of, how to, why ? and then the language like javascript on the end of it all - You can click over the right side in Googel for last month or years resutls to weed out old results. I fyou are a google hater I would stop it now. There is evidence it has more relevant results for coders but that is highly debabed so do what you want But when it comes to spellling things wrong Google is WAY better like WAY better at guessing what you meant so jsut I suggest using it.

How to Read Docs is a real job skill - learning new tech wil  likely forver be a part of your job as a developer. Readthe docs once then code somemore then come back to the docs I rpomse they make more sense over time. 
HOW TO INSTALL
quick basic examples of how to use the BASICS. most complicated stuff is not in the docs. so getting it to wroki with your code FOLLOW exactly what is said and if it does not work double check then google your dev enviroment issues thne mayeb try to change it up a bit if neede.d - Being a pro developer is KNOWING the docs for a particualr lary or framewwrok. 

go to the docs - try to get the code for the package or what not working independent of any other code IF you can " if that makes sense. then once wrorking bring into your own code. sometimes the docs are not good enough for you use case. Then ther are sites like JSBIN, COde Sandbox, REPLIT, where snippets of code are saved in a working order fashion to see in action.  Codepen NOW the risk of using this is you become the copy and paste guy and that will not get you a job 98 % of the time. SO do what you can to be the problem 

Toy Probelsm techinal Challenges
Look up all the possible array or string methods on W3 schools or MDn and find out if any of them can help do something like sort, or whatever.  break things down into tiny functions taht do one thing and do it well. 
immedealty handle eddge cases - empty array zero negative numbers werid stuff 
Once solved a problem look at or google all the other ansers to the problem this wil teah you much. 

write your program on paper. In a real world technical interview we cll it ww=whtieboaruding but paper or whitebaord writing the code helps take you out of the help from a code ditor or syntax errors etc aand jsut focus on the solivng the problme. 


**Skill 3:Be a Problem Solver: "Thinking Like a Programmer" & Pseudocode** 

TIP #2 - Rubber Duck It

Walk through your code out loud to an inanimate object (like a rubber duck!) and pose your question. As you’re asking the question, the answer might come to you. so many times I have jsut asked my neior or co worker devs a question and just asking it the anwer came to me but I had ot askit out loud (or at least in a Slack message)

Introduction to Programming Logic
https://www.youtube.com/watch?v=GNyvRP6HzhA&feature=youtu.be

Pseudo Coding - A real story - It happens all the time
Breaking things down into small steps: Story studnet coomes after projects were planned and started and says I am supposed to maek this button click and do this and that and all this and have no idea where to start. 
I then showed the student how she knew exactly how to do each and every thing she was assigned but was not breaaking it down to see that. At frist this will seem annoying but it wil help you break down tough prblems into magangelbe bite size pieces. Just ask yourself what is the exct thing I am tyring to accomplish right now and write it down in psuedo code - now GOogle that exact phrase in a general way - CEO code smith  reaserch reaserch research and no coidng then you have the copy and paste from stack overflow all your answers. You want to be in the middle in the "independant problem sovler" zone. 

After your second language, you'll get much faster at picking up new languages. 
accoring to the MIT course algoratishm that class shaves off about 8 years of experince. trade offs efficiency etc. algorithms course from a pro I repsct says jsut having had that problem is the almost only way to solve it hardly anyone very very rarley someon come up with some asnwer to a really tough algorithm like Ruecursvie finnaccci but those having studdied it before hand will be abel to pass the interview. thtat is why books like cracking the coding inertview are popular. 
v

**Skill 4 : Getting Outside Help**
Devs want to help each other - its liekley due to the fact that tech helps all improve so it jsut feels really good or something don't quote me on that. 
SLACK Facebook groups Slack cahnnels not our course 
If you have any questions about this project or the material we have covered, please post them in the community channels in slack so that your fellow developers can help you!
Medium, Stack overflow, Scotch.io Youtube, 
Some public groups include CodeNewbie, Code Buddies, and Career Change Coders. TIP #4 - FreeCodeCamp Message Boards

How to ask a Slack question or online 
Be specific. paste code snippets using ``` code here ``` basically it takes practice. how can you ask in a way that someone else not looking at your entire code base be able to help.  Its like Gooogling but with a code snippet. It may be bad form but I ask the same question is mulitipl palces in hopes htat at least one will asnwer so copy and paste into facebook gorup - salck channnels etc. mayeb 1-4 spots or soemthing .  then delete the 3 that don;t get ansered and ALWASY give great thanks to somone who gave you FREE help. I have helped some where I was stcuck and did not know the answer told him to slack it out in a speciifc channel for that tech and he got the exact spo ton tnaswer in less than minutes.  if the question is asked right more will be happy to answer. So if you get little help its very likyley jsut the way you are asking 

Finally you have OFfice hours and optional TUtor (ask COrrine and instucitrs about this ) If you are willing to put in the time it will come to you. You have a support network. Never take the easy way out at least come to office horus and get a C level HW withtheri help is better than incomplete since there is no GPA based final grade. 

Office horus at any point if you would like to learn outside topics not covered int he course request that it be taught in office horus mini lecture format bby TA or insrcutior IT YOUR TIME> - use it Redux, Flexbox, CSS GRID, Selenium,React native,  OR want to have a group review of the class content we can and would lvoe to do that ,


Where is the origin of said running code. function etc. Find out th last function that worked what variables are being used and then you can find what stopped the code. 
vraible is undefined or of the wrong type - type of console.log
console.log(teh exact code inside a conditional )
Clean maintainable code - Coming from a non tehinical backgournd where I thought everything should be automated and why are we using terminal not GUi etc for me espaieclly wriring well spaced code was so annoying and I was by habit asloppy writer. 2 spaces or 4 naming conventions for variables and fucnitons. feed back from other cohrots is hat they wish they knew this sutff before Just start good habits early and be very CLEan in all your code I pomsiei it wil pay off. " write code for OTHERS to come then read it"
DRY - if you ever fin yourself repeating code even twice you may need to refactor and genralize and do something better 
Trade offs CS algorithsm class - more efficient mosre cost etc. 



**5. Master Your Workflow Tools Better & General Tips**
Workflow and Tools VS Code GIT/Terminal - master your tools the perverbial tricks of the trade - swing the hammer acertian way even work smarter not harder. 
 Time Saving Frustations saving skills
Master your tools
hot keys like up arrow and VS code tricks can save lots of time and frustration. like draggin the file down to terminal to run it and knowing how to save all files with save key and on and on - usig things like Replit to run JS and Chrome dev tools to fix UI issues CSS and HTML problems of any sort. using the debugger tools in VS code and Chrome. 




Save the best for last. Commit and push often - I repeat commit and push often - YOU WIll face a day when that will save you so much headache  Back up back upback up. 


**SKILL 6  Learn [how to code] Duh! aka Learn How to Learn**


1. Learning aka Master New Content Fast learning how to learn - its on countless job postings as real skill. so do it. 
As a benchmark, consider spending 70–80% of your outside class time writing and reviewing code. Only the remaining 20% is for other passive activities.code smith  build stuff build stuff anything jsut build littl sandbox stuff watchign tutotirals is like listending to how to spseak Spanish cds all day and never saying a work in spanish or never going to a spanich reastautatn and practive the prhase learn by doing 
Get it working then refactor
Learning Mastery and Pro Tips:
Always be coding! Language Center whetherit be progmaming lanageu or human spoken langauge is only learned by speaking and in this case coding. 


HW and Sandbox
HW should build on class actiivtes. So make a sandbox and try to rebuild every single thing done in class 
Watch the Videos in the VideoGuide.md for each week and code along. 
write an article ust like this one and the many you find and read and it helps you master the contetn even makea Youtube video you coudl even put on your portoflio "your tutoriasl" I once spent 3 hours a a problems then foudn a 5 minture fix so I amde a video and got 78 50 views. \Emplyers like that you contribute to open source and also in my opion to the coidng comunity in general 


Make sure to PRoof read teh other README for lots of erros and maybe cut it all out and check the prework for all that debugging advice I found soemhwer  . check my fulls tak satery github repo and then ship this to medium and the repo

Mastering all technologies taught in the course. You'll learn so much in this bootcamp, it'll make your head spin. The skill you're really trying to pick up: learning how to teach yourself new technologies using online resources.we have countelss recources for you so jsut ask if you are not finding what you want o n Google 

Use project maangement tool like Trello ! Orgazition is said to have cause less repeat work and planning is well everything. break stuff down all that is applicapbe here .



Learning How to Learn - One of the most important skills you will learn in this program is how to independently learn. This course grounds you in a methodology.
Learn from others:
https://www.coursera.org/learn/learning-how-to-learn
Livecoding.tv - Watch (and chat with) developers live as they code projects. Great for seeing the thought process of other developers. It's also fun to watch them struggle with bugs.
TwitchTV - Programming - Similar concept as Livecoding.tv.
YouTube:

LevelUpTuts - Great (free) resources for taking your web development skills to the next level. Both novices and advanced developers will find plenty to learn from here.
LearnCode.academy - Another great resource, particularly for advanced topics on JavaScript, jQuery and Angular.js.
open source, vounteer work family friends on faebook ask around to offer free work as way to build protfolio. or accept money too 
sandbox have fun make cool stuff that interestes you . i am a single guy and made a cool dating app and that is how I learned React. 

take a tutoiral but then code 


TIP #6 - Revisit What You’ve Already Learned its really hard to learn all the first time thorugh go back and see if you missed soething in the lesson materials. 

 


#### About the Author
I have read and taken tons of online tutorials, completed lengthy UDEMY courses, workshops from other cool learning sites like Front End Masters. I feel like I can safely say I have been to 3 Fullstack Bootcamps. Once online with proclaimed "Complete Online bootcamp" courses taught even by  real ex boot camp instructors etc. I paid for and gradatued my own 3 month immersive bootcamp @DevMountain in which I paid the price of coding 13 hour days, graduated successfully and landed a fullstack dev job shortly thereafter at a wage I was told was at least the industry average in my area for someone out of bootcamp so I called it a success. I also have been a TA for the entire length at a 6 month university full stack developer bootcamp that was totally awesome. I feel like I am not a master yet but getting close and hope to share what I have learned and really what I wish I had known day one. One thing I do know for sure is how you feel right now and what to do about it. You got this! You don't have to love programming yet but if you love software and/or technology that is a great place to start this journey or else why do it?
