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
