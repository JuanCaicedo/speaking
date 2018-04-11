# speaking

This repo is a collection of submissions, ideas and talks for conferences.

As I've been trying to get better at techincal speaking and get my first talk
accepted to a conference, I often think about how great it would be to be able
to see other speaker's submissions, notes and talks. I figured why not be the
first, maybe some great speakers will end up doing it too!

# Thanks

I've had a huge amount of help getting started from Jordan Kasper
([@jakerella](https://github.com/jakerella/)), who offered to mentored me just
because he wanted to encourage more people to get into technical speaking.
Couldn't be more thankful! If you ever get a chance to show him some love, you
should.

# Systematized approaches to everyday life

Life is complex, full of uncertainty, and constantly changing. Does that sound
like software engineering? This talk will explore how we can use the methods
commonly applied in programming to other situations in real life, from packing a
bag to having difficult conversations. By examining areas other than
programming, well look at how pre-designed systems can help save mental
bandwidth and make it easier to adapt to the unexpected. By the end, developers
will be able to use these ideas to better create and evaluate software systems.

# Test-driven CSS

Your styles should be as high quality as all your other code. You should be able
to easily make changes without introducing regressions, enabling your codebase
to grow with ease. Automated testing and test-driven development facilitate this
for front-end and back-end code, but why not also do it for your CSS?

This workshop will introduce developers to Quixote, a Javascript library for
automated CSS testing. It will address both traditional stylesheets and
different versions of CSS-in-JS. Developers will learn how to apply Test Driven
Development techniques to the process of implementing designs as well as how to
introduce CSS testing to an existing code base.

## Prereqs

- Bring a laptop with dependencies installed
- Basic knowledge of at least one javascript testing framework
- Basic knowledge of CSS positioning and media queries

## Takeaways

# Critical and tailored CSS

Your page needs to load fast. More importantly, it needs to feel like it loads
fast. Among the worst factors for perceived performance is a user seeing
unstyled content. However, stylesheets for modern web applications quickly
become far to large to load completely before content is rendered to the user.

This talk will describe an approach known as critical css, where you inline
styles required for the above-the-fold content of a page and lazy load all other
styles. It will go a step further by describing the process we use at
SpanishDict.com to generate critical css specifically tailored for each of our
pages in order to include the minimum css required and ease maintenance costs.
At the end of this talk, developers will be able to evaluate the value of
critical css for their own sites and will know the tools required to
successfully implement it.

# Building Command Line Applications, the Node Way

A program becomes much more powerful when it evolves from a simple script to a
full-blown command line application. How to build a good CLA is a skill that
every Node developer should have. However, interacting with your logic through a
command prompt is very different from doing it on the web, and it takes
deliberate thought and consideration to do it well. In this talk, I'll share
what I've learned about creating reusable command line tools from my
professional and open source work. Developers will learn how to leverage their
skills and knowledge from web development to towards creating reusable and
distributable CLA's.

## Outline

* The UNIX philosophy of small modules
* Examples of node CLA
* Advantages of Node
* Development flow for CLA
* Reading command line arguments
* Testing command line utilities
* Explanation of piping and data streaming
* Composing utilites together
* Reading data streams
* Managing back pressure
* Interactive CLA
* How to use exit codes
* Handling error messages
* Visual rendering in terminal with React
* Sharing a CLA
* Frameworks for CLAs
* Disadvantages of node
* Other possible languages and platforms


# Integrating React into an existing application

When you outgrow your client-side architecture, you don't always have the
liberty to build another one from scratch. What if you could move to the latest
and greatest, without throwing out what you've previously built? This talk will
showcase how we did this at SpanishDict.com, by adding a fast, responsive, and
scalable React app into the middle of our server-rendered, jQuery-powered site.
Specifically, we'll cover the topics of code reuse (in js and styling), data
sharing, and integrating a new build process. By the end, developers will be
better able to assess how reimagining their client-side could fit into their
established web apps.

# Digital hygiene

Recent research -has shown that you have a limited quantity of the most crucial
resource: your attention. Yet as a developer, your attention is often pulled in
a hundred different directions. In this talk, we will establish the importance
of minimizing your focus as much as possible and how it can boost the quality of
your work. We'll go through tricks I've learned to avoid letting distractions
get the best of me, ranging from the technical (like using custom notifications
to alert when a CI build is finished) to the everyday (like journaling during
programming). This talk will combine modern psychology, tech, and practicality.
By the end, developers will be better able to identify sources of distraction in
their work and find strategies to combat them.

### Outline
* Why attention is so important
* Why attention is so fragile
* Custom notifications
* Reducing friction for critical tasks
* Psychology of digital space
* Digital organization
* Mindfulness in programming
* Journaling in programming
* The challenge-reward loop and its positive effects
* Maximizing focus through Test Driven Development
* How physical comfort affects concentration
* Using audio to heighten concentration
* Tools that I personally feel help my workflow
* Framework for evaluating whether a tool or process is worth adopting
* Scaling focus to larger teams
