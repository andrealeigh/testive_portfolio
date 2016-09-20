# testive_portfolio

This repo features projects I worked on as a UX/UI designer at Testive, Inc., including two high-fidelity mockups and two wireframes in coded in HTML/SCSS. Below are some notes for each project; they are intended to be read alongside each mockup or wireframe. 

# School Landing Page, Mockup for Testive, Inc.

[School Landing Page Mockup](high_fidelity_mockups/school_landing_page.pdf)

This mockup was for a custom landing page for schools. The primary purpose of this page was to help students sign up to use Testive’s free SAT/ACT software, and the secondary purpose was to help teachers and their students become more familiar with Testive and their paid coaching program.  

The high fidelity mockup was created using Adobe Illustrator. It followed a series of low-fidelity mockups (paper and pencil drawings) and feedback from Testive’s Director of School Partnerships, who worked closely with school administrators and teachers. 

Additional notes:

* UI elements: The alternating navy and white rows are consistent with Testive’s style guide, as are the hex values of navy and orange, the border-radius of the buttons and their all caps text,  and the Testive logo. 

* “Pixel Perfect:” This mockup was not intended to be pixel perfect since this was not in the scope of the project or a common practice at Testive. This means that there are minor spacing and size inconsistencies that were cleaned up during the development phase.

* Sections:
  * Nav Section: The navbar shows the Testive logo, a link to the Testive  software login page, and a link to a contact page. 

  * Hero with Signup Form: 
    * Features a large CTA for students and teachers to create a free account. A student submitting the “sign up” button would be redirected to Testive’s student platform, and a teacher would be sent to Testive’s School Analytics platform (see [School Analytics Mockup](high_fidelity_mockups/school_analytics.pdf)).

    * The map in the background, from The Noun Project, is meant to communicate the message that a school was joining a wider Testive network that spanned across the country. It also visually united the first two rows in the sections (the navbar and the hero) as well as the two columns in the hero (the large text on the left and the form on the right). 

    * The UI of the form fields established new style guidelines. Formerly, form field were encompassed in a rectangle with a 0% opacity background and an orange border. In the mockup, I removed the rectangle and incorporated the form field into the overall design of the hero. 

  * Software Info: Educates the user about Testive’s software with three informational bullet points and a short video. 

  * Prepping for Free: Features three informational bullet points illustrated by three icons. The rabbit icon is a custom icon I made for this  project; the other two are icons I picked from The Noun Project. 

  * Coaching Info: Encourages the user to explore paid coaching programs through Testive. The “learn more” button links to another page describing Testive’s coaching program in detail, and the text below offers a discount to students at this school.

* Future Improvement:
  * Reduce the number of form fields, if possible
  * In Coaching Info Section, change font-weight of text from thin to regular

# School Analytics, Mockup for Testive, Inc.

[School Analytics Mockup](high_fidelity_mockups/school_analytics.pdf), [School Analytics Mockup Extras](high_fidelity_mockups/school_analytics_mockup_extras.pdf)

This mockup was for a new product intended for teachers working with high school students preparing for the SAT/ACT. The purpose of the dashboard was to give teachers the ability to track progress based on a variety of group breakdowns: All students, students from a certain year, and individual students. 

The high fidelity mockup was created using Adobe Illustrator. It followed a series of low-fidelity mockups (paper and pencil drawings) and feedback from a variety of sources, including Testive coaches (who worked with individual students) and Testive’s Director of School Partnerships, who worked closely with school administrators and teachers. 

Additional notes:

* UI elements: The alternating white and navy rows are consistent with Testive’s style guide, as are the hex values of navy and orange, the border-radius of the buttons and their all caps text, the square radio buttons, and the Testive logo. 

* “Pixel Perfect:” This mockup was not intended to be pixel perfect since this was not in the scope of the project or a common practice at Testive. This means that there are minor spacing and size inconsistencies that were cleaned up during the development phase.
 
* Sections:
  * Navbar: Shows the Testive logo, the name of the school, and a place to logout. 
 
  * Sidebar: 
    * Shows which group of students is currently being rendered in the data sections. In the mockup example, the data is filtered to students who are graduating in 2016. The user can also quickly select all students (”all”) or a different year. 
    
    * Clicking on the person icon at the bottom renders a modal that allows the user to choose a specific student (in [School Analytics Mockup Extras](high_fidelity_mockups/school_analytics_mockup_extras.pdf), top right screenshot). 
    
    * The arrow on the top row expands the sidebar (in School Analytics Mockup  Extras, top left screenshot). In the expanded sidebar, a new row appears at the bottom, allowing the user to create a custom group of students. Once “create a new group” is selected, a modal appears (in School Analytics Mockup  Extras, bottom left screenshot).

    * The top navy row prompts the user to type the name of the custom group. There are two ways to search for students: with the search bar, or by scrolling an alphabetical list of all students or students in a certain year. After more than one student is selected, the user clicks the “review” button, and the modal flips from right to left, revealing the review state (in School Analytics Mockup  Extras, bottom right screenshot). Here, the user can review the name and student list of the custom group. The user can either click “edit,” which flips the list back to the first modal, or save, which saves the new group.
    
  * Data Sections: The three main data sections are Performance, Questions Practiced, and Student Engagement. Each section can show SAT or ACT data by clicking the dropdown arrow at the top of each section. 

    * Performance: Shows scores that can viewed in a variety of ways depending on which buttons are selected below the graph and whether “current” or “over time” is selected. In the mockup example, the current math scores are shown, as indicated by the light blue “math” button, the orange “current” radio button, and the title above the graph that changes depending on what is selection. 

    * Questions Practiced: Shows the number of questions being practiced over time in a variety of ways depending on which buttons are selected below the graph. In the mockup example, the graph shows how many math questions are being practiced. 
    * Student Engagement: Shows which students have established a baseline score (i.e., which students have taken an initial full practice test), and which students have practiced in the past week. The two large lists shows the names of individual students and the percentage of total students in the selected category fall into YES or NO. The pie charts also give a quick visual of percentage of students in YES or NO. In the mockup example, 50% of students graduating in 2016 have established a baseline score, while 74% have answered practice questions in the past week. (The percentage in the right student list does not match the percentage in the bottom pie chart. See “Future Improvement” for more examples of how this mockup could be better.) 

* Future Improvement: 
  * Reduce size of drop-down triangle next to “SAT” in the row titles
        
  * Use orange backgrounds and white text for selected buttons (active states)
        
  * Do not use orange for non-selected or non-button backgrounds, or for “data” in the line graph in the “Questions Practiced” section
        
  * Give the nav a little more context (like “George Walton’s Analytics Dashboard”)
        
  * Reverse the direction of the  arrows on the sidebar so that it makes more sense

  * Create an extra row for the “collapse” arrow on the expanded sidebar

# School Landing Page, Wireframe for Testive, Inc.

[School Landing Page Wireframe](wireframes/school_landing_page/index.html)

This wireframe was intended as version 1 of the HTML/SCSS associated with the School Landing Page Mockup (please read the section above for more context of the School Landing Page Mockup). 

Additional notes:

* This wireframe is not responsive. The landing page would only be accessed on school computers and not on smaller handheld devices. 

* After the form is submitted in the hero, a thank you message appears in place of the "sign up" button. In this wireframe, the signup form is not yet functional.
 
* In Software Info section, the gray box is a placeholder for a video that was not yet created. The size the gray box was based on the sizes of similar videos featured on the Testive website. 

* In the Coaching Info section, the "learn more" button does not linked to another page because it did not exist at this time. 
