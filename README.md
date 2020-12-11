# Bootcamp Homework 02 & 08- CSS and Bootstrap: Responsive Portfolio

## My Portfolio

This is an assignment to create a mobile responsive portfolio using the Bootstrap CSS Framework.  Requirements for the portfolio include a consistent navbar across each page of the portfolio, a responsive layout, and responsive images, while limiting the use of media queries.  

### Homework Deliverables and Codebase Updates

* Created `index.html`, `portfolio.html` and `contact.html` files
* Linked all pages to external BootstrapCDN
* Linked additional CSS to each page
* Added the Bootstrap navbar elements to all pages to create a universal responsive navbar
* Right-aligned the page links within the navbar
* Updated href attributes on navbar links for links to be functional
* Utilized Bootstrap grid system to create the main content across all pages 
* Added portfolio project images to `./assets` folder
* Added alt attributes to the HTML img elements
* Added links to GitHub, LinkedIn, Email, and Project/Assignment urls
* Created a README.md file to describe and demo the code
* Deployed the application to a live URL


### Notes on this project

Using the Bootstrap CSS Framework for this project was both fun and frustrating. My expectations regarding the difficulty level of each of my tasks were incorrect, in ways that I found surprising:
* The Bootstrap grid system was more difficult to control than I expected.  The `.container` class with it's `.row` and `.col` children seemed very straight forward and almost simple in class.  But on execution in this project, I struggled with the placement of the content on the page.  
    * The content did not align the way I expected (on both the About and Portfolio pages).
    * The content did not wrap the way I expected (again, on both the About and Portfolio pages).
    * My attempts to use additional CSS to adjust margins/aligment/floats/etc proved complicated.
* The responsive navbar elements were really fun to work with until I tried to move the page links to the right side of the screen.  This, embarrassingly, took me a long time to figure out.  In the end, I updated `.mr-auto` to `.ml-auto` and learned my lesson to google solutions earlier going forward.
* Using the [HTML validation service](https://validator.w3.org/#validate_by_input) was very helpful and led to a correction of the `.form-control` id associations on the Contact form.
* The responsiveness of the page is still a bit off (Images on Portfolio).  I'm hoping more practice will help me understand how to refine this functionality. 
* The links on the Contact page need some additional styling.  I would like to make the icons clickable, but ran out of time after realizing that simply putting the Font Awesome icons inside the anchor elements did not render well.  

## Screenshot

The following image shows the portfolio appearance and functionality:

![Portfolio About](./assets/index2-demo.png)

![Portfolio Contact](./assets/contact2-demo.png)

![Portfolio Page](./assets/portfolio2-demo.png)


## Application URL
* [Portfolio Index](https://thorgriffs.github.io/portfolio/index.html)
* [Portfolio Contact](https://thorgriffs.github.io/portfolio/contact.html)
* [Portfolio Page](https://thorgriffs.github.io/portfolio/portfolio.html)
