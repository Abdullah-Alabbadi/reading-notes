## HTML Images, CSS Color & Text

I hope I was able to cover the topics, there are many topics, but I will mention briefly and beautifully about reading, I hope you like it.

The first thing about; Image and we will talk about;

**How to add images to pages.**

``<img src="images/sea.jpg" alt="description of photo disappear" title="google URL" />``

`<img>` | It is an If we want to add an image to the HTML page we need to use an.

`<src>` | It is a brief tells the browser where it can find the image file location.

`<alt>` | It is a text description of the image which describes if you cannot see it.

`<title>` | It is a to provide additional information about the image.

---

There are **3** places to place the image code, which leads to different appearance;

**before a paragraph:** The paragraph will start on a new line after the image.

**Inside the start of a paragraph:** In the first of the text aligns with the bottom of the image.

**In the middle of a paragraph:** The image is placed between the words of the paragraph that it appears in.

**There are Three Rules for Creating Images ;**

1-we should Save images in the right format.

2-we should Save images of the right size.

3-we should use the correct resolution.

There is a way to use a photo in the same place by using | ``<figure>``

There is a way to add a description to an image by using | ``<figcaption>``

---

**How to add Colour to pages.**

before we get started I would talk about the three colour degree;

**RGB values:** These express colours in terms of how much red, green and blue.
Example: (111,222,130)

**hex codes:** It's six-digit codes that represent the amount of red, green and blue in colour
Example: #42ffdd

**colour names:** There are 147 predefined colours we can use it's
Example: whiteBlue

---

**background colour:** It's to make the background more live by changing the white colour.


There is a lot of ways to colour our background that can be by typing this code of CSS;
---

-----------------------------------------------\

**background-color: rgb(200,200,200);}**
Or

**background-color: DarkCyan;}**

Or

**background-color: #ee3e80;}**

Or

**background-color: white;**

-----------------------------------/

---

**How to add opacity to our pages;**

**opacity:** is The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15%).

we can do that by adding this code in CSS

``opacity: 0.5;``

OR

Merging it with a background like;

``background-color: rgba(0,0,0,0.5);``

---
How to add Text to our pages;

before we get started we should control of; Weight
like **(bold, black).**
Stretch **(Regular, Extended).**
Style like **(Normal, Italic).**

In order to use Style in our text in (HTML), we should to right this code in (CSS);

f``ont-family: Georgia, Times, serif;``

---

How to control in Size of Text;
 In order to use Size in our text in (HTML), 
 
 we should to right this code in (CSS);

``font-size: 12px;``

OR

``font-size: 200%;``

OR

``font-size: 1.3em;``

---

There are Units of Type Size that we can use in Size to get exactly the size that was printed in your brain like:

Pixels: like 24px

Percentages: like 200%

Ems: like 1.3em

---

There is a weight, Style weight of the text we can use it by this code;

font-weight: bold; //text appear like a Bold weight or we can use **(normal)**

font-style: italic;//text appear like a italic Style or we can use **(oblique,normal)**

---

**UpperCase & LowerCase text-transform**

There is an UpperCase, LowerCase and capitalize weight of the text we can use it by this text-transform: uppercase; //text appear like a uppercase or we can use(LowerCase, capitalize )

*__In the end, I hope you enjoying reading, best wishes.__*

