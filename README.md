# Horiseon Code Refactor Homework

## Summary

In this project I took the provided code and reformatted it to follow semantic html and also took the existing css and consolidated it and reordered it to follow the semantic html. This repository shows a few versions of the code I went through to get from what was provided to the final version. 
 
## Table of Contents

1. [Description](#Description)

2. [Process](#Process)

3. [What I Learned](#WhatILearned)

4. [Installation](#Installation)

5. [Resources](#Resources)

## Description

The main focus for this project was to take the already existing code and change it/modify it to follow accessibility standards. I did this by taking the code and changing many of the `<div>` elements to follow proper semantic html, as well as adding "alt" attributes to all of the image tags.
  
## Process  

Specific changes I made to the code include changing the first `<div>` element into a header which encompassesed the name of the company and the 3 links at the top of the page. I also changed the second `<div>` element into a navigation bar so that users using screen readers can easily find and click on the links to the 3 sections of the website.

![header and nav bar code](https://raw.githubusercontent.com/ClairePhillips51/HW1-Code-Refactor/main/assets/images/header%20and%20nav.png?raw=true) 

The main information on the webpage was formatted in 3 sections one for  SEO, online reputation, and social media marketing, but each one was a seperate `<div>` that I changed to a `<section>` tag. ![sections of webpage](https://raw.githubusercontent.com/ClairePhillips51/HW1-Code-Refactor/main/assets/images/body%20of%20wepage.png?raw=true)

A section on the side of the website provided additional information on the benefits of SEO that were not directly related to the other sections (see right side of image above) so I changed that into an aside tag.
![Aside code](https://raw.githubusercontent.com/ClairePhillips51/HW1-Code-Refactor/main/assets/images/aside.png?raw=true)
A footer at the bottom of the page that contions the copyright was also modified.

Once I had changed all the html to follow semanitc guidlines I worked on fixing broken links and making changse that allowed for better accessibility. One of those was adding alt attributes to all the img tags as they were missing. The one expection was the background picture.

A title was also added as it was not included in the original source code. I also included an extra `<meta>`  tag to add some keywords to promote better SEO.

All these changes lead to better accessibility for anyone not viewing the webpage in a traditional way. I.e. using a screen reader or only using a keyboard to navigate the page.

Consolidating css was also part of making the code better. For instance, each section had a separate class, but each of these classes had the same styling. I consolidated this under ".content section".

![Sections css](https://raw.githubusercontent.com/ClairePhillips51/HW1-Code-Refactor/main/assets/images/sections%20css.png?raw=true)

In addition, the images within the aside each had their own class, but these classes used the same styling. To consolidate this, I replaced these classes with the "benefit-sub" class.

![Aside css](https://raw.githubusercontent.com/ClairePhillips51/HW1-Code-Refactor/main/assets/images/aside%20css.png?raw=true)
  
## What I learned

I built this project to learn how to format semantic html and better understand what good/clean code looks like and acts like. I also learned the importance of the css matching the flow of the html.

One of the more challenging aspects of the code was the comments. What makes a good comment vs. a useless one? Good clean code is often easy to follow and so comments must be well thought out and add value to the code for anyone reading it instead of additional noise. Other challenges included navigating git. This project was very useful in getting the flow of how to pull code then add and push commits to GitHub. Also, as was witnessed in office hours deploying the webpage was a struggle due to having different assest folders. 
  
## Installation

Installation of the webpage included cloning the GitLab repo onto my local computer so I had access to the website's files. Then I created my own repo on GitHub and added the website files to it. I then started editing the html and css files. Once the code was to my liking and functioned properly I pushed commits to my GitHub repositiory. From there I went to settings > options > github pages and set the main branch to be the link to the deployed webpage.

### Resources
 I found the following websites valuable when completeing this assignment. 
  * [W3Schools HYML Sematic Elements] (https://www.w3schools.com/html/html5_semantic_elements.asp)
  * [HTML5 Element Flowchart] (http://html5doctor.com/downloads/h5d-sectioning-flowchart.pdf)
  * [W3Schools HTML Accessibility] (https://www.w3schools.com/html/html_accessibility.asp

