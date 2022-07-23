#Table Tennis Club

##About this Website
<br>
<sub>Hello everyone reading this! Welcome to my DHS Table Tennis Club Website! This website is meant for people in my school to join the club that I was starting. There are multiple tabs in the navigation which takes us to other pages, which is still part of the website, like official websites do. I will be explaining them more in depth in this README file.</sub>

##Home Page

######HTML

<sub>In the homepage of the Table Tennis Club Website, I added a few features such as a slideshow, some paragraphs, and of course, a header. Making the slideshow look the way I wanted it to look took sometime because I wasn't really sure with how to do it, or what to do with them. In this html file, I made sure to connect this with the HomePage.css so that they styling is maintained. Additionally, at the top of the page (of every page), I added a logo so that it is official. I made sure to mention exactly what will be covered in the club so that it would be easy for users to understand and navigate around the website. I created a box to be around each of the navigations, but it only shows up when it is active. For example, as you are on the home page, at the top where the navigation is, only "Home Page" is boxed. </sub>

######CSS
<sub>The styling of the Home Page was very well thought out because I really wanted it to look good. I wanted it to have a vibrant feel for the user's experience. In the home page, I included a slideshow, but to make sure that it looks good, centered, and has the right images, I edited it in the HomePage.css file. In here, I changed what I wanted the images to be, the sizes, to colors, and more. I also added an animation. The CSS was mainly for the slideshow because I wanted it to look really professional. However, I did still edit the text font and size using simple CSS.</sub>

##Meet Your Officers

######HTML
<sub>As I mentioned, I made this website for people at my school to join my club (after learning a lot from CS50). In the HTML file, there wasn't much I had to do, despite the number of lines. In a club, there are presidents, vice presidents, treasurers, and secretaries. I made it so that each officer has a picture (if I had one of them), and a description that each of us wrote for it to be displayed in the website. Other than that, I just linked the Meet Your Officers (MYO)'s CSS file, and the nav.css file which I will explain what I did over there at the end.</sub>

######CSS
<sub>In the CSS of the Meet Your Officers file, there was barely anything I had to do because everything looked formatted. All I needed to do was make sure the images were not too big or too long, because I didn't want a stretched out picture. I fixed this by changing the width and the margin to a very small percentage.</sub>

##Donate

######HTML
<sub>Again, in the HTML file of Donate, I didn't have to do much because I just wanted the users to have a preview of the gofundme instead of actually having to click the link and go there themselves.. Having it embedded just saves time. Luckily for me, Gofund me has a feature which allows me to embed a widget into my HTML file, so I copied the given code and pasted it in the HTML file. Although that was mainly what the whole HTML file contained, I still had to link it to the Donate.css file as well as the nav.css file, and I had to make sure to center it. There was no CSS that I included as the given widget was already styled.</sub>

##Join Our Community

######HTML
<sub>Online, there is a popular tool that many content creators and influencers use called Linktree. Linktree is where you can add a few links next to some logos, and instead of having to add multiple links to your bio on your social media page, creating a linktree lets you click on all of it in one link. It provides you with a linktree link and if you click it, you see a whole bunch of other links. I thought that it would be cool if I tried creating a type of Linktree myself, so in the Join Our Community file, I included 4 different buttons. I included the Gofundme Link, the Instagram profile, the discord server, and just for the fun of it, the website. Creating this took a lot of time, but I learned a lot of new things. I created classes for the buttons so that I can edit all of them to look the same in the css file. However, I downlaoded images to keep next to the buttons because a plain button doesn't look that good. Downloading these images and including them into the HTML was mainly all I did in this, other than linking it to the Join Our Community css page, and the nav.css page. Of course, I had to center it because I didn't think it would look good if it was all to the left or all to the right. One cool thing I learned was that by including _blank, I can let the users continue on a new tab which is more useful (otherwise they have to keep clicking the back arrow). </sub>

######CSS
<sub> When hovering over the button, I wanted to make it clear to the user that they can click on it. What I did to make it super clear was making the mouse turn into a clicker(pointer) as soon as the user hovers over the button. Adding on, I also added a transition because plainly clicking the button would just not seem smooth, so I added a transition so that the padding goes a little to the left after hovering over it. This was mainly what I did in the Join Our Community.css file. </sub>

##Events

######HTML
<sub> During the summer, I had hosted a table tennis event along witha few other officers. We let members of the discord server mark if they are interested. We also provided foods and drinks so that more people would come. This event was just the promotional event so that we can take a bunch of pictures, add it to the website, and hopefully get others interested. Again, I added a slideshow to go through some of the best pictures we took at the promotion event.</sub> 

######CSS
<sub> In the CSS file of Events, I mainly focused on getting the images down, and since the photos taken were all different sizes, I had to change the sizing to make them all look about equal. Other than the spacing and the sizing, I didn't really do anything else in the CSS file. </sub>

##Sign Up

######HTML
<sub> Last but certainly not least (for the navigation), we have the sign up page. Of course we need people to fill out this form so that we know who wants to join and how many of some items we need to buy based off of that! In the sign up html page, I made it so that the email must include "@mydusd.org" at the end, which is the school provided emails for my school, and I also made it so that the minimum grade one can enter is 9 and the maximum is 12, since this is a high school club! This is linked to my google spreadsheet so that once the user presses submit, the components save in different cells (next to each other) in the spreadsheet, like SQL. Additionally, once the user clicks submit, I added a checkmark to indicate that they have completed what they needed to do in there. Also, if you try submitting it again, it will say thank you for signing up, but it won't update anything on the spreadsheet. </sub>

######CSS
<sub> For the CSS of the Sign Up page, all I had to do was change the heights, colors, and just for effects, opacity, borders, and spacing. I set the submit button to be a green color. Other than that, I didn't do much in the CSS because I thought it looked pretty good. </sub>


######Navigation CSS/The chatbox
<sub> In the navigation bar, you see different options such as Sign Up and Meet Your Officers. But if you pay close attention on the page that you are on, in the navigation bar, it boxes it and highlights it a different color than the rest. Also, just for special effects, each time a user clicks on an option in the navigation bar (just to make sure that it doesn't feel rough), I made it smooth by making it slide from left to center. Additionally, at the end of every HTML page, you might've noticed at the bottom of the code a link. This is a chat feature that I used from UserLike which allows the website browsers to ask for any questions which gets redirected to my email. Again, luckily for me, it gave me a code to keep in javascript, so all I had to do is async type = text/javascript, and then what they gave me. </sub>

#[Youtube Link](https://www.youtube.com/watch?v=Es05NA2sHJM)

<strong>#MY NAME IS DHEERAJ, AND THIS IS CS50</strong>





