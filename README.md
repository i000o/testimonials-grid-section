# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Table of contents

- [Overview](#overview)
- [Goal](#goal)
- [Outcome](#outcome)
- [My process](#my-process)
- [Built with](#built-with)
- [Feedback](#feedback)
- [Lessons](#lessons)
- [Take forward](#take-forward)
- [Useful resources](#useful-resources)

## Overview

This task required that I use CSS Grid in the Desktop version in order to tile these testimonial cards. This design also needed to be responsive.

## Goal

My goal here is to practice a more complex CSS Grid and familiarise myself to grow in confidence. I also wanted to implement Sass here, too.

## Outcome

I'm satisfied with the outcome but I did have a hard time getting there. I started with a Mobile-first workflow, and I got that done pretty quickly. That can sometimes lead me into a false sense of security whereby I underestimate how much work is left to finish for the desktop version and I jump the gun. In this instance, I didn't approach my media queries for desktop with enough planning of how the Grid should change dependant on viewport, so I had to backtrack at one time and this was demoralising. Although, it didn't take too long in hours, I found myself circling the same lines of code again and again. I'd like to avoid this in future!

![](./)

:jigsaw: [Live Site URL](https://i000o.github.io/testimonials-grid-section/)  
:pencil2: [Solution URL](https://www.frontendmentor.io/solutions/testimonials-grid-sass-mobile-first-swUthCcCvo)

## Built with

:gear: Semantic HTML5 markup  
:gear: CSS Flex and Grid
:gear: Mobile-first workflow  
:gear: Sass

## My process

:alien: First, I wrote down and planned my HTML elements to figure out the DOM.
:alien: Then, I started to style the Mobile version which was pretty straightforward. I had fun grouping elements and managing to style many at once to increase my speed. For instance, styling all the `h1`'s, all the `p`'s, the cards' individual `margin`/`padding` simultaneously. I love when I get into a flow. I finished the Mobile version in 2 hours, which was encouraging. Then, I was excited to start the Desktop the next day.
:alien: I knew I had to use a Grid layout and was eager to approach this tile layout, where some cards spanned 2 columns/rows and some didn't. I thought it would be good practice. I jumped headfirst into styling the `1024px` media queries, without checking breakpoints for smaller viewports in the range after `320px`, I paid for this later where I had to go back and redo them because I couldn't grasp how the layout changed and which lines of code where impacting and which didn't warrant inclusion.
:alien: Once I'd accepted that I needed to go back and work from the earliest breakpoint again, I tried to keep my code as organised as possible and really understand each line since the document began to get lengthy, I felt. With this, I stopped paying attention to Sass implementation as such, other than nesting. I felt I had to prioritise getting the code right rather than making it super efficient in those moments. That was something I wanted to reflect on later, after I'd problem-solved the responsive Grid.
:alien: One of the ways that I dealt with this heavy problem-solving was to collapse sections of code so I could focus on one at a time without having to constantly scroll through the docuent and lose my place. One of the main prioritise in my work is organisation and focus, because they allow me to do excellent work if I can see the situation clearly. This is what I put my energy into when it came to resolving this responsive desktop version.

## Time taken

:alarm_clock: Mobile: 2 hrs  
:alarm_clock: Desktop: 7.5 hrs

## Feedback

## Lessons

1. Classes cannot start with a digit
2. `src` for image, `href` for links!
3. `background-image`, `background-position-x`, `background-position-y`, `background-repeat` `background-attachment: scroll;`
4. It seems I do have to initiate Sass in the command line when I start a new session `sass --watch input.scss output.css`
5. Plan out your Grid layouts early, much like your HTML, you will save yourself a lot of work by understanding the problem you're tackling thoroughly before you begin. Don't jump into it.
6.

## Take forward

:grey_exclamation: I'd like to start making Sass folders in my directories to keep my repos more organised now that I'm working with more files
:grey_exclamation: Continue using Sass syntax to make your code efficient and clean
:grey_exclamation:  
:grey_exclamation:

## Useful resources

[]()

# order-summary-component

# testimonials-grid-section
