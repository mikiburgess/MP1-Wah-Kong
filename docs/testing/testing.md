# Wah Kong II Website

Testing of Milestone Project 1 - Wah Kong II.

## Table of Contents

- [Introduction](#introduction)
- [Responsiveness](#responsiveness)
- [Browser Compatability](#browser-compatbility)
- [Lighthouse](#Lighthouse)
- [Code Validation](#Code-Validation)
- User Story Testing (inc able: 'User Story' and 'Testing' columns)
- Features (manually test all features. again inc table)
- [Bugs](#Bugs)
    - [Fixed Bugs](#Fixed-Bugs)
    - [Unfixed Bugs](#Unfixed-Bugs)


- - -

## Introduction
This document describes the testing process and results for Milestone Project 1. For additional project details please refer to:
- [Main project README document](../../README.MD)
- [Deployed web site](https://mikiburgess.github.io/MP1-Wah-Kong/)

## Responsiveness
(inc screenshots and poss video. test each page. inc summary table)


| Responsiveness | Android Mobile | Apple Mobile | Android Tablet Device | Apple Tablet Device | Desktop 1024px | Desktop >1200px | Notes | Evidence |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| Site is responsive >=700px | n/a | n/a |  |  |  |  | Notes | |
| Site is responsive <699px |  |  | n/a | n/a | n/a | n/a | Notes | |
| Text Readable | Good | Good | Good | Good | Good | Good | No readability issues identified on any tested viewport | |
| Links / URLs work |  |  |  |  |  |  | Notes | |
| Hero Images work |  |  |  |  |  |  | Notes | |
| Non-hero images work |  |  |  |  |  |  | Notes | |
| Contact form works |  |  |  |  |  |  | Notes | |
| Google map visible |  |  |  |  |  |  | Notes | |
| Site renders as expected |  |  |  |  |  |  | Notes | |

Site responsiveness across viewports can also be reviewed through [Am I Response?](https://ui.dev/amiresponsive?url=https://mikiburgess.github.io/MP1-Wah-Kong/)

## Browser Compatability
*(2-3 browsers. inc summary table)*

| ----------- | ----------- |
| | Chrome | Edge | Firefox | Safari | Opera | Notes | Evidence |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Intended appearance? |  |  |  |  |  |
| Intended responsiveness? |  |  |  |  |  |




## Lighthouse
*(remember to disable extensions)*


## Code Validation 
W3C online code validators were used to validate the final versions of all code developed for this project. Below are the results of using their [Markup Validation Service](https://validator.w3.org/) and [Jigsaw](https://jigsaw.w3.org/css-validator/). All code was validated using the 'direct input' option.

### HTML Validation
Completed using [W3C HTML Validator](https://validator.w3.org/)

On first check the validator raised the following, which were corrected: 
- **Index.html**: H1 element was not persent. As this impacts accessibility, this was corrected across all pages by updating the primary title (site logo) from H2 to H1. 
- **Index.html**: 'Info' alert that trailing slash on void elements has no effect. As such these were removed from all affected elements.
- **Index.html**: 'Warning' that using two consectutive hyphens in comments means documents are not mappable to XML 1.0. These consecutive hyphens were present in the header comment, and were removed from all pages.
- **Filming.html**: Missing 'blank' identified in target attribute of IMDB link, so '_' was corrected to '_blank'. 
- **Filming.html**: Unwanted 'frameborder' attribute identified in iframe element. This was removed.
- **Contact.html**: Validator identified that 'id' attribute was required in addition to 'name' attribute for non-hidden form controls. These were therefore added.

One warning was not corrected:
- **Gallery.html**: One warning recommending adding div element to section. As div element is present immediately below the section element, no change was made.


Following the initial tests, the following checks were completed:

| Page | Result | Evidence |
| ----------- | ----------- | ----------- |
| index.html | Document check completed. No errors or warnings shown. | [Screenshot](screenshots/html_validation_index.png) |
| gallery.html | Document check completed. No errors or warnings shown (other than the warning described above). | [Screenshot](screenshots/html_validation_gallery.png) |
| filming.html | Document check completed. No errors or warnings shown. | [Screenshot](screenshots/html_validation_filming.png) |
| contact.html | Document check completed. No errors or warnings shown.  | [Screenshot](screenshots/html_validation_contact.png) |


### CSS Valdation
Completed using [Jigsaw](https://jigsaw.w3.org/css-validator/), the W3C CSS Validation tool.

The site stylesheet, style.css, was validated and no errors were found ([Screenshot](screenshots/css_validation_stylesheet.png)). 

The following warnings were raised ([Screenshot](screenshots/css_warning_stylesheet.png)): 
- Due to validation by 'direct import' method imported stylesheets were not checked. 
- Due to the dynamic nature of CSS variables, these were not checked.
- Vendor extension flagged.


None of these warnings require action.


## User Story Testing
*(inc able: 'User Story' and 'Testing' columns)*

| User Story | Testing |
| ----------- | ----------- |
|  |  |
|  |  |

## Features
*(manually test all features. again inc table)*

| Feature | Action (test) | Effect (result) |
| ----------- | ----------- |
| | | |
| | | |
| | | |

## Bugs
During development and manual testing process, a number of bugs were identified. These are summarised below: those what were identified and fixed, and those that are not yet foxed but would be rectified with further development.

### Fixed Bugs 
| Problem | Solution | Result |
| ----------- | ----------- | ----------- |
| Gallery page: Slow to load | Gallery image files resized for web viewing | Reduced file sizes no longer results in unacceptable delay in page download |
| Contact page: Users were able to submit the contact form without ticking the "Yes, I'm a Human" confirmation box. | Error identified - required attribute was attached to label rather than checkbox. This was corrected. | User is now prompted to check the box if they fail to do so, and form submission will only be successful when all fields are complete.  |
| | | |

### Unfixed Bugs 

| Issue | Comments |
| ----------- | ----------- | 
| Contact page: Contact form data currently not used | This is a limitation of the currently project. Fixing this would be completed under future development. |
| Filming page: Inconsistent styling and responsive behaviour | This page was designed and developed in addiotn to the minimum project requirements. As such it needs further work to improve and complete the build - updating the formatting and layout of the movie text and trailer to be consistent with the Contact page to improve site consistency and page responsiveness. |
| Image formats and sizes | To improve performance the file size of all photographs need be reduced. For improved browser compatability they also need to be available in multiple formats (min. WebP and JPG). This is an action for future development. |

- - -