# Personal Wesite
#### Video Demo: https://youtu.be/GM6OowjrB1o
#### Description: This website is for both my final project of Harvard CS50 course and future personal use.
![image](https://github.com/faitinchan/Personal_Website/blob/main/personal_website.png)
## Design Concept
The idea for this personal portfolio website originated from a genuine need to showcase my work experience and technical skills during my job search. Rather than starting from scratch, I saw this as an opportunity to build something meaningful and long-lasting. Drawing on my prior experience with HTML, CSS, and JavaScript, I aimed to create a visually elegant and user-friendly site that not only highlights my past projects but also serves as a maintainable, evolving platform for future growth. This project reflects both practical functionality and thoughtful design, making it a natural extension of my development journey.
## Source of Inspiration
This project was shaped by two key sources of inspiration that significantly influenced both design and functionality.
### 1. [Javascript 30: Flex Panels Image Gallery](https://javascript30.com/) by [Wes Bos](https://x.com/intent/follow?original_referer=https%3A%2F%2Fjavascript30.com%2F&ref_src=twsrc%5Etfw%7Ctwcamp%5Ebuttonembed%7Ctwterm%5Efollow%7Ctwgr%5Ewesbos&screen_name=wesbos)

I had previously built a similar flex panel layout, and revisiting it for this portfolio site gave me the chance to refine it further. Rather than using full-page panels, I adapted the layout to occupy only half the screen, allowing users to engage with other content simultaneously. This required several design decisions, including responsive font sizing and layout adjustments to ensure usability across different devices and acreen sizes.
### 2. [Build a Responsive Timeline with HTML & CSS (No JavaScript) 🕒✨](https://www.youtube.com/watch?v=NVg5g8-gP8M&ab_channel=PIXELPERFECT) by [PIXEL PERFECT](https://www.youtube.com/@PixelPerfectLabs)

This tutorial inspired the design and structure of my Experience page. I adopted the timeline layout as a clean and intuitive way to present my professional history. However, it required considerable customization in terms of color scheme, spacing, and sizing to ensure it aligned with the overall aesthetic and responsive behavior of the site.

Both sources provided foundational ideas that I adapted and extended to suit the specific goals of this long-term portfolio project.
## Tools and Other Resources
For development, I opted for a minimalist setup using **Vim** as my code editor. This choice aligns well with my workflow and environment, as I do all my coding on an **Arch Linux** laptop. Vim's efficiency and lightweight nature make it an ideal tool for focused development.

In the Skills section of the website, I used icons from the open-source [skill-icons](https://github.com/tandpfun/skill-icons) GitHub repository. These icons provide a clean and consistent visual representation of the technologies I've worked with, enhancing the overall presentation of my skillset.
## Reflection & Potential Improvements
There are several areas in this project where I see room for improvement, particularly in terms of code structure and responsiveness.
### 1. Code Reusability & Project Structure
One key area is the repetition across HTML and CSS files. In our Flask lecture, we explored how templating and layout inheritance can help avoid duplicating code by dynamically rendering multiple pages from a single base layout. While this concept is powerful, I initially chose to keep the project static and simple for ease of deployment. Due to my limited experience with hosting, I decided to use **GitHub Pages**. However, I soon encountered limitations related to file structure and routing, which were not ideal for this project. This led me to switch to **Netlify**, which better supports flexible deployment for static sites.

If I had anticipated using Netlify from the beginning, I would have strongly considered using **Flask** as the project's framework. This would not only reduce code duplication but also lay the groundwork for incorporating backend features in the future. Rewriting the project with Flask is something I'm considering for scalability and better maintainability.

### 2. Responsive Design
Another area of improvement is device compatibility. The current design is primarily optimized for desktop and laptop screens. While it works well on larger displays, the user experience on tablets and mobile devices is suboptimal. Enhancing the site's responsiveness through media queries, flexible layouts, and better touch support is a top piority for the next iteration of the project.
