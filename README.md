# 100DaysOfReadingAnArticle

Documenting my #100DaysOfReadingAnArticle Challenge Tweets
Preferably using [daily.dev](https://daily.dev)
- Twitter: [@sexy_gravy](https://twitter.com/sexy_gravy)
 
## Table of Contents

- [Day 01](#day-01)
  - [How to write better code](#how-to-write-better-code)
  - [Make your React apps fast again](#make-your-react-apps-fast-again)
  - [Golang Aha! Moments: Generics](#golang-aha-moments-generics)
- [Day 02](#day-01)
  - [Top 14 Cutting-Edge Web Development Trends in 2023](#top-14-cutting-edge-web-development-trends-in-2023)
- [Day 03](#day-03)
  - [Dolt - A SQL Database that Works like Git](#dolt-a-sql-database-that-works-like-git)
- [Day 04](#day-04)
  - [Jokes only programmers will understand](#jokes-only-programmers-will-understand)
- [Day 05](#day-05)
  - [React Just Got Even More Awesome](#react-just-got-even-more-awesome)
- [Day 06](#day-06)
  - [Advice for Junior Developers](#advice-for-junior-developers)
- [Day 07](#day-07)
  - [Harvard CS50 – Free Computer Science University Course](#harvard-cs50-free-computer-science-university-course)
- [Day 08](#day-08)
  - [VSCode Updates, Frameworks, Git/CLI, JS Utils](#vscode-updates-frameworks-git-cli-js-utils)
- [Day 09](#day-09)
  - [Introducing Turbopack: Rust-based successor to Webpack](#introducing-turbopack-rust-based-successor-to-webpack)
- [Day 10](#day-10)
  - [Next.js 13](#next-js-13)
- [Day 11](#day-11)
  - [An animated guide for Node.js event loop](#an-animated-guide-for-node-js-event-loop)
- [Resources](#resources)
- [Devcards](#devcards)

## Day 01

These articles are all from [Hashnode](https://hashnode.com)

### [How to write better code](https://r.bluethl.net/how-to-write-better-code?source=personalized-newsletter&source-id=2022-10-13)
- by [Ronald Blüthl](https://twitter.com/rbluethl)

1. Undertstand the basics
2. Think before you write
3. Be consistent
4. Separate concerns
5. Don't use magic numbers
6. Don't reinvent the wheel
7. Use fewer dependencies
8. Use self-explanatory names
9. Don't over engineer
10. Avoid duplication or redundancy
11. Refractor if necessary
12. Don't make assumptions
13. Take advantage of immutability
14. Introduce environment variables
15. Get in the zone
  
### [Make your React apps fast again](https://avocadev.hashnode.dev/make-your-react-apps-fast-again?source=personalized-newsletter&source-id=2022-10-13)
- by [Developer Avocado 🇺🇦](https://twitter.com/dev_avocado)

- Profiling your React app and searching for bottlenecks
  - Understanding how React updates its UI
  - Measuring performance with React DevTools
  - React performance optimization technizues
    - Keeping component state local where necessary
    - Memoizing React components to prevent unecessary re-renders
    - Code-splitting in React using dynamic import()
    - Virtualize Long Lists
    - Lazy loading images in React
    - Multiple Chunk Files
  - Non React specific optimizations
    - Serve everything from a CDN
    - Use CSS Animations instead of JS Animations
    - Move from CSS-in-JS
    - SSR
    - Optimizing NPM Dependencies
    - Analyzing and Optimizing your Webpack Bundle Bloat
    - Other considerations

### [Golang Aha! Moments: Generics](https://openziti.io/golang-aha-moments-generics?source=personalized-newsletter&source-id=2022-10-13)
- by Paul Lorenz

## Day 02

### [Top 14 Cutting-Edge Web Development Trends in 2023](https://yellow.systems/blog/web-development-future-trends)

- Frontend development trends
The time when a front-end web developer only needed to know HTML, CSS, and JavaScript is long gone. So, the way to keep pace with a rapidly changing environment is to watch the latest front-end technologies.

![Screen Shot 2022-10-14 at 3 37 36 PM](https://user-images.githubusercontent.com/89284873/195939252-d5ab2e41-6221-42b7-82d6-7a21e1ffa66e.png)

- Why JavaScript rocks?
  - It’s an object-based and dynamic language used both on the client side and the server side.
  - It’s supported by many browsers, such as Safari, Chrome, Firefox, and Internet Explorer.
  - Interactivity is excellent because JavaScript is a language that gives the web page its structure and style.
  - Many libraries and frameworks are available.
  
- Jamstack
  - In the JAMstack definition (which appeared in 2015), JAM stands for JavaScript, API, and Markup, but now "Jamstack" is widely used. This is how Mathias Biilmann, the CEO and co-founder of Netlify, defines the term: "It’s a web development infrastructure based on client-side JavaScript, reusable APIs, and prebuilt Markup."
  
- Mobile-first Approach in Web Development
  - Focus on vertical orientation rather than landscape one, and on functions done with a touchscreen. 
  - Set up meta viewport tags to help browsers change how pages are scaled.
  - Use different layout methods, e.g. Grid, Multi-Column, or Flexbox, to make layouts fit the viewport.
  - Use CSS queries to change the size of things based on what the devices can do.

- Headless Architecture for Content Management 

![Screen Shot 2022-10-14 at 3 43 17 PM](https://user-images.githubusercontent.com/89284873/195940143-dc06494d-d643-4c75-b665-876482747016.png)

## Day 03

### [Dolt - A SQL Database that Works like Git](https://cult.honeypot.io/reads/dolt-a-sql-database-that-works-like-git/)
- by Chameera Dulanga

- What is Dolt?
Dolt is an SQL-based database that allows you to maintain your database like a Git repository.

- Features of Dolt
  - Versioning system similar to Git.
  - Works with standard SQL connectors.
  - Comes with a powerful CLI.
  - Allows exploring the complete history of your data.
  - Instant rollback to any commit.
  - DoltHub provides a web-based UI to collaborate on Dolt databases.
  - DoltLab allows the creation of self-hosted DoltHubs.
  - Built-in backup and monitoring.
  - Make money through DoltHub data bounties

## Day 04

### [Jokes only programmers will understand](https://codingpastor.hashnode.dev/jokes-only-programmers-will-understand)
- by [Coding Pastor](https://hashnode.com/@codingpastor)

** Note: I really enjoyed reading this one! This is your sign to lighten up and take a break! **

## Day 05

### [React Just Got Even More Awesome](https://dev.to/dayvster/react-just-got-even-more-awesome-f15)
- by [Dayvster](https://dev.to/dayvster)

How does the use hook work?
- Similary to await it simply unwraps the value of a promise, meaning that any async behaviour can be wrapped in a use hook now and react will natively handle the promise for us.

Others:
- [ReactJS rfcs](https://github.com/acdlite/rfcs/blob/first-class-promises/text/0000-first-class-support-for-promises.md)
- [react-query](https://tanstack.com/query/v4)

## Day 06

### [Advice for Junior Developers](https://dev.to/jeroendedauw/advice-for-junior-developers-30am)
- by [Jeroen De Dauw](https://twitter.com/JeroenDeDauw)

The blog post mentions and links to many valuable concepts that you can explore further as you see fit. It has three sections:

* Generic Advice — Important context and motivation for the technical advice
* Technical Advice — The main course
* Recommended Reading — Links to high-quality books and blogs that are great for getting started

## Day 07

### [Harvard CS50 – Free Computer Science University Course](https://www.freecodecamp.org/news/harvard-cs50/)

This course provides an introduction to the intellectual enterprises of computer science and the art of programming. This course teaches students how to think algorithmically and solve problems efficiently.

Topics include abstraction, algorithms, data structures, encapsulation, resource management, security, software engineering, and web programming. Languages include C, Python, and SQL plus HTML, CSS, and JavaScript.

[Link to the Youtube Videdo](https://www.youtube.com/watch?v=8mAITcNt710&t=4s) - 25-hour watch

## Day 08

### [VSCode Updates, Frameworks, Git/CLI, JS Utils](https://mailchi.mp/webtoolsweekly/web-tools-483)

Loved reading this article. VSCode is definitely my favorite IDE and I enjoy a lot of the extensions. Mostly because they make life easier for me. 

Here are some examples of stuff VS Code has added in recent months:

- Improved autoscroll behaviour – This improves the editor's behaviour when you click and drag to select a long piece of text that spans multiple screens.
- Explorer rename selection improvements – This allows you to use the F2 key to cycle through three different types of file renames: file name only, entire selection, and file extension only.
- Editor sticky scroll – This improves the editor UI to show scope during scrolling. For example, you can immediately see which class, namespace, function, constructor, etc. you're in within your document.
- Toggle between Light and Dark themes – This allows you to use a single command to switch between your preferred dark and light themes.

## Day 09

### [Introducing Turbopack: Rust-based successor to Webpack](https://vercel.com/blog/turbopack)

- How fast is Turbopack?

Turbopack is built on a new incremental architecture for the fastest possible development experience. On large applications, it shows updates 10x faster than Vite and 700x faster than Webpack. On even larger applications, the difference is greater—often 20x faster than Vite.

Turbopack only bundles the minimum assets required in development, so startup time is extremely fast. On an application with 3,000 modules, Turbopack takes 1.8 seconds to boot up, while Vite takes 11.4 seconds.

## Day 10

### [Next.js 13](https://nextjs.org/blog/next-13)

Next.js 13 lays the foundations to be dynamic without limits:

- app/ Directory (beta): Easier, faster, less client JS.
  - Layouts
  - React Server Components
  - Streaming
- Turbopack (alpha): Up to 700x faster Rust-based Webpack replacement.
- New next/image (stable): Faster with native browser lazy loading.
- New @next/font (beta): Automatic self-hosted fonts with zero layout shift.
- Improved next/link: Simplified API with automatic <a>.

## Day 11

### [An animated guide for Node.js event loop](https://dev.to/nodedoctors/an-animated-guide-to-nodejs-event-loop-3g62)

- Conclusion

The event loop, the delegation, and the asynchronous processing mechanism are Node.js's secret ingredients to process thousands of connections, read/write gigantic files, handling timers while working on other parts of our code.

In the article, we saw the vital role of Libuv and its ability to handle numerous potentially long-running tasks. At the same time, we went through the event loop and its role as a bridge/connector between callbacks of asynchronous operations in the I/O event queue and the call stack. In the following articles, we will explore in greater detail how timers, I/O, promises, and ticks are handled by the different phases of the event loop.

## Resources

- [How to design better APIs](https://r.bluethl.net/how-to-design-better-apis)
- [Introducing the New React DevTools](https://reactjs.org/blog/2019/08/15/new-react-devtools.html)
- [Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development)
- [Hacktoberfest: Contributing to React project](https://dev.to/this_mkhy/hacktoberfest-contributing-to-react-project-2b47)

## Devcards

Apparently, I have a few DevCards.
Depends on which gadget I use to read the article! 🤭

- [AshM10 devcard](https://api.daily.dev/devcards/26e912bd15b04e0cafe61d4b06b64bc7.png?r=xda)
<a href="https://app.daily.dev/AshM10"><img src="https://api.daily.dev/devcards/26e912bd15b04e0cafe61d4b06b64bc7.png?r=xda" width="400" alt="Asther Marie Moreno's Dev Card"/></a>

- [AshM10 devcard](https://api.daily.dev/devcards/ac17d32f6d6740bfadf6867807a9e2a0.png?r=qk1)
<a href="https://app.daily.dev/AshM10"><img src="https://api.daily.dev/devcards/ac17d32f6d6740bfadf6867807a9e2a0.png?r=qk1" width="400" alt="Asther Marie Moreno's Dev Card"/></a>
