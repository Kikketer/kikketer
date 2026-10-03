## Chris Weed

I'm a full stack engineer focused on NextJS, Agentic coding with an eye for User Experience. I'm always building up new and random projects for myself that are typically half-baked or incomplete.  All public repos are just experiments and playings to learn something new or prove out an idea.  My "real" work is done in private repos for the companies I work for. But here are a few of the fun projects I've worked on in the past as "Just for fun" or "Let me see if I can do X".

### For The Learn of It

[For The Learn of It](https://forthelearnofit.com) is a place I've put several of my experiments but also learning tools for students I teach. This project helps students learn about the ins-and-outs of web development with a custom built client/server side editor with live code editing. MakeCode Arcade is another focus of the work in here as that's the primary coding tool I use to teach. I've built AI assisted sprite, image, animation and music creation tools. These are all custom built tools for me to inspire students (and also learn something myself).

### Simple Mail Merge

[Simple Mail Merge](https://cjweed.com/Simple-Mail-Merge/) - a simple way to create "mail merge" aka a way to have a list of contacts and send emails individually to each. I had used Thunderbird and it's deprecated UI + an outdated extension for this in the past. I decided today that I can just create one using Electrobun.  It'll use your standard email settings (IMAP style auth) and allow you to craft a simple email that you can then send to a series of people.  Each person will receive an email addressed only to them.  Go check out other email clients out there, most say "we don't support this at all"... well now I have my own.

### Object Slicer

[Object Slicer](https://cjweed.com/object-slicer/) - an app for simply slicing up 3d models to be used for laser cutters. It creates either a stacked series of cuts or a "mesh".  It'll slice according to the page size you are limited to, etch the numbers for you and create solid grooves for interlocking pieces.  I built this because I was tired of the "get points for using our app" and also the paid for options. We are in an age of AI generated code, there's no need to pay for products that don't exactly fit your use case anymore.

### LineUp Field Manager

The [LineUp Field Manager](https://app.lineup.soccer) was built to help me manage painting soccer fields for my local club. It started out as a project to see how far I could take a PWA including things like Push Notifications and get exposure to other frameworks such as Solid, NextJS and Ionic Framework. It's now currently an Ionic PWA that is used by the club to help predict when fields need to be re-painted and helps coordinate when a field is needed for games.

Learned and Explored:

- Supabase along with auth and database techniques
- Push notifications in PWAs, mostly in iOS
- Ionic design library within React
- Offline-first caching
- Environmental considerations such as bright sunlight and busy hands

### WTFTimezone

(deprecated)
I built this super minimal application just to help me work out and explain timezones to people and shows not only the UTC time and "local to you" time. I've spent a ton of time (pun?) and an embarrassing amount of time thinking out timezones and what that means for people when working on international applications. I've seen some horrifying code where dates are "just strings that look like dates" and totally incorrect assumptions where things were accidentally working because of the location of the server. Anyway it's just mostly a tongue-in-cheek site that I was inspired to slap together in a few hours. [WTFTimezone](https://wtftime.zone)

Learned and Explored

- Absolutely slim and minimal html/css/js with installable apps
- The small annoyances of timezone math + browser handling of dates
- Solidified Github pages along with custom domains
- How quickly an app can be built when combined with AI

### Dawn E Photography

A simple static website using Eleventy to promote my wifes photography business. This was a fun learning opportunity around media handling, media sizing with the `<imgsrc`, SEO and minimum page generation. It's created using Pug templating language but the JS and CSS are just vanilla. It was nice and relieving to build a site with standard library imports, reminded me of the jQuery days. The result is a nice merge of simplicity, speed and cohesion between the static marketing page and the gallery platform she uses. [Dawn E Photography](https://dawnephotos.com/)

Learned and Explored

- Eleventy and the build process
- SEO and social network cards
- Minimum bundle sizes
- Image load on scroll and <imgsrc tag

### Swashed

I took the rules of a resonably fun but overly complicated boardgame called Swashbuckler and created a hybrid style boardgame. The main goal of this project was to learn some Python, Ruby on Rails and Deno but eventually turned into simply Deno + Svelte. The other trial of this project was to see how far AI could take a project and the results were mostly "it helps, but can't get all of the work done". At one point I was fixing bugs by simply asking AI to fix it, and every time it would undo the last fix, eventually I just got my hands dirty and fixed it myself. There's no public repo for this yet and it's mostly just an experiment and learning platform, the goal is to run it on a raspberry pi and have players join with their phones on it's own wifi network. Stay tuned for updates to this exciting project!

Learned and Explored

- Minimal hardware web server
- Server Sent Events
- Svelte and comparing it to my typical React knowledge
- Brain excersises around arrays and complex requirements

### Greedy Pirates

Built with my son during a MakeCode Arcade hackathon. This game is part of many of my projects that I do to simply learn and/or simply teach. I used the learnings from this to prepare for classes I taught for middle school aged students.  This also inspired some fun hacking with handheld devices. It's a pretty fun game go check it out: [Greedy Pirates](https://arcade.makecode.com/S66008-45860-30012-86138)

Learned and Explored

- MakeCode Arcade and typescript within that
- The inner workings of MakeCode Arcade such as the asset format
- Mostly so I can teach it to middle-school students

### Color by Pixel

A fun side project that helped me learn and excersise some frontend-only limitations. I was inspired by some homework my kids where they had to do math problems to fill in a color-by-number piece of art. With my love of pixelart and wanting to do some "known" sprites, I came up with a way for people to upload a pixelart sprite and have it turn into a coloring sheet that you can print out. It has some limits but I wanted to see what some of the client-only file handling could do around parsing the image and then producing a printable grid. I even found a nice library that had a pretty solid color-to-name coversion! Check it out: [Color by Pixel](https://kikketer.github.io/color-by-pixel/).

Learned and Explored

- File handling and reading within the browser
- Installable app
- Print considerations and stylesheets

### StorAI

This was done as part of a hackathon for [Wasp](https://wasp-lang.dev/) where I ended up placing 3rd. I experimented with the early versions of AI and how I could create a choose-your-own-adventure engine that uses AI + LangChain. The real goal was to see how Wasp works and how it could help build applications at lightning speed. Overall I liked the framework and the idea but it's still in it's infancy and with things like NextJS being the "big boat" it's hard to propose using a somewhat propriatary language to describe how to build the application vs just building an application. Although it does cross my mind when I think about possible full-stack builds and re-builds of the LineUp Field Manager (just to learn a new path).

Learned and Explored

- Wasp-lang framework and how it may apply to future projects
- Using LangChain to leverage early LLMs
- Hackathon with half written while offline
