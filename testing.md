# MILESTONE 1 PROJECT NAME - TESTING

👩🏻‍💻 View an example of this section [here](https://github.com/kera-cudmore/Found-In-Translation/blob/main/TESTING.md#found-in-translation----testing-documentation)

Add an image of the finished site here. I like to use [amiresponsive](https://ui.dev/amiresponsive) to get an image of my site on all device sizes, and amiresponsive allows you to click links on the page and scroll, so each device can show a different element of your site.

Add a link to the live site here, for Milestone 1 this will be the GitHub Pages Link from when you deployed the site.

If you want to add optional shields.io badges to your TESTING file, I like to add them to this section (Shields.io have some badges for W3C validation which makes it easy to see at a glance whether the project has passed validation).

---

## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
  * [WAVE](#wave)

* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

* [BUGS](#bugs)
  * [Known Bugs](#known-bugs)
  * [Solved Bugs](#solved-bugs)

---

## AUTOMATED TESTING

###  W3C Validator

W3C was used to validate the HTML on all pages of the website. It was also used to validate the CSS. I have checked the HTML via direct input and also by inspecting the page source and running this through the validator.

Index - No errors or warnings.

Trails -No errors or warnings.

Newsletter - No errors or warnings.

Landingpage - No errors or warnings.

Error 404 - No errors or warnings.

CSS - No errors or warnings.

#### **URI Input**

If you validate with your sites URL, you can run the validation and then copy the link from the address bar and insert the link here as your proof of validation.

Index - https://validator.w3.org/nu/?doc=https%3A%2F%2Fbluiss.github.io%2Fwinchester-bike-club%2F

Trails - https://validator.w3.org/nu/?doc=https%3A%2F%2Fbluiss.github.io%2Fwinchester-bike-club%2Ftrails.html

Newsletter - https://bluiss.github.io/winchester-bike-club/newsletter.html

Landingpage - https://validator.w3.org/nu/?doc=https%3A%2F%2Fbluiss.github.io%2Fwinchester-bike-club%2Flandingpage.html%3Ffirst-name%3DHarry%26last-name%3DBritton%26email-address%3Dharrydbritton%2540gmail.com

Error 404 - https://validator.w3.org/nu/?doc=https%3A%2F%2Fbluiss.github.io%2Fwinchester-bike-club%2F404

#### **CSS Validation**

CSS Validation can only be done by copying and pasting the CSS file contents into the direct input. Make sure that the checkbox for CSS is selected.

![!\[W3C CSS Validation\](documentation/milestone1-testing/w3c-css-validation.png)](assets/docs/wireframes/css-validator.png)

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to allow me to test the performance, accessibility, best practices and SEO of the website.

### Index 

![Homepage Lighthouse Report](assets/docs/lighthouse/homepage.png) 

### Trails 

![Trails Lighthouse Report](assets/docs/lighthouse/trails.png)

### Newsletter

![newsletter Lighthouse Report](assets/docs/lighthouse/newsletter.png)

### Landingpage

![Landingpage Lighthouse Report](assets/docs/lighthouse/landingpage.png)

### Suggestions

Overall perfomrance was not great, I had tried to convert the format and compress the images but this had minimal impact 

## MANUAL TESTING

### Testing User Stories

| Goals                                                                          | How are they achieved?                                                                    |
| ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------- |
| Client Goals                                                                   |                                                                                           |
| \- To be able to view all pages on a variety of devices                        | A description of what the site is is included on the home page and across all devices     |
| \- To make it easy for users to sign up to the newsletter                      | The description on the home page encourages new users to register for a newsletter        |
| \- Make it clear for users to view new photos and explanations of local trails | The trails section displays both local trails with images                                 |
| First Time Visitor Goals                                                       |                                                                                           |
| \- For new users to understand the different types of trails and styles        | Styles and trails are clearly labelled                                                    |
| \- To be able to navigate the website easily across all devices                | On mobile devices the nav bar becomes a hambuger menu                                     |
| \- To be able to find all social links easily                                  | On all pages they're labelled at the bottom                                               |
| Returning Visitor Goals                                                        |                                                                                           |
| \-  Find any new information on trails or the gallery                          | The location never changes so when it would updated returning users would see new content |

### Full Testing

Full testing was performed on the following devices:

* Desktop 
  * 27 Inch 1440p Monitor 
  * 24 Inch 1080p Monitor 
* Laptop:
  * Macbook Pro 2021 13 inch screen
* Mobile Devices:
  * iPhone 14 pro.
  * iPhone 12 pro.

Each device tested the site using the following browsers:

* Google Chrome
* Safari

| Feature                   | Expected Outcome                                                 | Testing Performed  | Result                       | Pass/Fail |
| ------------------------- | ---------------------------------------------------------------- | ------------------ | ---------------------------- | --------- |
| Navbar                    |                                                                  |                    |                              |           |
| Home Page Link            | When clicked the user will be redirected to the home page.       | Clicked link       | Redirected to the home page. | Pass      |
| Trails Link               | When clicked the user will be redirected to the trails page.     | Clicked link       | Redirected to the home page. | Pass      |
| Newsletter Link           | When clicked the user will be redirected to the newsletter page. | Clicked link       | Redirected to the home page. | Pass      |
| Footer                    |                                                                  |                    |                              |           |
| Social Icons              | When clicked the user will be redirected to the associated links | Clicked link       | Redirected to the home page. | Pass      |
| Home Page                 |                                                                  |                    |                              |           |
| Discplines titles         | Overlay shows when hovered                                       | Hoverd over        | Shows title                  | Pass      |
| Trails Page               |                                                                  |                    |                              |           |
| Trails content            | Overlay shows when hovered                                       | Hoverd over        | Shows trail information      | Pass      |
| Gallery                   | Resposnive and interactive zoom feature                          | Hoverd over        | Zooms in on images           | Pass      |
| News Letter Page          |                                                                  |                    |                              |           |
| Form                      | Form directs to proper landing page                              | Entered plain text | Redirected to Landing page   | Pass      |
| First name input          | Input required to submit form                                    | Entered plain text | Redirected to Landing page   | Pass      |
| Last name input           | Input required to submit form                                    | Entered plain text | Redirected to Landing page   | Pass      |
| Email Input               | Input required to submit form                                    | Entered plain text | Redirected to Landing page   | Pass      |
| Homepage redirection link | Redirected to homepage                                           | Clicked link       | Redirected to hoempage       | Pass      |
| Error 404                 |                                                                  |                    |                              |           |
| Homepage redirection link | Redirected to homepage                                           | Clicked link       | Redirected to hoempage       | Pass      |

## BUGS

### Solved Bugs

| No | Bug                                                                                                     | How I solved the Issue                                                            |
| -- | ------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| 1  | Text within the trails images was not responsive to change in width and would overflow out of container | Separate media queries for different screen sizes, font size ranging from 16-12px |
| 2  | The nav element would be behind an image when viewing the trails page one mobiles                       | Positioned top nav class with:                                                    |
| 3  | 404 page not displaying CSS styling                                                                     | Htaccess page was not formatted correctly                                         |
| 4  | Lighthouse performance was significantly lower than acceptable                                          | Had to compress and convert images into                                           |
| 5  | Too much white space around index content and images                                                    | Removed grid row attribute and increased padding on smaller screens               |

### Known Bugs

| No | Bug                                                                                                     | 
|    | ------------------------------------------------------------------------------------------------------- | 
| 1  | Performance is still lower than ideal due to images not compressing properly                            | 