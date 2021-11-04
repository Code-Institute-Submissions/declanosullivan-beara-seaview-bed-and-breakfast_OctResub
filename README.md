![Preview of site responsiveness](assets/documentation/wireframes/responsivepreview.png)

# Beara Seaview Bed & Breakfast

## About Project

The core purpose of this project is to create a website that promotes the featurea and unique offerings of the Beara Searview Bed and Breakfast. The building is currently underconstruction so I've used stock images until real images of the completed renovations are available. 

## UX

### User Stories
                    
Implemented  | User Story
------------- | -------------
Yes  | I need to read general description of B&B, 	so that I can compare to others in the area
Yes  | I want access to contact details, 	so that I can contact b&b with additional requestions
Yes  | I want to see pictures inside and outside B&B, 	so that I can decide I like the layout and decor
Yes  | I want quick access to rates,	so that I know quickly if the B&B fits my budget
Yes  | I want clear driving instructions, 	so that I can get from airport to B&B easily
Yes  | I want to read reviews from other visitors, 	so that I can feel a sense of trust 
Yes  | I want access to B&B social media profiles, 	so that I can see interactions from visitors.

### Design

I would have liked to use the Materialize framework as it's really impressive but my skill level is not yet there. It's something I'm looking forward to working towards.

### Color Scheme

I used the tool [material.io](https://material.io/resources/color/#!/?view.left=1&view.right=1&primary.color=D1C4E9&secondary.color=BBDEFB&secondary.text.color=000000&primary.text.color=0a0a0a) to create a primary and secondary color palette.

![Screenshot showing color pallete](assets/documentation/wireframes/colorpalette.png)

### Icons

I used [Font Awesome](https://fontawesome.com/) for the website's social media icons. Font Awesome has an incredible collection and make it straight forward to integrate their icons into a project which can then be customised to fit the design and colour scheme. I used these three icons:

![Screenshot showing social media icons](assets/documentation/wireframes/socialmediaicons.png)

### Typography

I used [Google Fonts](https://fonts.google.com/share?selection.family=Oxygen|Ubuntu). Google Fonts website is great to choosing fonts. If you pick one, it will recommend others that pair well with your first font. I've choose Oxygeny and Ubuntu because they are clean and easy to read.

![Screenshot showing choice of fonts](assets/documentation/wireframes/googlefonts.png)

### Wireframes

I used Balsamiq to create wireframes. Wireframing helped me get from the idea stage to coding. This in between step helped me breakdown the website into features. Below are my wireframes.

![Wireframe showing about section](assets/documentation/wireframes/wireframe1.png)

![Wireframe showing room image gallery section](assets/documentation/wireframes/wireframe2.png)

![Wireframe showing rates and directions section](assets/documentation/wireframes/wireframe3.png)

![Wireframe showing reviews section](assets/documentation/wireframes/wireframe4.png)

## Features

### Successfully Implemented Features

---

#### **Navigation Bar**

- This makes it easy for the visitor to access various sections of the sight. 

> ![Screenshot of navigation bar](assets/documentation/userstorytesting/navigationbar.png)

---

#### **Smooth Scroll Effect**

- This code enables smooth scrolling instead of jumping to a section. It's a nicer experience.

```html 
html {
  scroll-behavior: smooth;  
}
```

---

#### **Clickable Map (which opens in Google Maps)**

- The image is clickable and will open in Google maps to give full directions. 

> ![Screenshot of google map journey](assets/documentation/userstorytesting/mapbeforeclick.png)

> ![Screenshot of journey opening on google maps site](assets/documentation/userstorytesting/googlemaps.png)

---


* Image gallary

>I used CSS grid to show a selection of rooms images

![Screenshot of image gallery feature](assets/documentation/userstorytesting/imagegallery.png)


### Features Left to Implement

* Calendar - showing current availabiltiy

## Libraries & Technologies Utilised

* [HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML5) - used to define the content and structure of website.
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - used to define the appearance and presentation of the website.
* [Git](https://www.atlassian.com/git) - used for branching, merging, and rewriting repository history.
* [GitHub](https://github.com/) - used a hosting service for Git repositories.
* [Gitpod](https://gitpod.io/) - used as a workspace for Git repositories.
* [CSSgrid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - used to create a highly responsive grid that's structure is easily manipulated.
* [Google Fonts](https://fonts.google.com/share?selection.family=Oxygen%7CUbuntu) - Used to select and embed fonts in respository.
* [Material.io](https://material.io/resources/color/#!/?view.left=1&view.right=1&primary.color=D1C4E9&secondary.color=BBDEFB&secondary.text.color=000000&primary.text.color=0a0a0a) - Used to select and create primary and secondary colour paletete.
* [Font Awesome](https://fontawesome.com/) - Used to select and import icons into project.

## Testing

### Validators

* [HTML - W3C HTML Validator](https://validator.w3.org/nu/?doc=https://declanosullivan.github.io/beara-seaview-bed-and-breakfast)

> Passed with no issues

![Screenshot of passing HTML validator testing](assets/documentation/testing/htmlvalidation.png)

* [CSS - W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdeclanosullivan.github.io%2Fbeara-seaview-bed-and-breakfast&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

> Passed with no issues

![Screenshot of passing CSS validator testing](assets/documentation/testing/cssvalidation.png)

* [Google Lighthouse](https://developers.google.com/web/tools/lighthouse)

> Desktop (90-100 in all four categories): 

![Screenshot of lighthouse desktop report](assets/documentation/testing/lighthousedesktop.png)

> Mobile (90-100 in all four categories):

![Screenshot of lighthouse mobile report](assets/documentation/testing/lighthousemobile.png)

### Browser Compatibility

I've tested the site in the following browsers on desktop and mobile:

* Desktop - Chrome 95.0.4638.54

![Screenshot of site on Chrome desktop browswer](assets/documentation/browsertesting/chromedesktop.png)

* Mobile - Chrome 95.0.4638.50

![Screenshot of site on Chrome mobile browswer](assets/documentation/browsertesting/chromemobile.png)

* Desktop - Brave 1.31.87

![Screenshot of site on Brave desktop browswer](assets/documentation/browsertesting/bravedesktop.png)

* Mobile - Brave 1.32

![Screenshot of site on Brave mobile browswer](assets/documentation/browsertesting/bravemobile.png)

* Desktop - Edge 95.0.1020.30

![Screenshot of site on Edge desktop browswer](assets/documentation/browsertesting/edgedesktop.png)

* Mobile - Safari 15.0

![Screenshot of site on Safari mobile browswer](assets/documentation/browsertesting/safarimobile.png)

### Responsiveness

Insert screenshots views on desktop, tablet and mobile.

* Desktop - Chrome 95.0.4638.54

![Screenshot of site on Chrome desktop browswer](assets/documentation/browsertesting/chromedesktop.png)

* Tablet - Chrome 95.0.4638.54 (using inspect mode on desktop)

![Screenshot of site on Chrome desktop browswer](assets/documentation/browsertesting/chrometablet.png)

* Mobile - Chrome 95.0.4638.50

![Screenshot of site on Chrome mobile browswer](assets/documentation/browsertesting/chromemobile.png)




### User Story Testing

 User Story
------------- 
* I need to read general description of B&B, so that I can compare to others in the area.
* I want access to contact details, so that I can contact b&b with additional requestions.
* I want to see pictures inside and outside B&B, so that I can decide I like the layout and decor.
* I want quick access to rates,	so that I know quickly if the B&B fits my budget.
* I want clear driving instructions, so that I can get from airport to B&B easily.
* I want to read reviews from other visitors, so that I can feel a sense of trust.
* I want access to B&B social media profiles, so that I can see interactions from visitors.

### Known Bugs

No known bugs that I'm aware of.

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:
* In the GitHub repository, navigate to the Settings tab.
* From the source section drop-down menu, select the Main branch.
* Once the Main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

### Local Deployment

In order to make a local copy of this repo, you can type the following command in your IDE terminal:

- `git clone https://github.com/declanosullivan/beara-seaview-bed-and-breakfast.git`

Additionally if you're using Gitpod, you can click below:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://gitpod.io/#https://github.com/declanosullivan/beara-seaview-bed-and-breakfast)

## Credits and Learning Experience

### Content

Inspired by local bed and breakfast websites and the Love Runnng project.

### Media

* Pexels - All images are stock images from this site

### Acknowledgements

I'm really grateful for the support I've received from the CI course, CI community and my July-5p cohort. I'd like in particular to thank my mentor Tim as well as the tutors who've helped me through LMS challenages - Igor, Scott, Jo and John. 
