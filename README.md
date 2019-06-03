<h1>The Weavers</h1>

<p>The Weavers are a rock group from Edinburgh who formed in 1963. They have a small, loyal following but are looking to attract news fans and followers. In addition to playing festival and venues, the band can be booked for private functions.</p> 

<p>I have constructed a website with an attractive, simple form that has a design and colour-scheme which reflects the band's sound. The site allows visitors to listen to the band's music, watch videos and catch up on the latest news. Whilst the website will be regularly updated, the band has additional content on various social media platforms. The site therefore contains prominent links to these external pages.
  
<p>The site also exists to attract bookings for private functions, such as birthdays and weddings. To this end, there is a section of the site featuring testimonials from satisfied customers. There is also a contact form, allowing visitors to contact the band and request a quote for their own event. </p>  

<h2>UX</h2>

<p>The site has a very simple and clean layout. There is a navigation par on every page allowing visitors to listen to some of the band's tracks, see photographs of The Weavers in action and read the latest news. The final two pages allow you to read testimonials and send an enquiry to the band.</p> 

<p>The ability to contact the band is a key concern so a second link to the contact page is shown in the footer of the site.</p> 

<p>In terms of the appearance of the site, The Weavers are a heavy rock and roll outfit and so a dark colour scheme is best suited to their sound. It also provides a nice contrast to the splashes to colour in the photographs and landing page.</p> 
  
<p>Below are three user stories. Each scenario is explored in more detail in the testing section of this document.</p> 

<ol>
  <li>Alistair and Mandy are engaged to be married. Their wedding is in six months’ time. They are fans of rock and roll and want an experienced outfit with a large back-catalogue who can also take requests in advance of the big day and during the reception itself. They visit the page and immediately see that there is a page featuring testimonials from couples who had the band play at their reception. They are impressed by the feedback and so hit the button in the footer of the site (“Get a Free Quote”) and complete the form with details of the event.</li> 

  <li>Lonnie has been a fan of the band since the 1960s. He learned that once of the members of the band was in an accident on stage recently and wants to check on his condition. He visits the site and proceeds to the “News” where he sees a 'new' story confirming that the bassist is doing well. He also sees that the band has added a new gig to their summer schedule in his home town and uses the link to visit an external ticketing site.</li>  

<li>A new fan (Thomas) saw the band at a festival. He wants to listen to some of their hits. Once he has done so, he decides he’d like to hear more and so visits the band’s YouTube channel using the relevant social media link.</li> 
</ol>
  
<p>Images of the original design of the site are below</P>

<img width="100%" src="assets/images/Home page.png" alt="The Weavers"> 
<img width="50%" src="assets/images/page 7.png" alt="The Weavers">

<h2>Features</h2>

<h3>Existing Features</h3>

<ol>
  <li>Feature 1 – In the header are links to six pages (Home, Listen, Photographs, News, Testimonials, Contact the Weavers). On smaller screen sizes, the navbar shrinks to a burger icon.</li>

<li>Feature 2 – The final element of the header are six social media links. These take visitors to the band’s YouTube, Facebook, Twitter, Instagram and Spotify pages.</li> 

<li>Feature 3 – The “Listen” page allows users to listen to five of the band’s tracks an view one of the band’s music videos.</li> 

<li>Feature 4 – “Photographs” – This page shows a number of images of the band on stage as well as some shorts of happy, dancing wedding guests.</li> 

<li>Feature 5 – “News” – This page details the latest goings on with the Weavers. Any recently published stories are indicted with an icon. This section also includes any upcoming shows with a link to an external ticketing site.</li> 

<li>Feature 6 – “Testimonials” – In order to attract bookings, the site includes some of the positive feedback that the band has received from their customers along with images of the smiling, happy couples.</li> 

<li>Feature 7 – “Booking form” – This page allows prospective clients to easily contact the band and begin the process of having the Weavers appear at their function. The form is simple to use with instructions included as text within the various sections.</li>

<li>Feature 7 – Clicking on the banner image returns the user to the site's landing page.</li>

</ol>
  
<h3>Features Left to Implement</h3>

I'd like to include another page featuring a list of all of the band's upcoming shows. This page will include additional information such as maps, prices, times, directions. 

<h2>Technologies Used</h2>

<ul>
  <li>JavaScript – The project uses Java script to allow functionality for the dropdown navigation menu.</li> 
  <li>Bootstrap – The project Uses Bootstrap 4 on the Navbar and Social media buttons.</li>
</ul>  
 
<h2>Testing</h2>

<p>The code was tests on validator.w3.org with errors identified and corrected. No errors were identified with the CSS file.</p>

<p>The look of the site on various screen sizes was checked on developer tools in Google Chrome.<p> 

<h3>Scenario #1</h3>

<p>A visitor send a query to the band. They choose to do so by clicking on the “Get a Free Quote” button in the site’s footer.</p> 
<p>“Contact the Weavers” form:</p>

<ol>
<li>Go to the “Get a Free Quote” button in the site’s footer. This takes you to the form page.</li> 
<li>When attempting to submit an empty form, you receive an error message telling you to complete the first field.</li>
<li>When trying to submit a form with no email address (or an invalid address) you receive an error message.</li>
<li>When leaving the message field blank, you receive an error message. </li>
<li>When all fields are completed correctly, the form can be submitted. (as this is a front end only site, you are returned to the "Contact The Weavers" page.</li>
</ol>

<h3>Scenario #2</h3>
<p>Someone visits the site on a mobile device and wants to check on the condition of the band’s injured bassist. The proceed to visit and external ticketing site.<p> 
<p>Navigation bar and “News” page:<p>
  
<ol>
<li>The navigation menu appears as a burger in mobile view.</li>
<li>The navigation bar drops down when the burger is tapped.</li>
<li>The visitor selects “News” and is taken to the relevant page.</li>
<li>The visitor scrolls down to the foot of the page and can click on the “Book a Ticket” button.</li>
</ol>  
  
<h3>Scenario #3</h3>
<p>A visitor comes to the site and clicks on the “Listen” tab. After listening to the video and the tracks on that page the visitor wishes to listen to further material on the band’s YouTube page.<p>  
<p>"Listen" pages and Social Media Links:</p>

<ol>
<li>The music video on the “Listen Page” plays the video for Daydream Believer.</li>
<li>The five audio clips allow the user to listen to snippets of the bands tracks.</li>
<li>The link to the band’s YouTube channel functions correctly, taking the visitor to the external site.</li> 
</ol>  
  
<h2>The performance of the site on different screen sizes:</h2> 
<p>The navigation bar shows all pages on desktop view. This collapses to a burger on smaller screens (mobile phone and tablet).</p> 
<p>The social media links remain visible on all screen sizes.</p> 
<p>The footer elements (the band name and the button to the contact form) are side by side on the footer and appear on top of one another on smaller screens.</p> 
<p>On the desktop view, the “home” page has a wider image in the body of the site. This image is narrower for screens of a smaller width (I Pad and Cell phone) in order to avoid white space at the foot of the page.</p> 
<p>On the “photographs”, “listen” and “testimonials” pages the content appears side by side on desktops and stacked above each other on smaller screens.</p> 
<p>On the “Contact the Weavers” page, the width of the padding is less on smaller screens in order to avoid the content being too vertical on mobiles and tablets.</p> 

<h2>Bugs identified during testing:</h2> 
<p>There were no fatal bugs identified during the testing but validator.w3.org identified a few issues with syntax (the Bootstrap JavaScript links were incorrectly positioned, and images had no alternative).</p>

<h2>Deployment</h2> 

<p>The project has been deployed on GitHub Pages (https://taylord1982.github.io/milestone1/index.html). A commit was done for each page once it was originally created with additional commits as functionality was improved / added.</p> 

<p>For the site to function correctly when published from Github, it was necessary to enter settings > Github Pages and change the source to Master Branch. I then had to edit each page to that the links in the HTML code were correct for the Github deployment. I discovered at this point that Github does not support MP3 and MP4 files. This necessitated a new approach to the "Listen" page. Instead of playing tracks, I embedded the music from Spotify and the music video from Youtube. Unfortunately, Spotify only allows snippets of music and requires you to visit their site in order to hear more. A link to Spotify is included which will allow visitors to do this.</p> 

<h2>Credits</h2>
<h3>Media</h3>
<ul>
<li>The photos used in this site were obtained from https://pxhere.com/en/tag/549.</li> 
</ul>

<h2>Acknowledgements</h2>

<p>I’d like to thank those on Slack who assisted me with a few issues when I was unable to find the solutions on Google or by experimentation. In particular Anna Greaves, Anthony O’Brian and my mentor Seun provided valuable assistance and support.</p> 
