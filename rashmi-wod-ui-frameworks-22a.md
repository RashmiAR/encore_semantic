---
title: "WOD: Encore Saloon"
published: true
morea_id: encore-saloon
morea_type: experience
morea_summary: "Practice using Semantic UI."
morea_sort_order: 6
morea_labels: "Rashmi WOD"
---

# Rashmi WOD: Encore Saloon in Semantic UI

## Background

Encore Saloon is a mezcal bar serving Mexican inspired food at Chinatown, Honolulu.  Your task is to create a rough approximation of the [Encore Saloon website](https://www.encoresaloon.com).

The mockup created as a result of this practice WOD should look like this:

<img src="rwod-encore-saloon-solution.png" alt="Encore Saloon website implemented in Semantic UI" class="img-responsive">

## Instructions

1. Set up a new **private** GitHub repository for this exercise.

    1.1. Name the repository *encore-saloon*.

    1.2. Ensure that there is a README file for the project.

    1.3. Finish creating the repository on GitHub, then clone the repository to your local computer.

2. Create an IntelliJ **Static Web** project called *encore-saloon* within your local *encore-saloon* repo directory.

3. Load the Semantic UI and JQuery files into index.html following the instructions in [Semantic UI Hello World](reading-semantic-ui-hello-world.html). Also load your (currently empty) style.css file.

4. Create the top menu:

    4.1. In your index.html, create a div with the classes "ui topmenu menu". This div will create a Semantic UI menu, with a logo on the left and menu elements on the right. It also enables you to customize this div by selecting the topmenu element.
    
    4.2. In your style.css, you might want to create a CSS selector ".ui.topmenu.menu", which sets the background-color of your menu to **#e2231a**, the margin and border-radius to 0px and height to 80px.
    
    4.3. The first item in the menu can use the classes "ui image item", where the "src" is [the company logo](rwod-encore-saloon-logo.png)

    4.4. Create the right portion of the menubar. Use the class "right" on the second menu item to move the remaining items to the right side of the page. This should include the menu items **HOME**, **LOCATION**, **MENUS**, **CONTACT** and **TEL: 808.367.1656**. You need to implement the dropdown menus for the **MENUS** item. The dropdown items are **FOOD**, **DRINK** and **CATERING**. 
    
    4.5. In your style.css, you might want to create a CSS selector ".ui.topmenu.menu, .ui.menu .item, .ui.menu .dropdown.item .menu, .ui.menu .dropdown.item .menu .item", which sets the background color to **#e2231** and sets color to #ffffff. You may have to use `!important` to force the browser to use this color. Also set font-family to Arvo, font-size to 16px, font-weight to 400, font-style to normal, letter-spacing to .075em and line-height to 2em.
    
5. Create the middle image:
  In your index.html, you might want to create a img element with classes "ui fluid image", whose src is [encore saloon image](rwod-encore-saloon-image.png)

6. Create the footer:

    6.1. In your index.html, you might want to create a div with classes "ui grid footer".
    
    6.2. Create  another div with classes "centered row footer-one". The contents of this div could be the four lines of the footer, with a `<br/>` element to force a line break.
    
    6.3. In your style.css, set .footer to have same properties as mentioned in `step 4.5` and create a css selector ".footer-one", which sets padding to "80px 8%". You may have to use `!important` to force the browser to use this padding.
    
7. Commit and push your finished project to GitHub and verify that your code appears properly on the GitHub site.

8. Raise your hand to let me know you have finished this practice WOD.

{% include wod-times.html Rx="<18 min" Av="18-24min" Sd="24-40 min" DNF="40+ min" %}

### Imaginary Extra Credit Bonus Points

1. Implement the Semantic UI icons for Facebook and Instagram in the Footer.

### Submission instructions

You do not have to submit this Rashmi WOD.

{% include bit.ly.html url="http://bit.ly/" %}
