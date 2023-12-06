# [Web Programming Lab Report](https://anolchakraborty.github.io/Web-Programming-Basics/)

[![College Logo](https://i.ibb.co/K7Wwr8w/college-logo.png)](https://jecassam.ac.in/)

<hr/>

## Submitted By:

||----------|---|------------------------||
|--|--:|:--:|:--|--|
||***Name***|:|*Anol Chakraborty*|
||***Roll no.***|:|*220750007001*|
||***Term***|:|*5<sup>th</sup> Semester*|
||***Course***|:|*B.Tech CSE*|
||**----------**|**---**|**------------------------**|


<hr/>

![powered by](https://img.shields.io/badge/Powered%20By%20Markdown-grey?style=for-the-badge&logo=markdown)

> To view the program source codes in GitHub, [click here](https://github.com/AnolChakraborty/Web-Programming-Basics).

> You can also click the respective  `Lab Work 0--`  of every section to view its output in browser

<hr/>

<div style="break-after:page"></div>

## [Lab Work 001](https://anolchakraborty.github.io/Web-Programming-Basics/lab.001.html)

***Q1:*** Create a Web Page which shows how to use comments in HTML.

***Q2:*** Create a Web Page to demonstrate the use of all the heading tags.

***Q3:*** Check how to use the following Tags and create a web page to show their outputs:&nbsp;&nbsp;`<strong>`, `<em>`, `<ins>`, `<s>`, `<del>`, `<pre>`, `<sub>`, `<sup>`, `<small>`, `<mark>`, `<blockquote>`, `<abbr>`, `<code>`, `<samp>`, `<kbd>`, `<var>`

***Q4:*** Check how to insert special characters (**eg.:** `Copyright symbol`, `Trademark Symbol` etc ) and Emojis in Web Page. 

### <u>*Ans*</u>: 
`HTML Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="shortcut icon" href="assets/favicon.png">
  <title>WP Lab</title>
</head>

<body>
  <hr />
  <!--This is a comment-->
  Hello World, this is my first webpage.
  <!--Comments in an HTML file is not shown in the webpage.-->

  <hr />
  <h1>Heading 1</h1>
  <h2>Heading 2</h2>
  <h3>Heading 3</h3>
  <h4>Heading 4</h4>
  <h5>Heading 5</h5>
  <h6>Heading 6</h6>

  <hr />
  This is my <strong>1<sup>st</sup> HTML Web Page.</strong>
  (using "strong" tag)
  <br>
  <em>CSE</em> (using "em" tag)
  <br>
  <ins>5<sup>th</sup>Semester</ins> (using "ins" tag)
  <br>
  <s>2023</s> (using "s" tag)
  <br>
  <del>Jorhat</del> (using "del" tag)
  <br>
  <pre>2023-2024 (using "pre" tag)</pre>
  <p>
    Ca<sup>2+</sup>+ (OH)<sup>1-</sup>>>> Ca(OH)<sub>2</sub>
	 (using "sup" and "sub" tags)
  </p>
  <p>
    <small>The above reaction is a chemical reaction.</small>
	  (using "small" tag)
  </p>
  <br><mark>This is a highlighted text.</mark>
  (using "mark" tag)
  <br><q>WEB PROGRAMMING LAB</q>
	  (using "q" tag)
  
  <h3><i>Full Stack Web Developer</i></h3>
  <blockquote>The earth is round</blockquote> (using "blockquote" tag)
  <p><abbr title="Jorhat Engineering College">JEC</abbr>is under<abbr
      title="Assam Science and Technology University">ASTU</abbr>
	  (using "abbr" tag)</p>
  <p>
    In python, <code>print</code> function is used for outputs.
    (using "code" tag)
  </p>
  <p>
    Message from the Computer:<br>
    <samp>File Not Found, Press F1 to continue.</samp>
    (using "samp" tag)
  </p>
  <p>---- Shortcuts in MS-Word ----<br>
    Press <kbd>Crtl</kbd> + <kbd>C</kbd> to copy any text.<br>
    Press <kbd>Crtl</kbd> +
    <kbd>X</kbd> to cut any text.<br>
    Press <kbd>Crtl</kbd> + <kbd>V</kbd> to paste any text.<br>
    (using "kbd" tag)
  </p>
  <p>Value of <var>pi</var> is 3.1416 (using "var" tag)</p>

  <hr />
  <p>I &#128159; Web Develpoment.</p>
  <p>&#169; Anol Chakraborty</p>
  &euro;
  <br>&dollar;
  <br>I &#128153; UNIX<br>
  This is a copyright symbol-> &#169;<br>
  This is a Trademark Symbol-> &#8482;<br>
  <hr />
</body>

</html>
```
`Output:`

![Lab Work 001 Output](https://i.ibb.co/WpwpCBV/image-2.png)


## [Lab Work 002](https://anolchakraborty.github.io/Web-Programming-Basics/lab.002.html)

***Q1:*** Create a Web Page to show how to use Ordered List and Description lists.

***Q2:*** Create a Web Page to demonstrate the use of Nested Lists.

***Q3:*** Create a Web Page to show the use of image as a link.

***Q4:*** Create a Web Page to create a link to an e-mail address.

***Q5:*** Create a Web Page to show the use of bookmark.

***Q6:*** Create a table in a Web page to show the usage of `<caption>` tag and use of `colspan`, `rowspan` properties.

### <u>*Ans*</u>: 
`HTML Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="shortcut icon" href="assets/favicon.png">
  <title>WP Lab</title>
</head>

<body>

  <!DOCTYPE html>
  <html lang="en">

  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ordered and Description Lists</title>
  </head>

  <body>
    <h2 id="firstsection">Ordered List and Description List Example</h2>
    <h3>Ordered List:</h3>
    <ol>
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ol>
    <h3>Description List:</h3>
    <dl>
      <dt>Term 1</dt>
      <dd>Description for Term 1.</dd>

      <dt>Term 2</dt>
      <dd>Description for Term 2.</dd>

      <dt>Term 3</dt>
      <dd>Description for Term 3.</dd>
    </dl>

    <hr>
    <h2>Nested Lists Example</h2>
    <ul>
      <li>Item 1</li>
      <li>Item 2
        <ul>
          <li>Subitem 2.1</li>
          <li>Subitem 2.2</li>
        </ul>
      </li>
      <li>Item 3</li>
    </ul>

    <hr>
    <h2>Email Link Example</h2>
    <p>
      Contact me via email:
      <a href="mailto:user@mail.com">user@mail.com</a>
    </p>

    <hr>
    <h2>Bookmark Example</h2>
    <p><a href="#lastsection">Go to Last Section</a></p>
    <p><a href="#firstsection">Go to First Section</a></p>

    <hr>
    <h2>Image as Link Example</h2>
    <a href="https://jecassam.ac.in/">
      <img src="assets/college logo.png" alt="JEC Official Website">
    </a>

    <hr>
    <h2 id="lastsection">Table Example with Caption, colspan, and rowspan</h2>
    <table border="2">
      <caption>Student Details</caption>
      <tr>
        <th>Name</th>
        <th>Age</th>
        <th>Total Marks</th>
      </tr>
      <tr>
        <td>Anol Chakraborty</td>
        <td>22</td>
        <td rowspan="3">100</td>
      </tr>
      <tr>
        <td>Ankit Chakraborty</td>
        <td>21</td>
      </tr>
      <tr>
        <td>Rohan Kayastha</td>
        <td>23</td>
      </tr>
      <tr>
        <td colspan="3">Total Students : 3</td>
      </tr>
    </table>
  </body>

  </html>
```
`Output:`

![Lab Work 002 Output](https://i.ibb.co/xS6CqCy/image-3.png)

## [Lab Work 003](https://anolchakraborty.github.io/Web-Programming-Basics/lab.003.html)

***Q1:*** Create a Web Page to demonstrate the following `<form>` elements:
- `<fieldset>` and `<legend>`
- Input types: `date`, `file` and `color`
- `<datalist>`
- `<optgroup>`
	
***Q2:*** Create a Web Page to generate a form described below. The form should have the following features:
- The first two text boxes must not allow input of more than 10 characters.
- The contents of the third text box should not be modifiable. 
- Clicking on the **`AC`** Button should clear the contents of the first two text boxes.

### <u>*Ans*</u>: 
`HTML Code:`
``` HTMl
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="shortcut icon" href="assets/favicon.png">  
  <title>WP Lab</title>
</head>

<body>
  <h1>Form Elements Example</h1>

  <form>
    <fieldset>
      <legend><i>
          <h3>Personal Information</h3>
        </i></legend>

      <!-- Text input with max length -->
      <label for="input1">First Name (max 10 characters):</label>
      <input type="text" id="input1" placeholder="Enter First Name" maxlength="10">
      <br><br>
      <!-- Text input with max length -->
      <label for="input2">Second Name (max 10 characters):</label>
      <input type="text" id="input2" placeholder="Enter Second Name" maxlength="10">
      <br><br>
      <!-- Text input with readonly attribute -->
      <label for="input3">Address (readonly):</label>
      <input type="text" id="input3" value="Jorhat" readonly>
      <br>
      <br>
      <!-- Date input -->
      <label for="dateInput">Date:</label>
      <input type="date" id="dateInput">
      <br>
      <br>
      <!-- File input -->
      <label for="fileInput">File:</label>
      <input type="file" id="fileInput">
      <br><br>
      <!-- Color input -->
      <label for="colorInput">Color:</label>
      <input type="color" id="colorInput" value="#A020F0">
      <br><br>
      <!-- Datalist -->
      <label for="datalistInput">Datalist:</label>
      <input list="datalistOptions" id="datalistInput">
      <datalist id="datalistOptions">
        <option value="Option 1">
        <option value="Option 2">
        <option value="Option 3">
      </datalist>
      <br><br>
      <!-- Optgroup -->
      <label for="optgroupInput">Optgroup:</label>
      <select id="optgroupInput">
        <optgroup label="Group 1">
          <option value="Option 1.1">Option 1.1</option>
          <option value="Option 1.2">Option 1.2</option>
        </optgroup>
        <optgroup label="Group 2">
          <option value="Option 2.1">Option 2.1</option>
          <option value="Option 2.2">Option 2.2</option>
        </optgroup>
      </select>
		<br><br>
		<button type="reset"><strong>AC</strong></button>
    </fieldset>
  </form>
</body>

</html>
```
`Output:`

![Lab Work 003 Output](https://i.ibb.co/55Gs3Wc/Screenshot-20231207-013209.png)

## [Lab Work 004](https://anolchakraborty.github.io/Web-Programming-Basics/lab.004.html)

***Q1:*** Create a Web Page to show how to load a HTML document in an `iframe`, when the user clicks on the link (***i.e.,*** `iframe`  as the target of a link.)

***Q2:*** Create a Web Page to show how to play a YouTube video in a page.

***Q3:*** Create a Web Page to play a video file in the page.

***Q4:*** Create a Web Page to show how to include a Favicon.

### <u>*Ans*</u>: 
`HTML Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="assets/favicon.png">
    <title>WP LAB</title>
</head>

<body style="text-align: center;margin-top: 10px">
    <h1>Hello World</h1>
    <br>
    <p>
    <h3><i><u>This is an iframe - <a href="https://astuerp.in/" 
        target="my-iframe">
        click me to load a webpage in this iframe</a></u></i></h3>
    <iframe src="assets/frame.html" width="30%" height="250px" 
    alt="iframe example" name="my-iframe">
    </iframe>
    </p>
    <br>
    <p>
    <h3><i><u>This is a normal image</u></i></h3>
    <img src="assets/pic.jpg" width="15%" alt="">
    </p>
    <br>
    <p>
    <h3><i><u>This is an image with map</u></i></h3>
    <img src="assets/google-wikipedia.png" usemap="#image-map">
    <map name="image-map">
        <area target="_blank" alt="Google" title="Google" 
        href="https://www.google.com" coords="259,0,0,93"
            shape="rect">
        <area target="_blank" alt="Wikipedia" title="Wikipedia" 
        href="https://www.wikipedia.org/" coords="311,46,50"
            shape="circle">
    </map>
    </p>
    <br>
    <p>
    <h3><i><u>This is an audio sample</i></u></h3>
    <audio controls autoplay>
        <source src="assets/audio.mp3" type="audio/mpeg">
    </audio>
    </p>
    <br>
    <p>
    <h3><i><u>This is a local video sample</i></u></h3>
    <video width="20%" autoplay muted controls>
        <source src="assets/video.mp4" type="video/mp4">
    </video>
    </p>
    <br>
    <p>
    <h3><i><u>This is a Youtube video in iframe</i></u></h3>
    <iframe width="560" height="315" 
    src="https://www.youtube.com/embed/J1f5b4vcxCQ?si=-syAlbR7A8NvXBR5"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; encrypted-media; picture-in-picture;"
        allowfullscreen></iframe>
    </p>
</body>
</html>
```
`Output:`

![Lab Work 004 Output](https://i.ibb.co/1GdFTRj/image-5.png)


## [Lab Work 005](https://anolchakraborty.github.io/Web-Programming-Basics/lab.005.html)

***Q1:*** Create a Web Page to demonstrate different ways to specify colours to CSS (Predefined colour names `RGB`, `HEX` ,`HSL`,`HSLA`),

***Q2:*** Create a Web Page to demonstrate some of the common font properties in CSS (***eg.:*** `font-family`, `font-style`, `font-weight`, `font-variety`, `font-size`).

***Q3:*** Create a Web Page to demonstrate how to us e-Web Fonts in CSS.

### <u>*Ans*</u>: 
`HTML Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Lab Work</title>
    <link rel="shortcut icon" href="assets/favicon.png">
    <link rel="stylesheet" href="assets/style.css">
</head>
<body>
    <div class="container" id="div1">
        <div><u>Using System/Local Font `z003`</u></div>
        <br>
        <div id="div1a">COLOR using RGB</div>
        <div id="div1b">COLOR using RGBA</div>
        <div id="div1c">COLOR using HEX</div>
    </div>
    <div class="container" id="div2">
        <div><u>Using Web Font `kablammo`</u></div>
        <br>
        <div id="div2a">COLOR using HSL</div>
        <div id="div2b">COLOR using HSLA</div>
        
    </div>
</body>
</html>
```
<br>`CSS Code:`
``` CSS
@import url('https://fonts.googleapis.com/css2?family=Kablammo&family=Roboto:wght@100');

@font-face {
    font-family: "z003.local";
    src: url("./Z003.ttf");
}

div {
    font-size: 45px;
    font-weight: 900;
    font-style: italic;
    font-variant: small-caps;
}

.container {
    padding: 50px;
    border: 5px solid red;
    margin-left: 5%;
    margin-top: 5%;
    margin-right: 50%;
}

#div1 {
    font-family: 'z003.local';
    /* font-family: z003; */
}

#div2 {
    font-family: Kablammo;
}

#div1a {
    color: rgb(7, 155, 181);
}

#div1b {
    color: rgba(255, 0, 0, 0.2);
}

#div1c {
    color: #08b70e;
}

#div2a {
    color: hsl(252, 84%, 39%);
}

#div2b {
    color: hsla(317, 100%, 57%, 0.381);
}
```
`Output:`

![Lab Work 005 Output](https://i.ibb.co/rtJVbGM/Screenshot-20231207-010920.png)

## [Lab Work 006](https://anolchakraborty.github.io/Web-Programming-Basics/lab.006.html)

***Q1:*** Create a Web Page to demonstrate how to create rounded-corners, box-shadow, & text-shadow in CSS

***Q2:*** Create a Web Page to demonstrate some of the 2-D transforms in CSS (***eg.:*** `translate()`, `rotate()`, `scale()`,  `skew()`).

***Q3:*** Create a Web Page to demonstrate translations in CSS.

***Q4:*** Create a Web Page to demonstrate how to animate objects using `@keyframes` in CSS.

### <u>*Ans*</u>: 
`HTML & CSS Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <link rel="shortcut icon" href="assets/favicon.png">
    <title>Lab Work</title>
    <style>
        .mydiv {
            text-align: center;
            margin: auto;
            align-items: center;
            margin-top: 370px;
        }

        .custom-button {
            width: 200px;
            height: 100px;
            background-color: #2981bb;
            border: none;
            color: #fff;
            text-align: center;
            font-size: 20px;
            line-height: 30px;
            cursor: pointer;
            transform: translate(0, 0) rotate(0deg) scale(1) skew(0deg);
            border-radius: 15px;
            box-shadow: 21px 20px 10px rgba(0, 0, 0, 0.2);
            text-shadow: 4px 4px 8px rgba(0, 0, 0, 0.712);
            transition: transform 0.3s, box-shadow 0.3s, text-shadow 0.3s;
        }

        .custom-button:hover {
            transform: translate(5px, -5px) rotate(5deg) scale(1.1) skew(10deg);
            box-shadow: 8px 8px 12px rgba(0, 0, 0, 0.3);
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.5);
        }

        .custom-button:active {
            color: red;
            background-color: cadetblue;
            transform: translate(0, 0) rotate(70deg) scale(10) skew(0deg);
        }

        .anime {
            border-radius: 15px;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.74);
            width: 100px;
            height: 50px;
            background-color: rgba(247, 0, 255, 0.63);
            position: relative;
            animation-name: frames;
            animation-duration: 15s;
            animation-delay: 0s;
            animation-timing-function: cubic-bezier(0.215, 0.610, 0.355, 1);
            animation-iteration-count: infinite;
        }

        @keyframes frames {
            0% {
                background-color: red;
                left: 0px;
                top: 0px;
            }

            25% {
                background-color: yellow;
                left: 100%;
                top: 0;
            }

            50% {
                background-color: blue;
                left: 900px;
                top: 900px;
            }

            75% {
                background-color: green;
                left: 0px;
                top: 0px;
            }

            100% {
                background-color: red;
                left: 0%;
                top: 0px;
            }
        }
    </style>
</head>

<body>
    <div class="anime"></div>
    <div class="mydiv">
        <button class="custom-button">I'm a button, please click me</button>
    </div>
</body>

</html>
```
`Output:`

![Lab Work 006 Output](https://i.ibb.co/yBYY15k/image-6.png)

## [Lab Work 007](https://anolchakraborty.github.io/Web-Programming-Basics/lab.007.html)

***Q1:*** Create a Web Page to demonstrate the use of `media queries` in CSS.

***Q2:*** Create a Web Page to demonstrate Responsive Web Design in CSS.

### <u>*Ans*</u>: 
`HTML & CSS Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="assets/favicon.png">

    <title>Lab Work</title>
    <style>
        .mydiv span::before {
            content: "Welcome!";
        }

        body {
            padding-left: 10px;
            background-color: rgb(255, 255, 255);
        }

        /* up to 400px */
        @media (max-width: 400px) {
            body {
                background-color: rgb(255, 196, 196);
            }

            .mydiv span::before {
                font-size: 20px;
                content: "Welcome to the extra-small screen!";
            }
        }

        /* 401px to 600px */
        @media (min-width: 401px) and (max-width: 600px) {
            body {
                background-color: rgb(255, 236, 196);
            }

            .mydiv span::before {
                font-size: 30px;
                content: "Welcome to the small screen!";
            }
        }

        /* 601px to 1024px */
        @media (min-width: 601px) and (max-width: 1024px) {
            body {
                background-color: rgb(196, 255, 196);
            }

            .mydiv span::before {
                font-size: 45px;
                content: "Welcome to the medium screen!";
            }
        }

        /* 1025px to 1440px*/
        @media (min-width: 1025px) and (max-width: 1440px) {
            body {
                background-color: rgb(196, 210, 255);
            }

            .mydiv span::before {
                font-size: 85px;
                content: "Welcome to the large screen!";
            }
        }

        /* 1441px and above */
        @media (min-width: 1441px) {
            body {
                background-color: rgb(255, 196, 252);
            }

            .mydiv span::before {
                font-size: 100px;
                content: "Welcome to the extra-large screen!";
            }
        }
    </style>
</head>

<body>
    <div class="mydiv"><span></span></div>
    <br><hr><br>
    <div style="font-size: 5vw;">This is non media query text</div>
</body>

</html>
```
`Output:`

![Lab Work 007 Output](https://i.ibb.co/D4KQdXn/image-10.png)

## [Lab Work 008](https://anolchakraborty.github.io/Web-Programming-Basics/lab.008.html)

***Q1:*** Create a Web Page to demonstrate the use of JavaScript functions `alert()`, `confirm()` & `prompt()`.

***Q2:*** Using JavaScript, check if a given integer is Positive, Negative or neither (***i.e*** Zero)

***Q3:*** Using JavaScript, check if a given positive integer is Prime or not.

***Q4:*** Using JavaScript, calculate and print the first 20 numbers of the Fibonacci Series.

### <u>*Ans*</u>: 
`HTML & JS Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="assets/favicon.png">
    <title>JS Demonstration</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            zoom: 1.4;
            padding-left: 20px;
        }
    </style>
</head>

<body>

    <h2>Javascript Lab Work</h2>
    <br>
    <hr>
    <br>
    <li>
        <label for="first">Usage
            of&nbsp;&nbsp;&nbsp;<code>prompt()</code>&nbsp;,&nbsp;&nbsp;
            <code>confirm()</code>&nbsp; & &nbsp;<code>alert()</code>
            &nbsp;&nbsp;&#8680;&nbsp;</label>
        <button name="first" onclick="first()">Click me !</button>
    </li>
    <br>
    <li>
        <label for="second">Check if a given number is poistive or negative or
            neither(zero)&nbsp;&nbsp;&#8680;&nbsp;</label>
        <button name="second" onclick="second()">Click me !</button>
    </li>
    <br>
    <li>
        <label for="third">Check if a given numner is prime or not
            &nbsp;&nbsp;&#8680;&nbsp;</label>
        <button name="third" onclick="third()">Click me !</button>
    </li>
    <br>
    <li>
        <label id="fourth1" for="fourth">
            Calculate & print first 20 numbers of fibonacci
            series&nbsp;&nbsp;&#8680;&nbsp;</label>
        <button id="fourth2" name="fourth" onclick="fourth()">
            Click me !
        </button>
    </li>
</body>


<script>
    function first() {
        var1 = prompt("Enter first number", "");
        var2 = prompt("Enter second number", "");

        if (isNaN(parseFloat(var1)) == 1 || isNaN(parseFloat(var2)) == 1) {
            alert("Please enter valid number(s) !");
            return;
        }

        var3 = confirm("Would you like to add " + var1 + " & " + var2);

        if (var3 == true) {
            var4 = parseFloat(var1) + parseFloat(var2);
            alert("The result is : " + var4);
            return;
        }

        alert("Thanks !!");
        return;
    }


    function second() {
        var1 = prompt("Enter any number", "");

        if (isNaN(parseFloat(var1)) == 0) {
            if (parseFloat(var1) < 0) {
                alert("The number is negative");
            } else if (parseFloat(var1) > 0) {
                alert("The number is positive");
            } else {
                alert("The number equalls zero(0)");
            }
            return;
        }
        alert("Eneter a valid number !");
    }

    function third() {
        var1 = prompt("Enter any number", "");
        if (isNaN(parseFloat(var1)) == 0) {
            if (parseFloat(var1) == 1) {
                alert("1 is neither prime nor composite");
                return;

            } else if (var1 > 1) {
                
                for (i = 2; i < var1; i++) {
                    if (var1 % i == 0) {
                        alert(var1 + " is not a prime number");
                        return;
                    }
                }
                
                alert(var1 + " is a prime number");
                return;
            }
        }

        alert("Eneter a valid number (greater than 0) !");
        return;
    }


    function fourth() {
        let n1 = 0, n2 = 1, nextTerm;
        var var1 = "";
        for (let i = 1; i <= 20; i++) {
            var1 = var1 + " " + n1;
            nextTerm = n1 + n2;
            n1 = n2;
            n2 = nextTerm;
        }
        str = "First 20 numbers of fibonacci series is : <i>" + var1 + "</i>"
        document.getElementById("fourth1").innerHTML = str;
        document.getElementById("fourth2").style.display = 'none';

    }
</script>

</html>
```
`Output:`

![Lab Work 008 Output](https://i.ibb.co/DtbYvBj/image-18.png)

## [Lab Work 009](https://anolchakraborty.github.io/Web-Programming-Basics/lab.009.html)

***Q1:*** Create a '*Simple Calculator*' in HTML, add functionality to it so that the arithmetic operations can be carried out. You may also add some styling so that the numbers and the components are properly aligned, and are of proper size.

### <u>*Ans*</u>: 
`HTML, JS & CSS Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="assets/favicon.png">
    <title>JS Lab</title>
    <link rel="stylesheet" 
        href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" 
        crossorigin="anonymous">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            zoom: 1.2;
            padding-left: 50px;
            padding-top: 50px;
            padding-right: 800px;
        }

        input[type=number]::-webkit-inner-spin-button,
        input[type=number]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
            margin: 0;
        }
    </style>
</head>

<body>
    <h2>Javascript Lab Work</h2>
    <br>
    <hr>
    <br>
    <form>
        <div class="form-group" onsubmit="return false;">
            <label>First Number :</label>
            <input style="width: 50%;" type="number" class="form-control" 
            id="num1" placeholder="Enter first number">
        </div>
        <div class="form-group">
            <label>Second Number :</label>
            <input style="width: 50%;" type="number" class="form-control" 
            id="num2" placeholder="Enter second number">
        </div>

        <div id="out" class="form-group" style=" display:none;">
            <label for="outout" class="form-text text-muted">
                The result is :
            </label>
            <input style="width: 50%;" disabled="readonly" type="number" 
            class="form-control" id="output">
        </div>

        <div class="form-group">
            <small id="info" class="form-text text-muted">
                Click on the respective operator button to calculate the
                relevant operation & <b>AC</b> to clear output</small>
        </div>
    </form>

    <button class="btn btn-secondary" onclick="clearInput()">AC</button>
    <button class="btn btn-primary" onclick="add()">+</button>
    <button class="btn btn-primary" onclick="subtract()">-</button>
    <button class="btn btn-primary" onclick="multiply()">*</button>
    <button class="btn btn-primary" onclick="divide()">/</button>

</body>
<script>
    clearInput = () => {
        document.getElementById("num1").value = ""
        document.getElementById("num2").value = ""
        document.getElementById("out").style.display = "none";
    };

    add = () => {
        let num1 = parseFloat(document.getElementById("num1").value);
        let num2 = parseFloat(document.getElementById("num2").value);
        if (isNaN(num1) || isNaN(num2)) {
            alert("Enter two numbers to do this specific operation !");
            return false;
        }

        let output = num1 + num2;

        document.getElementById("output").value = output;
        document.getElementById("out").style.display = "block";
    };

    subtract = () => {
        let num1 = parseFloat(document.getElementById("num1").value);
        let num2 = parseFloat(document.getElementById("num2").value);

        if (isNaN(num1) || isNaN(num2)) {
            alert("Enter two numbers to do this specific operation !");
            return false;
        }
        let output = num1 - num2;

        document.getElementById("output").value = output;
        document.getElementById("out").style.display = "block";
    };

    multiply = () => {
        let num1 = parseFloat(document.getElementById("num1").value);
        let num2 = parseFloat(document.getElementById("num2").value);

        if (isNaN(num1) || isNaN(num2)) {
            alert("Enter two numbers to do this specific operation !");
            return false;
        }
        let output = num1 * num2;

        document.getElementById("output").value = output;
        document.getElementById("out").style.display = "block";
    };

    divide = () => {
        let num1 = parseFloat(document.getElementById("num1").value);
        let num2 = parseFloat(document.getElementById("num2").value);

        if (isNaN(num1) || isNaN(num2)) {
            alert("Enter two numbers to do this specific operation !");
            return false;
        }

        if (num2 == 0) {
            alert("Can't divide a number by zero !");
            return false;
        }
        let output = num1 / num2;

        document.getElementById("output").value = output;
        document.getElementById("out").style.display = "block";
    }

</script>

</html>
```
`Output:`

![Lab Work 009 Output](https://i.ibb.co/58s97Wf/Screenshot-20231207-012913.png)

## [Lab Work 010](https://anolchakraborty.github.io/Web-Programming-Basics/lab.010.html)

***Q1:*** Create a Web Page to demonstrate some of the methods of JavaScript arrays (***eg.:*** `concat()`, `join()`, `indexOf()`, `sort()`, `pop()` etc).

***Q2:*** Create a Web Page to demonstrate some of the methods of JavaScript strings (***eg.:*** `charAt()`, `indexOf()`, `concat()`, `match()`, `replace()` etc).

***Q3:*** Create a Web Page to demonstrate some of the methods of JavaScript Date object of JavaScript (***eg:*** `getTime()`, `getMonth()`, `getDate()` etc).

### <u>*Ans*</u>: 
`HTML & JS Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="assets/favicon.png">
    <title>JS Lab Work</title>
</head>

<body style="zoom: 1.5; padding: 20px; font-weight: 500; font-size: 15px">
    <center style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
        <h2><u>JavaScript Operations on Array, String & Date</u></h2>
        <img width="5%" src="assets/favicon.png">
    </center>
    <hr>
    <p style="font-size: 18px;"><strong>Q1: </strong>
        <i>
            Create a web page to demonstrate some of the methods of
            JavaScript arrays (e.g., concat(), join(), indexOf(), 
            sort(), pop(), push(), etc).
        </i>
        </p>
    <p><i><u>Array Operation Results :</u></i></p>
    <div id="results1"></div>

    <hr>
    <p style="font-size: 18px;"><strong>Q2: </strong>
        <i>
            Create a web page to demonstrate some of the methods of
            JavaScript strings (e.g., charAt(), indexOf(), concat(), 
            match(), replace(), etc).
        </i>
    </p>

    <p><i><u>String Operation Results :</u></i></p>
    <div id="results2"></div>

    <hr>
    <p style="font-size: 18px;"><strong>Q3: </strong>
        <i> Create a web page to demonstrate some of the methods of the
            Date object of JavaScript (eg. getTime(), getMonth(),
            getDate() etc).
        </i>
    </p>

    <p><i><u>Date Operation Results :</u></i></p>
    <div id="results3"></div>


    <script>
        let updateResult = (id, results) => {
            const resultsDiv = document.getElementById(id);
            resultsDiv.innerHTML = resultsDiv.innerHTML + '<p>'
                 + results + '</p>';
        };

        let pcBrands = ['Dell', 'HP', 'Lenovo', 'Acer', 'Asus'];

        updateResult('results1', '1. Original Array: <code>' 
            + pcBrands + '</code>');

        const moreBrands = ['Apple', 'Microsoft'];
        pcBrands = pcBrands.concat(moreBrands);
        updateResult('results1', '2. After concat(): <code>' 
            + pcBrands + '</code>');

        updateResult('results1', '3. After join(): <code>' 
            + pcBrands.join(' - ') + '</code>');

        updateResult('results1', '4. Index of "HP": <code>' 
            + pcBrands.indexOf('HP') + '</code>');

        pcBrands.sort();
        updateResult('results1', '5. After sort(): <code>' 
            + pcBrands + '</code>');

        updateResult('results1', '6. Popped brand: <code>' 
            + pcBrands.pop() + '</code>');

        updateResult('results1', '7. Array after pop(): <code>'
             + pcBrands + '</code>');

        pcBrands.push('MSI');
        updateResult('results1', '8. Array after push(): <code>' 
            + pcBrands + '</code>');

        let pcBrandString = "Dell is a popular PC brand " 
            + "known for its quality and performance.";

        updateResult('results2', '1. Original String: <code>' 
            + pcBrandString + '</code>');

        updateResult('results2', '2. Character at index 3: <code>' 
            + pcBrandString.charAt(3) + '</code>');

        updateResult('results2', '3. Index of "quality": <code>' 
            + pcBrandString.indexOf('quality') + '</code>');

        updateResult('results2', '4. After concat(): <code>' + 
            pcBrandString.concat(' It is a reliable choice.') + '</code>');

        const matchedWords = pcBrandString.match(/[\w]+/g);
        updateResult('results2', '5. Words in the string: <code>' 
            + matchedWords + '</code>');

        updateResult('results2', '6. After replace(): <code>' 
            + pcBrandString.replace('popular', 'renowned') + '</code>');

        updateResult('results2', '7. After toLocaleLowerCase(): <code>' 
            + pcBrandString.toLocaleLowerCase() + '</code>');

        const currentDate = new Date();
        updateResult('results3', '1. Current Date: <code>' + 
            currentDate + '</code>');

        updateResult('results3', '2. Current Date in UTC format: <code>' +
             currentDate.toUTCString() + '</code>');

        updateResult('results3', '3. Current Date in Locale: <code>' 
            + currentDate.toLocaleDateString("hi-IN", { weekday: 'long',
             year: 'numeric', month: 'long', day: 'numeric' }) + '</code>');

        updateResult('results3', '4. Current Year: <code>' 
            + currentDate.getFullYear() + '</code>');

        updateResult('results3', '5. Current Month (0-11, January is 0): <code>'
             + currentDate.getMonth() + '</code>');

        updateResult('results3', '6. Current Day of the Month: <code>' 
            + currentDate.getDate() + '</code>');

        updateResult('results3', '7. Current Day of the Week (0-6, Sunday is 0): <code>' 
            + currentDate.getDay() + '</code>');

        updateResult('results3', '8. Current Time in Milliseconds: <code>' 
            + currentDate.getTime() + '</code>');

        const customDate = new Date('2001, 07, 10:15');
        updateResult('results3', '9. Custom Date: <code>' 
            + customDate + '</code>');

        updateResult('results3', '10. Formatted Custom Date: <code>' 
            + customDate.toDateString() + '</code>');
    </script>
</body>

</html>
```
`Output:`

![Lab Work 010 Output](https://i.ibb.co/XxMP906/image-13.png)

## [Lab Work 011](https://anolchakraborty.github.io/Web-Programming-Basics/lab.011.html)

***Q1:*** Create a Web Page containing an image. When the user moves the pointer over an the image , the image should change to a new image. When the mouse pointer is moved away from the image the original image should be shown. Use JavaScript for this implementation.

***Q2:*** Create a Web Page to do form validation using JavaScript. Create a form for entering credit and debit card details. It should have `name field`, `card number field`, & an `expiry date` (month & year).
Use JavaScript to do the following:
- The name field must not be blank
- The card number field must have 16 digits
- The month in the expiry date field must only take values from 1 to 12
- The year in the expiry date field must only accept two digits.

### <u>*Ans*</u>: 
`HTML, JS & CSS Code:`
``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="assets/favicon.png">
    <link rel="stylesheet" 
        href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css">
    <style>
        input[type=number]::-webkit-inner-spin-button,
        input[type=number]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            -moz-appearance: none;
            appearance: none;
            margin: 0;
        }

        input {
            width: 100%;
            max-width: 220px;
            height: 45px;
            padding: 12px;
            border-radius: 12px;
            border: 1.5px solid lightgrey;
            outline: none;
            transition: all 0.3s cubic-bezier(0.19, 1, 0.22, 1);
            box-shadow: 0px 0px 20px -18px;
        }

        input:hover {
            border: 2px solid lightgrey;
            box-shadow: 0px 0px 20px -17px;
        }

        input:active {
            transform: scale(0.95);
        }

        input:focus {
            border: 2px solid grey;
        }

        button {
            font-family: ui-monospace, "Courier New", monospace;
            font-size: 17px;
            padding: 1em 2.7em;
            font-weight: 500;
            background: #1F2937;
            color: white;
            border: none;
            position: relative;
            overflow: hidden;
            border-radius: 0.6em;
        }

        .gradient {
            position: absolute;
            width: 100%;
            height: 100%;
            left: 0;
            top: 0;
            border-radius: 0.6em;
            margin-top: -0.25em;
            background-image: linear-gradient(rgba(0, 0, 0, 0), 
                        rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.3));
        }

        .label {
            position: relative;
            top: -1px;
        }

        .transition {
            transition-timing-function: cubic-bezier(0, 0, 0.2, 1);
            transition-duration: 500ms;
            background-color: rgba(16, 185, 129, 0.6);
            border-radius: 9999px;
            width: 0;
            height: 0;
            position: absolute;
            left: 50%;
            top: 50%;
            transform: translate(-50%, -50%);
        }

        button:hover .transition {
            width: 14em;
            height: 14em;
        }

        button:active {
            transform: scale(0.97);
        }
    </style>
    <title>DOM Manipulation</title>
</head>

<body style="font-family: Calibri, 'Trebuchet MS', sans-serif;">

    <br>
    <br>
    <center>
        <figure>
            <img id="image" src="assets/pic.jpg" width="300" height="200" 
                onmouseover="this.src='assets/favicon.png'"
                onmouseout="this.src='assets/pic.jpg'">
            <figcaption>Hover Over The Image</figcaption>
        </figure>
    </center>

    <hr>

    <div style="margin-left: 770px;">

        <h2 style="padding-left: 20px;" id="formHead">User Payment Form</h2>

        <br>

        <form style="padding-left: 20px;">
            <label for="name">Name:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</label>
            <input type="text" id="name" name="name" 
            oninput="validateName(this)" required>
            <span id="nameError" style="color: red;"></span><br><br>

            <label for="cardNumber">Card Number:</label>
            <input type="number" id="cardNumber" 
            name="cardNumber" oninput="validateCardNumber(this)" required>
            <span id="cardNumberError" style="color: red;"></span><br><br>

            <label for="expiryMonth">Expiry Month:</label>
            <input type="number" id="expiryMonth" 
            name="expiryMonth" oninput="validateExpiryMonth(this)" required>
            <span id="expiryMonthError" style="color: red;"></span><br><br>

            <label for="expiryYear">Expiry Year:&nbsp;&nbsp;&nbsp;</label>
            <input type="number" id="expiryYear" 
            name="expiryYear" oninput="validateExpiryYear(this)" required>
            <span id="expiryYearError" style="color: red;"></span><br><br>

            <button onclick="submitForm(event)">
                <span class="transition"></span>
                <span class="gradient"></span>
                <span class="label">Submit Form</span>
            </button>
        </form>
    </div>

</body>

<script>
    var Uname = false;
    var card = false;
    var year = false;
    var month = false;
    function submitForm(elem) {
        elem.preventDefault();
        if (Uname && card && year && month) {
            document.forms[0].style.display = "none"
            document.getElementById('formHead').textContent = "Payment Successful !"
            document.getElementById('formHead').style.color = 'blue'
            document.getElementById('formHead').style.fontWeight = '900'
            document.getElementById('image').src = 'assets/favicon.png'
        } else {
            alert("Please fill in all the feilds")
        }
    }

    function validateName(elem) {
        var name = elem.value;
        if (name.trim() === "") {
            document.getElementById("nameError").textContent = 
                    "Name field cannot be blank.";
        } else {
            Uname = true;
            document.getElementById("nameError").innerHTML = 
                    "<span style='color: green'>Name OK</span>";
        }
    }

    function validateCardNumber(elem) {
        var cardNumber = elem.value;
        if (cardNumber.length !== 16) {
            document.getElementById("cardNumberError").textContent = 
                    "Card number must have 16 digits.";
        } else {
            card = true;
            document.getElementById("cardNumberError").innerHTML = 
                    "<span style='color: green'>Card Number OK</span>";
        }
    }

    function validateExpiryMonth(elem) {
        var expiryMonth = elem.value;
        if (isNaN(expiryMonth) || expiryMonth < 1 || expiryMonth > 12) {
            document.getElementById("expiryMonthError").textContent = 
                    "Expiry month must be a number between 1 and 12.";
        } else {
            month = true;
            document.getElementById("expiryMonthError").innerHTML = 
                    "<span style='color: green'>Expiry Month OK</span>";
        }
    }

    function validateExpiryYear(elem) {
        var expiryYear = elem.value;
        if (isNaN(expiryYear) || expiryYear < 0 
                              || expiryYear.toString().length !== 4) {
            document.getElementById("expiryYearError").textContent = 
                    "Expiry year must be a four-digit number.";
        } else {
            year = true;
            document.getElementById("expiryYearError").innerHTML = 
                    "<span style='color: green'>Expiry Year OK<span>";
        }
    }
</script>

</html>
```
`Output:`

![Lab Work 011 Output](https://i.ibb.co/vzdRpYv/image-11.png)

## [Lab Work 012](https://anolchakraborty.github.io/Web-Programming-Basics/lab.012.html)

***Q1:*** Using PHP, check if a given integer is Positive, Negative or neither (***i.e.,*** Zero).

***Q2:*** Using PHP, check if a given integer is Prime or not.

***Q3:*** Using PHP, calculate & print the first 20 numbers of the Fibonacci series.

### <u>*Ans*</u>: 
`PHP & HTML Code:`
``` PHP
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PHP Lab Work</title>
    <link rel="shortcut icon" href="assets/favicon.png">
    <style>
        body {
            padding-left: 200px;
        }

        center {
            padding-right: 200px;
        }
    </style>
</head>

<body>
    <center style="padding-right: -200px">
        <h1><u>PHP Lab Work Exmaple</u></h1>
    </center>

    <br>

    <h2>
        <?php
        $num1 = 10;
        if (is_int($num1) || is_float($num1)) {
            if ($num1 > 0) {
                echo "<i>$num1</i> is Positive Number";
            } elseif ($num1 < 0) {
                echo "<i>$num1</i> is Negative Number";
            } else {
                echo "<i>$num1</i> is neither Positive Number or Negative Number;
                      i.e, it is Zero";
            }
        } else {
            echo "<i>$num1</i> is not a number";
        }
        ?>
    </h2>
    <hr>
    <h2>
        <?php
        $n1 = 0;
        $n2 = 1;
        $nextTerm;
        $var1 = "";
        for ($i = 1; $i <= 20; $i++) {
            $var1 = $var1 . "&nbsp;&nbsp;&nbsp;" . $n1;
            $nextTerm = $n1 + $n2;
            $n1 = $n2;
            $n2 = $nextTerm;
        }
        echo "First 20 fibonacci series number is : <i>$var1</i>";
        ?>
    </h2>
    <hr>
    <h2>
        <?php
        $num2 = 7;
        if (is_int($num2) || is_float($num2)) {
            if ($num2 > 0) {
                if ($num2 == 1) {
                    echo "<i>$num2</i> is a Composite Number";
                } else {
                    for ($i = 2; $i <= $num2 / 2; $i++) {
                        if ($num2 % $i == 0) {
                            echo "<i>$num2</i> is a Composite Number";
                            return;
                        }
                    }
                    echo "<i>$num2</i> is a Prime Number";
                }
            } else {
                echo "<i>$num2</i> cannot be determined";
            }
        } else {
            echo "<i>$num1</i> is not a number";
        }
        ?>
    </h2>
    <hr>

</body>

</html>
```
`Output:`

![Lab Work 012 Output](https://i.ibb.co/9Vshzk8/Screenshot-20231207-013620.png)

<hr/>
