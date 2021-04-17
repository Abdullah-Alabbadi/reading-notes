## Images & Practical Information.

#### In this reading, we will talk about important things in HTML like

##### 1-how to Controlling the size of images by using CSS

##### 2-Aligning images in CSS.

##### 3-Adding background images.

---

We can **control the size** of an image using the height and width properties by using CSS code for example;

**HTML ;**

`<img src="images/magnolia-small.jpg"class="small" alt="Magnolia" />`

**CSS ;**

`img.small {`

`width: 100px;`

`height: 100px;`

`}`

---

We can **control the Aligning** of an image by using CSS by type:

**HTML ;**

for example:

`<p><img src="images/flower.jpg"` `class="align-left medium" />`

`<b>Magnolia</b>`

`Lorem ipsum dolor sit amet, consectetur adipiscing.</p>`

**CSS ;**

`img.align-left {`

`float: left;`

`margin-right: 20px;}`

We can also add Centering images by using code ;

**HTML ;**

`<p><img src="flower-cent.jpg"`
`class="align-center medium" />`

<`b>Magnolia</b> Lorem ipsum dolor sit amet, consectetur adipiscing</p>`

**CSS ;**

`img.align-center {`

`display: block;`

`margin: 0px auto;}`

---

- We can add background images to our web page the background-image property allows you to place an image behind any HTML element by using simple code in CSS code;

`header {`
`background-image: url("images/love.jpg"`

- There is an important thing in an image called **(Repeating Images)** that makes the photo repeated that has 4 attributes;

**1-no-repeat:** make the image only shown once.

**2-repeat-y:** The image is repeated vertically only.

**3-repeat-x:** The image is repeated horizontally only.

**4-repeat:** The background image is repeated both horizontally and vertically.

! by using this code we can use these command code;

background-repeat: repeat-x;

- manage scroll or fixed image ;

**1-scroll:** The background image moves up and down as the user scrolls.

**2-fixed:** The background image stays in the same position on the page.

to use a scroll or fixed we use this command in CSS;

`background-attachment: fixed;}`

- To put the background in the center of your web we use;

we can use the background-position property while no repeted to specify where in the browser window the background image should be placed

code to implement;

`.my{`

`background-repeat: no-repeat;`
`background-position: center top;}`

OR using percentage ;

`background-position: 30% 30%;}`

We can use this diminsion listed below or we should use or % as we talk before ;

like;

**:left top;**

**:left center;**

**:left bottom;**

**:center top;**

**:center center;**

**:center bottom;**

**:right top;**

**:right center;**

**:right bottom;**

- All in one, we have a code that merges all code in one code that's called shorthand background;

`body {`
`background: #ed4334 //color`

`url("img/flower.jpg") //imge dir`

`no-repeat //reapeted`

`top right; } //position`

---

**Practical Information.**

In this section we will talk about;

*Putting your site on the web.*

**Search engine optimization:** is a huge topic and several books have been written on the subject.

**Third-Party Tools:** it's a tool to let us transfer our code and images from your computer to our hosting company, you use by using something known as File Transfer Protocol

*__In the end, I hope you enjoying reading, best wishes.__*
