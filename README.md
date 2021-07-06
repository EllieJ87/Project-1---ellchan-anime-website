Ellchan_Anime Website - Milestone Project One

This is a website that I created for my personal sketching and drawing works. My website will be used by existing, new, and inspiring artists wanting to find more information about my work.  Each page contains links to my personal sites where they can find more information or follow me on social media sites for up-to-date content.
Users can use my website to contact me directly via the email icon or the contact form to discuss works currently on the site or any collaborations they wish to work with me on.

![GitHub Logo](/screens/title-response.jpg)

UX

My website is for current and potential anime, gaming or drawing fans, who are looking to gain more content and a full library of my work.  My website provides a full overhaul of varied works over the past years, along with this links to my social media sites where they can follow me directly.

I have chosen to style my website in an exceptionally clean flow, I felt I did not want anything in the layout that was too distracting that draws attention away from the artwork.  Making the main pages white with a pop of colours helps draw the eye and keeps the user engaged with the site.  The chosen colour themes were based on the main banner image (these are their hair colours).  The main font used are inspired by a ‘modern’ Japanese feel where the main text is a clean text base that was not difficult for the user to read.  

User Stories

As an anime fan I want to know more about the work the artist’s work and what they had to offer.
Go to the artist site

As a general drawing / sketching fan I want to be able to contact the artist for commission works or upcoming collaborations.

Wireframes

I drew my wireframes using Adobe XD. I have done two wireframes for each page to show my consideration of how to make my website responsive. The links to the files are below:

index.html (xs and sm)
index.html (md, lg and xl)
home.html (xs and sm)
home.html (md, lg and xl)
about.html (xs and sm)
about.html (md, lg and xl)
anime.html (xs and sm) (portfolio pages)
anime.html (md, lg and xl) (portfolio pages)
contact.html (xs and sm)
contact.html (md, lg and xl)

There are some differences between my wireframes and my final website. This was due to visual preferences and feedback received from other users who tested my website.

Features

Existing Features

index.html

Main loading page for site, with a ‘Enter’ button this takes you directly to the main site through the home.html page where you will be able to find all the information and images dedicated to my site.

All Pages
Navigation links - allows users to navigate around my website by clicking each navigation link, which redirects them to the relevant webpage.

Navigation links: dropdown – allows users to navigate my portfolio pages where these are section by category so the user can select which area they wish to view on.

Hamburger button – this is visible on smaller devices; this then has a drop-down menu of all the navigation links to all pages on my website.  The user can click the links to navigate to the relevant webpage.

Social media links - Each link opens a new page with the relevant social media page to my personal social media site, (LinkedIn, Instagram, Twitter, and Facebook).  These links make it easy for users to access my social media profiles from one place. The social media profiles load in a new tab, which allows users to then return to the site. They are displayed to the left in the footer on large to extra-large screens, this is then stacked on medium to extra small screens and is centred.

Portfolio Pages

anime.html / games.html / pokemon.html / animals.html / other.html

Modal with image, title, and brief description of the image - The modal is triggered by clicking the image, this then opens the Modal with the image, title and brief description of the drawing in its own container.

contact.html

Form with submit button - Allows users to contact me for any further information or collaborations they wish to work with me on.  It also gives the user the opportunity to contact me if they like anything they see to have for themselves or any feedback they wish to give regarding any content on the site.

Features Left to Implement

Once I've learnt JavaScript and back-end web development, I will add further functionality to the existing features on my website.

Contact form 'Submit' button action – I will add that the form will be reset after the form has been submitted  I will add further functionality to the 'Submit' button so that it displays an on-screen 'Thank you' message. I will also add functionality for an email to be sent to users to confirm that the form has been received and they will receive a response

Form with submit button on contact.html page - I will add functionality to the 'Submit' button so that it displays an on-screen 'Thanks for booking us!' message. I will also add functionality for an email to be sent to users to confirm that they have booked the band for their event.
Hamburger button - I will add functionality for the burger button to change to a 'X' icon once the navigation links is triggered and displayed.

Portfolio pages – instead of a modal being used when the image is clicked this is to be changed just to the image it self at 100% rate

Portfolio pages (optional) – each image to have it’s own separate page where it has dimensions / price and accurate information on what materials have been used and different media these can be applied on for the user to buy from.

Technologies Used

Adobe XD

I've used Adobe XD to create wireframes of my website before building the actual site.

HTML5

The project uses HTML5 to create the basic elements and content of my website.

CSS3

The project uses CSS3 to add custom styles to the elements and content of my website.

Bootstrap v4.5.2

The project uses Bootstrap v4.5.2 to add a responsive grid system, prebuilt components, plugins built on jQuery, and Bootstrap styles to my website, before adding my custom styles.

jQuery

The project uses jQuery to simplify DOM manipulation. This is the standard jQuery that is built with Bootstrap
components.

JavaScript

The project uses JavaScript from Bootstrap which is required to add functionality to some of Bootstrap's components.

Google Fonts

The project uses Google Fonts to style the text and suit the style of the band.

Font Awesome

The project uses Font Awesome for the social media links and the hamburger button on my website.

Atom

I've used Atom as the development environment to write the code for my website.

Git

I've used Git as a version control system to regularly add and commit changes made to project in Atom, before pushing them to GitHub.

GitHub

I've used GitHub as a remote repository to push and store the committed changes to my project from Git. I've also used GitHub pages to deploy my website in a live environment.

Testing

Testing User Stories

I used my user stories and documented each of the steps that each user would need to accomplish what they have stated. Below is the link to the document that contains this information:

Testing User Stories

Responsive Testing

I used Google Chrome's Development tools to constantly test each change that I made to my website and to ensure that it appeared in the desired way on different screen sizes. I also tested my website on different screen sizes (mobile, tablet and desktop) to ensure it appeared in the desired way on different devices.

I used my own phone to test the orientation and how the site differs from portrait to landscape and to get a feel on the user experience.

To test my whole website, I went through each page, feature by feature, and documented the results on a spreadsheet. The spreadsheet also documents any responsive features and confirms that they work and appear as intended on different screen sizes. The link to the spreadsheet it below:

Testing Checklist

HTML and CSS Validation

I used the W3C HTML Validator tool to validate my HTML code.

I used the Autoprefixer tool to validate my CSS code.

I used the compressjpeg tool to ensure all my images were a load friendly size.

Interesting Bugs or Problems

First Draft of Website – notes for improvements

Index.html (Bootstrap framework not used)

Image was becoming central on the screen when being re-sized.

Title was fixed at the top and was not re-positioned when the screen was re-sized.

Title text was too heavy and not clean enough.

Enter button was fixed at the bottom of the screen, this was not being scaled / re-positioned when the screen was
re-sized.

Home.html (Bootstrap framework not used)

Banner image was not re-sized through screen sizes

Navigation bar was too big, even when the screen was re-sized.

Navigation bar was not fixed at the top but just at the side so scrolled with the main content.

Main text became too small and unable to read on smaller screen

Social media icons overlapping and not spaced evenly out, due to SVG’s being used and unable to easily style and position.

Second Draft of Website – Using Bootstrap framework

Banner Image

As the banner was fixed at the top, to optimize the layout in landscape testing to hide the banner image so more content was visible when this was scrolled this led to a re-shuffle of the navigation bar layout and fixtures.

Resolved: this was removed in the end, and the banner to be unfixed to enable the user to see more content.

Navigation Bar

Originally navigation bar to be a fixed element which was on the left side under the website title, in a vertical orientation for xl & lg screens.  This then repositioned into a horizontal orientation under the website title in md screens.  This became difficult for placement on smaller screens due to this being a fixed element, did not have a full flow to the website, did not have a fluid experience.

In the vertical position when fixed this was hiding / disturbing the main content so users were unable to navigate select items or fill in the contact form with ease, this due to being in a ‘header’ tag in fixed position and took up the full container width.

Burger Icon (for smaller screen sizes sm & xs) – Position underneath the title, did not have fluid movement for smaller screens due to placement this did not have a fluid or consistent placement, this made navigating the main content inconsistent due to this placement issue.

Ensuring the nav bar was on top, dropdown menu became transparent, and content was visible behind.  This was due to the nav bar being behind the content and

Resolved: To be a horizontal navigation on the right hand side and to be sticky when scrolled so the user can have more visibility of the content rather than the ‘filler space’ i.e the banner.

Portfolio Pages

Modals

Different code used to try different elements, did not link the right image when the modal was loaded this was due to not amending the ‘data-target’ and ‘id’ to the same name as this was not linking through.

Testing to amend the background colours and text colour to match the background image colour, to ensure the correct element part was targeted.  This then ran on all modals for consistency.

Resolved: All images and modals are linked correctly with the correct stylings applied.  To look into a more stream line way to expand the images rather than relying on modals.

Footer & Social Media Links

Were not stacking on top of each other and to be central, just by using the grid element in bootstrap, additional media queries were used to amend this break point styling to ensure the content was visible and user friendly.

Deployment

The hosting platform that I've used for my project is GitHub Pages. To deploy my website to GitHub pages, I used the following steps:

Loaded the terminal window in my Atom workspace.

Initialised Git using the git logo (bottom right hand corner).

Files that have been amended are automatically listed in the ‘Unstaged Changes’ header

Click the ‘Stage All’ icon which drops into the ‘Staged Changes’ display

Add comments in the ‘Commit Message’ section and click ‘Commit to Main’

Once this has been uploaded click the ‘push’ icon

This will add the updated files into the ‘main branch’ option under the ‘GitHub pages’ section

Ran several commits after testing was carried out throughout my project.

Repository Link

https://elliej87.github.io/ellchan-anime/

Running Code Locally

To run my code locally, users can download a local copy of my code to their desktop by completing the following steps:

Go to my GitHub repository.

Click on 'Clone or download'.

Click on 'Download ZIP'.

Once downloaded, extract the zip file's contents and run my website locally.

Credits

All media work has been drawn / sketched by myself for the sole purpose to share my work with other artists / anime and gaming fans.

Acknowledgements

A special mention to my mentor, Sunny Hebbar, for his feedback on my project's scope and design, and for hints on what information to include in my README.md file and what areas to look out for when resolving bugs / issues.

A special mention to my former mentor, Sophie Wickham, for helping me in the early stages and putting up and initial concept in mind for my first project.
