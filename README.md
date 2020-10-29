<h1>The Shoulder of Mutton, Wantage</h1>

<p>This project consists of an enhancement to a local pub's existing website. View the original site <a href="http://www.theshoulder.pub/">here.</a></p>

<p>Following discussions with the landlord it was decided that the existing text successfully conveyed the desired information about what the pub had to offer in terms of real ale, atmosphere and accomodation. 
The primary purpose of this enhancement was to present this information in a more interesting and visibly appealing fashion.</p>


<h2>UX</h2>

<h3>Objectives for the Business to Existing Customers</h3>
<ul>
<li>Express the community spirit of the pub in a way that is rarely seen on this kind of site.</li>
<li>Enhance a sense of familiarity and association with the pub.</li>
<li>Provide social media links.</li>
</ul>

<h3>Objectives for the Business to Potential Customers</h3>
<ul>
<li>Raise awareness of the features and qualities of the pub.</li>
<li>Provide a visually appealing experience that stands out from the crowd.</li>
<li>Encourage people to visit, participate in events and book a room.</li>
<li>Give information about contributing breweries and beers.</li>
<li>Provide contact and location information.</li>
</ul>

<h3>Objectives for Customers</h3>
<ul>
<li>Find a genuine real ale pub in Wantage.</li>
<li>Discover a pub with character.</li>
<li>Find somewhere to stay in Wantage.</li>
<li>Enjoy visiting a pub website that stands out from the crowd!</li>
<li>Have one-click links to the social media of the pub.</li>
</ul>


<h2>Project Planning</h2>

<p>A basic wireframe of the site is included <a href="https://github.com/Jegouar/shoulder-of-mutton-ii/blob/e94654592ff7cf88fa83e5b2a4c205a85fcdf94d/Shoulder%20of%20Mutton.pdf">here.</a></p>


<h2>Design Features</h2>

<h3>All Pages</h3>

<p>This site uses viewport-based units for dimensions and font sizes, specifically Viewport Width (vh). 
This was felt to be the best solution for the issue of differing screen sizes, particularly with respect to the alignment of three dimensional elements. 
Stylesheets are based on screen orientation rather than screen size breakpoints.</p>

<p>Bar pump clips are used to provide a more interesting theme to the navigation than typical sites. 
Their appearance reflects the pub and its existing logo and graphics.
In landscape format they are aligned vertically on a wooden pole to the left, and in portrait horizontally on bar pumps at the top.
By using CSS they subtly change depending on status - selected, non-selected, hovered over or clicked.</p>

<p>Standard text uses a slab serif font called 'Bitter'. 
As well as it's appropriate name, this font is well suited for the sentences and short paragraphs in which it appears.</p>

<p>The footer includes contact details and relevant links to Google Maps and social media. 
The dark green and gold colours are a reflection of certain features of the actual pub.</p>

<h3>Home page</h3>

<p>The 'hero image' animation was inspired by Code Institute's 'Love Running' project.</p>

<p>The introductory lines of text follow the lines of the background image using the CSS shape-outside property. 
Links to external sites open in fresh tabs.</p>

<p>The centrepiece of the home page is the beer board, a highly recognisable asset of the pub. 
By making it interactive with tabs that load and reveal text, the qualities and character of the Shoulder of Mutton are highlighted. 
Different handwritten and quirky fonts reflect the appearance of the real thing! 
The backboard displays a slideshow of customer images to back up what is stated in the text.</p>

<p>Like the CSS 3D transforms on other pages, positioning of the elements to match the perspective of the photograph was achieved through trial and error. 
Lessons have been learned should I wish to create similar effects in future projects. 
The idea for the animated tabs came after reading an article on the <a href="https://css-tricks.com/the-checkbox-hack/">CSS-Tricks website.</a> 
By positioning checkboxes off the page and styling the tabs as clickable labels, Javascript is not needed.</p>

<p>A missing feature of the original website is customer reviews. 
By making them visually interesting they are more likely to be read. 
Hence the fun invitation to 'Press the alarm!' or 'Click this brick!', depending on orientation, which enlarges the pieces of paper with handwritten and typed out comments.</p>

<h3>Beers page</h3>

<p>When opened the main text is gradually revealed as the level of beer goes down in the pint glass. 
The text wraps around the glass using 3D transforms, to achieve this it was necessary to divide the text into small sections set at different angles.</p>

<p>At the request of the landlord, links are provided to the brewery websites.</p>

<h3>Rooms page</h3>

<p>Again, a recognisable feature of the pub was chosen to display images of the accomodation.</p>


<h2>Technologies Used</h2>

<h3>Languages</h3>
<ul>
<li>HTML5</li>
<li>CSS3</li>
</ul>

<h3>Frameworks, Libraries and Programs</h3>
<ul>
<li>GitPod</li>
<li>GitHub</li>
<li>Google Fonts</li>
<li>Font Awesome</li>
<li>Autoprefixer</li>
<li>Adobe Photoshop</li>
</ul>

<h2>Testing</h2>

<p>While building the home page I used Chrome to test as features were added and edited. 
When I tried it out on Firefox there were a number of issues, so I made adjustments accordingly. 
From then on it generally paid to develop with Firefox and perfect appearance and functionality here first. 
Then the result usually worked in other browsers. 
I also asked a couple of friends with Apple devices to give their impressions. 
Early on the results were less than perfect but with the help of screenshots and conversations I was able to improve matters.</p>

<h3>Key tests</h3>
<p>Tests were carried out in the following browsers on a PC, in landscape and portrait orientation:</p>
<ul>
<li>Chrome</li>
<li>Firefox</li>
<li>Edge</li>
<li>Explorer</li>
<li>Opera</li>
</ul>
<p>The tests were repeated on an Android phone using Chrome.</p>

<p><b>Main Navigation</b></p>
<p>These tests were performed early on before other content was added to the pages, and intermittently afterwards.</p>
<ul>
<li>Do buttons appear as designed in their different states?</li>
<li>Do buttons link to the appropriate page correctly?</li>
</ul>

<p><b>Footer</b></p>
<ul>
<li>Is the footer position correct?</li>
<li>Do the links to Google Maps, Facebook and Twitter open in a separate window?</li>
</ul>

<p><b>Home page</b></p>
<ul>
<li>Does the hero image animation function correctly?</li>
<li>Do the links within the introductory text function correctly?</li>
<li>Does the board slideshow smoothly operate?</li>
<li>Do the objects in 3D orientation appear aligned to the surrounding images?</li>
<li>Do the tabs slide into the board and reveal text when clicked?</li>
<li>Do the customer reviews enlarge when "Press the alarm!" or "Click this brick!" is selected?</li>
</ul>

<p><b>Beers page</b></p>
<ul>
<li>Does the glass animation start when the page is loaded?</li>
<li>Is the text wrapped around the glass convincingly?</li>
<li>Is all the text legible?</li>
<li>Do the brewery logos enlarge when hovered over?</li>
<li>Do the links to brewery websites open in a separate window?</li>
</ul>

<p><b>Rooms page</b></p>
<ul>
<li>Does the sign slideshow smoothly operate?</li>
<li>Is the 3D alignment of the room images to the sign correct?</li>
</ul>

<h3>Test results</h3>
<p>All tests were conducted and any issues corrected before a relevant commit to Github.
Before the final results were achieved it was necessary to edit the alignment of objects subject to 3D transforms, often several times.
This will certainly be a consideration when tackling similar situations in future projects.</p>
<p>A couple of the animations were imperfect but deemed to pass the tests.
In both cases, the beer glass and the room sign, steps between images were a little jumpy.
If taking the project further I would aim to smooth out these transitions.</p>

<h2>Deployment</h2>
<p>This site is hosted using Github pages, deployed directly from the master branch. 
The deployed site updated automatically upon new commits to the master branch. 
In order for the site to deploy correctly on Github pages, the landing page was named index.html.</p>