# Wah Kong II Website

The website completed and presented for Milestone Project 1 is intended to showcase Wah Kong II, a classic wooden yacht based in Weymouth, UK. It has been designed and developed using a mobile-first approach, and is accessible and responsive across a range of devices.

![Wah Kong Website shown on a range of devices](docs/images/wah_kong_website.png)

[Visit the deployed site for Wah Kong II](https://mikiburgess.github.io/MP1-Wah-Kong/index.html)

- - -

## Table of Contents

- [Introduction](#Introduction)
- [User Experience (UX)](#User-Experience-(UX))
    - [User Stories](#User-Stories)
    - [Site Elements](#Site-Elements)
- [Site Design](#Site-Design)
    - [Wireframes](#Wireframes)
    - [Fonts](#Fonts)
    - [Color Scheme](#Color-Scheme)
    - [Site Content](#Site-Content)
- [Site Features](#Site-Features)
    - [Current Features](#Current-Features)
    - [Future Features](#Future-Features)
    - [Accessibility](#Accessibility)
-  [Development Process](#Development-Process)
    - [Tools](#Tools)
    - [Project Management](#Project-Management)
    - [Languages](#Languages)
    - [Frameworks](#Frameworks)
- [Testing](#Testing)
- [Deployment](#Deployment)
- [Future Development](#Future-Development)
- [Credits](#Credits)
    - [Site Content](#Site-Content)
    - [Code](#Code)
    - [Learning Resources and Inspiration](#Learning-Resources-and-Inspiration)
    - [Acknowledgements](#Acknowledgements)

- - -

## Introduction

## User Experience (UX)
This website showcases Wah Kong II, a classic wooden yacht currently moored in Weymouth, UK. Originally built in 1958, due to her age and construction she is of potential interest to the classic boat community.
She's been with her current owner since 2004, but at some point in the future she may need to be sold to a new owner. After discussion with the current owner it was decided that a website would be useful for communicating with various sailing communities, 
such as the classic boat community, and assist in her sale at some undefined point in the future.

From this initial discussion with the yacht's owner, a number of potential users and user stories were identified.

### User Stories
Three categories of users were identified:
- General site visitors,
- Visitors with specific interest in the yacht,
- Yacht owner (the primary customer for this web site).

##### GENERAL USERS
First time visitor to the site:
- As a First Time Visitor, I want to be able to navigate through the site easily and intuitively, to browse and locate the content.
- As a First Time Visitor, I want to be able to contact the owner with comments and/or to ask questions.
- As a First Time Visitor, I want to be able to where the organisation is located.

Returning visitors to the site:
- As a Returning Visitor, I want to be able to navigate the site quickly and easily in order to find the information I'm looking for.
- As a Returning Visitor, I want to be able to contact the owner with comments and/or to ask questions.

##### SPECIFIC USERS
Individuals with a personal interest in classic boats, such as other classic boat owners: 
- As a Site Visitor, I want to be able to see photos and read about the history and construction in order to learn more about her.

Individuals/companies interested in booking attendance at an event/regatta: 
- As an Event Organiser, I want to quickly and easily get an an overview of the history and build of the boat so that I can determine whether it's right for the event.

Companies looking for a classic boat for hire (TV/Film/Photography):
- As a Filmmaker/Photographer, I want to be able to see a variety of images so that I can determine whether the yacht may be a suitable candidate for the production and therefore worth reviewing on site.

Potential new owner: 
- As a Potential New Owner, I want to read about the specifications, construction and history, be able to view photos of various elements of the the yacht, so that I can determine whether she may be suitable for me therefore worth reviewing on site.

##### YACHT OWNER
- As the Owner, I want to be able to showcase my yacht so that anyone interested in her (national and international) can find out more and contact me directly.
- As the Owner, I want to advertise the yacht for potential commercial work, in order to raise fund for her maintenance.
- As the Owner, I want to be able to inform potential buyers of her details so that, in the future, I will be able to sell her to a classic yacht enthusiast.

### Site Elements
Considering the above user stories and the Milestone 1 Project Requirements, the following elements to be included in the site were identified:
- Overview of dimensions, construction and history
- Gallery showcasing the yacht herself and views from the yacht whilst at sea.
- Enquiry form for site visitors to request information regarding features/history, bookings and/or availability.
Plus, if time allows post-mvp (minimal viable product):
- Overview of her appearance in the movie ['On Chesil Beach'](https://www.imdb.com/title/tt1667321/)

- - -

## Site Design

### Wireframes
Wireframes were designed after the initial discussion with the yacht owner, reviewed with them during a second discussion in order to gather their feedback, then revised. The revision included adding a map to the contact page, showing the location. The final set of wireframes used for development are listed below:  
- [General page design](docs/wireframes/general_design.png) - the foundation for developing all site wireframes
- [Home Page (index.html)](docs/wireframes/p1_index.png)
- [Photo Gallery (gallery.html)](docs/wireframes/p2_gallery.png)
- [Contact Page (contact.html)](docs/wireframes/p3_contact.png)
- [Filming Page (filming.html; additional site page, post mvp)](docs/wireframes/p4_extra_filming.png)

### Fonts
- [Fontpair](https://www.fontpair.co/) was used to identify complementary font pairs for use across the site. The pair selected for use on this site - [Karla & Merriweather](https://www.fontpair.co/pairings/karla-merriweather) 
- The selected fonts were then imported into the stylesheet from [Google Fonts](https://fonts.google.com/).
- Additional site icons were obtained from [Fontawesome](https://fontawesome.com/). [Version 5](https://fontawesome.com/v5/search?o=r&m=free) was adopted due to being the version used in the Code Institute course. Future development however would involve upgrading this to the latest version.

### Color Scheme
The color scheme for the site was taken from the colors of Wah Kong near her mooring, using a photo including her deck, mast and cabin, the sea, and a clear blue sky. The photo was uploaded to the [Coolors](https://coolors.co/user/palettes) color palette creation tool, resulting in the following site color palette:

![Color palette for the Wah Kong website](docs/images/color_palette.png)

These colors were added as variables to the stylesheet to allow for easy reuse throughout the project:

``` 
{
    --wavesblue: rgba(208, 223, 228, .9);
    --wavesblue-light: rgba(208, 223, 228, .2);
    --skyblue: #67A3DF;
    --coverblue: #2D82DC;
    --mastbrown:#6D523D; 
    --cockpitbrown: #965825;
}
```

### Site Content
- The photographs used throuughout the site be taken, and owned, by myself and the yacht owner. 
- The text will be written by me, based on information provided by the yacht owner.
- Video of Wah Kong at sea will be taken, and owned by, myself.
- Movie trailer for 'On Chesil Beech' will be embedded from [YouTube](https://youtu.be/ZR6DWDfMDlM).
- The site icon of an Anchor was created on [Favicon](https://www.favicon.cc/?action=icon&file_id=996800), where it was both downloaded for project and shared online for others to use. 
- Location map for Weymouth Marina will be embedded from [Google Maps](https://www.google.co.uk/maps.


## Site Features
### Current Features
*(note:check requirements 3.2)*

### Future Features
This site was designed and developed according to the Milestone Project 1 requirements. As such it can be improved with further development to enhance funtionality and usability for the identified users. This includes (but is not limited to) the following:

- Incorporate [modal images](https://www.w3schools.com/howto/howto_css_modals.asp) into the photo gallery, allowing full size viewing of each gallery photo. 
- Add backend functionality to process submitted contact form data and respond accordingly (rather than using Code institute's form submission checker).
- Add a page of resources, including links to the [marina](https://www.boatfolk.co.uk/weymouth-marina-dorset), [yacht club](https://royal-dorset.com/), and [local boat yard](https://www.clarksboatworks.co.uk/).
- Current current social media links (site footer) do not currently direct the user to specific pages for Wah Kong, as these don't yet exist. Instead these links direct the user to the primary platform ,anding page. In future a social media presence will be developed, and links then added to the site footer.

If additional images are required,  royalty-free images will be obtained from [Pixabay](https://pixabay.com/). Those selected would be usable under their [Content Licence](https://pixabay.com/service/terms/) (Section 4) or licenced under the Creative [Commons Zero licence](https://pixabay.com/service/terms/) (Section 3).


### Accessibility
Site accessibility was considered throughout the deisgn and build process:
- Considering site colors for clarity and contrast.
- Using semantic HTML to dinstinguish between site elements.
- Adding descriptions to the alt attribute to all images across the site.
- Using aria labels to describe elements where there is no/limited descriptive text, such as the contact form data entry boxes.
- Including screen reader support for site icons (footer) with no explicit text descriptions, and ensuring menu accessibilty by explicitly idenfifying the current page.

- - -

##  Development Process
### Tools
- UI Wireframes were created using [Balsamiq](https://balsamiq.com/)
- Code was be developed locally using [Visual Studio Code](https://code.visualstudio.com/)
- (Chrome DevTools)[https://developer.chrome.com/docs/devtools/], as embedded within Google's Chrome browser, were used to support the development. In particular, the code inspector and the responsive design checker (for checking site responsiveness across all viewports)
- Versioning was managed locally using Git. All code was then pushed to [GitHub](https://github.com/mikiburgess)

### Project Management
Project planning and management was done using the GitHub Projects tool (i.e. a digital Kanban board).

### Languages
Pages were created using HTML and CSS. Comments were added throughout for explanation (where appropriate) and clarifying code structure.

### Frameworks
This project employed the Boostrap v4.5 framework (the version covered in the course videos). Bootstrap support was obtained through the official (Bootstrap documentation)[https://getbootstrap.com/docs/4.5/getting-started/introduction/, [W3Schools](https://www.w3schools.com/bootstrap/bootstrap_ver.asp, and through the Code Institute Slack Community.

- - -

## Testing
Results of site testing can be found in [TESTING.MD](docs/testing/TESTING.MD).

## Deployment

## Future Development
*to be completed - currently in separate notes document*
- - -

## Credits
I would like to credit the following resources and individuals for supporting both my learning and the development of this project.

### Site Content
- Yacht history, data and images were supplied by Martin Burgess, skipper and current owner of Wah Kong II. Additional images and video were taken from my personal library.
- Movie trailer video embedded from [YouTube](https://www.youtube.com/).

### Additional Code
- To align the page title text vertically in the frame on top of the hero image on each page, I used the [W3Schools 'How to'](https://www.w3schools.com/howto/howto_css_center-vertical.asp) guide and code (as also linked to explicitly in the project stylesheet).
- [Bootstrap v4.5](https://getbootstrap.com/) framework in site styling.
- The fonts used in this project are from [Google](https://fonts.google.com/) and [Fontawesome](https://fontawesome.com/). 
- Collapsible navigation menu was inspired by, and adpapted from Code Institute's *Whiskey Drop* walkthrough project. 
- Style of the site button, used on the Contact page, was inspired by Code Institute's *Love Running* walkthrough project.
- Shadow and hover action of the site button (contact page) was inspired by [W3Schools](https://www.w3schools.com/css/css3_buttons.asp).

### Learning Resources and Inspiration
Additional learning resources (*alongside Code Institute*):
- [Balsamiq Documentation](https://balsamiq.com/wireframes/desktop/docs/symbols/#importing-symbols-from-wireframes-to-go): learning how to use Balsamiq to develop Wireframes during the design stage,
- [Bootstrap v4.5 Documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/): Building upon the learning undertaken during the course to improve my knowledge and understanding of this framework.
- [W3Schools](https://www.w3schools.com/): Specifically the reference pages for [CSS](https://www.w3schools.com/css/default.asp) and [Bootstrap](https://www.w3schools.com/bootstrap4/default.asp), and their [Accessibility Guidelines](https://www.w3schools.com/accessibility/index.php).
- [Medium.com](https://medium.com/): Specifically for the article ['Best Practices on aria-label, aria-labelledby and aria-describedby'](https://medium.com/accessibility-a11y/best-practices-on-aria-label-aria-labelledby-and-aria-describedby-913fc9e396ae) by Saptarshi Katwala.
- [The Net Ninja on YouTube](https://www.youtube.com/playlist?list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR): Git & GitHub Tutorial for Beginners.


Creation of the README.MD and TESTING.MD files was inspired by the following: 
- Code Institute alumnus, [Kera Cudmore's](https://github.com/kera-cudmore) GitHub repository includes examples and advice for creating these documents for [milestone project 1](https://github.com/kera-cudmore/readme-examples/blob/main/milestone1-readme.md), plus an example completed repo for [Bully Book Club](https://github.com/kera-cudmore/Bully-Book-Club) website.

### Acknowledgements
I would like to acknowledge the following people who helped me complete this milestone project:
- [Iris Smok](https://github.com/Iris-Smok) - our Code Institute cohort facilitator, for being a constant source of support and encouragement.
- [Jubril Akolade](https://github.com/Jubrillionaire) - my Code Institute mentor, for their invaluable feedback and suggestions during the development of this project.
- Martin Burgess - owner and skipper of Wah Kong II, for providing images, yacht data, and feedback during the development process.
- Dr Nic Caine - professional software developer, for providing additional feedback during the development process.

- - -
