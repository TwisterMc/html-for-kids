# HTML for Kids

A tutorial to help kids learn the basics of HTML.

This tutorial is designed for kids to start learning HTML. It covers some very high level basics and allows kids to display text, links, and images on the screen. 

An adult does need to help setup the computer but there's not too much to it. 

Everything we write is actual HTML code, but nothing will be online. Everything runs locally.

## Level 0 - Setup

Work with an adult to get an HTML editor setup. I recommend [Visual Studio Code](https://code.visualstudio.com) as it's free.

It's also a good idea to install the [HTML Preview extension](https://marketplace.visualstudio.com/items?itemName=george-alisson.html-preview-vscode) so that you can have your code on one side of the screen and see a live preview on the other. That way you can see what you're creating in real time.

Next, create a folder on your computer called `my-website` and then open the `my-website` directory in Visual Studio Code. Not much is going on yet, but now we should be ready to code!

## Level 1 - Intro

HTML, or Hyper Text Markup Language if you want to get fancy, is the language of the web. Websites are built using many different web technologies, but they all started out with basic HTML.

HTML is used to tell a web browser what to render. HTML code is made up of opening and closing tags with some sort of content in between. These tags tell the browser what to render. HTML code is read from the top down, so what's at the top of your code is at the top of your web page.

HTML pages end in `.html` or `.htm`. Either are acceptable and any page you create should end in one of these file extensions. Other programming languages have different file extensions, but you don't have to worry about that now.

This is just the beginning. There's a lot to learn, but let's just focus on the basics. Let's create a page that outputs some content. Technically that's all you need. All the web professionals had to start here too!

- What is HTML - definition
- File Extensions (html or htm)
- Made up of open close tags
- What you can do with it. 
- Just the beginning in this tutorial
- What we're going to build.

## Level 2 - It Starts

Let's start out by creating a page that outputs some of your favorite things.

First, create a new page in Visual Studio Code, save it, and name it `index.html`. This should have saved into your `my-website` folder.

You just created your first web page! However, it's still empty. Let's fix that.

Each page starts out with an HTML tag. Add the open `<html>` tag to your page followed by the closing `</html>` tag.

Great now we have the code that tells the browser to render this page. Inside that page we have to add a BODY tag which is where we put or code that should be displayed in the web browser. After your open HTML tag add the open `<body>` tag followed by the closing `</body>` tag. 

Progress, but we still haven't told a web browser what to render.

From this point on, everything will go in between the opening BODY tag and closing BODY tag.

Let's add a HEADER to our page. This is typically the title of the page. Open a HEADER tag with `<h1>` and close it with `</h1>`. Now type `Hello World` in between the open and close HEADER tags.

Example:
`<h1>Hello World</h1>`

If you look at your preview, you should see `Hello World` displaying on the page. Pretty cool right? 

Now, after the closing HEADER tag, on a new line, let's add a paragraph of text. PARAGRAPH tags open with `<p>` and close with `</p>`. Then, put a sentence or two in between those tags; like what's your favorite food?

Example:
`<p>My favorite food is pizza.</p>`

Check that preview. Do you see `Hello World` in big text followed by your favorite food in smaller text?

Let's add another PARAGRAPH tag and tell us your favorite animal and why.

At this point, you've mastered level 2. You've been able to create a page that can be read by a web browser and displays information.

## Level 3 - Formatting

There are a lot of HTML tags for all different sort of things. Some help you with formatting your text.

If you want **bold** text, you use the STRONG tag. It starts with `<strong>` and ends with `</strong	>`.

If you want *italic* text, aka emphasis, you use the EM tag. It starts with `<em>` and ends with `</em>`.

If you want _underlined_ text, you use the UNDERLINE tag. It starts with `<u>` and ends with `</u>`. 

If you want something centered, use the CENTER tag. It starts with `<center>` and ends with `</center>`. 

Remember our HEADER tag? Well, there are actually 6 of them. They go from 1 through 6 with one being the biggest and 6 being the smallest. Just change the number in the HEADER tag.

Now, go back to your file and add some formatting. 

### Bonus: 

You can put some HTML tags inside other HTML tags. Formatting tags, for example, can be inside PARAGRAPH tags. Same with links and images which we'll be covering next.

## Level 4 - Links

### Relative Links

What if you wanted to have multiple pages and link to them? Well, that's where the LINK tag comes in; or HYPERLINK if you want to be fancy again. It creates a link from one page to another.

The link tag looks like this:
`<a href="page2.html">Page 2</a>`

The HTML tag is a bit more complex because it has the `href` attribute (more on those later) that tell the browser where you're linking to.

Now, create a new HTML page and name it `page2.html`. Back in your `index.html` file if you add the link we outlined above. Now when you preview the `index.html	` you can click on the link and it should take you to `page2.html`. Remember, that we didn't put anything in `page2.html` so it's probably completely white.

Let's build out `page2.html` a little. Edit `page2.html` and add what you've learned. Add the HTML tag, the BODY tag, a HEADER tag that says `Page 2`, and a link that links back to `index.html`. 

Your goal is to have to pages with content on each page and a link on each page that allows you to go between them when the links are clicked.

### External Links

Let's say you want to link out to another website like Disney's website. This is an external link. For this, you don't have to create any files, you just need to update the `href` attribute to point to the URL you want to go to.

An external link tag looks like this:
`<a href="https://www.disney.com">Disney</a>`

Let's edit `page2.html` and add an external link out to PBS Kids' website `https://pbskids.org`.

## Level 5 - Lists

There are two types of lists; unordered and ordered. 

### Unordered Lists

An unordered list starts with `<ul>` and ends with `</ul>`, but that's just the start. Each item in the list starts with `<li>` and ends with `</li>`. 

An unordered list looks like this:

```
<ul>
	<li>Blue</li>
	<li>Red</li>
	<li>Green</li>
	<li>Purple</li>
	<li>Yellow</li>
</ul>

```

In your `index.html` file, create an unordered list of 5 colors.

When you view your file, you should see your colors in a list with a round dot (bullet point) at the beginning of each item.

### Ordered Lists

Now let's create a list of your top 5 favorite colors. This time, the order matters.

An ordered list starts with `<ol>` and ends with `</ol>`. Each item in the list has the same formatting as before which starts with `<li>` and ends with `</li>`

An ordered list looks like this:

```
<ol>
	<li>Green</li>
	<li>Yellow</li>
	<li>Blue</li>
	<li>Purple</li>
	<li>Orange</li>
</ol>
```

When you view your file, you should see your colors in a list with a number at the beginning of each item.

## Level 6 - Images ... coming soon

- Image Tag

## Level 7 - Tables ... coming soon

- Table Formatting

## Level 8 - Attributes ... coming soon

- What are they?
- How do they work?
- Font-Size
- Font-Color
- Link Target

## Level 9 - CSS ... coming soon

- Inline CSS
- HEX Colors
