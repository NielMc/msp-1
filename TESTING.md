# Testing

Return back to the [README.md](README.md)

I have used various tools to Test Funcionality, Validity and responsiveness.
I have been sure to check all layouts, colours, text, forms, links, buttons are functioning on all devices and screen sizes that I have tested.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate Each of my HTML files.

[Index Test Result](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjaycode88.github.io%2Fmsp-1%2F)

![screenshot](documentation/indexhtmltest.webp)

[Gallery Test Result](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjaycode88.github.io%2Fmsp-1%2Fgallery.html)

![screenshot](documentation/galleryhtmltest.webp)

[FAQ Test Result](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjaycode88.github.io%2Fmsp-1%2Ffaq.html)

![screenshot](documentation/faqhtmltest.webp)

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

There are errors shown, But these are all due to third party applications. All CSS code entered by myself is validated.

[CSS Test Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjaycode88.github.io%2Fmsp-1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#errors)

![screenshot](documentation/csstest.webp)

## Browser Capability

I have tested my deployed project on multiple browsers to check for compatibility issues.

| Browser | Page/Form | Expected Look | Expected Behaviour |
|---------|-----------|---------------|--------------------|
|  Chrome |   Index   |        Y      |          Y         |
|         |  Gallery  |        Y      |          Y         |
|         |    FAQ    |        Y      |          Y         |
|         |   Modal   |        Y      |          Y         |
| Firefox |   Index   |        Y      |          Y         |
|         |  Gallery  |        Y      |          Y         |
|         |    FAQ    |        Y      |          Y         |
|         |   Modal   |        Y      |          Y         |
|  Edge   |   Index   |        Y      |          Y         |
|         |  Gallery  |        Y      |          Y         |
|         |    FAQ    |        Y      |          Y         |
|         |   Modal   |        Y      |          Y         |
|  Opera  |   Index   |        Y      |          Y         |
|         |  Gallery  |        Y      |          Y         |
|         |    FAQ    |        Y      |          Y         |
|         |   Modal   |        Y      |          Y         |

![screenshot](documentation/indexbrowsertest.webp)

![screenshot](documentation/gallerybrowsertest.webp)

![screenshot](documentation/faqbrowsertest.webp)

![screenshot](documentation/modalbrowsertest.webp)

## Responsiveness

I've tested my deployed project on multiple devices to check for responsiveness issues. 

| Device    | Page/Form | Expected Look |
|-----------|-----------|---------------|
|Desktop 22"| Index     | Y             |
|           | Gallery   | Y             |
|           | FAQ       | Y             |
|           | Modal     | Y             |
|Laptop 16" | Index     | Y             |
|           | Gallery   | Y             |
|           | FAQ       | Y             |
|           | Modal     | Y             |
| Iphone 13 | Index     | Y             |
|           | Gallery   | Y             |
|           | FAQ       | Y             |
|           | Modal     | Y             |
|Galaxy S20 | Index     | Y             |
|           | Gallery   | Y             |
|           | FAQ       | Y             |
|           | Modal     | Y             |
|Tablet     |Index     | Y             |
|           | Gallery   | Y             |
|           | FAQ       | Y             |
|           | Modal     | Y             |

### Desktop

![screenshot](documentation/desktopindex.webp)

![screenshot](documentation/desktopindex2.webp)

### Tablet

![screenshot](documentation/indextablet.webp)

![screenshot](documentation/gallerytablet.webp)

![screenshot](documentation/faqtablet.webp)

![screenshot](documentation/tabletmodal.webp)

### Mobile

![screenshot](documentation/indexmobile.webp)

![screenshot](documentation/gallerymobile.webp)

![screenshot](documentation/faqmobile.webp)

![screenshot](documentation/modalmobile.webp)

Responsiveness was tested using [Google Dev Tools](https://developer.chrome.com/docs/devtools/) As well as my personal devices.

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. 

### Index

![screenshot](documentation/lightdesktopindex.webp)

### Gallery

![screenshot](documentation/lightdesktopgallery.webp)

### FAQ  

![screenshot](documentation/lightdesktopfaq.webp)

## User Story Testing

| User Story                                                | Screenshot                        | Notes |
|-----------------------------------------------------------|-----------------------------------|-------|
|As a new site user, I would like to get information and advice, so that I can Decide wether this service is right for me. |![screenshot](documentation/whatican.webp)|Website displays plenty of info regarding services available|
|As a new site user, I would like to see example work portfolio, so that I can see the qaulity of previous jobs taken.| ![screenshot](documentation/gallerytablet.webp) | Gallery hosts images of previous work.|
|As a new site user, I would like to understand the process of obtaining dreadlocks and the maintainance they require, so that I can decide wether dreadlocks are for me.|![screenshot](documentation/faqtablet.webp)| The site conatains lots of information regarding dreadlocks the FAQ being the hub of informattion including a video.|
|As a new site user, I would like to see the simplicity in making an appointment, so that I can go ahead and request services.|![screenshot](documentation/tabletmodal.webp)|There are multiple contact buttons around the site that open an easy to fill form to submit. there is also contact information and social media links in the footer bar.|
|As a new site user, I would like to be able to locate the relevant content with ease , so that I can move through the site freely finding the information I need.|![screenshot](documentation/navbarlarge.png) | Easy to use nav bar for navigation.|
|As a returning site user, I would like to be able to find after appointment care advice, So that I can keep hair healthy and maintained until next appointment.|![screenshot](documentation/faqtablet.webp) | FAQ section as well as the option to make contact.|
|As a returning user to the site, I would like to make contact with an after care querie or book a maintainance appointment.| ![screenshot](documentation/tabletmodal.webp)|Pop up modal with plenty of links around site to action.|
|As a site administrator, I should be able to provide the basic information needed, so that I can take less time dealing with general queries.|![screenshot](documentation/faqtablet.webp)|FAQ Hub of information other pages also provide useful relevant information|
|As a site administrator, I should be able to collect customer data to use for future marketing.|![screenshot](documentation/modalbrowsertest.webp)| Form will collect information once back end built.|
|As a site administrator, I should be able to showcase my work.|![screenshot](documentation/gallerybrowsertest.webp)|Gallery is a page dedicated to photos of previous work.|
|As a site administrator, I should be able to make my services known to potential customers.|![screenshot](documentation/homepage.webp)| The index page highlights the services available as well as the site hosting a lot of information. The site's description in the <head> section makes the organisation's work clear for search engines.|

## Bugs

### Known Bugs

- There is a blue highlight affecting the arrow and around the question box section when clicked. This is due to using the [Bootstrap Accordian](https://getbootstrap.com/docs/5.0/components/accordion/). I have not been unable to remove it with doing a fair amount of internet research, I checked within the slack community as well as chatGPT. This does not affect functionality for the user but does not fit the colour theme.
