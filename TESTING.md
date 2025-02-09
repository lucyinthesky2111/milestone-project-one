# Testing

The Clutch Kings College Basic Car Maintenance Course website has been tested using the following methods:
- [Code Validation](#code-validation)
    - [W3C HTML Validator](#w3c-html-validator) 
        - [Homepage](#homepage)
        - [Course Information Page](course-information-page)
        - [About Page](#about-page)
        - [Meet Instructors Page](#meet-instructors-page)
        - [Apply and Contact Page](#apply-and-contact-page)
        - [Thank You Page](#thank-you-page)
        - [404 Error Page](#404-error-page)
    - [W3C CSS Validator](#w3c-css-validator)
- [Lighthouse](#lighthouse)
- [Responsiveness](#responsiveness)
- [WAVE Web Accessibility Evaluation Tools Checker](#wave-web-accessibility-evaluation-tools-checker)
- [Browser Compatibility](#browser-compatibility)
- [Testing User Stories](#testing-user-stories)
- [Peer Review](#peer-review)
- [Bugs](#bugs)
    - [Resolved](#resolved)
    - [Unresolved](#unresolved)


    Back to [README.md](/README.md#testing-and-validation)

# Code Validation
## W3C HTML Validator
The Clutch Kings College Basic Car Maintenance Course webpage returned no errors when tested using the W3C HTML Validator tool. There was one warning given as shown in the screenshots, about sections not having a heading. This was not changed as the sections do not need headings and adding these is only a recommendation not a requirement.
### Homepage
<h2 align="center"><img src="assets/readme-images/index-html-validation.png"></h2>

### Course Infomation Page
<h2 align="center"><img src="assets/readme-images/course-info-html-validation.png"></h2>

### About Page
<h2 align="center"><img src="assets/readme-images/about-html-validation.png"></h2>

### Our Instructors Page
<h2 align="center"><img src="assets/readme-images/our-instructors-html-validation.png"></h2>

### Apply and Contact Page
<h2 align="center"><img src="assets/readme-images/apply-html-validation.png"></h2>

### Thank You Page
<h2 align="center"><img src="assets/readme-images/thank-you-html-validation.png"></h2>

### 404 Error Page
<h2 align="center"><img src="assets/readme-images/404-error-html-validation.png"></h2>

## W3C CSS Validator
The Clutch Kings College Basic Car Maintenance Course webpage returned no errors or warnings when tested using the W3C CSS Validator tool.
### CSS Stylesheet
<h2 align="center"><img src="assets/readme-images/css-validation.png"></h2>

# Lighthouse
* I ran Lighthouse reports in Google Devtools to test for :- Performance, Accessibility, Best Practices and SEO.
* All pages performed reasonably well on desktop (with some performing very well): 
## Homepage (Desktop)
<h2 align="center"><img src="assets/readme-images/lighthouse-index-desktop.png"></h2>

## Course Information Page (Desktop)
<h2 align="center"><img src="assets/readme-images/lighthouse-course-info-desktop.png"></h2>

## About Page (Desktop)
<h2 align="center"><img src="assets/readme-images/lighthouse-about-desktop.png"></h2>

## Our Instructors Page (Desktop)
<h2 align="center"><img src="assets/readme-images/lighthouse-our-instructors-desktop.png"></h2>

## Apply and Contact Page (Desktop)
<h2 align="center"><img src="assets/readme-images/lighthouse-apply-contact-desktop.png"></h2>

## Thank You Page (Desktop) 
<h2 align="center"><img src="assets/readme-images/lighthouse-thank-you-desktop.png"></h2>

## 404 Error Page (Desktop) 
<h2 align="center"><img src="assets/readme-images/lighthouse-404-desktop.png"></h2>

* On mobile, results were not so good on many pages. Details can be found in [Unresolved Bugs](#unresolved).
## Homepage (Mobile)
<h2 align="center"><img src="assets/readme-images/lighthouse-index-mobile.png"></h2>

## Course Information Page (Mobile)
<h2 align="center"><img src="assets/readme-images/lighthouse-course-info-mobile.png"></h2>

## About Page (Mobile)
<h2 align="center"><img src="assets/readme-images/lighthouse-about-mobile.png"></h2>

## Our Instructors Page (Mobile)
<h2 align="center"><img src="assets/readme-images/lighthouse-our-instructors-mobile.png"></h2>

## Apply and Contact Page (Mobile)
<h2 align="center"><img src="assets/readme-images/lighthouse-apply-contact-mobile.png"></h2>

## Thank You Page (Mobile)
<h2 align="center"><img src="assets/readme-images/lighthouse-thank-you-mobile.png"></h2>

## 404 Error Page (Mobile)
<h2 align="center"><img src="assets/readme-images/lighthouse-404-mobile.png"></h2>

# Responsiveness
A combination of Bootstrap and CSS media queries were used to make this website responsive. When writing media queries, I used the same breakpoints as Bootstrap. Details of these breakpoints can be found [here](https://getbootstrap.com/docs/5.0/layout/breakpoints/). Responsivity at the Bootstrap breakpoints and on different device screen sizes was tested using Google Chrome Devtools. Device screen sizes tested include:
* iPhone SE
* iPhone XR
* iPhone 12 Pro
* iPhone 14 Pro Max
* Pixel 7
* Samsung Galaxy S8+
* Samsung Galaxy S20 Ultra
* iPad Mini
* iPad Air
* iPad Pro
* Surface Pro 7
* Surface Duo
* Galaxy Z Fold 5
* Asus Zenbook Fold
* Samsung Galaxy A51/71
* Nest Hub
* Nest Hub Max
* Galaxy Fold

* I personally tested the website on a Samsung Galaxy S22 (See [Resolved Bugs](#resolved)) for details and an Asus Tuf Gaming A15.

# WAVE Web Accessibility Evaluation Tools Checker
When tested using the WAVE Web Accessibility Evaluation Tools Checker, the Clutch Kings College Basic Car Maintenance Course webpage returned 2 contrast errors on the About page. Unfortunately, the checker does not show where the contrast errors are located, they should be shown on screen in red but are not (see relevant screenshots below). Due to time constraints, I am not able to investigate this issue further. No errors or contrast errors were returned on any other pages of the site.
## Homepage 
<h2 align="center"><img src="assets/readme-images/wave-home.png"></h2>

## Course Information Page 
<h2 align="center"><img src="assets/readme-images/wave-course-info.png"></h2>

## About Page 
<h2 align="center"><img src="assets/readme-images/wave-about-contrast-error.png"></h2>
<h2 align="center"><img src="assets/readme-images/wave-about-contrast error2.png"></h2>

## Our Instructors Page 
<h2 align="center"><img src="assets/readme-images/wave-instructors.png"></h2>

## Apply and Contact Page
<h2 align="center"><img src="assets/readme-images/wave-apply.png"></h2>

## Thank You Page 
<h2 align="center"><img src="assets/readme-images/wave-thank-you.png"></h2>

## 404 Error Page  
<h2 align="center"><img src="assets/readme-images/wave-404.png"></h2>

# Browser Compatibility
* The site was tested and performed as expected on Google Chrome and Microsoft Edge.
* The site was also tested on Samsung Internet, on which there were some issues (see [Resolved Bugs](#resolved) for details).

# Testing User Stories
* All tasks are completed and all acceptance criteria are met for User Stories 1-7. Due to time constraints, no tasks have been attempted for User Stories 8-10.

# Peer Review
* Whilst still in progress, this project was submitted for peer review by Code Institute students and alumni on Slack. This resulted in me receiving help with a spacing issue on the footer and with the responsiveness of the site (see [README.md Credits section](/README.md#credits) for details). I would have liked to have re-submitted the project for further feedback once it was finished but there was not enough time to do this.
* The project was also reviewed by my mentor Mitko Bachvarov who suggested that I improve the site by styling the submit button on the application form on the Apply and Contact page to match the buttons on the rest of the site. It was also suggested that I improve the layout of the site by adding extra margins and padding where required. These changes were implemented. The navbar originally contained 2 links that went to the same page page (1 link labelled Apply and 1 labelled Contact both going to the Apply and Contact page). On my mentor's advice, the text on the links was amalgamated and one link was removed.
* I asked a number of friends and family members to test the site for typos and to check all links worked correctly and that the external links to social media sites in the footer all opened in new tabs. No errors were reported.


# Bugs 
## Resolved
* The Apply and Contact Page initially returned an error due to the inline styles applied to the iFrame element. This was resolved by removing the inline styles and adding the styles directly to the stylesheet instead.
<h2 align="center"><img src="assets/readme-images/error-apply-html-validation.png"></h2>

* On first run of the the W3C HTML Validitor, the error shown below was flagged on several pages of the site. This was resolved by removing the button element and styling the a element as a button. All pages of the site subsequently passed validation.
<h2 align="center"><img src="assets/readme-images/button-error.png"></h2>

* I noticed that on mobile view on my personal device (Samsung Galaxy S22), the introductory text under the college and course name on the Homepage was spilling out of its containing div into the one beneath it. This issue was only occurring on this particular device, it did not happen in on mobile screen size views on Devtools. I inspected the page on Devtools and was able to ascertain that the issue was stemming from the manual height I had set on the containing div (#course-intro). Changing this value to ‘fit-content’ resolved this issue. 

* I noticed that on mobile and tablet screens, there was a gap between the sections for Steve and Becky on the ‘Our Instructors’ page that was not there in large screen view. Upon inspecting the page in Dev tools, I saw that this issue was rectified by adding a margin-top value of –16px to the div with the id of Becky Ludlington. 


## Unresolved
* As discussed in the WAVE Web Accessibility Evaluation Tools Checker, the 2 contrast errors flagged on the About page remain unresolved due to my being unable to locate the origins of the errors. 

* Lower Lighthouse performance scores on mobile. To improve performance, Lighthouse recommends saving images in next-gen formats and eliminating render-blocking resources. This was not implemented due to time constraints. 

* Lower Lighthouse best practice score on Apply and Contact page on both desktop and mobile. To improve the best practice score, Lighthouse recommends not using third-party cookies. This is an issue I cannot resolve at the moment, third-party cookies is outside of my knowledge range at this stage in my learning journey and due to time pressures, I am unable to research this.
