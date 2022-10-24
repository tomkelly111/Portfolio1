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

## Testing
<table>  
            <tr>
              <th>Action</th>
              <th>Expected Behaviour</th>
              <th>Pass / Fail </th>
            </tr>
            <tr>
              <td></td>
              <td>07/10/2022</td>
              <td>€1,570</td>
            </tr>
            <tr>
              <td>Chris Moneymaker</td>
              <td>05/10/2022</td>
              <td>€990</td>
            </tr>
            <tr>
            	<td>Phil Ivey</td>
                <td>03/10/2022</td>
                <td>€875</td>
              </tr>
</table>


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