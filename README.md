# testive_portfolio

This repo features projects I worked on as a UX/UI designer at Testive, Inc., including two high-fidelity mockups, two wireframes in coded in HTML/SCSS, and two screenshots of small projects I made within the Testive MVC framework. Within this README are notes accompanying each project.

# school_landing_page.pdf

School Landing Page, Mockup for Testive, Inc.

This is a high fidelity mockup I created while working as a UX/UI designer at Testive, Inc. The mockup was for a custom and dynamic landing page for schools. The primary purpose of this page was to help students sign up to use Testive’s free SAT/ACT software, and the secondary purpose was to help teachers and their students become more familiar with Testive and their paid coaching program.  

The high fidelity mockup was created using Adobe Illustrator. It followed a series of low-fidelity mockups (paper and pencil drawings) and feedback from Testive’s Director of School Partnerships, who worked closely with school administrators and teachers. 

Here are some notes to accompany the mockup (school_landing_page.pdf):

UI elements: The alternating white and navy rows are consistent with Testive’s style guide, as are the exact hex values of navy and orange, the border-radius of the buttons and their all caps text,  and the Testive logo. 

“Pixel Perfect:” This mockup was not intended to be pixel perfect since this was not in the scope of the project or a common practice at Testive (In other words, Testive was a typical startup with a fast-paced environment). This means that there are minor spacing and size inconsistencies that were cleaned up during the development phase.

Nav Section: The navbar shows the Testive logo, a link to the Testive  software login page, and a link to a contact page. 

Signup Section: The hero of the page features a large CTA for students and teachers to create a free account. A student submitting the “sign up” button would be redirected to Testive’s student platform, and a teacher would be send to Testive’s School Analytics platform (see school_analytics.pdf).

The map in the background is meant to communicate the message that a school was joining a wider Testive network that spanned across the country. It also visually united the first two rows in the sections (the navbar and the hero) as well as the two columns in the hero (the large text on the left and the form on the right). 

The UI of the form fields established new style guidelines. Formerly, form field were compassed in a rectangle with a 0% opacity and an orange border. In the mockup, I removed the rectangle and incorporated the form field into the design. 

Software Info Section: This section educates the user about Testive’s software with three informational bullet points and a short video. 

Prepping for Free Section: This section features three informational bullet points illustrated by three icons. The rabbit icon is a custom icon I made to this  project; the other two are icons I picked from The Noun Project. 

Coaching Info Section: This section is encouraging the user to explore paid coaching programs through Testive. The “learn more” button links to another page describing Testive’s coaching program in detail, and the text below offers a discount to students at this school.

Future Improvement:

        Reduce the number of form fields, if possible
        In Coaching Info Section, change font-weight of text from thin to regular

# school_analytics.pdf, school_analytics_extras.pdf

School Analytics, Mockup for Testive, Inc.

This is a high fidelity mockup I created while working as a UX/UI designer at Testive, Inc. The mockup was for a new product intended for teachers working with high school students preparing for the SAT/ACT. The purpose of the dashboard was to give teachers the ability to track progress based on a variety of group breakdowns: All students, students from a certain year, and individual students. 

The high fidelity mockup was created using Adobe Illustrator. It followed a series of low-fidelity mockups (paper and pencil drawings) and feedback from a variety of sources, including Testive coaches (who worked with individual students) and Testive’s Director of School Partnerships, who worked closely with school administrators and teachers. 

Here are some notes to accompany the mockup (school_analytics.pdf):

UI elements: The alternating white and navy rows are consistent with Testive’s style guide, as are the exact hex values of navy and orange, the border-radius of the buttons and their all caps text, the square radio buttons, and the Testive logo. 

“Pixel Perfect:” This mockup was not intended to be pixel perfect since this was not in the scope of the project or a common practice at Testive (In other words, Testive was a typical startup with a fast-paced environment). This means that there are minor spacing and size inconsistencies that were cleaned up during the development phase.
 
Nav Section: The navbar shows the Testive logo, the name of the school, and a place to logout. 
 
Sidebar: The sidebar shows which group of students is currently being rendered in the data sections. In the mockup example, the data is filtered to students who are graduating in 2016. The user can also quickly select all students (”all”) or a different year. Clicking on the person icon at the bottom renders a modal that allows the user to choose a specific student (in school_analytics_extras.pdf, top right screenshot). Additionally, the arrow on the top row expands the sidebar (in school_analytics_extras.pdf, top left screenshot). In the expanded sidebar, a new row appears at the bottom, allowing the user to create a custom group of students. Once “create a new group” is selected, a modal appears (in school_analytics_extras.pdf, bottom left screenshot).

The top navy row prompts the user to type the name of the custom group. There are two ways to search for students: with the search bar, or by scrolling an alphabetical list of all students or students in a certain year. After more than one student is selected, the user clicks the “review” button, and the modal flips from right to left, revealing the review state (in school_analytics_extras.pdf, bottom right screenshot). Here, the user can review the name and student list of the custom group. The user can either click “edit,” which flips the list back to the first modal, or save, which saves the new group.

Future Improvement: 

        Reduce size of drop-down triangle next to “SAT” in the row titles
        
        Use orange backgrounds and white text for selected buttons (active states)
        
        Do not use orange for non-selected or non-button backgrounds, or for “data” in the line graph in the “Questions Practiced” section
        
        Give the nav a little more context (like “George Walton’s Analytics Dashboard”)
        
        Reverse the direction of the  arrows on the sidebar so that it makes more sense

        Create an extra row for the “collapse” arrow on the expanded sidebar
