# UXDI Adventures

### whiteboard pre-class
* make sure to install atom
* warmup: here is a picture of a website (maybe like the GA homepage). what types of content show up on this page?
* warmup 2: draw a picture. you type google.com into your address bar. what happens between that moment & seeing the site in your browser? (not knowing is fine! guesses are great!)

## Welcome
Hi I'm [Name] I'm cool I'm here to learn you the internets here's ur warmup

come back together and talk about answers to that warmup

## How The Internet Works
draw ur client/server diagram. there's a client. there's a server. maybe put the server in the cloud. label it "google". there's a request. the browser sends it, saying "please give me google dot com thank you", the internet (a bunch of computers) sends that to the server. the server then uses that request to say "yo somebody from this address wants google.com" and figures out what that should look like and sends back the data that makes google.com the site in your browser. then that gets rendered, your browser takes that data and uses it to put things on the page for you. and yes all of those steps happen in less than a second computers are magical boxes.

## What's being rendered though: HTML

### tools
let's see what it actually looks like to write those pages that your browser knows how to render. to do that we gotta talk about tools, let me show you my computer and how i use these tools. y'all installed atom right? here's my atom, it might have different colors from yours but it should work the same. this is the program I use to write code. the same way you use word to write nice text documents, or sketch to make beautiful drawings, you use a text editor to write code. code doesn't get formatted with like dumb things, it it literally pure text, but we write that text using specific syntax/symbols that help us do neat things.

### codealong
ok let's make some basic HTML using this cool editor. let's start by making a file, call it index.html, and then let's start adding content. words words words, save, look at it, wow look how boring this is haha, let's fix the HTML to do cool stuff. like probably at the top we want a heading. in HTML we'll use specific tags to create those things that we want. these angle brackets let us set up the tag we want to show, and then we give the name of the tag. H1 is the way we make a big header, so let's make an open H1, and then close that H1 this way. save, refresh, wow look it's different now! yay!

### ok some questions:

* what do we think H1 stands for? do we think there are other similar tags?

* what if we wanted to have a normal less than sign on our site? how do???

let's add more tags to the tags we know about!

* p
* img
* a
* ul/li, talk about nesting tags
* input (this will blow their minds :D )

and one last thing, usually when we write these tags there is a little more detail about how we actually see that page. add in html, head, title, body

let's also take a second to look at how we can learn more about what's happening both on sites that you create, and on other sites around the internet. developer tools are super useful. (exploration)

Alright now it's your turn! I'll show you a neat page, you write HTML to represent it. we'll take about 10 minutes for this. go!

### recap

have them talk about how they achieved each part and why

### good time for a break now!

## CSS: Adding style

OK now we have a cool basic site! yay! when is the last time you saw a site that looked like this? no? if a developer brought you a site that looked like this, would you be happy? nope me neither! so we talked until now about how to structure our sites, how to use HTML to set up what elements show up on our page. next is going to be adding style to our page, and to add style we're going to use a different language: CSS.

CSS stands for "cascading style sheets" but you don't have to care or remember that. what we care about is what it does: helps us make sites look different.

so let's take this neat site we have. in the head, let's add this style tag. that's where we can write this style information in this other language. what do we want to change about the styling?

things to definitely cover:
* colors
* font
* width/height

we might also want to add more whitespace around some of these things on the page. it's weird that everything is way over on the left. how do we do that? let's talk box model. use developer tools. there's padding and margin and border. it's kinda a lot but i never remember which is which i  literally check here.

and how do we attach that CSS to each element? so we saw that you can use the name of the element but like, what if you want only one of them to turn into a red one??? we can do that too! we use classes for that. can assign classes. use dots to say this style is about a class name now, not about a type of element. yay.

oh and guess what the Chrome developer tools can ALSO help us see what's happening with CSS! just use the developer tools literally all the time!

ok sweet now here's what i want you to build overall, GO.

another like 10 minutes for writing your own CSS, then recap, then break.
