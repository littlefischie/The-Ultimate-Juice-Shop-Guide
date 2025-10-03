# Introduction and Usage

### Why Use Juice-Shop
--------------------------------
Juice-Shop is one of the best test-environments when it comes to web-app penetration testing. It structures itself extremely well, progressing from easy to hard and carries concepts from the last excercise to the more advanced one. It's a progression that feels natural, challenging, and well-rounded. I highly recommend it to anyone and the skills will certainly pay-off when it comes to finding bug-bounties in almost any web-app. From low level bugs to critical remote code executions. 
##### Note that I won't cover installation as there are already guides available through OWASP that are more than sufficient.
##### Note that I'm using Kali Linux. I recommend you do too.

### Why I'm Making This Guide
--------------------------------
This guide seeks to solve several issues I've had on my journey solving OWASP Juice-Shop. I want a guide that:

1. Includes both guidance and hints
2. Includes solutions
3. Properly explains key concepts, takeaways, learning outcomes, etc.

Juice-Shop has been my introduction into web-app penetration testing and penetration testing in general, so I came at this with no prior knowledge. This means that when I attempted to solve things on my own I simply had no chance as I had no idea what something like a null-byte or html-encoding was. 

I also found myself diving down rabbit holes. The recon methodology was something that was extrememly hard to do as guides had already scoped it out and gone straight to the right place. I embraced giving up on recon after finding one thing that looked good and going tunnel-vision for hours.

This leads to my general dislike for the guides I found and used. Hacksplained on Youtube was easily my favorite as he does a good job explaining the concepts, but it's outdated and doesn't cover all of the challenges. Notably, he doesn't have walkthroughs for the highest difficulty challenges. The other options are OWASP's official guide, which has both a hints section that doesn't teach the concepts critical to solving the challenge, and their solutions guide, which gives solutions plainly but also fails to explain said concepts. There's another guide here on Github but it absolutely whizzes past all the concepts, doesn't explain why they make the decisions they do, and just gives answers. There are also a lot of extremely low quality guides on Youtube that are also guilty of the same flaws. Thus, as both a help to others and a help to my own learning, I'm choosing to make the guide that I wish I'd had. 

### Usage
-----------
The general structure of this guide will introduce the challenge and highlight key elements. It will then list key concepts and fully explain what techniques should be used. That way someone who knows nothing has a chance at being able to solve it themself. I recommend that people stop reading here and give themself 15, 30, or 45 minutes to attempt the challenge themself. The timing should be adjusted based on how much you know at the time. The first few guides maybe you're entirely stumped after 15 and need more help. The more advanced challenges give yourself 45 to see if your recon skills hold water and if you can properly apply the technique covered. Most of these challenges can be solved in 5 minutes if you know exactly what to do, so if it's taking you 45 minutes of chasing your own tail it probably means you could use some extra guidance. 

Please don't just read through to the solutions. Just because you get confetti doesn't mean you learned anything. You should also be taking extensive notes. Remember in school the teacher would basically give you the answers, you'd take notes, then move on to solving similar problems on your own. Even if you need to follow the solution step by step your notes should include exactly how you or I reached said solution. Notes, and thinking through the problem yourself is how you learn and that's the whole point of why we're here. Once you progress to CTFs and Bug-Bounties there are no full guides so you'll need to think for yourself. 

Anyway, I'll be adding to this guide slowly so if all the challenges aren't covered when you first find this, check back and hopefully the guide will be available. 

I hope this is helpful!