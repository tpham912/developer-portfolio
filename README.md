# Developer Portfolio 

<p align="center">
<img src="https://raw.githubusercontent.com/PhantomScript/asset-container/b26b0ebaaa13bec7fac796ee0b8296676df6ee0b/developer-portfolio/website.svg" alt="" width="450px"/>
</p>

## Table of Contents :scroll:
- [Sections](#sections-bookmark)
- [Installation](#installation-arrow_down)
- [Usage](#usage-joystick)
- [Hosting](#hosting-globe_with_meridians)
- [SEO](#seo-spider)
- [Packages Used](#packages-used-package)
- [APIs Used](#apis-used-world_map)
- [Fonts and Images](#fonts-and-images-performing_arts)
- [Upcoming Features](#upcoming-features-construction)
- [Contributors](#contributors-man_technologistwoman_technologist)

<br /><br />


# Sections :bookmark:
- HOME
- ABOUT
- RESUME
    - EDUCATION
    - SKILLS
    - EXPERIENCE
    - PROJECTS 
    - Achievements <br />
- SERVICES 
    - TESTIMONIALS <br />
- BLOG
- CONTACTS 

<br /><br />

# Demo :movie_camera:
![](https://raw.githubusercontent.com/PhantomScript/asset-container/main/developer-portfolio/demo.gif)
## View live demo [here](https://dev-portfolio-template.netlify.app/).

<br />


#### Make sure you have the latest version of both Git and Node on your computer.

```
node --version
git --version
```

<br />

# Getting Started :dart:
### Fork and Clone the repo

#### To Fork the repo click on the fork button at the top right of the page. Once the repo is forked open your terminal and perform the following commands

```
git clone hhttps://github.com/<YOUR GITHUB USERNAME>/developer-portfolio.git
cd developer-portfolio
```
### Install packages from the root directory
```
npm install
```
#### or
```
yarn install
```
### Start the development server
```
npm start
```
#### or
```
yarn start
```
<br />

# Folder Structure

```bash
├── LICENSE   
├── README.md        
├── package-lock.json
├── package.json     
├── public
│   ├── _redirects   
│   ├── favicon.ico  
│   ├── favicon.png
│   ├── favicon512.png
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src
│   ├── App.css
│   ├── App.js
│   ├── assets
│   │   ├── fonts
│   │   │   └── Bestermind
│   │   │       └── BestermindRegular.ttf
│   │   ├── pdf
│   │   │   └── resume.pdf
│   │   └── svg
│   │       ├── about
│   │       ├── contacts
│   │       ├── education
│   │       ├── experience
│   │       ├── projects
│   │       ├── skills
│   │       ├── social
│   │       └── testimonials
│   ├── components
│   │   ├── About
│   │   │   ├── About.css
│   │   │   └── About.js
│   │   ├── Achievements
│   │   │   ├── Achievements.css
│   │   │   └── Achievements.js
│   │   │   └── AchievementCard.js
│   │   ├── BackToTop
│   │   │   ├── BackToTop.css
│   │   │   └── BackToTop.js
│   │   ├── Blog
│   │   │   ├── Blog.css
│   │   │   ├── Blog.js
│   │   │   └── SingleBlog
│   │   │       ├── SingleBlog.css
│   │   │       └── SingleBlog.js
│   │   ├── Contacts
│   │   │   ├── Contacts.css
│   │   │   └── Contacts.js
│   │   ├── Education
│   │   │   ├── Education.css
│   │   │   ├── Education.js
│   │   │   └── EducationCard.js
│   │   ├── Experience
│   │   │   ├── Experience.css
│   │   │   ├── Experience.js
│   │   │   └── ExperienceCard.js
│   │   ├── Footer
│   │   │   ├── Footer.css
│   │   │   └── Footer.js
│   │   ├── Landing
│   │   │   ├── Landing.css
│   │   │   └── Landing.js
│   │   ├── Navbar
│   │   │   ├── Navbar.css
│   │   │   └── Navbar.js
│   │   ├── Projects
│   │   │   ├── Projects.css
│   │   │   ├── Projects.js
│   │   │   └── SingleProject
│   │   │       ├── SingleProject.css
│   │   │       └── SingleProject.js
│   │   ├── Services
│   │   │   ├── Services.css
│   │   │   ├── Services.js
│   │   │   └── SingleService
│   │   │       ├── SingleService.css
│   │   │       └── SingleService.js
│   │   ├── Skills
│   │   │   ├── Skills.css
│   │   │   └── Skills.js
│   │   ├── Testimonials
│   │   │   ├── Testimonials.css
│   │   │   └── Testimonials.js
│   │   └── index.js
│   ├── contexts
│   │   └── ThemeContext.js
│   ├── data
│   │   ├── aboutData.js
│   │   ├── achievementData.js
│   │   ├── blogData.js
│   │   ├── contactsData.js
│   │   ├── educationData.js
│   │   ├── experienceData.js
│   │   ├── headerData.js
│   │   ├── projectsData.js
│   │   ├── servicesData.js
│   │   ├── skillsData.js
│   │   ├── socialsData.js
│   │   ├── testimonialsData.js
│   │   └── themeData.js
│   ├── index.css
│   ├── index.js
│   ├── pages
│   │   ├── Blog
│   │   │   ├── BlogPage.css
│   │   │   └── BlogPage.js
│   │   ├── Main
│   │   │   └── Main.js
│   │   ├── Project
│   │   │   ├── ProjectPage.css
│   │   │   └── ProjectPage.js
│   │   └── index.js
│   ├── reportWebVitals.js
│   ├── theme
│   │   ├── images.js
│   │   └── theme.js
│   └── utils
│       ├── ScrollToTop.js
│       └── skillsImage.js
└── yarn.lock
```
<br />

# Hosting
## Heroku
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [Heroku](https://www.heroku.com/) | [Deploying React App on Heroku from GitHub](https://medium.com/make-it-heady/deploying-create-react-app-on-heroku-from-github-49447561f670) | [Youtube](https://www.youtube.com/watch?v=dn4mmfbletg) |

## Github Pages
| Site   | Docs  | Demo  |
| :-------------: |:-------------: |:-------------: |
| [GitHub Pages](https://pages.github.com/) | [Deploying React App on GitHub Pages from GitHub](https://create-react-app.dev/docs/deployment/#github-pages) | [Youtube](https://youtu.be/F8s4Ng-re0E) |

<br />
<br />

# Packages Used :package:

| Client Side Packages  |
| :-------------: |
| @material-ui/core  |
| @material-ui/icons  |
| axios |
| react-fast-marquee |
| react-helmet  |
| react-icons  |
| react-reveal |
| react-router-dom  |
| react-router-hash-link  |
| react-slick  |
| slick-carousel |
| validator |


<br />

# APIs Used
- [SheetDB](https://sheetdb.io/)

 
<br />

# Fonts and Images

## Illustrations
- [Icons8](https://icons8.com/illustrations/styles)
- [SVG Porn](https://svgporn.com/)

## Icons
- [Material Icons](https://material-ui.com/components/material-icons/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Fonts
- [Poppins](https://fonts.google.com/specimen/Poppins)
- [Montserrat](https://fonts.google.com/specimen/Montserrat)
- [Raleway](https://fonts.google.com/specimen/Raleway)
- [Big Shoulders Text](https://fonts.google.com/specimen/Big+Shoulders+Text)
- [Bestermind](https://www.dafont.com/bestermind.font)
- [Roboto](https://fonts.google.com/specimen/Roboto)

<br />

# Contributor

<div>
    <table>
        <tr>
            <td align="center"><a href="https://github.com/tpham912"><img src="src/assets/jpg/pp.jpg" width="135px;" height="135px;" alt=""/><br /><b>Tina P</b></a></td>
        </tr>
    </table>
</div>

