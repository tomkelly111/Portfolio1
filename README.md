# The Card Club
The Card Club is a website which is intended to be used by a poker club. The target audience is poker players in Dublin, Ireland. The site will be useful for people in Dublin who are looking for live poker games whether that be cash or tournament games.

## Features

### Logo and Navigation Bar
The Card Club has a logo and navigation bar which is identical accross all pages. When the logo is clicked it brings the user to the home page. The navigation bar contains links to each section of the site and allows the user to "jump" to different sections of the home page such as the "Find Us" section. Links were used in this manner to allow the user to easily navigate the site and avoid having to use the "back" button.

### About Section
The About section gives a brief description of The Card Club and serves to highlight key offerings of the club to entice users to play.

### Games Section
The Games section provides a detailed list of the various games on offer at The Card Club, including times, buy-in amount, starting stack and blind levels. This section can be updated if game times change.

### Find Us Section
The Find Us section provides an embeded google map which shows the location of The Card Club to enable users to find their way to The Card Club with ease.

### Register Page
The Register page contains a form which allows users to input their name and email address as well as select the types of games they are interested in. The form is designed so that all fields must be completed and an email address containing an "@" symbol must be used. Once sign3ed up the user is brought to another page which thanks them for registereing. 

### Results Page
The Results page contains a table of the three most recent tournament winners. This can be updated with new winners after each game and lists the date the game was played and the amount won.

### Thank You Page
Once the user completes the Sign Up form on the Register Page, they are brought to a Thank You page which contains the header and links to the rest of the site, avoiding the user being brought away from the site and allowing easy navigation back to other areas of the site.

### Footer
The footer appears on each page of the site and contains links to Facebook, Instagram and Twitter.

## Testing

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
              <td>Partial Pass - when clicking to sections of the home page, sections appear behind logo and drop down menu does not automatically close</td>
             </tr>
             <tr>
             <td>Resizing window to below 800px width</td>
              <td>Games section aligns vertically</td>
              <td>Pass</td>
             </tr>
</table>

### Validator Testing

HTML - No errors were returned when code was checked with the official W3C validator.
CSS - No errors were returned when code was checked with the official (Jigsaw) validator.

### Unfixed Bugs
When the site's "Burger" menu is used on devices with screens with a width below 800px, the menu does not automatically close when the anchor links are clicked.

## Deployment



Took code from (https://stackoverflow.com/questions/2204634/how-to-disable-automatic-links-coloring-without-selecting-a-color) to remove underlines and color from links.

a, a:hover, a:visited, a:active {
  color: inherit;
  text-decoration: none;
 }


took logo image from (https://www.stockvault.net/photo/134256/playing-cards#)

took footer from coders coffee house:

<span>Find us on:</span>

		<a href="https://www.facebook.com" target="_blank" rel="noopener" aria-label="Find us on Facebook (link opens in a new tab)">Facebook</a>
		<a href="https://www.instagram.com" target="_blank" rel="noopener" aria-label="Find us on Instagram (link opens in a new tab)">Instagram</a>
		<a href="https://www.twitter.com" target="_blank" rel="noopener" aria-label="Find us on Twitter (link opens in a new tab)">Twitter</a>

		<p>Copyright © Coders Coffeehouse 2020</p>


		colors taken from (https://mycolor.space/?hex=%2300452D&sub=1)


		https://www.pexels.com/photo/person-holding-king-of-diamonds-playing-card-1658747/


		footer icons taken from love running
		<!-- font awesome script --> 
    <script src="https://kit.fontawesome.com/b49a34db96.js" crossorigin="anonymous"></script>

	took register button styling from love running


took small window media sizing from love running


took burger menu from https://codepen.io/alvarotrigo/pen/MWEJEWG


bug with fotter not sitting at bottom of page below 800px


fixed anchor links rom scrolling behind  header with code from (https://getpublii.com/blog/one-line-css-solution-to-prevent-anchor-links-from-scrolling-behind-a-sticky-header.html)scroll-padding-top: 4rem;