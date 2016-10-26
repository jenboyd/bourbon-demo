[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Have a Drink: Layout and Design with Bourbon/Neat/Bitters/Refill

## Prequisites

-   [ga-wdi-boston/html-css-layout](https://github.com/ga-wdi-boston/html-css-layout)
-   [ga-wdi-boston/html-css-layout-study](https://github.com/ga-wdi-boston/html-css-layout-study)
-   [html-css-layout-bootstrap-sass](https://github.com/ga-wdi-boston/html-css-layout-bootstrap-sass)

## Objectives

By the end of this lesson, students should be able to:

- List characteristics of thoughtbot/Bourbon suite of products
- Explain the difference between Bootstrap and Bourbon/Neat/Bitters/Refills
- Identify when you would Bourbon vs Bootstrap
- Serve a bourbon drink (deploy a site using the Bourbon suite)
- Reference the Bourbon/Neat/Bitters/Refills documentation


## Bourbon
Mixin Library for Sass
- Using Sass let’s you simplify your css
- Handles up to date vendor prefixes
- Manages mixins and functions for writing simpler more responsive layout
- Should be something that you use on every project
- Compare to compass
http://bourbon.io/

## Neat
Semantic Sass Grid Framework
- Out of the box responsive
- Does not use extra wrapping divs
- Semantic naming for readability
- Supports break points and media queries
- Directly came from taking over Bootstrap sites
- Grid system for people that don’t like libraries
http://neat.bourbon.io/

## Bitters
Style and Structure Scaffolding System for Bourbon
- Provides structure for managing site styling and elements
- Makes it easy to manage and customize sites that are using Bourbon/Neat
- Gives you a nice looking site that you can easily update and replace components
http://bitters.bourbon.io/

## Refills
Modular Components and Patterns for Bourbon/Neat Sites
- Provides sample design elements that are easy to implement and customize on sites that are using bourbon and neat
- Makes it easy to add common web design elements to your site and follow best practices for layout and design.
- There was a ask for pre-made components with minimal styling that can be easily branded
- Compare to bootstrap and foundation
http://refills.bourbon.io/

## Why were these products created?
Designers and developers want to have a web framework that they can quickly deploy so they can focus on styling and layout of the site that’s being deployed. A common option is Bootstrap, a web framework created by twitter.
While Bootstrap is very robust it also has some major drawbacks

- Bloat - when you’re requiring Bootstrap you’re also adding a large library of design and functionality. A good portion of this is never used by your site.
- Design conflicts - When you’re trying to customize elements in Bootstrap you need to negotiate around the names and behavior of the preconfigured elements. This can lead to unexpected behavior if your elements are automatically inheriting properties from Bootstrap, or if you accidentally use their naming.

## Useful Resources

- About Bourbon/Quickstart: https://robots.thoughtbot.com/quick-start-your-bourbon-and-neat
- Bourbon Smash course from Thoughtbot on Upcase
https://thoughtbot.com/upcase/bourbon-smash
- Neat Semantic Sass Grid - Team Treehouse
http://blog.teamtreehouse.com/introduction-neat-semantic-sass-grid
- Styling a Middleman Blog - Thoughbot
https://robots.thoughtbot.com/middleman-bourbon-walkthrough
- Bourbon Neat: Semantic Unopinionated Responsive Grids - tuts plus
https://webdesign.tutsplus.com/articles/bourbon-neat-semantic-unopinionated-responsive-grids--cms-24853
- Bourbon, Bitters, and Neat - Tower
https://www.git-tower.com/learn/bourbon-neat-bitters/in-practice/grid
- How to make your CSS awesome with Bourbon, Neat, Bitters - Codecourse
Has an interview with Kyle from thoughtbot
https://www.youtube.com/watch?v=8ItNE_DX6Cc
