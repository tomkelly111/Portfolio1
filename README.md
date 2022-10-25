# [The Card Club](https://tomkelly111.github.io/The-Card-Club/)

<img width="625" alt="image" src="https://user-images.githubusercontent.com/111172617/197868327-633a253d-6ff9-49ef-bbd6-045b4c72ace3.png">


[The Card Club](https://tomkelly111.github.io/The-Card-Club/) is a website which is intended to be used by a poker club. The target audience is poker players in Dublin, Ireland. The site will be useful for people in Dublin who are looking for live poker games whether that be cash or tournament games.

## FEATURES

### Logo and Navigation Bar
<img width="941" alt="image" src="https://user-images.githubusercontent.com/111172617/197868886-a47465b0-9eab-4c45-8fc9-a9c55bad8cd1.png">

The Card Club has a logo and navigation bar which is identical accross all pages. When the logo is clicked it brings the user to the home page. The navigation bar contains links to each section of the site and allows the user to "jump" to different sections of the home page such as the "Find Us" section. Links were used in this manner to allow the user to easily navigate the site and avoid having to use the "back" button.

### About Section
<img width="494" alt="image" src="https://user-images.githubusercontent.com/111172617/197882265-84f91b17-b68a-4c53-a66c-b623ea6ccfd2.png">
The About section gives a brief description of The Card Club and serves to highlight key offerings of the club to entice users to play.

### Games Section
<img width="947" alt="image" src="https://user-images.githubusercontent.com/111172617/197882337-90c1ef80-f856-47ac-aba3-4b1d53041571.png">
The Games section provides a detailed list of the various games on offer at The Card Club, including times, buy-in amount, starting stack and blind levels. This section can be updated if game times change.

### Find Us Section
<img width="502" alt="image" src="https://user-images.githubusercontent.com/111172617/197882406-a0abb7e5-b728-49bf-8908-1a4a24669867.png">
The Find Us section provides an embeded google map which shows the location of The Card Club to enable users to find their way to The Card Club with ease.

### Register Page
<img width="497" alt="image" src="https://user-images.githubusercontent.com/111172617/197882511-45de8585-383d-4def-96b9-1cc377bce2a9.png">
The Register page contains a form which allows users to input their name and email address as well as select the types of games they are interested in. The form is designed so that all fields must be completed and an email address containing an "@" symbol must be used. Once signed up the user is brought to another page which thanks them for registereing. 

### Results Page
<img width="304" alt="image" src="https://user-images.githubusercontent.com/111172617/197882579-10ab736f-b2c8-41ec-bddd-922b7aa0161c.png">
The Results page contains a table of the three most recent tournament winners. This can be updated with new winners after each game and lists the date the game was played and the amount won.

### Thank You Page
<img width="402" alt="image" src="https://user-images.githubusercontent.com/111172617/197882760-ccb4540a-f315-4a3e-940f-73c2ae6c09f5.png">
Once the user completes the Sign Up form on the Register Page, they are brought to a Thank You page which contains the header and links to the rest of the site, avoiding the user being brought away from the site and allowing easy navigation back to other areas of the site.

### Footer
<img width="488" alt="image" src="https://user-images.githubusercontent.com/111172617/197882897-73886ace-e45d-4ea4-8a6a-d051d611cce8.png">
The footer appears on each page of the site and contains links to Facebook, Instagram and Twitter.

## TESTING

### Manual Testing
<table>  
            <tr>
              <th>Action</th>
              <th>Expected Behaviour</th>
              <th>Pass / Fail </th>
            </tr>
            <tr>
              <td>Clicking Logo</td>
              <td>Returns user to home page from all pages of the site</td>
              <td>Pass</td>
            </tr>
            <tr>
              <td>Clicking Naviagation Links</td>
              <td>Brings user to specified sections of the site</td>
              <td>Pass</td>
            </tr>
            <tr>
            	<td>Clicking Footer Icons</td>
              <td>Brings user to specified sites</td>
              <td>Pass</td>
             </tr>
             <tr>
            	<td>Clicking Footer Icons</td>
              <td>Sites open in new tab</td>
              <td>Pass</td>
             </tr>
            <tr>
            	<td>Completing Sign Up Form</td>
               <td>Form does not let user leave blank fields</td>
               <td>Pass</td>
             </tr>
             <tr>
            	<td>Completing Sign Up Form</td>
               <td>Form requires "@" in email field</td>
               <td>Pass</td>
             </tr>
             <tr>
            	<td>Completing Sign Up Form</td>
               <td>Form requires one of the radio buttons to be selected</td>
               <td>Pass</td>
             </tr>
             <tr>
            	<td>Completing Sign Up Form</td>
               <td>Sign Up button changes color when hovered over</td>
               <td>Pass</td>
             </tr>
             <tr>
            	<td>Completing Sign Up Form</td>
               <td>Completing form brings user to thank you page</td>
               <td>Pass</td>
             </tr>
             <tr>
            	<td>Resizing window to below 800px width</td>
              <td>Header is replaced with "Burger" menu</td>
              <td>Pass</td>
             </tr>
             <tr>
              <td>Resizing window to below 800px width</td>
              <td>Clicking "Burger" icon opens drop down menu</td>
              <td>Pass</td>
             </tr>
             <tr>
              <td>Resizing window to below 800px width</td>
              <td>Clicking links on drop down menu brings user to specified sections</td>
              <td>Partial Pass - when clicking to sections of the home page drop down menu does not automatically close</td>
             </tr>
             <tr>
             <td>Resizing window to below 800px width</td>
              <td>Games section aligns vertically</td>
              <td>Pass</td>
             </tr>
</table>
### Bugs Found
- When carrying out manual testing it was noticed that the footer on the Thank you page did not show at the bottom of the page but instead appeared behind the Logo. This was then amended but could not be fixed at all screen sizes for unknown reasons.


### Validator Testing

HTML - No errors were returned when code was checked with the official [W3C validator](https://validator.w3.org/).
<img width="910" alt="image" src="https://user-images.githubusercontent.com/111172617/197873160-e2124e45-ae64-4932-9188-e66a8975827b.png">

CSS - No errors were returned when code was checked with the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/).
<img width="922" alt="image" src="https://user-images.githubusercontent.com/111172617/197877362-22680f92-e0ec-43ab-9d53-9cfcd0f5abf4.png">

Accessibility - I confirmed the code used is accessible by using lighthouse in devtools.
<img width="412" alt="image" src="https://user-images.githubusercontent.com/111172617/197878985-0cf95a2d-f297-4903-8f6f-34a673216bea.png">

### Unfixed Bugs
When the site's "Burger" menu is used on devices with screens with a width below 800px, the menu does not automatically close when the anchor links are clicked.

## DEPLOYMENT
### Publication
In order to publish the site, deployment was carried out using GitHub pages. In order to deploy the site the following steps were followed:
- Open the GitHub repository
- Navigate to the "settings" tab
- On the left hand side of the page scroll down and select "pages" 
- Under "source" select "deploy from a branch"
- Under "branch" select "main"
- Click "save"
- The live link is: https://tomkelly111.github.io/The-Card-Club/

### Local Deployment
In order to deploy the site locally a user can enter "git clone https://github.com/tomkelly111/The-Card-Club.git" into the command prompt on their computer and hit enter.

## CREDITS

### Color:
- Colors were selected from the following site: https://mycolor.space/?hex=%2300452D&sub=1 

### Footer:
- Icons for the footer were taken from [Font Awesome](https://fontawesome.com/)
- The code for the insertion of the icons into the footer was based on code taken from the Love Running Project on https://learn.codeinstitute.net/ Original code is as follows:
    

		<footer>
        <ul class="social-networks">
            <li>
                <a href="https://facebook.com" target="_blank" rel="noopener" aria-label="Visit our Facebook page (opens in new tab)"><i class="fa-brands fa-facebook"></i></a>
            </li>
            <li>
                <a href="https://twitter.com" target="_blank" rel="noopener" aria-label="Visit our Twiter page (opens in new tab)"><i class="fa-brands fa-twitter"></i></a>
            </li>
            <li>
                <a href="https://youtube.com" target="_blank" rel="noopener" aria-label="Visit our Youtube page (opens in new tab)"><i class="fa-brands fa-youtube"></i></a>
            </li>
            <li>
                <a href="https://instagram.com" target="_blank" rel="noopener" aria-label="Visit our Instagram page (opens in new tab)"><i class="fa-brands fa-instagram"></i></a>
            </li>
        </ul>
    </footer>
    <!-- font awesome script --> 
    <script src="https://kit.fontawesome.com/b49a34db96.js" crossorigin="anonymous"></script>

### Navigation Links
- Code to remove the underline and color of links in the Navigation Bar wad take from the following URL: https://stackoverflow.com/a/2204687 which was provided by users mikemaccana and simaofreitas.

      a, a:hover, a:visited, a:active {
      color: inherit;
      text-decoration: none; } 

### Media
- The background image was taken from an open source image site at the following URL: https://www.stockvault.net/photo/134256/playing-cards#


### Sign Up Button
- Code for the Sign Up button on the Register page was based on code taken from the Love Running Project on https://learn.codeinstitute.net/
		

### Burger Menu
- Code for the "Burger" Menu that displays on screens with a width less than 800 pixels was taken from https://codepen.io/alvarotrigo/pen/MWEJEWG and provided by user Álvaro. This code was useful as it was one of the few pieces of code found that allow for the use of a "Burger" Menu without the use of Javascript. The code provided by Álvaro was adapted for the Card Club by amending the colors used and updated the navigation links.
		
### Bugs
Initially when the navigation links on the homepage were clicked, the section that was jumped to displayed behind the header. A fix for this was found at https://getpublii.com/blog/one-line-css-solution-to-prevent-anchor-links-from-scrolling-behind-a-sticky-header.html and was provided by Bob Mitro. The original code which was adapted is as follows:

      scroll-padding-top: 4rem;

