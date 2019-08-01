<h1>Queen Unnoficial Website</h1>

<p>Stream One Project: User Centric Frontend Development - Code Institute</p>
<p>This is a website for the rock band Queen. It details all original members, contains photos of both live and staged performances, music videos, the Bohemian Rhapsody film trailer with links to buy the film, a store to buy Queen memorabilia, and a fan club sign up.</p>

<h2>Demo</h2>

<p>Click <a href="https://olan1.github.io/milestone-project-1/" target="_blank">here</a> for a live demo.</p>

<h2>UX</h2>

<p>My design goals were to combine the flamboyant colourful nature of Queen with a minimalist approach. All pages share a similar layout and color scheme in order to make navigation as easy and intuitive as possible for the user.</p>
<p>The wireframes for this site can be found <a href="https://github.com/Olan1/milestone-project-1/blob/master/assets/wireframes/wireframes.pdf" target="_blank">here</a>.</p>
<p>Fans / potential fans can see an overview of each member, view pictures of live performances, watch music videos, view the trailer for the Bohemian Rhapsody feature film, and to purchase if they choose. They also have the ability to purchase other Queen memorabilia, and sign up either for the fan club or just to recieve updates on the band.</p>

<h2>Technologies</h2>
<p>1. HTML5</p>
<p>2. CSS3</p>
<p>3. Bootstrap (4.3.1)</p>
<p>4. Hover.css</p>

<h2>Features</h2>
<p>A smooth scrolling effect was created using the "scroll-behavior: smooth" css property. The navbar remains in a collapsed form regardless of screen size to reduce content on screen. A Hover.css effect is used on the nav boxes on the home page to make their interactivity intuitive. This page also makes use of Bootstraps modal feature, and the CSS3 animation / keyframe feature.</p> 

<h3>Features Left to Implement</h3>
<p>In future I would like to add full albums to the music section, with an animation that displays all songs in the album when the image is hovered over. I would also like to expand the video library library with autoplay and autostop functions. I would also like to add a scrolling effect using JavaScript, as the "scroll-behavior: smooth" css property does not work on all browsers.</p>

<h2>Testing</h2>
<p>The header on each page contains the Queen logo and name, which are both links back to the homepage. Tooltips appear when hovered over notifying the user of their function. A font-awesome icon and title tell the user what page they are currently on. The navbar is fixed in place. The navigation menu is permanantly collapsed, and is opened using the menu icon on the right of the navbar. A Q icon and the current page the user is on can be seen in the browsers title bar.</p>
<p>The footer on each page contains a form for the user to enter an email address. If you try to submit no email or an invalid email address, an error message will appear. The logo when hovered over will display an up arrow, and when clicked will cause smooth scrolling to the top of the page. A tooltip describes its functionality to the user. The social icons link to Queens social networking pages, which open in separate tabs when clicked. Tooltips appear when hovered over naming their destination.<p>
<p>The home page showcases the band immediately, with a full screen-width picture of the band, letting the user know they are in the right place. Directly underneath this banner the user can see all the sections of the website with titles, images, font-awesome icons, and a Hover.css hover feature to encourage clicking. Underneath the illustrative navigation section, there is a back to top icon and title which when clicked will scroll smoothly back to the top of the page. Tooltips describe each navigation elements function.</p>
<p>The members page exhibits a large picture of all band members upon arrival. A separate picture of each band member is displayed accompanied by a short description. On smaller screens the description appears directly below the images, where as on larger screens it appears to the right of the image.</p>
<p>The gallery page exhibits a large animation cycling through all pictures in the gallery. Below this is the video section. Each video is represented by a Bootstrap card. When the cards are hovered over, a red YouTube play icon transitions in and a tooltip saying "Play" appears. When clicked, a modal appears with the video. Once the video is played, it will continue playing until it finishes, even if the modal is closed. The videos are embedded from YouTube.</p>
<p>The music page uses a fixed background showing a collage of Queen records. Spotify embeds allow short song samples to be played, and provide links to spotify to listen to the full song.</p>
<p>The film page exhibits a large fixed image of the film poster showing the cast as Queen. Below this is the a YouTube embed of the film trailer. This video resizes to take up the full screen of any device it is displayed on. Below this are cards displaying the movie on DVD, Bluray, and the book of the film. Each card is a link to purchase each item. A tooltip appears over each card saying "Buy Now".</p>
<p>The store section displays all the available products on cards. Each card has a hover transition effect to encourage clicking. Each card links to where the product can be purchased. A tooltip appears over each card saying "Buy Now". The background is fixed. There is no header image for this page since the products are the main focus.</p>
<p>The sign-up page is a simple form with a large fixed background. Each form input is required and an error message appears if they are empty. If an invalid email address is entered, an error message will appear. The terms and conditions text is a link that opens to a separate tab.</p>
<p>This site was tested across multiple browsers (Chrome, Firefox, Safari and Microsoft Edge). It was tested on several screen sizes (iphone 6/7/8, 6+/7+/8+, X, ipad, and laptop screens). The scroll-behaviour property doesn't work on Safari or Microsoft Edge. The scroll-effect was much quicker on firefox than Chrome. The animations do not work on Edge. The animation transitions do not work on Firefox. On mobile screens, fixed backgrounds appear zoomed in on ios devices. This is an issue that GitHub is aware of and is currently addressing. I used a media query to change background-attachment from fixed to scroll for all screens below 576px.</p>

<h2>Deployment</h2>
<p>This site is hosted on GitHub. It is deployed directly by the master branch and will automatically update upon new commits to the master branch.</p>

<h2>Credits</h2>

<h3>Content</h3>
<p>All content in the members description section was sourced from the <a href="http://www.queenonline.com/" target="_blank">Official Queen website</a>.</p>
<p>All content in the terms and conditions section was sourced from the Official Queen website <a href="http://www.queenonline.com/privacy_policy" target="_blank">privacy policy</a>.</p>

<h3>Media</h3>
<p>All image were taken from the <a href="http://www.queenonline.com/" target="_blank">Official Queen website</a>, <a href="https://ultimateclassicrock.com/queen-albums-worst-to-best/" target="_blank">Ultimate Rock Classic</a>, and <a href="https://medium.com/one-reel-at-a-time/film-review-bohemian-rhapsody-5d4032f7fd79" target="_blank">Medium</a>.</p>
<p>All videos were taken from <a href="https://www.youtube.com/" target=_blank>YouTube</a>.
<p>All songs were taken from <a href="https://www.spotify.com/ie/" target=_blank>Spotify</a>.

<h3>Acknowledgements</h3>
<p>The Hover.css effects can be found at this link <a href="https://ianlunn.github.io/Hover/" target="_blank">here</a>.</p>
<p><a href="https://www.w3schools.com/" target="_blank">w3schools.com</a> provided the scroll-behaviour property, as well as clarification and explanations for many CSS properties and values.</p>
<p><a href="https://wpshout.com/quick-guides/create-text-outline-css/" target="_blank">wpshout</a> provided the text-outline class.</p>
<p>The key, value, personal-info-item and section-colum classes were taken from Code Institutes resume project.</p>
<p>The <a href="https://www.haleyschafer.com/" target="_blank">Haley Schafer Portfolio</a> website's <a href="https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/README.md#demo" target="_blank">README.md</a> was used as the template for this readme file.</p>

<p>This site is for educational purposes.</p>
