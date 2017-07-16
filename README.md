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

# The new asynchrony, understanding async/await

Asynchronous code is here to stay. As javascript is used for more and more
complex tasks, asynchronous code becomes more and more complex. The great news
is that there are tools that make it possible to take that complexity and make
it simple, and they come built-in to ES7 (ES 2016)! This talk will introduce
developers to the async/await features in modern javascript, covering a
foundation in promises and generators. By the end of the talk, developers will
learn some new tricks to tame their asynchronous beasts.

# Test-driven CSS

Your styles should be as high quality as all your other code. You should be able
to easily make changes without introducing regressions, enabling your codebase
to grow with ease. Automated testing and test-driven development facilitate this
for front-end and back-end code, but why not also do it for your CSS?

This workshop will introduce developers to Quixote, a Javascript library for
automated CSS testing. Through the process iteratively designing and building
the styles that make up SpanishDict.com's language learning guide, it will
explore how and why to test CSS both at the unit and integration levels.
Developers will learn how to apply Test Driven Development techniques to the
process of implementing designs as well as how to introduce CSS testing to an
existing code base.

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

# How to bring a project back from the dead

Great modules sometimes become unmaintained. It's a sad aspect of Open Source
and the (huge) NPM ecosystem, but one we often have to grapple with. The great
news is that you as a developer can take that code and get it back to thriving
with determination, planning, and not as much effort as you might think. In this
talk I'll talk about how I took Oboe.js, a library for progressive JSON parsing,
and got it back up to a thriving project with great tooling and an all ES6 code
base.

# Stealth-caching: showing our most expensive feature to 10m users

How do you show the results of a complicated query (that may not have results)
while still keeping fast load times? This was a problem we faced at
SpanishDict.com when we rolled out our example sentences feature to our 10
million unique monthly visitors. In this talk, I will talk through our solution
that leverages client-side rendering for improved performance and caching
through Redis for improved user experience.

# Stealth-caching: como mostrarle el feature más costoso a todos los usuarios

Cómo se hace para poder mostrarle el resultado de un query complicado (el cual
podría no tener resultados) manteniendo un tiempo de carga corto? Éste fue el
problema que tuvimos en SpanishDict.com cuando queríamos mostrarle nuestras
frases de ejemplos a todos nuestros 10 millones de usuarios mensuales. En esta
charla, explicaré nuestra solución que utiliza rendering desde el cliente para
mejorar el rendimiento y caching con Redis para mejorar la experiencia del
usuario.

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
