# Wah Kong II Website

Overview of the testing of Milestone Project 1 - Website for yacht Wah Kong II.

![Wah Kong Website shown on a range of devices](../images/wah_kong_website.png)

[Visit the deployed site for Wah Kong II](https://mikiburgess.github.io/MP1-Wah-Kong/index.html)

- - -

## Table of Contents

- [Introduction](#Introduction)
- [Browser Compatability](#Browser-Compatbility)
- [Responsiveness](#Responsiveness)
    - [Devices Tested (Emulated)](#Devices-Tested-(Emulated))
    - [Test Results](#Test-Results)
- [Code Validation](#Code-Validation)
    - [HTML Validation](#HTML-Validation)
    - [CSS Validation](#CSS-Validation)
- [Lighthouse](#Lighthouse)
    - [Lighthouse Testing Results Summary](#Lighthouse-Testing-Results-Summary)
    - [Performance](#Performance)
    - [Accessibility](#Accessibility)
    - [Best Practices](#Best-Practices)
    - [Progressive Wep App (PWA)](#Progressive-Wep-App-(PWA))
- [User Story Testing](#User-Story-Testing)
- [Features](#Features) 
- [Bugs](#Bugs)
    - [Fixed Bugs](#Fixed-Bugs)
    - [Unfixed Bugs](#Unfixed-Bugs)


- - -

## Introduction
This document describes the testing process and results for Milestone Project 1. For additional project details please refer to:
- [Main project README document](../../README.MD)
- [Deployed web site](https://mikiburgess.github.io/MP1-Wah-Kong/)


## Browser Compatability
Browser compatability testing was completed with Chrome, Firefox, Safari and Opera, running on a MacBook. Edge and IE were not tested at this stage due to lack of access to those browsers. Before professional site deployment, compatability would need to be tested on Windows-specific and a selection of mobile-specific browsers.


| | Chrome | Firefox | Safari | Opera | Notes | 
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- 
| Intended appearance? | Good | Good | Good | Good | No issues identified |
| Intended responsiveness? | Good | Good | Good | Good | No issues identified |

Results of the testing undertaken on each browser can also be seen in the following folders: [Chrome](browsers/chrome/), [Firefox](browsers/firefox/), [Safari](browsers/safari/), [Opera](browsers/opera/).

- - -

## Responsiveness

Responsiveness tests were undertaken using Google Chrome DevTools on a MacBook. Due to lack of access to multiple devices, all responsiveness tests were completed using the emulation tool. Before professional site deployment, responsiveness would need to be tested on real devices.

### Devices Tested (Emulated)
|   | Android Mobile | Apple Mobile | Android Tablet Device | Apple Tablet Device | Desktop 1024px | Desktop >1200px |
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Device  | Pixel 2 (411px) | iPhone 6/7/8 (375px) | Galaxy Tab S4 (712px) | iPad (768px) | 1024px (emulated) | 1300px (emulated) |
| Index.html | [standard](responsive/deployed_index_html_Pixel_2.png/) / [full-size](responsive/deployed_index_html_Pixel_2-FULL.png)| [standard](responsive/deployed_index_html_iPhone_6_7_8.png) / [full-size](responsive/deployed_index_html_iPhone_6_7_8-FULL.png) | [standard](responsive/deployed_index_html_Galaxy_Tab_S4.png) / [full-size](responsive/deployed_index_html_Galaxy_Tab_S4-FULL.png) | [standard](responsive/deployed_index_html_iPad.png) / [full-size](responsive/deployed_index_html_iPad-FULL.png) | [standard](responsive/deployed_index_html-1024.png) / [full-size](responsive/deployed_index_html-1024-FULL.png) | [standard](responsive/deployed_index_html-1300.png) / [full-size](responsive/deployed_index_html-1300-FULL.png) |
| Gallery.html | [standard](responsive/deployed_gallery_html_Pixel_2.png/) / [full-size](responsive/deployed_gallery_html_Pixel_2-FULL.png)| [standard](responsive/deployed_gallery_html_iPhone_6_7_8.png) / [full-size](responsive/deployed_gallery_html_iPhone_6_7_8-FULL.png) | [standard](responsive/deployed_gallery_html_Galaxy_Tab_S4.png) / [full-size](responsive/deployed_gallery_html_Galaxy_Tab_S4-FULL.png) | [standard](responsive/deployed_gallery_html_iPad.png) / [full-size](responsive/deployed_gallery_html_iPad-FULL.png) | [standard](responsive/deployed_gallery_html-1024.png) / [full-size](responsive/deployed_gallery_html-1024-FULL.png) | [standard](responsive/deployed_gallery_html-1300.png) / [full-size](responsive/deployed_gallery_html-1300-FULL.png) |
| Filming.html | [standard](responsive/deployed_filming_html_Pixel_2.png/) / [full-size](responsive/deployed_filming_html_Pixel_2-FULL.png)| [standard](responsive/deployed_filming_html_iPhone_6_7_8.png) / [full-size](responsive/deployed_filming_html_iPhone_6_7_8-FULL.png) | [standard](responsive/deployed_filming_html_Galaxy_Tab_S4.png) / [full-size](responsive/deployed_filming_html_Galaxy_Tab_S4-FULL.png) | [standard](responsive/deployed_filming_html_iPad.png) / [full-size](responsive/deployed_filming_html_iPad-FULL.png) | [standard](responsive/deployed_filming_html-1024.png) / [full-size](responsive/deployed_filming_html-1024-FULL.png) | [standard](responsive/deployed_filming_html-1300.png) / [full-size](responsive/deployed_filming_html-1300-FULL.png) |
| Contact.html | [standard](responsive/deployed_contact_html_Pixel_2.png/) / [full-size](responsive/deployed_contact_html_Pixel_2-FULL.png)| [standard](responsive/deployed_contact_html_iPhone_6_7_8.png) / [full-size](responsive/deployed_contact_html_iPhone_6_7_8-FULL.png) | [standard](responsive/deployed_contact_html_Galaxy_Tab_S4.png) / [full-size](responsive/deployed_contact_html_Galaxy_Tab_S4-FULL.png) | [standard](responsive/deployed_contact_html_iPad.png) / [full-size](responsive/deployed_contact_html_iPad-FULL.png) | [standard](responsive/deployed_contact_html-1024.png) / [full-size](responsive/deployed_contact_html-1024-FULL.png) | [standard](responsive/deployed_contact_html-1300.png) / [full-size](responsive/deployed_contact_html-1300-FULL.png) |

### Test Results

| Responsiveness | Android Mobile | Apple Mobile | Android Tablet Device | Apple Tablet Device | Desktop 1024px | Desktop >1200px | Notes | 
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | 
| Site is responsive >=700px | n/a | n/a | Good | Good | Good | Good | Responsive across all tested viewports |
| Site is responsive <699px | Good | Good | n/a | n/a | n/a | n/a | Responsive across all tested viewports |
| Text Readable | Good | Good | Good | Good | Good | Good | No readability issues identified on any tested viewport |
| Links / URLs work | Good | Good | Good | Good | Good | Good | No broken links identified |
| Hero Images work | Good | Good | Good | Good | Good | Good | No issues identified |
| Non-hero images work | Good | Good | Good | Good | Good | Good | No issues identified |
| Contact form works | Good | Good | Good | Good | Good | Good | No issues identified |
| Google map visible | Good | Good | Good | Good | Good | Good | Map displays as expected across all viewports |
| Site renders as expected | Good | Good | Good | Good | Good | Good | No issues identified |

Site responsiveness across a selection of viewports can also be reviewed through [Am I Response?](https://ui.dev/amiresponsive?url=https://mikiburgess.github.io/MP1-Wah-Kong/)

- - -

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

The following warnings were raised ([Screenshot](screenshots/css_warnings_stylesheet.png)): 
- Due to validation by 'direct import' method imported stylesheets were not checked. 
- Due to the dynamic nature of CSS variables, these were not checked.
- Vendor extension flagged.


None of these warnings require action.

- - -

## Lighthouse
Lighthouse was used to generate reports on the Mobile and Desktop versions of each site page.
This was done by opening the deployed site in a Google Chrome Incognito page (to ensure all Chrome extensions were disabled for testing).

Below is a tabular summary of the Lighthouse report results for every page, with links to the detailed reports (for reference). Following the results is a reflection of the results and actions that would be undertaken in future to improve site performance.

### Lighthouse Testing Results Summary

| Test | Performance | Accessibility | Best Practices | SEO | Report |
| -------- | -------- | -------- | -------- | -------- | -------- |
| Index - Mobile | ![73](lighthouse/ratings/073.jpg) | ![98](lighthouse/ratings/098.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/index-mobile-report.pdf) / [html](lighthouse/index-mobile-report.html) |
| Index - Desktop | ![94](lighthouse/ratings/094.jpg) | ![98](lighthouse/ratings/098.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/index-desktop-report.pdf) / [html](lighthouse/index-desktop-report.html) |
| Gallery - Mobile | ![73](lighthouse/ratings/073.jpg) | ![98](lighthouse/ratings/098.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/gallery-mobile-report.pdf) / [html](lighthouse/gallery-mobile-report.html) |
| Gallery - Desktop | ![75](lighthouse/ratings/075.jpg) | ![98](lighthouse/ratings/098.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/gallery-desktop-report.pdf) / [html](lighthouse/gallery-desktop-report.html) |
| Filming - Mobile | ![67](lighthouse/ratings/067.jpg) | ![98](lighthouse/ratings/098.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/filming-mobile-report.pdf) / [html](lighthouse/filming-mobile-report.html) |
| Filming - Desktop | ![71](lighthouse/ratings/071.jpg) | ![98](lighthouse/ratings/098.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/filming-desktop-report.pdf) / [html](lighthouse/filming-desktop-report.html) |
| Contact - Mobile | ![76](lighthouse/ratings/076.jpg) | ![93](lighthouse/ratings/093.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/contact-mobile-report.pdf) / [html](lighthouse/contact-mobile-report.html) |
| Contact - Desktop | ![95](lighthouse/ratings/095.jpg) | ![93](lighthouse/ratings/093.jpg) | ![100](lighthouse/ratings/100.jpg) | ![100](lighthouse/ratings/100.jpg) | [pdf](lighthouse/contact-desktop-report.pdf) / [html](lighthouse/contact-desktop-report.html) |


Based on the above it can be seen that there are a few areas where the site could be improved.
The main issues to be considered in future project, and rectified when developing this site further for the client, are listed below:

### Performance
- *Serve images in next-gen formats*: This project currently uses png and jpg images. During project development I learned about WepP format, and multiple browsers by providing both WebP and alternative formats. This will improve site performance, especially on mobile devices.
- *Efficiently encode images*: Improved encoding will reduce network payload and improve page load time.
- *Properly size images*: All photographs need to be checked and sized according to a standard site size setting. Height and Width attributes can then be set for each photo. This will reduce uneccessary processing and improve performance.

### Accessibility
- *Heading elements are not in a sequentially-descending order*: This was highlighted as H5 was used as a small heading, when on reflection this should have been a sequential decending from previous headers. According to the final design, all H5 elements will be revised to H4 and the stylesheet updated accordingly.
- *Background and foreground colors do not have a sufficient contrast ratio*: In future more time will be spent during the design stage testing the color palette to ensure the colors support accessibility.
- *```<frame>``` or ```<iframe>``` elements do not have a title*: Where used, in future these will incorporate title attributes to improve accessibility.

### Best Practices
- All fine.

### Progressive Wep App (PWA)
Additional suggestions for improvement were included in the PWA section of each report.
- *Does not set a theme color for the address bar*: In future a color scheme will be explicitly specified for each page, for both light and dark, using the ```<meta name="theme">``` tag, with corresponding color themes in the css stylesheet (standard - light; media query for suporting 'dark').
- In future projects sites will be checked against a [PWA checklist](https://web.dev/pwa-checklist/?utm_source=lighthouse&utm_medium=devtools).

- - -

## User Story Testing

| User Story | Testing |
| ----------- | ----------- |
| As a First Time Visitor, I want to be able to navigate through the site easily and intuitively, to browse and locate the content. | Navigation menu is clearly visible at the top of every page. |
| As a First Time Visitor, I want to be able to contact the owner with comments and/or to ask questions. | The contact form enables any visitor to send a message directly to the crew. |
| As a First Time Visitor, I want to be able to where the organisation is located. | Google map is embedded within the contact page, showing location of Wah Kong's home marina.  |
| As a Returning Visitor, I want to be able to navigate the site quickly and easily in order to find the information I'm looking for. | Navigation menu is clearly visible at the top of every page. |
| As a Returning Visitor, I want to be able to contact the owner with comments and/or to ask questions. | The contact form enables any visitor to send a message or question directly to the crew. There are no limits as to the number of messages a user can manually submit through this form. |
| As a Site Visitor, I want to be able to see photos and read about the history and construction in order to learn more about her. | Brief history and summary of construction is presented on the home/landing page. The Gallery includes internal and external photographs of the yacht, including the deck, hull, cockpit, cabin, sails and mast. |
| As an Event Organiser, I want to quickly and easily get an overview of the history and build of the boat so that I can determine whether it's right for the event. | Brief history and summary of construction is presented on the home/landing page, with summary of her availability for hire. |
| As a Filmmaker/Photographer, I want to be able to see a variety of images so that I can determine whether the yacht may be a suitable candidate for the production and therefore worth reviewing on site. | A gallery of photographs is provided, showcasing a variety of aspects of the yacht herself and views from the yacht. The filming page also presents one example of where and how she was used in a movie. Availability for hire is summarised on the home/landing page. |
| As a Potential New Owner, I want to read about the specifications, construction and history, be able to view photos of various elements of the yacht, so that I can determine whether she may be suitable for me therefore worth reviewing on site. | Brief history and summary of her specifications and construction is presented on the home/landing page. The Gallery includes internal and external photographs of the yacht, including the deck, hull, cockpit, cabin, sails and mast. |
| As the Owner, I want to be able to showcase my yacht so that anyone interested in her (national and international) can find out more and contact me directly. | Site contains a variety of images, and two videos, showing a number of aspects of the yacht, and provides an insight into what she is like to sail. Site has been deployed on Github Pages, and in future will be deployed on a server with a bespoke URL, making this accessible worldwide.  |
| As the Owner, I want to advertise the yacht for potential commercial work, in order to raise fund for her maintenance. | Availability for hire is summarised on the home/landing page. The filming page showcases one example of where and how she was used in a movie. The Contact page provides a quick way for interested parties to make direct contact with the owner. |
| As the Owner, I want to be able to inform potential buyers of her details so that, in the future, I will be able to sell her to a classic yacht enthusiast. | Brief history and summary of her specifications and construction is presented on the home/landing page. The Gallery includes internal and external photographs of the yacht, including the deck, hull, cockpit, cabin, sails and mast. The Contact page provides a quick way for any potential new owner to make direct contact with the current owner. |

- - -

## Features
*(manually test all features. again inc table)*

| Feature | Action (test) | Effect (result) |
| ----------- | ----------- |
| | | |
| | | |
| | | |

- - -

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