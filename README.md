# GitHub Page of [Kevin R. Whitley](https://kevinrwhitley.com)

I'm an open-source developer, architect, and builder of ideas. 

## Prototyping/Building
I design and build products from end-to-end, with a focus on global-availability, automatic scaling (within reason), and simplicity of design. I execute ideas from start to finish - data design, cloud architecture, simple interface, front-end code, styling, you name it - then I launch it or hand it off to long-term support teams.

## Open Source Lessons Learned
Along my journey to deliver exciting prototypes and products, I've occassionally needed to create tooling that didn't quite exist for the given space yet.  Early in my career, one of my mentors encouraged me to polish [one such tool](https://npmjs.com/package/apicache) up and share it with the world.  This experience paved the way, and today, I routinely share my more [generically-useful libraries](https://itty.dev).

Along the way, I've learned a few things, such as:

- **Work backwards.**  Start with how you want your code/product to look/work in the most ideal world, as if it was already written.  Iterate here first, THEN make it actually work.
- **Everyone is lazy.** We all want to accomplish more with less effort. Whether developing code for developers (DX) or users (UX), keep this in mind.  Do you enable them to achieve more, while doing less... or thinking less?  If so, you're probably on the right track!
- **You can't please everyone.** If you attempt to do so, you'll end up pleasing no one.  Instead of making a generic tool that does a lot of things OK, consider making a great one that does a one or two things exceptionally.  This will help in the next point...
- **The most maintainable library/code is the *simplest* library/code.**  K.I.S.S.
- **Don't obsess with developer minigames.** These include all the things we insist we need to develop (e.g. the most perfect Types/hinting, TypeSafe everything, the most perfect eslint rules, etc. Spoiler: Your consumers/clients/customers don't care about any of this, and many successful products have been launched before any of this stuff existed.  Save it for later!
- **Don't test too early...** Except in the rare case where TDD (test-driven development) is appropriate (e.g. perhaps a code competition like Advent of Code), skip testing in the early phase.  Iterate and harden the API/interface first, *then* add test coverage only when it becomes important to protect the code integrity (e.g. if users are using it, or downstream code depends on it).  Otherwise, this is a waste of time.
- **...but don't ignore testing.** Every tool has its place.  If you look at my open source libs, you'll notice many have 100% coverage with hundreds of tests to cover only a few lines of code.  This is because users don't like their experience to break just because we add a cool new feature.  Protect them from yourself!
- **The API is hard to change.** Changing an interface/API in production is hard.  You'll lose customers, period. What do you do about this?  Be far more thoughtful about your end-code/API design up front, because once it's live, it's very hard to change.  Don't paint yourself into a corner on day 1.
- **Stay humble.** When I was too young/immature to know better, I used to think *I* was a rockstar; but now I've met the *real* ones. When you start to collaborate with the real leaders of our industry, it quickly humbles you. This is a good thing. :)

## Focus Areas For the Future

There are a few areas I've played with in the past and am dying to explore further:

- **Deep reinforcement learning/neuro-evolution.**  I've done a fair bit of work in the applied side of neuro-evolution (specifically around financial models), and am eternally fascinated by how quickly we can evolve autonomous agents within a digital twin environment.  I have some sick demos to share in this area for anyone curious!
- **VR/MR development.**  I've spent hundreds of hours (easily) within VR, and can assure you that the industry is currently content-starved.  This is a golden opportunity for creators!  Specifically, my interest centers around architectural/interior design, either in VR or possibly MR (as tools like the Quest 3 start to make that more feasible).  Designing spaces/worlds (or modifications to our own, such as say, a closet/kitchen remodel), should be much, much more accessible!
- **Game development.** Honestly I started my programming journey with Pascal/Assembler ages ago... making graphics effects and video games.  I miss this level of tactile visual feedback.  Web apps are cool and all, but just not the same!

### CONTACT
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/kevinrwhitley)
[![GitHub](https://img.shields.io/badge/github-%23EEE.svg?style=for-the-badge&logo=github&logoColor=121011)](https://github.com/kwhitley)
[![LinkedIn](https://img.shields.io/badge/linkedin-%23EEE.svg?style=for-the-badge&logo=linkedin&logoColor=0077B5)](https://www.linkedin.com/in/kevinrwhitley/)
[![Portfolio](https://img.shields.io/badge/kevinrwhitley.com-%23EEE.svg?style=for-the-badge&logo=kirby&logoColor=f0c)](https://kevinrwhitley.com)

### MY SEMI-POPULAR LIBRARIES
[![apicache](https://img.shields.io/npm/dw/apicache?style=for-the-badge&logo=npm&color=ded&label=apicache)](https://npmjs.com/package/apicache)
[![itty-router](https://img.shields.io/npm/dw/itty-router?style=for-the-badge&logo=npm&color=ded&label=itty-router)](https://npmjs.com/package/itty-router)
[![itty-router-extras](https://img.shields.io/npm/dw/itty-router-extras?style=for-the-badge&logo=npm&color=ded&label=itty-router-extras)](https://npmjs.com/package/itty-router-extras)
[![itty-cors](https://img.shields.io/npm/dw/itty-cors?style=for-the-badge&logo=npm&color=ded&label=itty-cors)](https://npmjs.com/package/itty-cors)
[![itty-durable](https://img.shields.io/npm/dw/itty-durable?style=for-the-badge&logo=npm&color=ded&label=itty-durable)](https://npmjs.com/package/itty-durable)
[![itty-fetcher](https://img.shields.io/npm/dw/itty-fetcher?style=for-the-badge&logo=npm&color=ded&label=itty-fetcher)](https://npmjs.com/package/itty-fetcher)
[![treeize](https://img.shields.io/npm/dw/treeize?style=for-the-badge&logo=npm&color=ded&label=treeize)](https://npmjs.com/package/treeize)

### CURRENT STACK
![Vite](https://img.shields.io/badge/Vite-%23EEE.svg?style=for-the-badge&logo=vite&logoColor=646CFF)
![SvelteKit](https://img.shields.io/badge/Svelte/Kit-%23EEE.svg?style=for-the-badge&logo=svelte&logoColor=FF3E00)

![Cloudflare Pages](https://img.shields.io/badge/Cloudflare-Pages-%23f38020.svg?style=for-the-badge&logo=cloudflare&logoColor=f38020)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare-Workers-%23f38020.svg?style=for-the-badge&logo=cloudflare&logoColor=f38020)
![Cloudflare Durable Objects](https://img.shields.io/badge/Cloudflare-Durable%20Objects-%23f38020.svg?style=for-the-badge&logo=cloudflare&logoColor=white&logoColor=f38020)
![Cloudflare KV](https://img.shields.io/badge/Cloudflare-KV-%23f38020.svg?style=for-the-badge&logo=cloudflare&logoColor=f38020)
![Cloudflare R2](https://img.shields.io/badge/Cloudflare-R2-%23f38020.svg?style=for-the-badge&logo=cloudflare&logoColor=f38020)
![Supabase](https://img.shields.io/badge/Supabase-%23EEE.svg?style=for-the-badge&logo=supabase&logoColor=3ECF8E)

##### NEXT UP / INTERESTED
![Kotlin](https://img.shields.io/badge/kotlin-%23EEE.svg?style=for-the-badge&logo=kotlin&logoColor=#7F52FF)
![Swift](https://img.shields.io/badge/Swift-%23EEE.svg?style=for-the-badge&logo=swift&logoColor=F05138)
![Unity](https://img.shields.io/badge/Unity-%23EEE.svg?style=for-the-badge&logo=unity&logoColor=000)

##### THE OBVIOUS STUFF
![CSS3](https://img.shields.io/badge/css3-%23EEE.svg?style=for-the-badge&logo=css3&logoColor=1572B6)
![Express](https://img.shields.io/badge/Express-%23EEE.svg?style=for-the-badge&logo=express&logoColor=000)
![GitHub](https://img.shields.io/badge/GitHub-%23EEE.svg?style=for-the-badge&logo=github&logoColor=000)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-%23EEE.svg?style=for-the-badge&logo=githubactions&logoColor=2088FF)
![JavaScript](https://img.shields.io/badge/javascript-%23EEE.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Jest](https://img.shields.io/badge/-jest-%23EEE?style=for-the-badge&logo=jest&logoColor=C21325)
![HTML5](https://img.shields.io/badge/html5-%23EEE.svg?style=for-the-badge&logo=html5&logoColor=E34F26)
![Markdown](https://img.shields.io/badge/markdown-%23EEE.svg?style=for-the-badge&logo=markdown&logoColor=000000)
![MongoDB](https://img.shields.io/badge/MongoDB-%23EEE.svg?style=for-the-badge&logo=mongodb&logoColor=47A248)
![MySQL](https://img.shields.io/badge/mysql-%23EEE.svg?style=for-the-badge&logo=mysql&logoColor=4479A1)
![Node](https://img.shields.io/badge/Node.js-%23EEE.svg?style=for-the-badge&logo=node.js&logoColor=339933)
![NPM](https://img.shields.io/badge/NPM-%23EEE.svg?style=for-the-badge&logo=npm&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23EEE.svg?style=for-the-badge&logo=postgresql&logoColor=4169E1)
![Sass](https://img.shields.io/badge/Sass-%23EEE.svg?style=for-the-badge&logo=sass&logoColor=CC6699)
![TypeScript](https://img.shields.io/badge/typescript-%23EEE.svg?style=for-the-badge&logo=typescript&logoColor=3178C6)
![Visual Studio Code](https://img.shields.io/badge/VSCode-%23EEE.svg?style=for-the-badge&logo=visual-studio-code&logoColor=0078d7)
![Vitest](https://img.shields.io/badge/Vitest-%23EEE.svg?style=for-the-badge&logo=vitest&logoColor=6E9F18)

&nbsp;

###### "Sunsetting" Tech (I focus on helping teams migrate from these onto better tools)
![React](https://img.shields.io/badge/React-%23FFF.svg?style=for-the-badge&logo=react&logoColor=61DAFB) 
![Redux](https://img.shields.io/badge/Redux-%23FFF.svg?style=for-the-badge&logo=redux&logoColor=764ABC)

###### Fully-Retired Tech (a few that I'm no longer interested in working with at all, for any price)
![AngularJS](https://img.shields.io/badge/AngularJS-%23FFF.svg?style=for-the-badge&logo=angularjs&logoColor=E23237) 
![PHP](https://img.shields.io/badge/PHP-%23FFF.svg?style=for-the-badge&logo=php&logoColor=777BB4) 
![.NET](https://img.shields.io/badge/.NET-%23FFF.svg?style=for-the-badge&logo=.net&logoColor=512BD4)
