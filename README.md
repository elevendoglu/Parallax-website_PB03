# Project-003 : Parallax Website (HC-03)
(iOS style toggle button added)

## Description
Project aims to create parallax website.
Project aims to compile sass editor (sass to css compiler)
finally I added a toggle button to change screen modes (dark-light)

## Problem Statement

- Company has recently started on a project that aims to create a parallax website. So my team have started to work on the project.
- Examine the expected output #objection part below. 

## Project Skeleton 

```
003-parallax-website (folder)
|
|----readme.md         # Given to the team (Definition of the project)          
|----images            # Given to the team (Images of the project)   
|----solution
        |----sass folder
	|           |----style.scss (includes imports)
	|           |----_roots.scss (main body font etc. properties)
	|           |----_normalize.scss (you may choose reset.scs instead of this temlate file. I find this file ready to use from google)
	|           |----_globals.scss (primary and secondary colors)
	|           |----_sections.scss (style the div and sections with this file
	|           |----_toggle.scss (I put template which I found in google) 
	|
	|
	|----index.html (includes js codes for toggle button with main skeleton)
        |----#style.css (automatically created by sass. simultaneously compliling. you can follow with terminal)
	|----#style.css.map (automatically created by sass.)
        |----images
	
```

## Expected Outcome

![Project 003 Snapshot](Project_003_.png)
note: I added extra toggle button property.

## Objective

Build a Landing that is functionally similar to this: [Parallax Website](https://aaron-clarusway.github.io/parallax-website/)

### At the end of the project, following topics are to be covered;

- HTML

- Sass

- List Properties

- Overflow Property-The float Property-Opacity / Transparency-Units in CSS

- CSS Setting height and width-CSS Outline-CSS Combinators


### At the end of the project, students will be able to;

- improve coding skills within HTML, Sass & CSS

- use git commands (push, pull, commit, add etc.) and Github as Version Control System.

- be know about some JS functions.

## Steps to Solution
  
- Step 1: Download or clone project repo on Github 

- Step 2: Create project folder for local public repo on your pc

- Step 3: Set up Sass compiler

- Step 4: Create Parallax Website

-Step 5: Add a toggle button 

>>Part-1 HTML Structure

	- Create structure of the HTML5
	- Give name of your project (title)
	- Create the main structur of the HTML
	
>>Part-2 Set up Sass compiler

	- Set up Node JS then install npm ($ npm install -g sass)
	- Create sass files
	- $ sass -watch ./sass/style.scss:style.css
	- follow the compiler screen on bash terminal.
	
>>Part-3 Sass & CSS Structure
	
	- Set a background and define font-color="white"
	- Set container background color and margin
	- Define others color-size-padding etc...
	- Add parallax property to secton style
	- Add toggle styles

- Step 4: Add JS function into HTML
	
- Step 5: Push your application into your own public repo on Github

- Step 6: Deploy your application on Github template to showcase your app within your team.


## Resources

-  [Images](https://github.com/clarusway/cw-fs-workshop/tree/master/html-css/projects/003-parallax-website/img)


