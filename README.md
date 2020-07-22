# Project Overview


|  Day | Deliverable | Status
|---|---| ---|
|Day 1| Project Description | Incomplete
|Day 1| Wireframes / Priority Matrix / Timeline | Complete
|Day 3| Core Application Structure (HTML, CSS, etc.) | Complete
|Day 4| MVP & Bug Fixes | Complete
|Day 5| Final Touches | Complete
|Day 6| Present | Complete


## Project Description

My Portfolio will contain a headshot of me at the top, along with my name, and my career aspirations. This will resemble a resume containing my prior education, work experience, and projects that I have completed up to date. Additionally, the website will have a contact page where recruiters may enter their information to contact me.

## Google Sheet

[Link To Google Sheet](https://docs.google.com/spreadsheets/d/1UUsLTR3KfDVDztVxiJ9pC61R8jDDpiVVilF-fxHzp4U/edit#gid=0)

## Wireframes 

    
-[cloudinary](https://res.cloudinary.com/)

- [Mobile](https://res.cloudinary.com/stephaniev/image/upload/v1595453354/mobile_format_faq4d4.jpg)
- [Tablet](https://res.cloudinary.com/stephaniev/image/upload/v1595453340/Tablet_Framework_hpovtj.jpg)
- [Desktop](https://res.cloudinary.com/stephaniev/image/upload/v1595453377/Desktop_Framework_pvm8em.jpg)


## Time/Priority Matrix 

[Prioritized](https://res.cloudinary.com/stephaniev/image/upload/v1595454521/Time_Matrix_imcjmt.jpg) based on the `Time and Priority` Matrix.  

#### MVP 

- Inserting Logos
- Navigation Bar
- Project Session
- Contact Section
- Hamburger Menu
- Inserting API's
- Media Query
- Flexbox

#### PostMVP 

- Additional Logos
- Additional Content For Skills
- External Links

## Functional Components



#### MVP
| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Inserting API's | H | 12 hours | 10 hours | 10 hours|
| Navigation Bar | H | 5 hours | 8 hours | 8 hours|
| Media Query | H | 7 hours | 15 hours | 15 hours|
| Hamburger Menu | H | 4 hours| 1hr | 1hr |
| Project Section| H | 10 hours | 12 hours | 12 hours|
| Contact Section | L | 2 hours| 5 hours | 5 hours |

| Total | H | 40 hours| 51 hours | 51 hours |

#### PostMVP
| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Additional Logos | L | 2 hours | 1hr | 1hr|
| Additional Content For Skills | L | 3 hours | 1hr | 1hr|
| External Links | L | 1hr | 1hr | 1hr|

| Total | L | 6 hours| 3 hours | 3 hours |

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description  

```
//hamburger menu

const showMenu = (event) => {
    if (show) {
        $tabletLinks.each(function(index){
            $(this).css("display","none")
        })
        show = false
    } else {
        $tabletLinks.each(function(index){
            $(this).css("display","block")
        })
        show = true
    }
}

```

## Issues and Resolutions
 My project section would not move from the top of my webpage, regardless of using positioning, flexbox, and grid.
   
**RESOLUTION**: Positioning and flexbox conflict with each other, therefore had to take out all the absolute positioning. Along with height in properties that didn't need height. 