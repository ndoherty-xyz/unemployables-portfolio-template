![image](https://user-images.githubusercontent.com/103902448/164163511-37d22660-905c-4355-a6f4-91c6eee2d1a4.png)
# Unemployables Portfolio Template
A template for the Unemployables who need to showcase their creative work, whatever that may be.
<br />
<br />

## About this template
After joining the Unemployables community (https://unemployables.io/) and seeing the mission to help people become self-employed and grow their businesses, I immediately thought about helping people build portfolios. It's something that I've helped friends with in the past. 

This is a simple HTML and CSS template to help others get a portfolio up and running quickly. The idea is that it's simple enough to change and customize for people who want to code a bit of their own portfolio website, but may not be experienced in web development. This README also includes instructions on how to host the website on Github Pages **(for free)**.
<br />
<br />

## How to customize this template
**All changes that need to be made are commented in the code with a `TODO` tag.**
Search for it and you'll find all the changes you need to make. That being said, there are some high level things to know:

- Image assets that you add for projects, header photo, or the favicon should go in the `assets/images` folder
- For every new project page, make a copy of `project-template.html` and keep it in the `project-pages` folder
- All styling is located in the `css` folder, have at it if you feel like changing up the styling.
- The `js` folder holds one script file that you can add any custom Javascript into. It only has a smooth scrolling function for the header button.
<br />

### Steps for linking a project page to the homepage
1. Make a copy of `project-template.html` in the `project-pages` folder and rename it to `<project-name>.html`
2. Open `index.html` and find the `div` with `className='project-container'`
3. Add a new project card into the div. Here's the template for a project card:
```
  <div class="project-card">
    <img src="./assets/images/IMAGE_NAME" class="project-image">
    <div class="project-card-text-container">
      <div class="subheader-text project-title">PROJECT_NAME</div>
      <div class="body-text project-card-text">SMALL_PROJECT_DESCRIPTION</div>
    </div>
    <a class="button" href="./project-pages/PROJECT_PAGE_NAME.html">
      <span class="button-text">Read More</span>
      <image src="./assets/icons/arrow-right.svg" class="right-arrow-icon"/>
    </a>
  </div>
```
4. Change `PROJECT_PAGE_NAME.html` to the name of the html file you copied from the project template
5. The project page is now linked to the homepage! Customize the names, images, and text to your hearts content. 
