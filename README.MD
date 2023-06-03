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
    - [Accessibility](#Accessibility)
    - [Future Features](#Future-Features)
-  [Development Process](#Development-Process)
    - [Tools](#Tools)
    - [Project Management](#Project-Management)
    - [Languages](#Languages)
    - [Frameworks](#Frameworks)
- [Testing](#Testing)
- [Deployment and Local Development](#Deployment-and-Local-Development)
    - [Deployment](#Deployment)
    - [Local Development](#Local-Development)
- [Future Development Practices](#Future-Development-Practices)
- [Credits](#Credits)
    - [Site Content](#Site-Content)
    - [Code](#Code)
    - [Learning Resources and Inspiration](#Learning-Resources-and-Inspiration)
    - [Acknowledgements](#Acknowledgements)

- - -

## Introduction

This repository and associated deployed website comprise my submission for the Diploma in Web Development, Milestone Project 1. This project was developed according to the stated [project requirements](docs/requirements.md), and is described here  ...

- - -


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
- [General page design](docs/wireframes/general_design.png) - This is the foundation for developing all site wireframes, ensuring a consistent layout and design propagates throughout the site.
- [Home Page (index.html)](docs/wireframes/p1_index.png) - Landing page, making clear the purpose of site as a showcase for this yacht.
- [Photo Gallery (gallery.html)](docs/wireframes/p2_gallery.png) - For displaying a variety of photographs, highlighting differnt aspects of the yacht. (due to mix of landscape and portrait format images, these will be grouped into sets of 4 images, as illustrated in the wireframe)
- [Contact Page (contact.html)](docs/wireframes/p3_contact.png) - Facility for site visitors to find out more by contacting the crew/owner via an online form, or visiting in person by provision of a location map.
- [Filming Page (filming.html; additional site page, post-mvp)](docs/wireframes/p4_extra_filming.png) - Page to be added to the site after the minimum 3-pages have been created. This will provide an example of where the yacht has been hired for professional media use. 

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
- The photographs used throughout the site be taken, and owned, by myself and the yacht owner. 
- The text will be written by me, based on information provided by the yacht owner.
- Video of Wah Kong at sea will be taken, and owned by, myself.
- Movie trailer for 'On Chesil Beech' will be embedded from [YouTube](https://youtu.be/ZR6DWDfMDlM).
- The site icon of an Anchor was created on [Favicon](https://www.favicon.cc/?action=icon&file_id=996800), where it was both downloaded for project and shared online for others to use. 
- Location map for Weymouth Marina will be embedded from [Google Maps](https://www.google.co.uk/maps.


- - -

## Site Features
### Current Features
The website currently comprises four pages: [Home](https://mikiburgess.github.io/MP1-Wah-Kong/index.html), [Gallery](https://mikiburgess.github.io/MP1-Wah-Kong/gallery.html), [Filming](https://mikiburgess.github.io/MP1-Wah-Kong/filming.html) and [Contact](https://mikiburgess.github.io/MP1-Wah-Kong/contact.html) pages.


[Home Page (index.html)](https://mikiburgess.github.io/MP1-Wah-Kong/index.html):
- A brief history of yacht Wah Kong, a summary of her design, construction and specifications, and information about hire opportunities.
- Video of Wah Kong out at sea, sailing along the Jurassic Coast (autoplay disabled).

[Gallery Page (gallery.html)](https://mikiburgess.github.io/MP1-Wah-Kong/gallery.html):
- Selection of photographs of the yacht showing external construction above and below the waterline, internal cabin, photos of her at sea, and photos taken from on-board.
- Photographs are grouped into sets of 4 images, comprising either landscape or portrait photos. These sets ensure consistency in row sizes across all viewports. 

[Filming Page (filming.html)](https://mikiburgess.github.io/MP1-Wah-Kong/filming.html):
- Example of where the yacht has been hired for professional media use.
- Overview of the film 'On Chesil Beach', including video.
- Selection of photographs taken on filming location.

[Contact Page (contact.html)](https://mikiburgess.github.io/MP1-Wah-Kong/contact.html):
- Form for making contact with the yacht's owner and crew, using form data entry widgets which validate user input (all fields must be completed, email address must be in the form of an email address).
- Form submission only possible if the user confirms that they are a human. 
- On form submission, the entered data is currently presented back to the user. *In future development this will be replaced by backend functionality that will process submitted data*.
- A map shows the location of the yacht, in Weymouth Marina.

All pages also have the following features:
- Responsive navigation bar at the top of the page, allowing for users to navigate the site without using browser back/forward buttons. This navigation bar collapses to a menu toggler on smaller viewports to maintain site readability.
- Responsive hero image with page title is at the top of each page, directly beneath the navigation bar. Although each page has a different hero image, the placement, dimensions, and responsive behaviour is consistent across all pages.
- Viewport-width footer containing a copyright notice (placeholder/unofficial) and links to all relevant social media platforms. The standard, recognisable logos for each platform have been used to keep the footer as clean as possible. On larger viewports the footer is full width comprising the copyright notice aligned left and social media icons alighned right. On smaller viewports the social media icons are aligned centrally, under the copyright notice, to ensure footer content remains readable.

### Site Accessibility
Site accessibility was considered throughout the deisgn and build process:
- Considering site colors for clarity and contrast.
- Using semantic HTML to dinstinguish between site elements.
- Adding descriptions to the alt attribute to all images across the site.
- Using aria labels to describe elements where there is no/limited descriptive text, such as the contact form data entry boxes.
- Including screen reader support for site icons (footer) with no explicit text descriptions, and ensuring menu accessibilty by explicitly idenfifying the current page.


### Future Features
This site was designed and developed according to the Milestone Project 1 requirements. As such it can be improved with further development to enhance funtionality and usability for the identified users. This includes (but is not limited to) the following:

- Incorporate [modal images](https://www.w3schools.com/howto/howto_css_modals.asp) into the photo gallery, allowing full size viewing of each gallery photo. 
- Improve site performance and accessibility by providing multiple image options (including WebP and jpeg) for all site photographs.
- Add backend functionality to process submitted contact form data and respond accordingly (rather than using Code institute's form submission checker).
- Add a page of resources, including links to the [marina](https://www.boatfolk.co.uk/weymouth-marina-dorset), [yacht club](https://royal-dorset.com/), and [local boat yard](https://www.clarksboatworks.co.uk/).
- Improve consistency of Filming page (changing the text currently in 'card' format to match the text layout format used on the Contact page) and improving responsiveness of the YouTube video.
- Add link to top of page to the standard site footer, to improve site easy of use (especially for the Gallery page).
- Current current social media links (site footer) do not currently direct the user to specific pages for Wah Kong, as these don't yet exist. Instead these links direct the user to the primary platform ,anding page. In future a social media presence will be developed, and links then added to the site footer.
- Footer 'Copyright notice' to be updated as appropriate for the official (professional) deployment stage. 

If additional images are required,  royalty-free images will be obtained from [Pixabay](https://pixabay.com/). Those selected would be usable under their [Content Licence](https://pixabay.com/service/terms/) (Section 4) or licenced under the Creative [Commons Zero licence](https://pixabay.com/service/terms/) (Section 3).



- - -

##  Development Process
### Tools
- UI Wireframes were created using [Balsamiq](https://balsamiq.com/)
- Code was be developed locally using [Visual Studio Code](https://code.visualstudio.com/)
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/), as embedded within Google's Chrome browser, were used to support the development. In particular, the code inspector, [Lighthouse](https://developer.chrome.com/docs/lighthouse/), and the responsive design checker (for checking site responsiveness across all viewports)
- Versioning was managed locally using [Git](https://git-scm.com/). All code was then pushed to [GitHub](https://github.com/mikiburgess).
- Completed site was deployed using [GitHub Pages](https://pages.github.com/).

### Project Management
Project planning and management was done using the GitHub Projects tool (i.e. a digital Kanban board).

### Languages
Pages were created using HTML and CSS. Comments were added throughout for explanation (where appropriate) and clarifying code structure.

### Frameworks
This project employed the Boostrap v4.5 framework (the version covered in the course videos). Bootstrap support was obtained through the official [Bootstrap documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/), [W3Schools](https://www.w3schools.com/bootstrap/bootstrap_ver.asp), and through the Code Institute Slack Community.

- - -

## Testing
Results of site testing can be found in [testing.md](docs/testing/testing.md).

## Deployment and Local Development

### Deployment
[GitHub Pages](https://pages.github.com/) was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to GitHub.
2. Locate the project repository.
3. Click on the Settings link.
4. Scroll down to find the Pages link in the left hand side navigation bar.
5. Click on the Pages link and locate the Build and Deployment section.
6. Under the Source option, select *Deploy from a branch* from the drop-down box.
7. Under the Branch section, select *master* then */(root)* from the two drop-down boxes, then click Save. 

The site will now be deployed by GitHub Pages and available at the URL shown near the top of the page. Click on the Visit Site button to be taken there directly.

### Local Development

#### How to Fork this Project Repo
1. Log in (or sign up) to Github.
2. Navigate to the project repository (scroll to the top of this page, or visit [mikiburgess/MP1-Wah-Kong](https://github.com/mikiburgess/MP1-Wah-Kong)).
3. Click the Fork button at the top right of the page.

#### How to Clone this Project Repo
1. Log in (or sign up) to GitHub.
2. Navigate to the project repository (scroll to the top of this page, or visit [mikiburgess/MP1-Wah-Kong](https://github.com/mikiburgess/MP1-Wah-Kong)).
2. Click on the Code button, ans select the Local tab.
3. Select whether you would like to clone with HTTPS, SSH or GitHub CLI.
4. Copy the link shown by clicking the 'copy' button.
5. Open the  in your code editor and change the current working directory to the location you want to use for the cloned directory.
6. Type the command 'git clone' into the terminal and then paste the link you copied from GitHub. 
7. Press enter. You will now have a clone of the project repo.

## Future Development Practices
Reflecting on the lessons learned and skills developed during this project,  both the site and project could be improved in a number of ways. 
In future projects, including developing the Future Features listed above, I therefore entend to consider the following:

### Website Design and Development
- Stylesheet: Structure and build first draft of stylesheet after initial design stage, as opposed to building it concurrently with site content. This would improve consistency, reduce duplication, and increase opportunities for style reuse.
- Grid Layout Design: In addition to wireframes, a grid overlay design will also be completed to support the use of a grid layout framework (such as Bootstrap).
- Deployment: For assessment and portfolio development purposes this site is hosted on GitHub. In future this will be hosted externally with direct URL, based on the requirements of the yacht owner.
- Photographs: To improve performance of sites in future, all images will be processed using a tool to compress them appropriately for online download, such as [TinyPNG](https://tinypng.com/) and available in a variety of formats (inc. [WebP](https://web.dev/serve-images-webp/)) to improve performace and browser compatability.

### Version Control
Commit messages: Git commit mesages would be improved by writing them in a standard format - "<type>(<scope>): <subject>". This would be based on the conventions presented by Ishan Makadia on dev.to (https://dev.to/ishanmakadia/git-commit-message-convention-that-you-can-follow-1709) and Apurva Jain on medium.com (https://medium.com/swlh/writing-better-commit-messages-9b0b6ff60c67)
Commit frequency: Reflecting on the early days of the project with my mentor, we realised that my use of git could be improved by increasing the number of commits. By committing changes more often (after every feature addition, bug fix, etc), this will improve rep usability and help develop an improved professional development practice.  

### Project
- Version Control: Develop professional practice by committing changes to Git and pushing to GitHub repo more regularly during the development process, through the development of a clear version control procedure. 
- MD files: Rather than creating these post-development from the notes taken during the project, these will be designed during the project startup process and developed concurrently with primary project deliverables.
- Wireframes: Small and large wireframes were produced for this project. In future a minimum of three will be produced, for small (mobile), medium (tablet) and large (desktop) viewports.

### Third-Party Resources
- Bootstrap: Bootstrap v4 was used during this project due to it's use in the course. Moving to Bootstrap v5 would therefore be done in the future.
- Fontawesome: Fontawesome v5 was used during this project due to it's use in the course. Upgrading to v6 will be done in future projects.

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
- Hero image styling was inspired by, and adapted from, Code Institute's *Love Running* walkthrough project.
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
