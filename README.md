# JSON Portfolio Website

A ReactJs and Bootstrap 5 framework website that dynamically creates a multi-page portfolio site from several JSON files with a central customisation functionality and deployment pipeline.

<a href="http://brandonabela.github.io/json-portfolio" target="_blank"> DEMO </a> | <a href="http://www.brandonabela.github.io" target="_blank"> My portfolio </a>

## Features

- Responsive ReactJS website by reading information from multiple JSON files
- Automatically deploy website on each commit that has occurred to the project
- Adapts to different screen sizes, from phones to desktops
- Ability to showcase projects that were defined in JSON files
- Ability to define slide-shows, links and videos for projects
- All sections are defined through the use of a JSON file
- Support personal biography, social media links, education, work, projects and contact sections

## Instructions

### Preview Website:

1. In terminal input ```npm install``` to install the website packages
2. In terminal input ```npm start``` to launch the website in a local environment
3. In terminal press ```CTRL + C``` to terminate the website process

### Deploy Website:

1. In ```package.json``` change ```"name": "json-portfolio"``` to ```"name": "github-username"```
2. In ```package-lock.json``` change ```"name": "json-portfolio"``` to ```"name": "github-username"``` for both the ```root``` and ```packages```
3. In ```public/index.html``` change ```<title> JSON Portfolio </title>``` to ```<title> Your Name | Portfolio </title>```
4. In ```public/index.html``` change ```<meta name="description" content="..." />``` to ```<meta name="description" content="Website Description" />```
5. Fork Repository with ```github-username.github.io``` as your repository name
6. Modify the JSON files to reflect your details and upload any necessary images
7. Commit the files on the forked repository
8. In Github access the ```repository settings > pages > sources``` and select ```gh-pages``` with ```/ (root)``` folder

## Customisation

The website customisation is primarily driven by two primary stylesheets;

* ```styles/scheme.scss``` is used for changing colours and padding of content and section
* ```styles/typography.scss``` is used for setting font sizes of text headings and paragraphs

# Contributions

Please report any issues or submit pull requests with code changes. I love it when my work helps someone.  So, if you're utilizing my project or have been inspired to develop something of your own, please let me know! My social media are featured in my portfolio.
