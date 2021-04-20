### Read: 14a - CSS Transforms, Transitions, and Animations

<br>

**Transforms:** it's like a way that helps us to make our code more beautiful and have a live animation in Transforms we can select the place of element and change it in any way we want.

<br>

#### **Type of Transforms:**

**1-two-dimensional.**

**2-three-dimensional.**

<br>

**Transform Syntax:** it has an alike value that specifies the transform type followed by a specific amount inside parentheses for example:

`div {`
`-webkit-transform: scale(1.5);`

`-moz-transform: scale(1.5);`

`-o-transform: scale(1.5);`

`transform: scale(1.5);`


`}`

---

### 2D Transforms

It's a dimensional plane or three it's work on x, y, And z it helps us to detect the width, height also depth of, so if we want to use it we can bay type this code:

**In HTML**

`<figure class="box-3">Box 3</figure>`

`<figure class="box-4">Box 4</figure>`

**In CSS**

`.box-3 { transform: rotate(20deg); }`

`.box-4 { transform: rotate(-55deg); }`

### 3D Transforms

We can talk it has a better diminution that makes us see element more realistic and real that by change value of z for example:

`<figure class="box-1">Box 1</figure>`

`<figure class="box-2">Box 2</figure>`

`<figure class="box-3">Box 3</figure>`

<br>

`.box-1 { transform: perspective(200px) rotateX(45deg); }`

`.box-2 { transform: perspective(200px) rotateY(45deg); }`

`.box-3 { transform: perspective(200px) rotateZ(45deg); }`

### Transitions, and Animations

they are like a video, that repeats the movement of the photo or the thing we selected in a specific border, if we want to use it we should type like this code to configure animation.

`.box {`
`background: #2db34a; //color`

`transition-property: background;// attripute` `for show in a background`

`transition-duration: 2s; // like speed for animation`

`transition-timing-function: linear;`

`}`

`.box:hover {`

`background: #ff7b29;`
`}`

---

If you want to dazzle the user  you can do that by 8 things is important using it's also lead to using animation

**1-Inset border**

**2-Swing**

**3-3D shadow**

**4-Square to circle**

**5-Rotate elements**

**6-Grow & Shrink**

**7-Change color**

**8-Fade in**

#### There is a website that can help you to nake your style in a faster way: Click here to see

If you want to use animation CSS3: Click here to see.

or for 404: Click here to see.

also for Pure CSS Bounce Animation: Click here to see.

By using These sites can save you a lot of time designing

**_In the end, I hope you enjoying reading, best wishes_**

**_resource:_**

<https://learn.shayhowe.com/advanced-html-css/css-transforms/>

<https://learn.shayhowe.com/advanced-html-css/transitions-animations/>

<https://www.webdesignerdepot.com/2014/05/8-simple-css3-transitions-that-will-wow-your-users/>

<https://codepen.io/retyui/pen/ByoaXV>

<https://codepen.io/akshaychauhan/pen/oAfae>

<https://codepen.io/kieranfivestars/pen/MYdQxX>

<https://codepen.io/dp_lewis/pen/gCfBv>
