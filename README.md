# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#A responsive News Hompage)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Toggle the mobile menu (requires some JavaScript)

### Screenshot




### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with


- Flexbox
- CSS Grid
- javaScript
**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

I learnt how to use CSS grid and flexbox and media query while building this project
 using JavaScript for toggle was helpful as i learnt the very basics of JavaScrit


```html
<h1>Some HTML code I'm proud of</h1>
<section class="header">
     <li><a href="#">Categories</a></li>
          </ul> 
        </div>  <nav>
        <a href="#"><img id="logo" src="assets/images/logo.svg" alt="logo"></a>
        <div class="nav-links" id="navLinks">
          <img class="fa" src="assets/images/icon-menu-close.svg" alt="" onclick="hideMenu()" />
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">New</a></li>
            <li><a href="#">Popular</a></li>
            <li><a href="#">Trending</a></li>
            
        <img class="fa" src="assets/images/icon-menu.svg" alt="" onclick="showMenu()" />
     </nav>
 
    </section>
```
```css
.proud-of-this-css {
  @media (max-width: 750px) {

        .nav-links ul li{
            display: block;
            font-weight: 700;
        }
        .nav-links{
            position: absolute;
            background: #fff;
            height: 100vh;
            width: 200px;
            top: 0;
            right: -200px;
            text-align: left;
            z-index: 2;
            transition: 1s;
        }

        nav .fa{
            display: block;
            color: black;
            margin: 10px;
            font-size: 22px;
            cursor: pointer;

        }
        .nav-links ul{
            padding: 30px;
        }
        .wrapper{
            grid-template-areas: 
            'item-1'
            'item-3'
            'item-2'
            'item-4';
            grid-template-columns: 1fr;
        }
       
        .p-3{
            text-align: start;
        }
        div, h4{
            text-align: start;
        }
        .btn{
            align-items: center;
            display: inline;
        }
        .item-3-header, p{
            margin-bottom: 10px;
        }
    }
    @media (max-width: 675px) {
        .item-2{
            grid-template-columns: 1fr;
        }
        .item-4{
            grid-template-columns: 1fr;
        }
        .btn{
            display: block;
            text-align: center;
            margin: auto;
        }
        .img-1{
            display: none;
        }
        .img-1{
            display: none;
        }
        .img-3{
            display: block;
        }
    }
}
```
```js
const proudOfThisFunc = 
    var navLinks = document.getElementById("navLinks");
    function showMenu(){
         navLinks.style.right = "0";
    }
    function hideMenu(){
         navLinks.style.right = "-200px";
    }
  

```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development
I want to focus on website responsivness and javaScript


### Useful resources

- [Trasvery Media](youtube) - This helped me understood CSS grid and media query reason. I really liked this pattern and will use it going forward.


## Author

- Website - [Haruna Tawakalt](https://www.your-site.com)
- Frontend Mentor - [@Lahitan](https://www.frontendmentor.io/profile/Lahitan)
- Twitter - [@Olahitan14](https://www.twitter.com/Olahitan14)
