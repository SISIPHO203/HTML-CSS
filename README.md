# HTML-CSS
HTML is a markup language that is used in website,apps and webpages.It informs user's computer about various elements on the code.

CSS is used for styling the pages using  fonts,sizes clour and adding annimations on your website to make it look good.

Javascript is a language that is used is create interactive website.If there are lines of code that javascript does not understand it refuses to run unlike HTML that figures out what you were trying to do and fix your mistake.

#HTML formating

HTML uses tags to mark different elements, there is a opening tag <>, closing tag</>.
example of opening and closing tag on list the opening tag for list is <li> and the closing tag is</li>, some elements require both opening and closing tags while others do not require closing tag.
HTML Headline:the headlines comes in 6 different types from h1,h2, h3, h4, h5 and h6, each headline has a distinct visual effect where h1 is the largest headline and h6 is the smallest.

#HTML italic and bold:

we use <i> for italic and <b> for bold.
we use italic element to to apply visual italics it also goes with <em> element to add emphasis on text.they look the same visualy but they have different meaning
we also have two elements to emphisize or make something bold we use <b> to make somethimg bold visually and we use <strong> which is used to show the importance and seriousness of a point.

#HTML Lists:

we have three types of lists, un-ordered list,ordered list, and description  list .
Each item on the list is enclosed with <li> element.To identify the entire list and to specify its type we wrap all elements in <ul> for un-orderd list,<ol> for orderd list 
we use ordered list to indicate that there's a specific order to the items on the lis.
Definition list is used when we want to create a list that resembles a key value pair.To create definition list we use specific elements, a <dt> tag for definition term and <dd> for definition description.

#HTML QOUTES:
we use  <blockquote> element to quote paragraphs and <cite> element to show citations.when we want to quote a line we use inline quotes<q>.

Date elements:we use datetime attribute that helps us to speciy date or time format in a way that a computer understands.it is written like this <time datetime = year-month-day> specify the date </time>.
Time elements:we use also use the datetime element to specify time format  e.g <time datetime ="hh:mm:ss.ddd">specify the time</time>.
we can also combine date and time using datetime attribute, stating with date then time.

#Subscripts , superscripts and small text:

they are used when you want to mark up parts of content that have a different meaning than the rest.
Subscripts are characters that are set below the baseline of text,while superscripts are characters that are set above the baseline of text.

Class attribute:it allows us to assign reusable name to any element, it can be styled using CSS for all elements that are sharing the class.
ID attribute:it allows us to use unique name once on a HTML page, it can be used to CSS targeting and Javascript specific elements and targeted links .it ensures that there will bwe only one element with that ID 
Lang attribute : it allows us to specify the language of the content using short language code.
dir attribute: it indicates the direction in which the text flows,using "LTR" for left-to-right scripts and "RTL"for right-to-left.


Comments help in enhancing code readability and explains its purpose, comments are inserted by typing "<!--" at the start and "-->" at the end.Comments also helps to prevent confusion when the code does not funcion as expected.

in HTML elemnts can be written in uppercase and lowercase also browser support is not affected either way, so you can write with any case you want.
Non-breaking space in HTML: they tell the browser not to break the like between two words. we use "&nbs;"to insert a non-breaking space between the two names so that they stay in same line.when you add multiple spaces on HTML, browsers ignore the spaces and recognize only one but non-breaking space are not ignored by browsers if you include one you can have two spaces between words.

#HTML LINKS

HTML links: when we want to create a link we use A element ,to do this we need to add href attribute with URL enclosed in quotes, the URL is where the link will take us.href is placed between the opening and the closing A tags.We can place texts, images to make them clickable.
absolute URLs they point to aprecise location on the web.
HTTP and HTTPS :"S"stand for secure it is recommended that you use HTTPS for enhanced security.

#HTMLimages and graphics

Images: to make your web not be dull you can add images , we use image element that is written as IMG,there are four attributes that need to be included for every image.
First, SRC attribute which tells the browse which image file to load
Second, ALT attribute which provides the text description of the image.
Lastly, width and height attributes which determine the size of the image.
Image Formats: there are four commonly used image formats which are GIF, SVG,JPG and PNG ,each with its own strength and weeaknesses when it comes to compressing images.

#Responsive images

CSS offers a solution for displaying images in different sizes to accomodate large screens and small screens.
when dealing with high resolution images that contain large amount of data it can be problematic for users with slow network connections or limited data as this takes long time to download and can be costly.To solve this issue ocnsider reducing the size of images,making them physically smaller also by reducing amount of coloured data.

#Responsive width
we use the image element and src attribute to display images we indicate the width of each file .
the browser decides which image to show based on device density and viewport width.This can lead to problem where the choosen image does not fit the layout you want.
the browser makes this decision early in the loading process, before it even knows the layout details.it does not know the size of the box where the image will go.

#Figcaption and figures

We have two additional elements to consider when it comes images, or specifically figures.
First show a picture and add caption to it. 
use the figcaption element to wrap the text and designate it as a caption, then put the image and the caption together in a figure element, this gives the browser information about the relationship between the image and the caption.
Figures can be used for more than just images e.g using them for interactive graphic.
Figcaption and figure elements are really useful for anything that serves as visual illustration or demonstration of a concept that needs a caption.

#wORKING WITH AUDIO

The audio element has opening tag and closing tag unlike image element that has one tag.
there are differnt audio file formats e.g MP3 file. We need to let the browser know that we want it to provide some controls like aplay button, timeline, and volume control .Using the browser's built-in controls is optional.
You can create your own using JavaScript and the HTML media element API instead of relying on pre-built audio player controls.
There are other attributes that can be used with audio element too ,for example "loop" will make the file repeat from beginning once it reaches the end.
Äutoplay" can automatically play the audio as soon as the page loads.
The audio element is an excellent tool for embedding audio files and a player on a webpage.

#Working with video

We can easily put videos on web pages using the HTML video element. This element also has an opening tag and closing tag.
To display a video we use the source attribute to sppecify the video file and if the controls attribute is added, the browser will automatically create a video player.
Video files contain a lot of data, and if not compressed they become too large to be efficiently transmitted over the internrt.

#Working with captions and subtitles

We are going to use the track element and link it to a text file to add captions to the video.This element adds functionality to the video player, allowing viewrs to toggle captions on and off or switch between different subtitle options.
On web a file formart called ibvitt,which stands for web video text tracks ,will be used. 

#Embeeding media via Iframes

There is awide range of content that can be embedded on a page. It is a common practice to embed complex contet from a service that handles the technical aspects.
When building a website also consider security aspects related to the iframe element.If multiple people will be adding content to the system ,do not allow all iframes without thinking about secirity measures.

#HTML LANGUAGE SUPPORT

lang attribute is used to specify the language of a webpage,set it on the opening tag of HTML e.g lang ="en-UK" .Set the language on the main element that wraps everything else, which is usually the HTML element
If your web page has multiple languages ,specifyy the language for each part of the content, use lang attribuute on any element.
it is important to also specify the content's direction.If the content on your page follows the same direction, define it once on the outer HTML element.
Each language uses its own set of characters or alphabet, so do not forget to set rhe charset for your project.
Inform the browser about the character set being used, to specify charset in HTML simply include a meta charset tag that equals UTD-8. Place this meta element within the head element on every page of the website.


#HTML generic elemnts ,div, span
DIV: block-level element
Span: inline element
Sometimes we need a method to group elements or highlight a phrase ,other times  we need to target a specific part of the DOM with CSS or JavaScript.


#HTML page
 Firstly the file should begin with doctype statement , which indicates the era of this HTML file.
 Next we enclose everything lese on the page within an HTML elemnt , which maens an element named HTML, place the opening HTML tag at the top and the closing HTML tag at the bottom.
 At the beginning specify few things . declare the language being used and content flow direction .
Inside the HTML element, there aretwo main parts where everything goes ,the head and the body create them using head and body elements.
THe head contains all the metadata that the browser needs to know but will not display on the page.
Te body , on the othe hand , is foe all the content and composed of various elements., the body is were the most action happens.


#Document head

Inside the head of the a webpage , you put information that the browser needs to know about the website.
Ensure that meta elements are only placed inside the head as they provide metadata about the page .
The web page tittle is what appears on the browser tab or bookmark when it is saved, it is the name that uppears under top sites when new browser is opened. 

The link element is cruicial component used extensively within head section.It serves to connect various assets that should load such as CSS files, fonts and favicons. 
To inform the browser about the type of asset, utilize the rel attribute.
href attribute is employed to specify the URL for asset.
Script tag is acommonly used element in HTML document's head , it instructs the browser to load a JavaScript file.

#Content structuring 

typical structure inside the body , ther are six elements to understand

Main : the main element is used once per webpage and tells the browser where the main content is located.

Header: header is used for site headers, article headers, and headers within the content. Header is usually found at the top of most web pages and may include a logo, site name, and navigation.

Footer: the footer signiies that there are extra things to convey, regardless of its position on the page.

Article: this element wraps around any type of content unit, whether it as a long written article , a shot snippet, a teaser card,a tweet, or even an app element . It represents a standalone unit of content.

Section: this element is used to mark sections of content, it is also useful for dividing different topic zones on a website.

Aside:thise element is for content that is off to the sid, like sidebar information or additional details that accompany and article but are not part of its main flow.

#Form fundamentals

Form fields they are used for various tasks like logging into webstites , making purchases, conducting searches and adding content. 
By using HTML form elements, we ensure that forms will be compatible with all devices and input/output hardware , even those we may not be familiar with.
To create a form we start with the form element which informs the browser about the presence of a form using opening and closing tags.
Use input element to provide places for users to type in .
use button element for users to submit the form , the text on the button can be customized to whatever is required.

#HTML TABLES
to create an HTML table , you use several different HTML elements in just the right combination. Table,TR, TH and TD.

The Table element wraps around the whole table, around all content and markup for that table, making the beginning and the end of the table itself.
 
The TR elementstands for table row and wraps around a set of eleemnts, defining them as belonging to the same row .

 The TH element stands for table header and defines a header for a column.

 The TD element stands for table data and marks up the cells of data.
 

# INTRODUCTION TO CSS

CSS: is a style sheet thst holds all the styles for yur webpage, this adds visual apeal to your web page.
CSS has two parts  the selector and the declaration block.
The selector specifies a pattern in the HTML and if te pattern matches the styles within the declaration block applied to the corresponding HTML elements.
In each style declaration consists of two parts a PROPERTY and a VALUE.
The fiesrt aspect of CSS id the selector because it is essential to be able to select specific elements in our HTML. 




