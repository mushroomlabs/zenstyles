# Zen - The CSS non-framework

Modern front-end development has developed an amazing set of tools to
make our lives easier. CSS Preprocessors helped solve a lot of issues
that existed with CSS2, it reduced the amount of repetition and it
made it easy to integrate any given style to an existing set of HTML
components. All in all, a lot of progress has been made.

But of course, not everything is perfect. When I started working on
[Hub20](https://hub20.io), I knew that I wanted to have the [checkout
widget](https://gitlab.com/mushroomlabs/hub20/checkout) able to match
the original site look and feel. I wanted to provide one single set of
components with "naked" html, and let the style be defined separately.

After trying many of the current "CSS frameworks", I realized that all
of them required changes in the HTML that I was provided. Why is that?


## Separation of content and presentation was always a good idea. Let's bring it back!


This project is named after [CSS Zen
Garden](http://www.csszengarden.com/), a website that demonstrated
what CSS could do. More importantly, it showed how powerful is the
idea of separating presentation and content. There are hundreds of
unique styles that can be achieved *while requiring no single change
of line in the HTML.*

## Basic principles for Zen

 - Each theme provides ONLY sass files. No Javascript dependencies.
 - Each theme should provide ONLY mixin, functions and variable definitions.
 - This theme is used as the entrypoint for your web application styling.
