--Readme document for *YOUR NAME*, *YOUR_EMAIL@uci.edu*--

A reminder on academic integrity, as described in the syllabus.

In general, the course staff expects that you will look at code and examples from many online resources as part of the assignments, particularly to resolve syntax and understand frameworks. We expect that you'll use other libraries you find, and will even require it in some assignments. These practices are often critical to the work of developers today. The best developers are adept at interpreting the examples they see, customizing them to their specific situation, and citing their sources so they can find them later. We expect you to do the same.

While learning from examples is encouraged, attempting to pass an existing project or example from the web as your own is not allowed. If you ever have a question about what is or is not appropriate, feel free to ask the course staff!

Talking to classmates about class material, assignment requirements, etc. is a great way to verify ideas and get feedback. But this distinctly does *not* permit attempting to pass off someone else’s code as your own. Talking over ideas and approaches is allowed, but the work that you produce and submit must be your own.

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

10/10
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What (a) basic features, (b) CSS features, and (c) advanced features did you include in your portfolio?

(a) Basic features
Both of the home and experience pages are connected with the navigation bar at the top. Each page has a header. main, section, and a footer to help
organize some of the content. The home page comes with my headshot (polaroid) and a bio about my interests and what I currently work as.
For the experience page, there are three recent roles with a very short description of what I did, the dates, the role, and the name of the company.
The footer on both pages has links to both my email and linkedin. The experience page also features a button that 
brings the user to a pdf of my resume. 
- Images with alt text
- Headings and text on both pages
- Links to my linkedin, email, and resume pdf
- Semantic tags like header, nav, main, section, article, and footer
- Icons from Font Awesome for job icons, interests, and the buttons on the footer



(b) CSS features
I used Google Fonts (Jost and Playfair Display), banners for each page, and some navigation links. The navigation links have a hover animation/state.
I used CSS to make the circular images on the experiences page. 
- Custom navigation links
- Bootstrap btns
- Google Fonts




(c) Advanced features
I added a navigation bar that shows the active state/current page. I also added nested selectors like job-section h2. 
Since the assignent calls for me to consider other device and screen sizes, I used Bootstrap's grid layout that automatically
rearranges items on different screens, like on Figma. I also use utility classes to align items on my portfolio.
- Navigation bar
- Nested selectors
- Bootstrap grid layout and utility




3. Did you ignore any of the warnings or errors presented by the accessibility checker? If so, why does this not seem like an accessibility concern? If it's useful, you can consolidate your thoughts on multiple warnings/errors if the rationale is similar.
AChecker didn't report any known or likely problems for both pages, but there were a couple potential problems.
I decided they weren't real accessibility issues.
Below are some potential issues:
- Job images: The icons I used for my experiences has pictures, and the pictures don't convey any 
information that isn't already in the text. Each image already has alt text.
- Scripts: I only used Font Awesome, which loads the icons, and there's nothing to interact with.
There's no animation and it doesn't use color to communicate anything.
- Long alt text: The checker flagged that I had a long alt text for my headshot, but I wanted it to be descriptive since it describes the author (me).



4. How long, in hours, did it take you to complete this assignment?
I would say it took me around 10-15ish hours to complete this assignment? I only really had Figma experience beforehand, 
so HTML and CSS is completely new to me. A lot of the time taken to complete this assignment was just me rereading the lecture slides. 


5. What online resources did you consult when completing this assignment? (list specific URLs, describe queries to Generative AI, or use of AI-based code completion)
For specific tools:
- Bootstrap: https://getbootstrap.com/docs/5.3/getting-started/introduction/
- Font Awesome: https://fontawesome.com
- Google Fonts: https://fonts.google.com
- GitHub Pages: https://pages.github.com

Generative AI (Claude):
I used Claude to help with styling and debugging.
I asked Claude to:
- Stylize my experience section to have individual sections for each of my roles, with icons and images of the job.
- Add a hero banner
- Add a navigation bar
- Teach me how to center my text and headshot, and how to move elements around
- Teach me how to add borders and buttons
- Find any bugs in my HTML and CSS, such as unclosed div tags, any missing ">", and any other syntax errors
- Clean up my HTML and CSS files, merging any old and unused code
- Explain to me what exactly media queries are and how to make the page responsive

Images used:
Peter the Anteater: https://www.oit.uci.edu/files/2022/07/R22_OIT_UndergraduateAnteaterfortheOITHomepage_Icon_1000x1000.png
Mentor Global Consultants Logo: https://media.licdn.com/dms/image/v2/D5622AQFRhdQpxCL4oA/feedshare-shrink_800/feedshare-shrink_800/0/1706425326269?e=2147483647&v=beta&t=lom60Tz-PLKjvmfD_fZ-R7Z0UTm28nTxLe8sUyngRn0
Skechers corporate: https://about.skechers.com/wp-content/uploads/2021/10/INTL50759_330ExpansionImageUpdates_21_08_30_330_BUILDING_NIGHT_SHOT_1_Crop2-Retouched-scaled-e1633550040283.jpg
Home page banner: https://i.pinimg.com/1200x/73/9f/42/739f421bd8f07e7cea297cc5c34dc8c1.jpg
Experiences page banner: https://i.pinimg.com/736x/37/db/c8/37dbc8980f3d9a957a98f27224b1db31.jpg




Any changes made by Claude I tested myself using Live Server.


6. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
N/A.


7. Is there anything special we need to know in order to run your code?

