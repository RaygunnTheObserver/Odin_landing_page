# Odin_landing_page

First full landing page practice assignment.

Post-completion notes:
I went beyond the scope of this project in learning how to keep things presentable when resizing the window. Based on the submissions of other Odin students, I see this was meant to be a static full-screen webpage.
I learned, however, that there are some interesting combinations of width and max-width properties along with percentage values that can keep things flexing smoothly.
I also learned that empty divs are to be avoided. I tried to use one as a flex item to inhabit space between two flex items that were mashing into each other. I then found out I could achieve this in a flex-shrink scenario using the gap property as a minimum (found in a reddit comment suggesting also display:grid or simply padding: https://www.reddit.com/r/webdev/comments/109g30g/is_it_bad_practice_to_have_empty_divs_in_my_html/).

In keeping with the scope of the project, I was able to gain a more practiced understanding of flexbox, making use of flex-direction:column and nested flex containers.

As a tandem practice, I learned two things from Flexbox Zombies that were helpful here. 
The first is that flex-shrink:1 is the default value of any flex item.
The second is that justify-content becomes irrelevant in a flex container when any flex item is set to flex-grow:1 or higher because it will eat up all the space that would otherwise be divvied up between items in the container.

I kept getting confused when text-size wasn't doing anything lol. It's /font-size/, my guy, font-size!!