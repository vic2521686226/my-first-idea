# Original idea

“Do It or Not.” When a user chooses a color that matches their mood and tosses the decision coin, the system reveals either “Do It” or “Don’t Do It.”

## Open it and run it

No installation or build step is needed. Open [index.html](index.html) in any modern web browser. On macOS, you can also double-click the file in Finder.
Public link for access: https://vic2521686226.github.io/my-first-idea/

## AI tool used

I used Codex as my AI-assisted coding tool. I used natural-language prompts to describe the visual design, interaction, and changes I wanted to make.

## Selected prompts

“Make the atmosphere peaceful and reassuring rather than stressful.”
“Change the interaction so that it feels more like tossing a coin rather than pressing a button.”
“Use a right arrow for ‘Do It’ and a left arrow for ‘Don’t Do It.’”
“The arrows are appearing in the wrong direction after the coin flips. Please fix the orientation.”
“Make the result use a check mark for ‘Do It’ and a cross mark for ‘Don’t Do It.’”
These prompts show how I gradually translated my design ideas into instructions for AI. Some prompts were relatively abstract, such as describing the desired “atmosphere,” while others became more specific when I was debugging an interaction.

## Reflection

I tested several screen-color combinations to see whether the visual atmosphere matched my intention. The first version used black, purple, and yellow, which created a mysterious mood, but I wanted the experience to feel calmer and more reassuring for people who are uncertain about a decision. I therefore changed it to a lighter, more elegant palette. This showed me that Codex could respond well even to an abstract direction such as “make the atmosphere peaceful,” rather than only to specific color instructions. 
![Color design](assets/color-design.png) 
I also changed the click effect: at first, I imagined a push-button interaction, but later I wanted it to feel more like tossing a coin. The final circular element became something between a button and a coin: it flips and then presents either “Do It” or “Don’t Do It.” Although this interaction communicates the intended result, its visual effect still does not fully achieve the satisfying coin-toss motion I originally imagined. 
![Coin visual effect](assets/coin-visual-effect.png)

AI helped me quickly test visual directions and interaction ideas, but I still needed to decide what user experience the program should create and what level of clarity mattered most. One unresolved problem was the result icon: I wanted a right arrow for “Do It,” suggesting forward movement, and a left arrow for “Don’t Do It,” suggesting stepping back. However, after the coin flipped, the arrows repeatedly appeared in the opposite direction, likely because the icon flipped together with the coin. Even after I tried to describe the problem more precisely, the result remained incorrect. I finally changed the system to use a check mark for “Do It” and a cross mark for “Don’t Do It.” 
![Debug 1](assets/debug-1.png)![Debug 2](assets/debug-2.png)![Debug 3](assets/debug-3.png) 
This process made me realize that my everyday language is not always precise enough for AI instructions. There is a significant difference between describing an idea naturally and giving clear, structured instructions that an AI can translate into an interaction.
