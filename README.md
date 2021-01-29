# **Projekt strony / Page Design**
## **PodróżOla**

![N|Solid](http://127.0.0.1:5500/img/monogram.jpg)

The web site is called **PodróżOla**. The website is responsive and used programming languages such as **HTML5** and **CSS3**.

  
# On website

  - You can view photos from the trip.
  - You can view the website on your iPhone


You can also:
  - Save files from website
  - Export information as PDF

### Tech

PodrożOla uses a number of open source projects to work properly:

* [HTML5] - HTML enhanced for web apps!
* [CSS3] - awesome web-based text editor
* [Responsive Web Design] - using HTML and CSS to automatically resize, hide, shrink, or enlarge, a website, to make it look good on all devices (desktops, tablets, and phones).

And of course PodróżOla itself is open source with a repository on GitHub.

#### Building 
Bookmarks :

```sh
about me
```
```sh
portfolios
```
```sh
contact.
```

A choice of cities: Lviv, Prague, Athens.

#### Code CSS3 for RWD

@media (max-width: 1024px) {

    body {
        display: flex;
        flex-direction: column;
    }
    .header {
        display: flex;
        flex-direction: column-reverse;
    }
    .bar {
        display: flex;
        justify-content: space-evenly;
        padding-bottom: 20px;
    }
    .bar li {
        top: 10px;
    }
    .bar li a {
        white-space: nowrap;
        padding-left: inherit;
        padding-right: inherit;
    }
    .monogram {
        align-self: flex-start;
    }
    .monogram img{
        width: 75px;
    }
    #title {
        position: static;
        width: 100%;
    }
    .title {
        height: auto;
    }
    .cities {
        border: none;
        box-shadow: none;
        left: 0; 
        width: auto;           
    }
    .cities img {
        display: none;
    }
    .cityNames {
        display: flex;
        flex-wrap: wrap;
        position: static;
        justify-content: center;
    }
    .cityNames a {
        position: relative;
        display:inline-block;
        flex-direction: row-reverse;
        justify-content: center;
        width: calc(100%/3);
        margin-right: 5px;
        margin-bottom: 5px;;
    }
    .gallery {
        margin-top: 10px;
        display: flex;
        flex-wrap:wrap
    }
    .gallery img {
        width: calc(100%/3);
        padding: 5px;
    }
    .contact form textarea {
       position: relative;
       width: 300px;
       justify-content: center;
    }
    .contact form button {
        margin-right: -200px;
        padding: 10px 25px;
    }
    .info {
        display: flex;
        flex-direction: column;

    }
    .info img {
        width: 150px;
    }
    .galleryDevided {
        display:flex;
        flex-direction: column;
        width: 200px;
        border:none;
        box-shadow: none;
    }
    .galleryDevided h1 {
        text-align: center;
        margin-left: 5px;
        margin-right: 5px;

    }
    .galleryDevided img {
    position:flex;
    flex-direction: column; 
    width: auto;   
    }




