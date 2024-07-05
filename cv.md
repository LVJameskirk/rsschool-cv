# Vitaly Laletin
![My Photo](/MyPhoto.jpg "My photo")

## Contacts
* **Tel:** +79138339744
* **Email:** LVJameskirk@gmail.com
* **Discord:** @LVJameskirk
* **Telegram:** @LaletinVitaly
* **GitHub:** [LVJameskirk](https://github.com/LVJameskirk)

## About Me
My goal is to become a Full-Stack developer, master all the necessary technologies for writing the Frontend and Backend parts of a WEB application
I consider my strong point to be my experience in IT as a QA Engineer for more than 5 years. This allows me to have a good understanding of the software development process and the role of each participant. Also, in the process of work, I have already mastered many technologies that are used in practice. Read more about them in the section - Skills.

## Skills 
* HTML&CSS
* Sass
* Basics JS
* GIT & Command line
* SQL
* Languages:
  + Russian - Native
  + English - B1 Intermediate

## Work Experience

**Sber**
*Senior QA Engineer*
March 2024 - Now
Web and Backend Testing
Establishing testing processes in a team
Scrum master

**Skyeng**
*Middle QA Engineer*
November 2020 - August 2023
Functional testing of new features and regression.
On Frontend, I actively used dev tools and mocks.
On Backend - API testing via Postman. PostgreSQL - for working with databases.

## Education
* [Hexlet](https://code-basics.com/ru). Courses on the basics of HTML, CSS and JS on the platform
* Certificate Sololearn - Web Development
![Sololearn](/certificate.jpg "Certificate Sololearn")
* [RS School](https://rs.school/js/) in the “JavaScript/Front-end”

## Projects
[This CV](https://github.com/LVJameskirk/rsschool-cv)
[Personal project about high points. Using Sass and Webpack technologies](https://allhighpoints.ru/)

## Code
```
const addTagsClickHandler = () => {
    document.querySelector('.region-tabs__list').addEventListener('click', (e) => {
        if(e.target.classList.contains('region-tabs__item')){
            let clickedTag = e.target;
            removeSelectedTags();
            selectClickedTag(clickedTag);
            showGrid(clickedTag);
        }
    })
}
```