# Martina Zampa Personal Trainer 
## David J. Buchanan's User Centric Frontend Development Milestone Project Submission

Acheive confidence and body positivity through personal training with Martina Zampa. Whether it be as part of a lifestyle change or the continuation of an already satisfied existence, this is your opportunity to get to the next level. By developing a bespoke training package that gives both holistic and focused benefits, Martina will work with you to create and maintain a positive body image. Martina specialises in yoga, HIT and strength training to provide a holistic & bespoke programme for you! 
On this site you can read about Martina's skills and services; get in contact with her; and stay 'up-to-date' with her using the newsletter facility. 

Note: This website provides a portal through which a fictional personal trainer (FPT) advertises her skills and services. In addition the website invites potential clients to contact her in order to solicit 
services and or information via a newsletter. The FPT is based in New York city and as such the site supplies locations as rendezvous points for fictitious products.  

## UX

The webite was designed for the purpose of the Code Institute's User Centric Frontend Development Milestone Project Submission. The brief required a multi-page responsive design that gave the user a positive user experience whilst allowing the to intuitively navigate the site. The inclusion of information, links, imagery and layout were designed to acheive this goal.
The target users are listed below:

<ul>
<li>Type (1) A potential client looking to compare and contrast potential personal trainers for the purpose of soliciting their skills. A visually attractive 'home' page  with a simple callout invites the browser to easily navigate to see skills on the 'about' page; and options on the 'products' page. Thus allowing them to make an informed decision prior to engaging in contact with the FPT.</li>

<li>Type (2) A potential client commited to contacting the FPT in order to establish contact and initiate a professional relationship. Further more this user type would 
want specific information regarding the venues / geographical locations which would be facilitated by the links on the 'services' page.</li>  

<li>Type (3) An existing client looking to establish a social relationship either with the FPT or similar user type as themselve. This would be acheived by accessing the social links at 
the footer of all pages.</li>
</ul>

### Mockups 

Generated on Lucidchart and can be accessed at https://www.lucidchart.com/invitations/accept/a6f68e35-84df-4fbe-8b3d-b2c671013cf8

## Existing Features

<ul>
<li>
Feature 1 - the navbar  
Allows user types 1, 2 & 3 to move between pages. This was designed to look identical on all pages and viewport sizes with the exception of narrow viewports where a
dropdown menu was employed.
</li>

<li>
Feature 2 - the footer
Enables user types 1 & 3 to access newsletter feature by adding their email address and submitting it via the 'submit' bnutton. This feature is sacrificed on narrow viewports 
otherwise looks identical on all pages. The feature is not enabled and the submission of email address data is not recorded. However a modal opens completion of the task for good user experience. 
</li>

<li>
Feature 3 - the footer
Allows user types 1 & 3 to access the social links of the FPT. Clicking on the social media icon opens a new page that links to the respective site. The feature looks 
identical on all pages.
</li>

<li>
Feature 4 - the callout
The homepage has a fullscreen background image with a callout inviting the user to click on the 'products' button inviting user type 1 to browse available products and type 2 
to find detailed information to use products i.e. the addresses of venues.
</li>

<li>
Feature 5 - the testimonials
Purely a visual form of learning for user types 1 to browse
</li>

<li>
Feature 6 - the products
A visual form of learning for user types 1 to browse. User types 2 will click on the links to opens a new page that links to the respective site.
</li>

<li>
Feature 7 - the contact section
User types 1, 2 & 3 can type in their email address and a message to the FPT in the respective boxes and click 'submit' to contact the FPT
</li>
</ul>

### Future Features

<ul>
<li>
Feature 8 - the modal  
Allows user types 2 & 3 to have confirmation that the submission of the contact form and/or newsletter request has been successful by a message popup confirming success.
</li>
</ul>

## Technologies Used

Language types, frameworks and libraries used:

HTML https://www.w3.org/html/

CSS https://www.w3.org/Style/CSS/Overview.en.html

Java Script https://www.javascript.com/

Bootstrap https://getbootstrap.com/

Fontawesome https://fontawesome.com/


## Testing

All testing performed manually on Google Chrome, using the following scenarios:

### Contact form:
Go to the "Contact" page

Try to submit the empty form and verify that an error message about the required fields appears - WORKS

Try to submit the form with an invalid email address, i.e. missing '@', and verify that a relevant error message appears - WORKS

Try to submit the form with all inputs valid and verify that a success message appears. - FAIL (see Feature 8 above)

### Mailing list form:
Go to any page

Try to submit the empty form and verify that an error message about the required fields appears - WORKS

Try to submit the form with an invalid email address, i.e. missing '@', and verify that a relevant error message appears- WORKS

Try to submit the form with all inputs valid and verify that a success message appears.- FAIL (see Feature 8 above)

### Social media links:
Go to any page

Try to click on the link, have a new page open and be directed to the site in question - WORKS

### Navigation bar (large screen or larger):
Go to any page

Try to click on the links and be directed to the site in question - WORKS

### Navigation bar (medium screen or smaller):
Go to any page

Try to click on the 'HOME' link or toggle button (& then links) and be directed to the site in question - WORKS

### Product links:
Go to the "Services" page

Try to click on the link, have a new page open and be directed to the site in question - WORKS

### Responsive Design
The site was tested on the following screen sizes (landscape and portrait (where appropriate))
<ul>
<li>
Apple iPad pro
</li>
<li>
Apple iPad
</li>
<li>
Apple iPhone 5/SE/6/7/8/X/6 plus/7 plus/8 plus
</li>
<li>
Samsung Galaxy S5
</li>
<li>
Pixel 2/2 XL
</li>
<li>
Laptop
</li>
<li>
Desktop
</li>
</ul>


## Bugs 

To date there have been no identified bugs on Google Chrome when inspecting on various viewport sizes. However the following issues were recorded when viewing the deployed site on an actual iPhone 6S

<ol>
<li>
Footer texts deploys over two lines rather than just one on portrait viewport.
</li>
<li>
Services page - background - is too dark and not centered on portrait or landscape viewports.
</li>
<li>
README.md page can open at the top or bottom of the page, meaning the user has to scroll to the top on initially openning the page.
</ol>

## Deployment

Deployment was on Github Pages https://davidjbuchanan.github.io/MS1-Martina-Zampa/

## Credits

### Text 
All content is fictional, the "about" page was inspired by content from the following two pages
http://www.jilleverettpersonaltrainingnyc.com/about.html &
https://www.puregym.com/personal-trainer/rainier-cocozza/.


### Media
#### The photos used in this site were obtained from stock supply sources and from the Code Institute:
Shutterstock https://www.shutterstock.com/home

Pexels https://www.pexels.com/

https://codeinstitute.net/



