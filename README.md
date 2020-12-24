# Code Institute: Milestone Project 1

## New Gym

The purpose of this project was to design a website for New Gym, a fictional gym based in Newport, Wales. The website was to provide details about the gym and promote the gym facilities to attract new clients and retain current gym members. The website was to fit with the New Gym brand.

### Main Aims
* To create a website that provides a quick and simple way for new members to join the gym.
* To create a website that provides the information needed to attract new members and retain current members.
* To design a website that is both visually appealing and easy to navigate for the wide range of potential users. 
* To create a website that fits with the gym brand colours of yellow, grey, black and white.
* To create a website that provides a good user experience on desktop, tablet and mobile devices.

### User Stories
* I am a local person, who wants to know the opening hours, facilities and price of membership, so that I can decide if I want to become a member of the gym.
* I am a current member, I want to know what classes are running this week and what day and time they are, so that I can decide which I want to attend.
* I am the gym manager, I want a website that looks professional, gives users a range of ways to get in contact with the gym and provides a quick and simple process for new members to join the gym, so that I increase the number of gym members.
* I am a personal trainer, I want to know who currently works at the gym and what services they offer, so that I can decide if I would like to work there.
* I am a local parent, I want to know if the gym has a swimming pool and if they offer swimming lessons, so that my child can learn to swim.

### Wireframes
After listing my main aims and designing the user stories, I first created rough, hand-drawn sketches that showed the basic layout and information that I wanted the website to include.

INSERT SKETCHES

Before I started coding my project, I created wireframes using Balsamiq. I created wireframes for desktop, tablet and mobile devices to decide the layout at different screen sizes. I also used the user stories to add more detail to the website to provide a better user experience.

INSERT WIREFRAMES

### Features
The website has four separate pages: Home page (index.html), About Us (about.html), Membership (membership.html) and Join Now (join.html).
Features consistent across the four pages:
#### Navbar
The navigation bar is consistent across all four pages. It has the logo in the top left-hand side which when clicked returns the user to the home page. On the right-hand side are four navigation tabs linking to each of the four pages. The dark grey colour (#424242) fits with the brand colours and provides a goo contrast for the light-coloured text and logo. The logo is yellow to fit with the brand colours. The navigation tabs are white in colour except the active page that changes to yellow to provide visual feedback to the user to let them know which page they are on.
	The navbar collapses to a toggle button on mobile devices for an improved user experience on smaller screen sizes.

#### Hero image and call to join button
Each page has a hero image, although the image is different for each page to reflect the content of that page. Within the hero image is a callout message (again the message is different for each page to fit with the page content) that includes a ‘Join Now’ button that links to the Join Now page or submits the user’s email and password details on the Join Now page to sign them up.

#### Footer
The footer is the same dark grey colour as the navbar to provide consistency in design. The footer is the same across all four pages. It includes social media links which are coloured yellow to fit with the brand colours. It also provides the copyright information as the footer is the normal place that a user would look for this.

#### Home page:
* Includes a hero image showing the gym equipment.
* Includes a call to action ‘Join Now’ button that links to the Join Now page.
* Includes location, opening times and contact information. I set this against a medium grey background and highlighted the feature icons in yellow to make them stand out and to provide a visual reference to the features, to aid the user’s understanding.
* Includes a background image showing one of the gym classes with the timetable for classes that week displayed over the top of the image.

#### About Us page:
* Includes a hero image showing two gym members meeting a member of the gym team.
* Includes a call to action ‘Join Now’ button that links to the Join Now page.
* Includes a profile picture of the key gym staff members, along with their name, job title and a brief description of how that team member may be able to help the user.

#### Membership:
* Includes a hero image showing the café and seating area facilities.
* Includes a call to action ‘Join Now’ button that links to the Join Now page.
* Includes the different membership package options with prices and included features listed. I set this against a medium grey background and highlighted the membership package icons in yellow to make them stand out and to provide a visual reference to the package options, to aid the user’s understanding.

#### Join Now:
* Includes a hero image showing people exercising.
* Includes a form asking the user to input their email address and to create a password before pressing a ‘Join Now’ button. The email address input only allows an email address to be entered, with a ‘please enter an email address’ error message and highlights the input box with a red border if the input is not an email address. The password input provides a suggested secure password to aid the user in choosing one. It is envisaged that once the user clicked the ‘Join Now’ button that they would then go on to a secure payment process to enable them to sign up to the gym. However, this is outside the scope of this project.
* A telephone contact is provided beneath the form in case the user would rather sign-up via an alternative method, or in case they experienced any issues with the website sign up process.
* Includes quotes from current gym members, along with their names and a small photo of them to provide greater credibility to the reviews which will help to convince the user to join.

### Features changed from wireframes
* On small tablet devices like an iPad, the About Us page profile pictures and job role infor looked too cluttered at third screen width and half screen width. I changed the design so that on small devices the profile pictures were col-12, the same as mobile devices, but included the extra job role info that isn't shown on mobile devices.
* Changed navbar and footer colour to darker grey to make the white and yellow text more readable, whilst still fitting with the brand colours.
* Changed some of the images to higher quality images than didn't pixelate when enlarged.
* Changed all font awesome icons to yellow colour to fit with the brand colours and to make them stand out better to the user.
* Centered the social media icons and copyright information in the footer bar as this looked better on the website.
* Changed the background colour on the main features section of the Home page and Membership page to add colour to the pages and to provide contrast to the icons to help them stand out. Also changed text colour for better readability.
* Removed underline from headings and the website looked better without these.
* Added a white background to the callout message and Join Now button to make it stand out better from the background hero image.
* Changed the position of the callout message and Join Now button to top right of the hero image, to make it one of the first items the user can see on the webpage and so that the user doesn't have to scroll down the page to get to the Join Now button.
* Added a picture to the quotes section on the Join Now page to give the reviews better credibility from the User's point of view. Also removed bold styling of the quote text and made the names a smaller font to improve the visual appeal of this section. 

### Features left to implement:
* If I had more time to improve my website, I would add a page detailing the gym classes available with a description for each class. This could be further improved in the future by adding photos or a video clip to improve the user’s understanding and website experience.
* To improve the website further I could add a proper logo rather than just the name of the gym. This would provide a greater visual appeal and look more professional.
* In the future I could add greater content for new and current members like workout videos or incorporate a fitness blog.
* For a real-life gym, the Join Now form would need to be more detail and link to a secure payment process that allows the user to sign up to the gym and make their membership payments.
* In the future a feature that allowed gym members to book onto gym classes would be useful as well as a member’s log-in area where they could see what classes they are booked to attend.

### Technologies Used:
* HTML5 to create the .html pages.
* CSS to style the html pages.
* [Bootstrapv5](https://getbootstrap.com/docs/5.0/getting-started/introduction/) used for the grid layout to make the website responsive and to style appropriately for different screen sizes, to improve the user experience. I also used the bootstrap templates for the navbar (including the toggle button feature), Join Now buttons and the form for signing up to the gym.
* [Font Awesome](https://fontawesome.com/icons?d=gallery) for the social media icons in the footer; map-marker, phone and clock for the feature icons on the Home page and for the membership package icons on the Membership page.
* [Google Fonts](https://fonts.google.com/) used to style the headings and main text across all my pages.
* [Color Tool](https://material.io/resources/color/#!/?view.left=0&view.right=0&primary.color=212121&secondary.color=FFFF00) used to decide the shade of grey for the navbar, background colour and footer. I also used the accessibility feature to find what coloured text to use with the background for good readability for the user. 
* [W3C Markup Validation Service](https://validator.w3.org/) used to check the validity of my html code for all .html pages.
* [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/#validate_by_input) used to check the validity of my css code in my style.css file.

### Testing
#### HTML Validation
* I used the [W3C Markup Validation Service](https://validator.w3.org/) to check my html code. On the first page I checked (index.html) I had an error message 'Warning section lacks heading' relating to my callout message on the hero image. I changed the callout message tag from a paragraph to a heading 1 and this corrected the error. I updated this change on all of my html pages.
* Another error was raised on my join.html page 'the aria-describedby attribute must point to an element in the same document'. I realised that this related to a part of the form that I had decided to remove (a decalration that the User's email would not be shared with anyone else that I decided to remove to give the form a cleaner look). I therefore removed this part from my code and no further errors were found. 

#### CSS Validation
* I used the [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/#validate_by_input) to check my css code. No errors were found by the validator.

#### Bugs Found
* I used a Bootstrap template for the navbar but when viewed on a mobile device, the navbar did not collapse as expected. The toggle item was hidden and no menu dropped down when clicked. I initially changed my code using the Code Institute Whiskey landing page tutorial as an example, thinking it was a coding error. However, this did not fix the issue. I then researched on the Code Institute Slack channel and found this [post](https://code-institute-room.slack.com/archives/C7J2ZAVHB/p1592942326084700?thread_ts=1592936056.080800&cid=C7J2ZAVHB) from JosV which gave three scripts to add at the end of the body section. This fixed my error.
* Once my navbar was working, I wanted to style the navigation tabs on the navbar to white with the text of the active page in yellow. I also wanted to change the colour of the navbar toggler to fit with the brand theme. I found the bootstrap styling options were either navbar-light or navbar-dark. I removed these styling options and used CSS to style the text colours. This caused the toggler to disappear from the user's view but it was able to be clicked still. I did some internet research into this problem and found this [post](https://www.geeksforgeeks.org/how-to-change-hamburger-toggler-color-in-bootstrap/) on GeeksforGeeks that gave me the code to implement the change of toggler colour. I then edited this code to get the yellow colour I wanted. 
* When viewed on a small tablet device (like an iPad), the profile picture images on the About Us page overlapped. I found this to be because I had set the container size for the images at 400px x 400px and this was bigger than the 1/3 screen width of the Bootstrap grid on a mobile device. I fixed this issue by reducing the container size to 300px x 300px.
* When viewed on a small tablet device, the call-out container was hidden. When I was looking at my code I realised that I had styled for mobile and larger screen sizes but not medium devixes. This made me realise that I could do one responsive style across all devices instead of seperate styling for each screen width. I re-did my code and simplified the css. the result was that the callout message and Join Now form were in the same position on every page (top right of the hero image). Furthermore, this was the same across all device sizes. This provides the user with a more consistent experience across each page and across different devices.
* When viewed on a iPad device I found that there was still a bug with the About Us page profile pictures overlapping. Viewing it on a desktop screen, as I reduced the screen size I could see that there were points at which the profile pictures overlapped before changing col format as the screen sized reduced further. This was why I hadn't picked up the issue before, because it worked on small tablet devices but not at specific sizes like the iPad size. This made me realise that I didn't have enough breakpoint column widths in my code. I added this extra detail to my code so that the layout changed before the profile pictures could overlap to fix this issue.

### Credits
* The text on the website was created by myself.
* The code for changing the navbar toggler came from this [post](https://www.geeksforgeeks.org/how-to-change-hamburger-toggler-color-in-bootstrap/) on GeeksforGeeks.
* The code for the scripts to make my navbar work came from JosV on this [post](https://code-institute-room.slack.com/archives/C7J2ZAVHB/p1592942326084700?thread_ts=1592936056.080800&cid=C7J2ZAVHB).

### Media
The photos used on the website are from the following sources:
#### Home page:
* [Hero image](https://i.pinimg.com/originals/07/d4/ea/07d4ea937079e24490be9f8c8b24cb01.jpg)
* [Class timetable background image](https://static01.nyt.com/images/2017/06/18/nyregion/18FIT3/18FIT3-superJumbo.jpg)

#### About Us page:
* [Hero image](https://www.ihrsa.org/uploads/Articles/Column-Width/staffing_precor-consultation_column.jpg)
* [Kevin profile picture](https://i.pinimg.com/originals/8f/5b/b5/8f5bb59ce014bc08582a7f1d6022e215.jpg)
* [Louise profile picture](https://activedgefit.com/wp-content/uploads/2018/01/Activedge-2018-Headshots-0040.jpg)
* [Charles profile picture](http://totalcitygirl.com/blog/wp-content/uploads/2015/09/NADEEM-30-FINAL-sm.jpg)
* [Tony profile picture](http://www.julianashphotography.com/wp-content/uploads/2018/01/Fitness_Instructor_Headshots_Nash-038.jpg)
* [Claire profile picture](https://d17zfk1skw2aas.cloudfront.net/wp/wp-content/uploads/2016/04/27155825/HeadShotJeanetteJenkins-1024x1020.jpg)
* [Amanda profile picture](http://www.joinforjustice.org/wp-content/uploads/2017/05/megan-headshot.jpg)

#### Membership page:
* [Hero image](https://www.davidlloyd.nl/-/media/david-lloyd/images/clubs/rotterdam-blijdorp/new/dl-blijdorp-restaurant-1440x780new.jpg)

#### Join Now page:
* [Hero image](https://static.onecms.io/wp-content/uploads/sites/35/2017/03/03190846/1200-woman-lifting-heavy-weights.jpg)
* [Katie profile picture](https://crosstownfitness.com/wp-content/uploads/2017/11/amyheadshot-11.jpg)
* [Freddie profile picture](https://isaacinsoll.com/wp-content/uploads/2014/03/kial-gold-coast-personal-trainer-gym-fitness-headshot.jpg)
* [Jenny profile picture](https://blacksheepstudiosnj.com/wp-content/uploads/2018/11/cindy_headshot.jpg)

### Acknowledgements
I received inspiration and guidance through my project from:
* Code Institute mentor Seun Owonikoko.
* Code Institute mentor Akshat Garg whose feedback throughout the project influenced my website design and content.
* Miranda (Github user mkthewlis) whose milestone 1 project was provided to me be mentor Seun as a good example of what I should be aiming to achieve in my own project and therefore provided me with inspiration for my own project. 

