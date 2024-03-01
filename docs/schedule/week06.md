# Week 6 - Design & Visual Rhetoric
*Do you distrust a website that looks old or poorly designed or sketchy? What does good design mean and why does it make us trust the information more? We'll learn some basic design principles for use on our websites, data visualizations, and digital essays.*


### Prep for Tuesday: 
* Read: [What Screens Want](https://frankchimero.com/blog/2013/what-screens-want/) - Chimero
* Read: [The Interface as Discourse](https://journals.sagepub.com/doi/full/10.1177/1461444814520873) - Mel Stanfill, New Media & Society. This is a tough one, but give it your best shot. We'll discuss thoroughly in class.


## Tuesday, February 20, 2024
* icebreaker: You are building your dream house - what one room or feature must you include?
* Activity 6.1 - 5 min paper. How do you relate to visual design? Think about the websites/apps you visit most. Setting aside the content, why do you return? Are the websites easy/hard to use? What makes them that way? Is there a style of website you prefer and why? What makes you trust a website?
* Reading discussion 
* Activity 6.2 - Your turn! Each table will be assigned a category of website (sports, shopping, etc). In the Boxnote in our class folder, address the following:
	* Where are the levels of abstraction? What activities/labor/problems/humans are there, represented by this website? (Chimero)
	* Where is the flux? What is changing on this website? Where is the interaction? (Chimero)
	* What are the functional affordances of the site? What can the site do? 
	* What are the cognitive affordances of the site? How do you know what it can do?
	* What are the sensory affordances of the site? What do you see/feel/hear?
	* Take a look at the site in the [Wayback Machine](http://web.archive.org/) or the [Web Design Museum](https://www.webdesignmuseum.org/timeline). How has the site changed over the years? Have the affordances changed? 
* Activity 6.3 - Let's do a little work on your website. Pairing up with someone at your table, look at each other's course website. What's working? What's not? What are the functional/cognitive/sensory affordances? Identify a short list of things to change. 



### Prep for Thursday:
* [The Hidden Image Descriptions Making the Internet Accessible - The New York Times](https://www.nytimes.com/interactive/2022/02/18/arts/alt-text-images-descriptions.html) 
* [On Rational, Scientific, Objective Viewpoints from Mythical, Imaginary, Impossible Standpoints](https://data-feminism.mitpress.mit.edu/pub/5evfe9yd/release/5) - Data Feminism 
* [When the Designer Shows Up in the Design](https://www.propublica.org/article/when-the-designer-shows-up-in-the-design) - ProPublica


## Thursday, February 22, 2024
* icebreaker 
* Guest speaker: Prof. Rachel Levit Ades (Philosophy + Mudd Center) will talk to us about design, ethics, web accessibility, and image alt text. [Find her slides here.](https://docs.google.com/presentation/d/1jXdQauh501LZK8mwa2u0d90pu8NxkipI4Ak_lS6zXwY/edit?invite=CLOy5YIB#slide=id.g2bb5336a496_0_239)

## Week 6 Assignments - Due Tuesday at 12pm **after break**

### Blog post #6 - Website Genealogy

Let's practice applying *discursive interface analysis* to a website of your choosing. It doesn't have to be related to your project, but it would be helpful if it was! Address the following: 

* What are the functional affordances of the site? What can the site do? 
* What are the cognitive affordances of the site? How do you know what it can do?
* What are the sensory affordances of the site? What do you see/feel/hear?
* How do these affordances produce norms? What are the norms? 
* Look at the site in the [Wayback Machine](http://web.archive.org/) or the [Web Design Museum](https://www.webdesignmuseum.org/timeline). How has the site changed over the years? Have the affordances changed? Jump back as far as you can. 

**Specs:** 

* Create a WordPress post, turn in the link on Canvas.
* 300-500 words.
* Include 3-5 screenshots of the website from its current iteration and past versions. 
* Free from grammatical errors, typos.
* Credit and link out to sources when appropriate. I won't require that you use a certain citation style, but you should be in the habit of crediting sources and using in-text links. If you feel better about using a formal citation style, go for it!

### Activity log #6 

Let's apply some of the design principles we discussed this week in class to your own site. First, take a look at your site as an outside observer. What are the functional/sensory/cognitive affordances? What can your site do and what might you need to change to make it work better or look better or be more accessible? 

You may have to Google or watch a video to figure out how to change features. That is okay and encouraged! Part of this class is learning how to figure out new technology without detailed instructions. What happens when you press the help button? 

**Specs:** 

* Spend 30-60 minutes improving the design and functionality of your WordPress site. 
* Add alt text image descriptions for all your images. 
* Write some custom CSS using the CSS skills we learned early in the term. See Activity 6.4 below for some advice and direction. 
* Turn in your site URL on Canvas when you're done. Summarize your changes in a comment. 

***


* Activity 6.4 - Code meet WordPess. Beyond the options provided to you in WordPress, how can you change your website using the HTML/CSS we learned earlier in class? 
	* In the admin screen for your WordPress site, navigate to Appearance > Customize. 
	* Check out all these settings and see what you might want to change! Your content should be safe. 
	* Visit the `Additional CSS` screen. Remember our CSS from a few weeks ago? Write some here to change the style of your site. 
	* You might need to use the Inspect tool in your browser to figure out how to target the HTML element or CSS class you're trying to change. For example, I'm always annoyed at seeing the "Powered by WordPress" line on my site. By inspecting the page, I can see that that piece of text is in a `<div class="powered-by">` So I can write the following to hide it:
			`
		.powered-by {
			display:none;
		}
		` 

