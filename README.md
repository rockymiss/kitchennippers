 <p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642702127/kitchen-nippers/kitchen-nippers-logo_fevkgk.png"></p>


# Table of Contents

1. [Kitchen Nippers](#kitchen-nippers)
    -  [Who is this for?](#who-is-this-website-for-and-what-does-it-do)
2. [User Experience](#user-experience)
    -  [Users Perspective](#from-a-users-perspective)
    -  [Users Fulfilment](#users-fulfilment)
3. [UX](#ux)
    -  [Strategy](#strategy)
    -  [Scope](#scope)
    -  [Structure](#structure-plane)
    -  [Skeleton](#skeleton)
    -  [Surface](#surface)
        - [Colors](#colors)
        - [Typography](#typography)
    -  [Future Implementation](#future-implementation)
    -  [Technologies Used](#technologies-used)
    -  [Resources](#resources)
    -  [Testing](#testing)
        -  [Local Testing](#local-testing)
        -  [User Testing](#user-testing)
        -  [Browser Testing](#browser-testing)
        -  [Validators](#validators)
        -  [Responsiveness](#responsiveness)
        -  [Lighthouse](#result-chrome-desktop-lighthouse)
        -  [Webpagetest](#result-webpagetest)
        -  [Color Contrast Test](#color-contrast-testing)
        -  [Issues/Bugs Fixed](#issuesbugs-fixed)
        -  [Issues Unresolved](#issues-unresolved)
    -  [Version Control](#version-control)
        -  [Git & GitHub](#git-and-github)
        -  [Deployment](#deployment)
    -  [Acknowledgements](#acknowledegments)

        
    
# Kitchen Nippers

For my **Portfolio 1 Project** on the **Code Institute's Diploma in Software Development (E-commerce Applications)** course I have created a fictional website called Kitchen Nippers that teaches children and their adults how to cook together. 

Please click [here](https://rockymiss.github.io/kitchennippers/) for link to the website 

The Design has been focused to **Desktop** first and **Responsive**

![alt text](https://res.cloudinary.com/rockymiss/image/upload/v1642702153/kitchen-nippers/multi-device-mockup_sc3qbw.png)

-----
## Who is this website for and what does it do? 
-----

Kitchen Nippers is for adults and children that teaches them how to cook together using simple recipes that everyone will eat and are easy to make.  It's targeted at parents who want to spend more time with their children in the kitchen but may not have a lot of time to go through difficult recipes with them. Kitchen Nippers is entirely online with a view to expanding in the future.  For the purpose of this Portfolio Flatbread is the recipe the website is focusing on for January 2022. 

-----
## User Experience
-----

### From a User's Perspective
As a user it is important: 

1. that it is easy to navigate the site.
2. to learn an easy recipe to make with their child.
3. that the website doesn't require a lot of time to find what they want.
4. that the instructions are clear.
5. that everything that is needed is listed.
6. to find out more about the company and other recipes they may have.

### Users Fulfilment

1. In order to guide the user to what they want the navigation, footer and content are laid out in a clear way.
2. the user can find the recipe that is suited to a level for a child or beginner-adults learning how to cook.
3. The recipe can be found on all pages through navigation links or buttons.  As there is only one recipe there is no need to search.
4. Clear instructions are laid out in the recipe page together with a video for assistance.
5. Everything including the cooking implements are included in the recipe section.
6. The idea is that the user can sign up to a monthly newstletter which will give them access to past and future recipes and more tips to learn how to cook.

-----
## UX 
-----

### Strategy 

The website is created to get adults and children cooking together using simple yet effective recipes.  Once a month an easy recipe is posted with clear instructions and an opportunity is there to sign-up to learn more and to get more recipes.   Only one recipe a month is posted.  It is hoped that users like the site, it's ease of use, the easy recipes posted and that they come back each month for a new recipe.

The main aim is that the adults have very little to navigate to get to the instructions and the recipe, there is less to read, and the layout is simple so there are little to no distractions. 

### Scope  

Features are set up to be simple, welcoming and easy to use.  The main existing features are: 

- Logo
    - The Logo for Kitchen Nippers is located on all pages and will link back to the home page when clicked. 
    
- Navigation
    - The navigation menu is located on all pages below the Logo.  It contains links to all of the pages on the website and they are fully responsive.   A text shadow is used so that the text will glow/shine on the page that is active to show the user which page they are currently on. 

- Footer Social Media Links 
    - The Footer is located at the bottom of every page and links to Facebook, Instagram, Youtube and Twitter.   The Instagram and Youtube links will link directly to the video on how to make Flatbread. 

- Buttons
    - There is a button to "Get Cooking on the Home Page and on the Sign-up page for ease of use.  

### Structure Plane

There are 4 different pages on this website: 

- Home page:  
  This is the first page the user will see.  It's designed to give a clear direction of what the website is about.  An overlay is placed over the main image with the words "Learn to Cook with Kitchen Nippers".  The main image was chosen as it was primarily a parent cooking happily with their child which gives a very good idea of what the site is about.  Beneath the image there is an about section telling the user a little bit about Kitchen Nippers.  A "Get Cooking" button is featured at the bottom of the page which will bring the user directly to the recipe page.      

- Recipe Page:  
  This page lets the user know about the recipe for the month which is Flatbread for January 2022.  Clear instructions are given, a list of ingredients and tools required and an instructional video on how to make Flatbread.  Recipe pages on websites can be sometimes complex and full of information users do not want to know about.  The recipe page is designed to get to the point quickly as the users being targetted are parents who generally have very little time to read about the history of Flatbread or the lives of the people showing you how to cook it! 

- The Sign-up page:  
  The Sign-up page allows the user to sign-up to monthly newsletters which will give them access to past recipes and hints and tips on cooking.  It is a straightforward form asking for the users name and email address.   **It is important to note that for the purpose of this Portfolio that the sign-up page is a dummy page and the action 'GET' was used instead of 'POST'.**  

- Thank you page:  
  Once the user submits the form on the Sign-up page they will be redirected to this page thanking them.  It is beneficial for users to know if they have completed forms correctly and this will give them an indication that they have filled out the form correctly.  

### Skeleton 

The design was focused to desktop first but can be used on smaller devices such as tablets and mobiles too.  Wireframes are done using balsamiq:  

##### Index

![alt text](https://res.cloudinary.com/rockymiss/image/upload/v1642761921/kitchen-nippers/index.html_vdbciv.png)

##### Recipe

![alt text](https://res.cloudinary.com/rockymiss/image/upload/v1642702153/kitchen-nippers/recipe.html_ivgosz.png)

##### Sign-up

![alt text](https://res.cloudinary.com/rockymiss/image/upload/v1642702153/kitchen-nippers/sign-up.html_utxa3z.png)

##### thank-you 

![alt text](https://res.cloudinary.com/rockymiss/image/upload/v1642702153/kitchen-nippers/thankyou.html_iaxxjv.png)


### Surface  

##### Colors 

The following palette of colors were chosen as they were clean, welcoming and easy to read: 

![alt text](https://res.cloudinary.com/rockymiss/image/upload/v1642702153/kitchen-nippers/color-palette_ihhogz.png)

#/rgb(22,57,80) - for navigation menu, footer menu and buttons. 
#/rgb(167,182,199.08) - for overlay circle  
#/rgb(167,182,199) - for hover over links 
#/rgb(22242,244,248) - for background to text sections 
#/rgb(255) - for website background and text on navigation, footer and buttons.  

##### Typography

For the logo the font **Anton** was used.  The logo was created externally using Canva.com.

Throughout the website the font **Poppins** was used.   This font was obtained using Google Fonts and differnt sizes were used.  These fonts fall back to sans-serif if they fail to load.  Poppins was chosen because it has a professional look and is clean and easy to read.    

For the video on YouTube the font **Bebas** was used.  This was chosen particulary because it was easy to read.  **AmaticSC** was used on the original Instagram video in May 2020.

-----
## Future Implementation 
-----

- A fully working Newsletter sending out past recipes with hints and tips for cooking with children. 

- A shop/online school with live tutorials for specilised cooking classes and equipment

- A monthly blog about Kitchen Nippers. 

- Cookie pop up for GDPR

- All social media links will link to a page for Kitchen Nippers rather than just the sign-in page.  

- Testimonials from users about the service. 

-----
## Technologies Used 
-----

- HTML5 to provide content and structure to the website.
- CSS3 to provide style for the website. 
- Coolors.co to select colors for the website that would work well together.  
- Cloudinary.com to store images for the website.
- Font Awesome for the social media icons on the footer. 
- Google Fonts for font.
- Gitpod to create and edit the website. 
- GibHub for hosting files and deployment of the website.
- Balsamiq to create wireframes.
- Inshot Video Editor to create video on recipe page and YouTube video link
    - the video was created by me (youtube username: Rachel McDermott/Instagram username: rockymiss)  in May 2020.  The recipe is my own and has been adjusted and is a commonly used recipe with many variations.  The video is also on Instagram so the link on the footer from Instagram will link directly to the video.  The Youtube link also links directly to the video.  Click [here](https://youtu.be/B037WcSqDog) to view video. 
- canva.com for logo and spoon and fork seperator on the recipe page.  
- TinyPNG - to compress images

<details open>
<summary>Tinypng image</summary>
<br>
<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642702388/kitchen-nippers/tinypng-com-images_fwpvi2.png"></p>

</details>

-----
## Resources 
-----

- Code Institute course materials, tutor and mentor support.
- Code Institute Slack Community.
- Love Running walk-through on Code Insitute.
- Form Structure was used from the Love Running challenge. 
- Youtube - https://www.youtube.com/watch?v=k32voqQhODc (for flexbox).
- Youtube - https://www.youtube.com/watch?v=pMVO1OPfVJ8&t=0s (for grid).
- W3schools. 
- Pexels.com for images. 
    - Gustavo Fring - Main hero image woman and child (index page).
    - Jill Wellington - Shamrock biscuit image (index page).
    - Jasmin - Star and Jam cookies image (index page).
    - Drake Nicolls - bun tray and other tools image (index page).
    - Michael Burrows - bread in a frying pan (recipe page).
- Youtube - video on recipe page
- Music credits on Video: 
    - Song: Mes(s)merized
    - Musician: Philip E Morris

-----
## Testing
-----

### Local Testing

Manual testing of all buttons, links, functionality and grammer on the website has been carried out.  The following was verified by manual testing: 

- Navigation on all pages: 
  - Clicking the logo on the top of each page will bring the user back to the home page/index page.  
  - All navigation links work smoothly and link to the correct page. 
  - All navigation links have the correct color when using the :hover psuedo selector.  
  - The text for the active page has the text shadow effect when active.
  - All navigation links are responsive for large, medium and small screens.
- Footer on all pages: 
  - The facebook icon links to facebook. 
  - The instagram icon links to a video directly on instagram showing the user how to make Flatbread. 
  - The Youtube icon links to a video directly on Youtube showing the user how to make Flatbread. 
  - The Twitter icon links to Twitter. 
  - The links remain responsive and in a row.   
- Home/Index page:
  - The hero image changes for responsiveness. 
  - The overlay text remains in a good viewable position over the hero image and disappears for mobile devices. 
  - That all text and images are central and not hidden and are fully responsive.  
  - That the 'Get Cooking' button links to the recipe page and the correct color shows when using the :hover psudeo selector. 
- Recipe page:
  - That the month is shown on the page to indicate to the user the recipe has been updated for that particular month.  In this case Janaury 2022.   
  - That the text and image in the about Flatbread section is aligned correctly to be easily read and fully responsive. 
  - That the ingredients are listed fully, are correct, aligned to the center and are fully responsive. 
  - That the Instructions are listed correctly, aligned to the left and fully responsive. 
  - That the video is aligned to the center and fully responsive. 
- Sign-up page:
  - That all elements on the form are working correctly. 
  - That the required information is needed to submit the form and a warning message appears. 
  - That a correct email address needs to be submitted and a warning appears if it is not. 
  - That when the submit button is clicked it will bring the user to the thank-you page. 
  - That the page is fully responsive. 
- Thank-you page: 
  - That the text is aligned to the center. 
  - That the 'Home' button brings the user back to the home page. 
- Entire website: 
  - That the text is clearly presented with the correct font-size and font-style.  
  - The the text does not have any spelling mistakes. 
  - That the website is fully responsive. 


Note:   Some links to the video needed to be updated after testing and the  facebook page was not opening as local testing showed.  The link used facebook.ie instead of facebook.com so this was changed to fix the issue.  Other minor issues such as centering and spellings came up and were fixed immediately.  

### User Testing

The website was sent to a group of approximately 20 people, most of which were parents.  Users found the website very functional and easy to navigate.  Some devices used were as follows: 

- Huawei P30
- IPhone 7s
- IPhone 11
- Iphone 12 Pro max
- Redmi note 9
- Samsung A21.  

This testing proved very helpful with responsivness errors as some errors did not show up using chrome dev tools.  Issues arose with iphone devices, (except the pro max), where text was hidden in the about section of the index page.  This also occured on the Redmi note 9.  This issue, as shown in the images below, was fixed by adjusting the height of the section in question.      


<center>**Error**</center>

<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642702153/kitchen-nippers/user-test-1-error_fsmxlz.png"></p>

<center>**Fix**</center> 

<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642702153/kitchen-nippers/user-test-1-fix_rvtypf.png"></p>

### Browser Testing

The Website has been tested on Google Chrome, Microsoft Edge, Safari and Opera.   On all browsers testing was as expected and functionality and responsiveness was good. 


### Validators 

The website was tested using Jigsaw W3C validation.  This showed up minor syntax errors and they were fixed accordingly.  Once issues were dealt with the validator showed no errors in either html or css. 

### Responsiveness 

To check responsiveness I used Google Chrome Dev Tools.  Desktop, Mobile and tablet sizes were tested.  The website responded well.   

###  Result: Chrome Desktop Lighthouse 

<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642765289/kitchen-nippers/lighthouse-test-1_xvyl02.png"></p>

When using Chrome lighthouse an error occured because I hadn't applied width and height to the images on the index page.  Width and height wwere applied and this corrected the best practices score. 

<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642782074/kitchen-nippers/image-error_jcfol8.png"></p>

### Result: Chrome Mobile Lighthouse 

<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642765289/kitchen-nippers/lighthouse-test_oub3s8.png"></p>


### Result: Webpagetest
<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642765626/kitchen-nippers/wepage-test_el1zl1.png"></p>


### Color Contrast Testing 

I used [a11y](https://https://color.a11y.com/) to test the color contrast on the website which produced no issues. 

<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642768376/kitchen-nippers/color-contrast-test_ijpwic.png"></p>


### Issues/Bugs Fixed 

The main issue was an embedded video from Instagram.  Instagram uses alot of styles which seemed to affect my own styling.  I searched for a solution and noted that others online seemed to have the same issues with Instagram videos.  After changes to some of the styling it helped slightly but not sufficient enought for responsiveness.  As mentioned previously the video was created in May 2020.  The original video had been lost and as Instagram do not allow downloading of videos I decided to re-create the video.  As in May 2020 I used Inshot to edit the video.  Fortunately I still had elements of the video so I could easily re-create the video using Inshot again.  I then posted the video to Youtube where the styling is considerably less and I could manipulate it easily to fit into my code.  Re-creating the video also meant that I could change the text on the video to be better read by the visually impaired.  I felt it was a good idea for future features to have the video on different platforms rather than in the directory.  

### Issues Unresolved

After running a test using webpagetest.org an issue appeared in relation to cross-site scripting.  After further research on this I understood it to be an issue in relation to javascript and script used in the code for icons from font awesome.  While I understand the importantance of cross-site scripting I felt that for the purposes of this portfolio it was not necessary to fix and that I would be learning more about this in the next section of the course.  I did attempt to get a cdn link from fontawesome however this required a pro account, which I do not have.     

<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642765790/kitchen-nippers/webpage-security_bynvsi.png"></p>

-----
## Version Control
-----

### Git and GitHub 

Local repository and IDE used: GitPod
Remote repository used: GitHub

Steps followed: 
- I created a new public repository on GitHub using the Code Institute template.
- I then created a workspace and started coding on GitPod. 
- Pages were created along with assets folders and css style file. 
- As I worked I previewed changes using ports to open the browser.
- To save my work safely I continued to use the terminal consistently by using: 
    - **git add .** to add work to git
    - **git commit -m""** to commit the work 
    - **git push** to update work to GitHub 

### Deployment 


  #### Deployment: 
        
    To deploy the site to Github pages the following steps should be followed: 

    - From your list of repositories select the repository you want to deploy.
    - Click on settings. 
    - Scroll down to GitHub pages and open Github pages. 
    - Select main branch and click save.
    - The page should automatically refresh and the deployed link is provided.

<details open>
<summary>Deployment Preview Image</summary>
<br>
<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642789616/kitchen-nippers/deployed-site_fgqlhc.png"></p>

</details>
    

  #### Fork: 
        
    A copy can be made of a repository by forking the repository.  The copy can then be viewed and changed without affecting the original repository. 
    
      - From your list of repositories select the repository you want to fork.
      - On the top of the page to the right had side you will see a fork image.  Click on the button to create a copy. 

      
  <details open>
<summary>Fork Preview Image</summary>
<br>
<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642789173/kitchen-nippers/fork-preview_xraeo2.png"></p>

</details>


  #### Clone: 
        
    Cloning this project from GitHub can be done by following these steps: 
    
      - From your list of repositories select the repository you want to deploy.
      - Click on the code tabe. 
      - Click on the clipboard icon to copy the URL.  
      - Open Git Bash in your IDE. 
      - Change the current working directory to the location you want to place the clone. 
      - Type git clone and paste the copied URL.  
      - Press enter for the clone to be created. .

  <details open>
<summary>Clone Preview Image</summary>
<br>
<p align="center"><img src="https://res.cloudinary.com/rockymiss/image/upload/v1642790166/kitchen-nippers/clone-preview_kkvsfx.png"></p>

</details>


-----
## Acknowledegments
-----

The website could not be completed without the help and support from my mentor Spencer Barriball, the Slack Community, my cohort facilitator Kasia and msletb class.  

Rachel Rock January 2022


