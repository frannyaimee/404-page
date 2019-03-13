# 404-page
>This is simply a sample 404 page that we created in BeCode. It was one of the first exercises given to us by the coaches.
>This is simply the page that would load if someone using my site were to get lost or try to reach a link that doesn't exist
>I chose a background image of the forest with an opacity layer of it, so that I could use the terms "You took a wrong turn somewhere"
>The link at the top of the page leads the user back to my GitHub page
>There is a little bit of animation on the text as it loads and comes into screen
>There is also animation on the link at the top of the page that leads back to my GitHub-- the animation is simply a line that appears.

>>Installation:
>No installation needed. I used Sublime Text as my text editor and coded this page simply using HTML and CSS.

>>The only HTML code inside of my Body tag:
<div class="container">
	  <a href="https://github.com/frannyaimee" class="button"> Back to where you came from </a>
</div>
<div class="test">
		Oops!
		<br />
		We made a wrong turn somewhere...
</div>

>>My CSS code consists of about 100 lines of code:
.button {
    padding: 1em;
    display: inline-block;
    text-transform: uppercase;
    padding-top: 50px;
    margin: 0 auto;
    color: white;
    font-size: 40px;
    text-decoration: none;

    -webkit-transition: all 0.2s ease-in-out;
    -moz-transition: all 0.2s ease-in-out;
    -ms-transition: all 0.2s ease-in-out;
    -o-transition: all 0.2s ease-in-out;
    transition: all 0.2s ease-in-out;
}
>>I ensured that my transitions/animations was compatible/would work on all web-browsers so I included the different perimeters.
  
>>As of right now this is a finished product, although I am not completely pleased with it. If I need a 404 page I will come use this one and make the necessary changes so that it fits the current project.



>>This is where my 404 page is published:
https://frannyaimee.github.io/404-page/
