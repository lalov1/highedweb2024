# What's new with CSS

Interop is a cross browser standard for all browsers to work on the same things

- Baseline - web.dev/baseline

## CSS Nesting

- Similar to SASS
  - Can't use an ampersand
  - Can nest a media query

## Range Syntax

    - New way to do media breakpoints
    - @media (600px <= width <= 800px)

## align-content

    - easier to center things without Flexbox

## :not()

    - Not within the parenthesis

## :is()

    - Anything within this query is what we want you to select
    - :is(section, article, aside) :is()

## :where()

    - li:where(:not(.d=foo, .bar))

## :has()

    - figure:has(figcaption)

## View Transitions (Chrome only)

    - Animation from one page to the other

## Scroll-driven Animations (Chrome only)

    - Progress bar at the top - scroll()
    - Fade in image - view()

## scroll-snap

    - Snaps into place
    - Could snap at start, center or end

## Cascade layers

    -

## Subgrid

    - child inherits parent

## Container queries

    - Needs a container type
    - Could name container

## popover

    - modal elements
    - add attribute of popover to a div

## dialog

    - could animate pop in of dialog
    - Could animate background

## @media scripting

    -
