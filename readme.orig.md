### Hi there 👋
I'm Suhail Ahmed. I've done my Bachelors in Technology, Computer Science with specialization in Artificial Intelligence and Machine Learning. I love to learn about pretty much anything under the sun and sometimes I end up building something cool from my learnings. I'm drawn to the creative aspect of coding and love nothing more than to kick back and code something fun while listening to music. (80% of the time I'm bumping to Travis, Weeknd or Artemas. Trust me, that 80% is quite a crazy number once realized.)

### 🔭 Some of my (kinda polished) work ...

#### [expressReserve](https://github.com/SuhailAhmedVelorum/expressReserve)* - Couldn't open source it as I wasnt sure if I am allowed to.
- Since COVID, HPE rolled out a policy to have floating seats in the IWF office. They had a web application where they expected employees to reserve seats in the office for themselves/ their team.
- I was tasked with reserving the seats for my team. That was a really painful task. It took me 30 mins to reserve about 15 seats.
- So naturally, I took a weekend out to automate a 30 mins task. 😂
- expressReserve started out as a simple python script that was hardcoded for our usual seats and deployed on my work VM under a cron job that ran every day.
- Even though it never went public, the news spread like wildfire and I was getting requests from other teams to use it.
- So I decided to formalize it a bit more and make it generic to run for any seats on any day, read off a config file.
- Eventually, I got bored on another weekend (SURPRISE! SURPRISE!) and moved it to c++.
- Some optimizations:
    - Parallelized the seat reservation process
    - Made the requests async (IDK why I didn't think of this sooner)
    - Added support for some seats to be "hot" and reserved them first
    - I could book over 30 seats in under 3 seconds! Down from 30 mins.
- Couldn't open source it as I wasnt sure if I am allowed to. But I did share it with my team and they loved it.
- 30 mins of man hours saved 2 days a week. Crazy!
- Ask anyone from 4C in the HPE IWF office. They either use my script or hate me for taking up huge chucks of seats on the floor. 😅
- Super proud of how this one turned out.
- [Got an award for it from work](https://www.linkedin.com/posts/suhailahmedvelorum_wearehpe-hpe-activity-7107419019414044673-yW5b?utm_source=social_share_send&utm_medium=member_desktop_web&rcm=ACoAAC1Z9IYBHjSVWIYEJhY2ymtVbBCRrIMGDZI). 🎉


#### [ShiftKit](https://github.com/SuhailAhmedVelorum/ShiftKit) - WORK IN PROGRESS
- "Necessity is the mother of invention." YOU BET! Or in this case, an unnecessary re-invention of the wheel.
- Not that this was absolutely necessary though. XD I just thought it would be fun to build something of my own and have it super customized for my needs.
- ShiftKit is a python project that is meant to help me (and maybe you) with quickly setting up your systems with software/config and all the other good stuff.
- I am the typical distro hopper and I kept wrecking my system often. I bit the bullet and kept doing everything manually for a while.
- But when I finally decided to build my own PC (Go ahead, ask me about it, don't be shy.), I saw an opportunity to finally automate the process.
- An unncessarily complicated way to define "packages" (units of configuration - Think system packages, network config, desktop customizations, dotfiles, etc.). You know what? I don't care about the complexity of the system. I just want it to work. I'll optimize it later.
- I want to be in control of my system. I want everything I want installed, installed, without me stressing about it.
- I had hyper-personalized my Arch (Yes, I use\[d\] arch BTW) and even Ubuntu installs with a ton of customizations and productivity tools.
- I built out ShiftKit to help me with that. Read more about it in the project [README](https://github.com/SuhailAhmedVelorum/ShiftKit/blob/main/README.md).
- Still working on it. So expect some rough edges and of course, let me know what you think about it.

#### [Learn in Bit](https://learninbit.com/)
- Started out as an online coding platform where me and my friends could quickly write and run code. (Kinda like Repl.it but something of our own)
- The intial idea for (then named codeplex) came to us in our second year of college. We started out naive and built our own code execution python package - Compylex (Which we had on PyPI for a while. RIP!)
- We then started out with a simple UI and started building out the platform.
- Eventually, we got a couple of other friends interested in the project and we started working on it more seriously.
- It is totally legit. Not that I'm bragging or anything. XD

#### [DocSearch for VSCode](https://github.com/Doc-Search)
- Alrighty! This one kinda hurts, so grab a tissue.
- This was back when ChatGPT and LLMs werent a thing. My buddy Ashiq was reading up and working on [JINA](https://jina.ai/). (Their website wasnt as flashy back then. They really did such a great job with it.)
- Now, I don't remember who exactly came up with this use case but I remember us talking about using it as some sort of search engine within VS code for quick documentation lookup.
- I know, super visionary for the time. But we started working on it only as a project to submit as a project for college. (I can get super philosophical about how college is killing creativity. But let's not.)
- We then built it with a couple of friends and it was a lot of fun. Our professor wasnt too happy about it but we werent too worried.
- Once we were done, we submitted and washed our hands clean. But I'll bet, if we were to do it again, we'd be using LLMs.
- Could have been a great project, ended up being a good project. But, that's life.

#### [I'm cooking something cool! Shhhhh!](https://www.youtube.com/watch?v=WLHb7WGlS3Q)
- CODENAME: RACCOON, don't ask me why. I'm just that kind of person.

#### And a bunch of other stuff that I have built/ am building for my personal use.

### 🌱 I’m currently learning ...
- VIM - This one is a bit of a journey. Don't deprive yourself of the joy of writing a complex macro for a very specific use case that you'll never use again. No kidding, it's fun.
- Low level design and system programming - Here and there, by chance.
- MCP - So many use cases, so little time, but absolute fun!
- Random odd perls and software design from Unix and Linux.
- [UV](https://docs.astral.sh/uv/) Ooh! Look at that! New shiny thing! But what does it do better?
- Slowly but surely, my team's product and it's inner workings. [SimpliVity](https://www.hpe.com/in/en/storage/simplivity.html) There's soooo much to learn! ♥️
- Just got into GPGPU programming, I know nothing, but I'm excited! Thinking in parallel is very new to me. Going to need a project for this. - If you've tried it, let me know how you think I should approach it.

### 👯 I’m looking to collaborate on ...
- Any cool projects, at any stage, of any complexity, written in any language.

### 📫 How to reach me: ...
[![Gmail Badge](https://img.shields.io/badge/-suhailahmedvelorum@gmail.com-c14438?style=flat&logo=Gmail&logoColor=white)](mailto:suhailahmedvelorum@gmail.com "Connect via Email")
[![Linkedin: ](https://img.shields.io/badge/-SuhailAhmedVelorum-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https:https://www.linkedin.com/in/suhail-ahmed-372992192/)](https://www.linkedin.com/in/suhailahmedvelorum/?_l=en_US)
[![Telegram](https://img.shields.io/badge/-SuhailAhmedVelorum-blue?style=flat-square&logo=Telegram&logoColor=white&link=https://t.me/thesecondbit)](https://t.me/thesecondbit)
