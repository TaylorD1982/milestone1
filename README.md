<h1>The Weavers</h1>

<p>The Weavers are a five-piece from Edinburgh who formed in 1963. They have a loyal following and are also available for private 
functions.</p> 

<p>This purpose of this project is to construct a website that has a nice, simple form and is user-friendly whilst providing 
the content required by both existing fans of the band and prospective clients looking to hire the band for a private function. It is 
easy to find details of the latest news, shows and photographs as well as contacting the band directly.</p> 

<p>Whilst the website will be regularly updated, the band has additional content on various Social Media platforms. The site therefore 
contains simple to find links to these external sites.</p>  

<p>Finally, I include a testimonials page where prospective clients can see some of the great feedback that the band has received 
from those that have previously hired the band to play for them.</p> 

<h2>UX</h2>

The website is for existing fans of the band, new fans who want an introduction to their material and prospective customers who wish to book the band for a function such as a wedding or birthday. 
The site has a very simple and clean layout. There is a navigation par on every page provide clear links to listen to some of the bands tracks, see photographs of The Weavers in action and read the latest news. The final two pages allow you to read testimonials and send an enquiry to the band. 
The ability to contact the band is a key concern and so a second link to the contact page is shown in the footer of the site. 
In terms of the look of the site, The Weavers are quite a heavy rock outfit and so a dark colour scheme is best suited to their sound. It also provides a nice contrast to the psychedelic photos and landing page image of the band on stage. 
Below are three user stories. Each scenario is explored in more detail in the testing section of this document. 
1.	Alistair and Mandy are engaged with a wedding planned for six months’ time. They are fans of rock and roll and want an experienced outfit with a large back catalogue who can also take requests in advance of the big day and during the reception itself. They visit the page and immediately see that there is a page featuring testimonials from previous couples. They are impressed by the feedback and so hit the button in the footer of the site (“Get a Free Quote”) and complete the form with details of the event. 

2.	Lonnie has been a fan of the band since the 1960s. He learned that once of the members of the band was in an accident on stage recently and wants to check on his condition. He visits the site and proceeds to the “News” where he sees a new story confirming that the patient is fine. He also sees that the band has added a new gig to their summer schedule and uses the link to visit an external ticketing site.  

3.	A new fan (Thomas) saw the band at a festival. He wants to listen to some of their hits. Once he has done so, he decides he’d like to hear more and so visits the band’s YouTube channel using the relevant social media link. 
A link to the original design of the site is shown below
ADD LINK
Features
The Header contains a banner image of the band’s logo. 
Existing Features
1.	Feature 1 – In the header are links to six pages (Home, Listen, Photographs, News, Testimonials, Contact the Weavers). On smaller screen sizes, the navbar shrinks to a burger icon.

2.	Feature 2 – The final element of the header are six social media links. These take visitors to the band’s YouTube, Facebook, Twitter, Instagram and Spotify pages. 

3.	Feature 3 – The “Listen” page allows users to listen to five of the band’s tracks as well as watch one of the band’s videos. 

4.	Feature 4 – “Photographs” – This page shows a number of images of the band on stage as well as some shorts of happy, dancing wedding guests. 

5.	Feature 5 – “News” – This page details the latest goings on with the Weavers. Any recently published stories are indicted with an icon. This section also includes any upcoming shows with a link to an external ticketing site. 

6.	Feature 6 – “Testimonials” – In order to attract bookings, the site includes some of the positive feedback that the band has received from their customers along with images of the smiling, happy couples. 

7.	Feature 7 – “Booking form” – This page allows prospective clients to easily contact the band and begin the process of having the Weavers appear at their function. The form is simple to use with instructions included as text within the various sections. 
Features Left to Implement
Upcoming gigs to include additional information such as maps, prices, times, directions. 
Technologies Used
•	JavaScript – The project uses Java script to allow functionality for the dropdown navigation menu. 
•	Bootstrap – The project Uses Bootstrap 4 on the Navbar and Social media buttons
Query this
Testing
The code was tests on validator.w3.org with errors identified and corrected. No errors were identified with the CSS file. 
How the site works on various screen sizes was checked on developer tools in Google Chrome. 
Scenario #1
Someone visits the sight looking to send a query to the band. They choose to do so by clicking on the “Get a Free Quote” button in the site’s footer. 
“Contact the Weavers” form:
1)	Go to the “Get a Free Quote” button in the site’s footer. This takes you to the form page. 
2)	When submitting an empty form, you receive an error message telling you to complete the first field.
3)	When trying to submit a form with no email address (or an invalid address) you receive an error message.
4)	When leaving the message field blank, you receive an error message. 
5)	When all fields are completed correctly, the form can be submitted. 
Scenario #2
Someone visits the site on a mobile device and wants to check on the condition of the band’s injured bassist. 
Navigation bar and “News” page:
1)	The navigation menu appears as a burger in mobile view.
2)	The navigation bar drops down when the burger is tapped.
3)	The visitor selects “News” and is taken to the relevant page.
4)	The visitor scrolls down to the foot of the page and can click on the “Book a Ticket” button
Scenario #3
A visitor comes to the site and clicks on the “Listen” tab. After listening to the video and the tracks on that page the visitor wishes to listen to further material on the band’s YouTube page. 
Social Media Links:
1)	The music video on the “Listen Page” plays the video for Daydream Believer
2)	The five audio clips function correctly.
3)	The link to the band’s YouTube channel functions correctly. 
How the site works on different screen sizes: 
The navigation bar shows all pages on desktop view. This collapses to a burger on smaller screens (mobile phone and I Pad). 
The social media links remain visible on all screen sizes. 
The footer elements (the band name and the button to the contact form) are side by side on the footer and appear on top of one another on smaller screens. 
On the desktop view, the “home” page has a wider image in the body of the site. This image is narrower for screens of a smaller width (I Pad and Cell phone) in order to avoid white space at the foot of the page. 
On the “photographs”, “listen” and “testimonials” pages the content appears side by side on desktops and stacked above each other on smaller screens. 
On the “Contact the Weavers” page, the width of the padding is less on smaller screens in order to avoid the content being too vertical on mobiles and tablets. 
Bugs identified during testing: 
There were no fatal bugs identified during the testing but validator.w3.org identified a few issues with syntax (the Bootstrap JavaScript links were incorrectly positioned, and images had no alternative).
Deployment
The project has been deployed on GitHub Pages. A commit was done for each page once originally created with additional commits as functionality was improved / added. 
For the site to function correctly when published from Github, it was necessary to enter settings > Github Pages and change the source to Master Branch. 
I then had to edit each page to that the links in the HTML code were correct for the Github deployment. 

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).
In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
•	Different values for environment variables (Heroku Config Vars)?
•	Different configuration files?
•	Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.
Credits
Media
•	Music files and videos were supplied by Code Institute. 
•	The photos used in this site were obtained from https://pxhere.com/en/tag/549. 
Acknowledgements
•	I’d like to thank those on Slack who assisted me with a few issues when I was unable to find the solutions on Google or by experimentation. In particular Anna Greaves, Anthony O’Brian and my mentor Seun provided valuable assistance and support. 
