# aWebsite Design System

[Codecademy WEB DEVELOPMENT FOUNDATIONS Challenge Project: Build a Website Design System](https://join.codecademy.com/learn/paths/full-stack-engineer-career-path-b/)

This is my attempt at the challenge project I'm doing for the Web Development Foundations part (Chapter 1-7) of the [Full-Stack Engineer Career Path](https://join.codecademy.com/learn/paths/full-stack-engineer-career-path-b/) I'm participating in at [Codecademy.](https://www.codecademy.com/) Check out the [live site for this project](https://andrekolmeijer.github.io/design-system/) to see the result.

## What I learned

I've been working with [Tailwind CSS](https://tailwindcss.com/) for a while now and went from CSS beginner to using Tailwind almost exclusively pretty qucikly. I wanted to see if the knowledge I gained from working with Tailwind, would carry over working with CSS again. Also I knew how easy it is to predict what Tailwind classes will be, based on the CSS  property names. What I didn't know was that this goes both ways. Working with CSS again was much more of a breeze than I originially remember. In the end though I had to struggle a lot more with specificity writing CSS, than I would writing with [Tailwind CSS.](https://tailwindcss.com/) Also I like that Tailwind takes care of the different user agent stylesheets. What I liked about CSS though was playing around with the `:first-child`, `:last-child` and `:nth-child()` selectors. All in all I feel more comfortable writing both now.

_Also I learned that doing a website design system right takes considerable more time then just checking the boxes and moving on._

Interesting links that helped me gain a better understanding of specificity and how to deal with it in CSS (funnily enough both are actually about [Tailwind CSS](https://tailwindcss.com/)):

- [Tailwind: The Base, the Components and the Utilities](https://darkghosthunter.medium.com/tailwind-the-base-the-components-and-the-utilities-a81137c52534)
- [Using CSS and @layer](https://tailwindcss.com/docs/adding-custom-styles#using-css-and-layer)
- [Reusing Styles](https://tailwindcss.com/docs/reusing-styles)

### One peculiar thing

There is one thing that I ran into that I found quite peculiar in this day and age. Apparently, there is still no `transition` support for the `text-decoration` property. I ran into this when designing the buttons and will have to look into it.

- [CSS transition not working with underline](https://stackoverflow.com/questions/30352431/css-transition-not-working-with-underline)
- [HTML-CSS: Hover underline animation](https://www.w3resource.com/html-css-exercise/html-css-practical-exercises/html-css-practical-exercise-15.php)
- [Hover underline animation](https://www.30secondsofcode.org/css/s/hover-underline-animation/)

## Keep expanding

I want to know if I can work on and come back to a project over a longer period of time. That's why there are a couple of more things I want to add to this the project:

- Make the site responsive
- Add a sticky aside navigation
- Make headings into navigatable links
- Make the colors click-to-copy
- Add a scroll to top button
- Inlcude more of the utility classes I created
- Add animations to the buttons
- Use a code formatter to format my code
- Split the code into multiple files

## The future

Since I am learning Full-Stack development there are a couple of ways I could use what I created for future projects. I do think that for that I would first port it to [Tailwind CSS.](https://tailwindcss.com/) Then I could use it in either of the following or all ways:

### A design template

Built it into more of a re-usable template that I could clone and use to quickly get a new design system figured out. For that button properties and things like that would need to be a dynamic. Tailwind uses a config file for that. Buttons might have to be extracted into an external package and used as a plugin.

### A changelog template

Since I'll be learning React later during this career path, I don't think [Next.js](https://nextjs.org/) is a big leap from there. So I plan on using it to experiment with [Commit,](https://tailwindui.com/templates/commit) a [brand new changelog template](https://tailwindcss.com/blog/2023-04-24-new-changelog-template-and-the-biggest-tailwind-ui-update-ever) for [Tailwind UI.](https://tailwindui.com/)

Looking forward to getting to know GitHub better in the process. Thinking of automatic versioning here, with GitHub Releases & Tags using something like [Semantic Release.](https://github.com/semantic-release/semantic-release) This article illustrates it nicely:

- [Automating Versioning and Releases Using Semantic Release](https://medium.com/agoda-engineering/automating-versioning-and-releases-using-semantic-release-6ed355ede742)

### An Express backend

Later again during this career path, I'll be learning backend with [Express.js.](https://expressjs.com/) I might be able to use it for that as well.
