# Legends of Andalor

Legends of Andalor is a website of a real existing symphonic metal band, located in Umeå, Sweden, that has high goals and all the opportunities to reach them.
Tha site is targeted to popularise band music and give more information about band itself, its goals, plans and gets an opportunity
to listen to their music. The audience of a website will be existing fans, coming fans and all the people and organisators of different concerts. Website is a part of an
Electronic Press Kit (EKP).

![Responsive Design](/assets/images/responsive.PNG)

#### [Live website](https://genagrig.github.io/legends-of-andalor/index.html)
#### [GitHub repository](https://github.com/GenaGrig/legends-of-andalor)

## Features

### Existing Features
#### 1. Home page
* Social links
  - At the top of the page users can find links to different social links and music platforms, which provides all the neccessary information about the band, contacts via social networks or links to band music on a popular music services.
  - Social links presented on all pages of a website and contains links to Facebook, Instagram, Youtube Music, Spotify and Apple Music. All the links opens in new tab to allow easy navigation for users.
* Navigation bar
  - Navigation bar is presented on each of eight pages and contents an dropdown menu in "band" section.
  It is responisve and take a form of "hamburger" menu on smaller screens. It contents links to Home page, News, Music, Shows, Band with a dropdown menu of Story and Members, Gallery and Contact.
  - Navigation bar allows users to easily navigate the website and choose information they want to watch at. 
* Five different blocks with images. 
  - They repeats the main menu with only difference that they are not clickable. Right now they take a decorative option at the website and will be removed later, because the main page will be redesigned for better UX and faster loading.
  - The purpose of them was a training of different positioning of elements on the page and making them responsive as well.
* Footer
  - Footer contains only copyright information and has fixed position at page bottom. 

#### 2. News page
* News page contains updatable information, that band will lay out to support their fans with all the important and suitable news and plans in coming future. It can be coming shows, releasing a single or any other information that is connected to a band.
* Some news contains clickable links on an existing pages on a website to make it easier for users to reach the neccessary page.

#### 3. Music page
* Music page contains a widgets to a different players which are connected to a specific music platform. On this page users can find now links to a first band single on Soundcloud, Spotify, AppleMusic and YouTube Music. 
* All widgets has the same size and are fully responsive on different screen sizes.

#### 4. Shows page
* Shows page provides users with an information about coming band shows in form of a horizontal table and clickable links to venue and events on Facebook or other platforms. 
* This table is responsive and take a form of a vertical table on a smaller screen sizes.
* Go To Event button is also responsive and changes on a different screen sizes.

#### 5. Band page dropdown menu
* #### 5.1 Story
  - Band story page is a short information about how band was created and provides users with a little background of band creation process.
* #### 5.2 Members
  - This page contains information about each band member. On the left users can see a photo of a band member and on the right is short information which contains some artist background.
  - Page is responsive and takes a look of a column on a smaller screens sizes. 

#### 6. Gallery
* Band gallery provides photos of a band that are taken at different places, like live concerts or photoshooting sessions. 
* This section shows the active band life and that band is not only take a rehearsals, but makes other important activities as well.

#### 7. Contact
* Contact page contains a form where user can send band an email, using his own email client. To make this user needs to enter his name, email and feedback or message and push "send message" button to initiate opening of an email client. 
* This option may be not convenient to many users, thats why it was added a container beneath which contains two direct links to band profile pages on Facebook and Instagram, where user can write direct message. 

### Features left to implement
* Re-desing of a Home page to make it more attractive, simple and loading faster. 

## Testing
### Functionality testing
* #### Navigation bar
  - Navigation bar was tested on a computer with big 27' screen, laptop, tablet and mobile phones. 
  - Navigation bar becomes a hamburger menu on screen sizes smaller than 1100px, because testing showed that it is the optimal size, when menu do not sticks outside the screen and has maximum width.
  - The hamburger menu stays on top on all pages and is easy to havigate, all links are working.
  - The only problem on a mobile phones is a dropdown menu. It is hard to click on a Members link, because it is quite close to Story and I have not figured how to make a space between this two links wider.

* #### Heading below navigation bar
   - This heading in different variations is presented on each website page and changes three times on a screen sizes below 1100px, 850px and 376px to not override the menu and disturb pressing the menu button.

* #### Main page
  - Five boxes itself are responsive and changes on different screen sizes in width and the center Gallery box falls down below others on screen size below 600px. 
  - The images inside are not responsive and stays on their places despite of box changes. I do not make them responsive and clickable, because it will make the whole project more complex and right now this is not neccessary.

* #### General testing
  - All pages were checked on a tablet and mobile phone for responsive design and successfull working of such elements as:
    - Navigation bar. Every link works and opens in a parent tab.
    - Social media links on the top of the page. Every link works and opens in a new tab.
    - All elements of every page are responsive and shows correctly on a tablet and mobile phones. Margins are correct and nothing extends the screen width or overrides other elements. 
    - Widgets on music page are sized and shows correctly on every screen size.
    - Shows page table and buttons are responsive and easy to read and understand. Button links working and opens in new tab.
    - Band members page is showing correctly in a column style on screens below 800px and mobile phones.
    - Gallery photo rows are collapsing when screen changes size from wide to narrow.

## CSS3 validator results - Pass
<p>
    <a href="https://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss"
            alt="Correct CSS!" />
    </a>
</p>

## HTML validator results
* Known issues - 3 constant errors on all pages about navigation bar (hamburger menu). Errors are unfixed, because changes in code makes the menu not to work properly.
  - [Error Results here](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Findex.html)
  - [Main page results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Findex.html)
  - [News page results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Fnews.html)
  - [Music page results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Fmusic.html)
  / Error issues regarding iframe and using of CSS instead. Tried to change errors removing information from widgets code and adding to CSS instead, which resulted that widget stopped loading and working or was not responsive and was not able to change size.  
  - [Shows page results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Fshows.html)
  - [Band story page results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Fband_story.html) 
  - [Band members page results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Fband_members.html) / Error issues regarding "span" element and "br" element. Removing them makes styling not available in that code that is written. For upgrading the code and keep same design to avoid this errors I have lack of knowledge right now.  
  - [Gallery page results](https://genagrig.github.io/legends-of-andalor/gallery.html)
  - [Contact page results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgenagrig.github.io%2Flegends-of-andalor%2Fcontact.html)

## Usability testing
* To get some feedback I gave link of this site to my band members and requested a code review in a peer-code-review channel in Slack. 
- One feedback was given from Slack channel, saying 
> Hi it looks really good, I'm looking at this on a mobile, just look at the heading on band/members it's a bit too big and preventing me to click on the menu button again to select something else. Well done on completing first project     
- This error was fixed.
- Feedbacks from band members was positive and website was checked on both tablet and mobile phone. No negative issues were concerned and everything was tested and is working as it should on all devices.

## Bugs
No bugs were detected.

## Deployment
This website is published using GitHub Pages. The procedure of deployment is written below:
1. Log in to the GitHub website.
2. Choose the appropriate repository of that project that needs to be published. [My repository for this project](https://github.com/GenaGrig/legends-of-andalor
3. Click on a Settings button in navigation bar above project files.
4. On the left side you will see a list of sorted menus. Find the Pages button in Code and Automation. Push it.
5. On the right side in Build and deployment you need:
  - In Source dropdown menu choose Deploy from a branch
  - In Branch dropdown menu choose "main" then "/(root) and click Save.
6. Page will reload but nothing more happens. Link will not appear at once, wait a while.
7. In a couple of minutes above Build and deployment you will see a statement that "Your site is live at" and a link to your website.

* The site was deployed to GitHub pages, live link is here:
[Legends of Andalor on GitHub pages](https://genagrig.github.io/legends-of-andalor/index.html)

## Credits

Some elements was not covered in HTML and CSS essentials, thats why I searched in Google for some elements, used and adapted code for my purposes. 

### Content
* Social media icons was taken from [Font Awesome](https://fontawesome.com)
* Two fonts that are used on a website was imported from [Google Fonts](https://fonts.google.com)
* Idea for main page structure and some code examples was taken from our course project [Love Running](https://code-institute-org.github.io/love-running-2.0/index.html)
* All the information content was written by author - Genadijs Grigorjevs
* README file was written with a help of Code Institutes documents
  - Code Institute [README template](https://github.com/Code-Institute-Solutions/readme-template)
  - GitHubs [Basic writing and formating syntax](https://github.com/Code-Institute-Solutions/readme-template)
  - README from existing project from [Liga Baikova - Boredom Project](https://github.com/LigaMoon/Boredom-guide/blob/master/README.md)
* New responsive table design and code on a Shows page taken from https://css-tricks.com/responsive-data-tables/, adapted and changed by myself
* Responsive button code on a Shows page taken from https://codepen.io/dlekovic/pen/nNOagr, adapted and changed by myself
* Responsive image code on a Band Members page was taken from [W3SCHOOLS](https://www.w3schools.com/howto/howto_css_image_responsive.asp), adapted and changed by myself
* Code for navigation bar menu to make it responsive was taken from https://www.makeuseof.com/responsive-navigation-bar-using-html-and-css/ , adapted and changed by myself
* Gallery. Code was taken from [W3SCHOOLS](https://www.w3schools.com/css/css_image_gallery.asp), adapted and changed by myself
* Pictures on main page was taken from free web resource [PEXELS](https://www.pexels.com) and own band photo collection

### Media
* All music widgets and links to them was taken from the band page on [Record Union](https://www.recordunion.com). To access links you need to log in to the website and then use the Smart Links or release links to music services. ![Music Links](/assets/images/music-links.PNG)

## Acknowledgements
* Some ideas and inspirations to my band website I saw at [EPICA](https://www.epica.nl/home) webpage.
* I want to thank my mentor Maranatha Ilesanmi for good feedback and advices throught my first Portfolio Project.
* Thank my band members and members on Slack for giving feedback at different stages on project realisation.





