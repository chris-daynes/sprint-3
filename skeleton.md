#Working with Frameworks: Skeleton.


**What happens to the layout when you resize the screen to less than 550 px. How do you think that works? If you're stuck, discuss with your cohort in Slack.**


Using the Skeleton demo, as the screen size gets smaller the layout changes.
Elements that lined up next to each other on the larger screen size now stack on top of each other.
These elements now take up the full width of the screen view.

This is achieved by a new CSS3 rule called 'Media queries'.
The `@media` rule uses a code block of CSS properties only if a certain condition is true. This is used in conjunction with a grid pattern framework, using media queries to alter the framework as the screen size changes.

Skeleton's media queries are "mobile first" targeting min-width rather than max-width so that up load speed on mobile devices is optimised.
