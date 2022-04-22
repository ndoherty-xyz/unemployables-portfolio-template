![image](https://user-images.githubusercontent.com/103902448/164163511-37d22660-905c-4355-a6f4-91c6eee2d1a4.png)
# Unemployables Portfolio Template
A template for the Unemployables who need to showcase their creative work, whatever that may be.
<br /><br />
**Demo:** https://whitevans-eth.github.io/unemployables-portfolio-template/
<br />
<br />

#### Table of Contents:
<a href="https://github.com/whitevans-eth/unemployables-portfolio-template#about-this-template">About this template</a></br>
<a href="https://github.com/whitevans-eth/unemployables-portfolio-template#getting-started">Getting started</a></br>
<a href="https://github.com/whitevans-eth/unemployables-portfolio-template#how-to-customize-this-template">How to customize this template</a></br>
&nbsp;&nbsp;&nbsp;<a href="https://github.com/whitevans-eth/unemployables-portfolio-template#creating-a-new-project-page-and-adding-it-to-the-homepage">Creating a new project page</a></br>
&nbsp;&nbsp;&nbsp;<a href="https://github.com/whitevans-eth/unemployables-portfolio-template#adding-images-to-the-project-gallery">Adding gallery images</a></br>
<a href="https://github.com/whitevans-eth/unemployables-portfolio-template#publishing-with-github-pages">Publishing with Github Pages</a></br>
<br />
<br />

## About this template
After seeing the mission of Unemployables (https://unemployables.io/) to help people become self-employed and grow their businesses, I immediately thought about helping people build portfolios. It's something that I've helped friends with in the past and really enjoyed doing. <br /><br />
This template is mobile friendly, so you won't have to worry about your site not working on phones.
<br />
<br />

**The goals of this template are:**
- To be a starting point for someone who's never touched web development but wants to build their own portfolio website. 
- Help keep costs of running a portfolio website low by publishing the website on Github Pages for free (instructions further down).
<br />
<br />

## Getting started
**If you haven't used Git / Github before, here's some guides to get you started:**
- Basics of git: https://www.freecodecamp.org/news/learn-the-basics-of-git-in-under-10-minutes-da548267cc91/
- Forking a repository: https://docs.github.com/en/get-started/quickstart/fork-a-repo
<br />

**Template instructions:**
1. Click the `Use As Template` button above and name your new repository (it should be set to public).
2. Clone your newly created repo to your local machine.
3. Navigate to the cloned repo on your machine and open `index.html` with your browser.
4. Open the repo folder in your favorite code editor and start editing. (Make sure to refresh the browser to see the code changes you make!)
5. Publish your site by pushing your commits to your repo.
6. Set up Github Pages (guide further down!)
<br />
<br />

## How to customize this template
**All changes that need to be made are commented in the code with a `TODO` tag.**
Search for it and you'll find all the changes you need to make. That being said, there are some high level things to know:

- Image assets that you add for projects, header photo, or the favicon should go in the `assets/images` folder
- For every new project page, make a copy of `project-template.html` and keep it in the `project-pages` folder
- All styling is located in the `css` folder, have at it if you feel like changing up the styling.
- The `js` folder holds one script file that you can add any custom Javascript into.
<br />

### Creating a new project page and adding it to the homepage
1. Make a copy of `project-template.html` in the `project-pages` folder and rename it to `<project-name>.html`
2. Open `index.html` and find the `div` with `className='project-container'`
3. Add a new project card into that div. Here's the template for a project card:
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
4. Change `PROJECT_PAGE_NAME.html` to the name of the new html file you copied from the project template
5. The project page is now linked to the homepage! Customize the page and `"project-card"` to your heart's content. 
<br />

### Adding images to the project gallery
1. Make sure the images that you want to show are added to the `assets/images` folder
2. Open the project page you want to edit and find the `div` with `class="project-gallery-content"`
3. To add an image, copy one of the two templates below and paste them into the `project-gallery-content`
```
Full Width Image:

    <div class="gallery-image-container">
      <img src="../assets/images/IMAGE_NAME" class="gallery-image">
      <span class="image-caption">IMAGE_CAPTION</span>
    </div>


Half Width Image:

    <div class="gallery-image-container half-width">
      <img src="../assets/images/IMAGE_NAME" class="gallery-image">
      <span class="image-caption">IMAGE_CAPTION</span>
    </div>
```
4. Change IMAGE_NAME to the filename of the image you added to `assets/images` and IMAGE_CAPTION to whatever caption you want (or remove it, I don't mind)
5. Refresh the project page in your browser and boom! Your image has been added to the gallery.
<br />
<br />

## Publishing with Github Pages
Github Pages allows us to host this website for free! It's pretty simple to set up as well.

1. Head to `Settings` on the repository
2. The repository will need to be public for this work (if it's not, navigate to `General` and scroll all the way down to `Change repository visibility`. Make it public)
3. Navigate to `Pages` in the sidebar
5. For `Source` choose `main` from the dropdown. Save the changes.
6. That's it! Github should give you a URL that your website is published on (give it a few minutes to update).
7. To add a custom domain (i.e. yourname.com), follow this guide: https://medium.com/codex/add-a-custom-domain-to-your-github-pages-personal-website-53ab40e7c7d0
<br />
<br />

## That's it!
Feel free to send me pictures of your portfolio website once it's up and running. Would love to see them!
https://twitter.com/whitevans_eth
