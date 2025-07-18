---
title: "Praneet's PCB Business Card"
author: "Praneet"
description: "My custom PCB business card"
created_at: "2025-07-05"
---
<em>Total Time Spent: 12.50h</em>

# July 5th P1: Designed v1.0 and v2.0 of project!

To start off, I researched different projects that would fit my abilities and the hack club project guidelines. After finalizing the PCB Business Card as my project, I researched different tutorials that could help me understand the basic process of designing a PCB that could be shipped. I ended up finding the perfect resource right here at hack club: https://jams.hackclub.com/jam/hacker-card.

I first watched the tutorial without beginning the design on my product. This was so that I did not just copy the tutorial and instead learned the techniques being used within it (very important sicne I am not too familiar with PCBs). After getting an understanding of the basics of PCB design, I noted down the components used in the resource and made sure they were cost-efficient and capable for my needs.

At this point, I began designing my PCB business card. To begin, I created the necessary schematic with the necessary parts using EasyEDA. Next, I converted this schematic into a PCB design and traced the necessary connections there. This took a solid chunk of time since I had to get familiar with each of these things while working on them. 

In my initial prototype (v1.0), I kept only the very backbone of the ideal end PCB, with one LED (and the neccessary associated components) and minimal silkscreen text. Once I had implemented these things, I moved on to adding more to the PCB. I first added text essential in any business card (name, skills, etc.) and added the two main features of versions 1.0 and 2.0 of my PCB Business Card: an NFC antenna and svg-based QR Codes linking to my socials. I also experimented with my visual design at this stage, testing the look of the PCB Business Card with different variations of layers (some shiny, some plain silkscreen, etc.), text sizes, fonts, and more.

After settling on my base version 1.0 visual and technical design, I moved on to preparing version 2.0 of my PCB Business Card. The main objective of this update would be to increase the number of LEDs on my PCB Business Card. This portion of development was probably the biggest obstacle I faced today. The reason for that was the fact that adding an LED required that many diffferent constraints be met: sufficient voltage, efficient wiring (parallel in this case, I believe this was the issue that stopped another hack clubber from implementing multiple LEDs in his project), and most importantly (annoyingly), connecting an entire new LED to the components already on the PCB design. This took me an insane amount of time. When attempting to trace the necessary connections on the PCB design, I constantly ran into scenarios that owuld result in short-circuiting, leading to an extremely tedious trial-and-error proocess to find the optimal connection paths. After playing a game of technical free flow, I had successfully added another LED to my PCB Business Card. This would be version 2.0 of my product.

![v2.0_schematic](https://github.com/pdumpa08/PCB-Business-Card/blob/main/img/v2.0_schematic.png?raw=true)
![v2.0_2d](https://github.com/pdumpa08/PCB-Business-Card/blob/main/img/v2.0_2d.png?raw=true)

**Total time spent: 5.75h**

# July 5th P2: Designed v3.0 of project!

New design made! I took a look at my design again and thought: how can I make this thing stand out. After considering all of my options, I came upon the idea of adding a cool design. Initially, I considered adding a phoenix with the eye lighting up, but the form factor wouldn't work with the space I had remaining on my PCB Business Card. So, in the end I decided on a dragon breathing fire (more horizontal than a phoenix would've been).

Adding the design was an amazing hassle. I had to find the right image (insanely hard even with AI) and then convert that image into a form that could be used on my PCB Business Card (svg). While doing so, I had to modify the image on canva and figma to ensure the colors and size were appropriate. Later, I had to separate the flame from the dragon's image in order ot size the two separately on my PCB Business Card.

Lastly, I attempted to move one of the LEDs into the dragon's eye. Although all the connections work and there are no DRC errors, I found, after querying AI, that there were important electrical engineering principles that I had not included in my desing (45 degree angles, ground planes, etc.). That will have to come tomorrow.

![v3.0_2d](https://github.com/pdumpa08/PCB-Business-Card/blob/main/img/v3.0_2d.png?raw=true)

**Total time spent: 2.50h**

# July 6th: Final Push!

Today, I went through all of the improvements I found out about the previous night. A little more specifically, I modified the positioning of the traces and components so that current is able to flow without short circuiting or getting interrupted and added a ground piece of copper to the design to further enhance the connectivity. In addition, I moved the components around to better modularize the design and make it efficient based on electrical engineering principles (ChatGPT helped me with finding out what changes were important). I also found another PCB Business Card project that uses 2 LEDs and an NFC. His setup was also parallel and from his README, he seems quite experienced with hardware, giving me more confidence that the low voltage the NFC provides will be enough for the LEDs.

After making all of those changes, I spent a singificant amount of time preparing my github repo/project for submission based on the highway guidelines. This is in all honesty one of my first hardware projects and I'm very happy with the design, technical ability, and cost efficiency of my product (version 4.0, the final edition for now). Looking forward to submission!

![v4.0_2d](https://github.com/pdumpa08/PCB-Business-Card/blob/main/img/v4.0_2d.png?raw=true)

**Total time spent: 3.00h**