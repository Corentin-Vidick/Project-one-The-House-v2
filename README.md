# The House

The house is a site intended to showcase how we run our house and how it evolves over time. We target younger new homeowners and give them an overview of what we go through and how we set up our space. We hope to be able to help other people see possibilities in their future or new property and the outcomes of certain decisions.

[Responsive Mockup](https://ui.dev/amiresponsive?url=https://corentin-vidick.github.io/Project-one-The-House-v2/index.html)
![Responsive mockup image](/documentation/resp-design.jpg)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __The title__
  
-	Repeated on every page, it doubles up as an internal link to come back to the main page from anywhere on the website.

- __The banner image__

-	Repeated on every page, it showcases some of our pets to make for a welcoming site.

- __Navigation Bar__

-	Repeated on every page, it consists of the main pages, Inside, Outside and Learn More, as well as our Contest page.
-	It allows users to navigate between pages without having to go through the main page.

![Title and banner](/documentation/header-nav.jpg)

- __Footer Bar__

-	Repeated on every page, consists of external links to social media pages: Facebook, Pinterest and Instagram, as well as the Contact link.

![Footer](/documentation/footer.jpg)


- __Main page__

-	Receives user on page load. Makes first contact with:
o	Welcome: gives an overview of the website and motivates user to read the articles as well as participate in feedback and development ideas.
o	Overview: gives a general overview of what the website is about.
o	Contest: focus drawing to contest page offering a BBQ, used to bring attention to what is to win and how to participate. Contains a direct link towards contest form to motivate and ease application.

![Main](/documentation/main.jpg)

- __Outside page__

-	Contains articles about the outside of the property, garden and adjacent land. Gives a description and explanation of the transformations that are being made, as well as what we grow and the results. Each article contains various paragraphs that can have images embedded. Currently contains three articles but design to adapt to any amount.

![Outside](/documentation/outside.jpg)

- __Inside page__

-	Contains articles about the inside of the property. Currently describes the layout, the transformations in the bathroom and the living room. Each article contains various paragraphs that can have images embedded. Currently contains three articles but design to adapt to any amount.

![Inside](/documentation/inside.jpg)

- __Learn more page__

-	Contains external links to particular points of interest. One container per article on the website. List of external links to learn more about particular subjects.

![Learn more](/documentation/learn-more.jpg)

- __Contest page__

-	Form page to participate in a contest to win a BBQ at The House. Requires information input from user: user details, answering three multiple choice questions and choice of preference.

![Contest](/documentation/contest.jpg)

- __Contact page__

-	Form to send a message to website’s owner (me). Requires user information and message.

![Contact](/documentation/contact.jpg)



### Features Left to Implement

  -  Add links within articles to “Learn more” page, auto view focus on correct link and hovering.
  -  Add “Animals” page, covering Pets, Reptiles and Homestead animals.
  -  Actually use information sent through "Contact" and "Contest" pages



## Testing

__Features__

-	Internal links: all pages accessible from anywhere on the website, each page contains internal links in h1, navigation bar and right-hand-side of footer.
-	External links: all external links – social media and “Learn more” – open in new tab.
![External links](/documentation/ext-links.jpg)
-	Accessibility: all images have alternate text in case of not loading or impaired user. All links have clear description of functionality.
![Accessibility](/documentation/no-img.jpg)
-	Responsiveness: Script size and article size/positioning adapt to screen size. Banner image shrinks and expands conserving its ratio. Navigation bar and footer re-organise to suit screen size.
![Responsiveness](/documentation/responsiveness.jpg)
- All links change colour when hovered over and current page made clear by style change.
![Links](/documentation/links.jpg)
- Browser compatibility: website responds correctly on different browsers
![Browser Chrome](/documentation/browser-chrome.jpg)
![Browser Edge](/documentation/browser-edge.jpg)
-	Use of floats and flexbox to style pages and improve adptability.
```css
.flex-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-content: space-around;
}

.flex-item {
    text-align: center;
    margin: 20px;
    width: 45%;
    background-color: #70d145;
}
```

```css
.nav-left a {
    float: left;
    padding: 10px 30px;
}

.nav-right {
    float: right;
    padding: 10px 30px;
}
```

__Testing__

-	Responsiveness and links tested throughout build. Page loaded and trialled on different devices to test adaptability.
![Smartphone](/documentation/smartphone.jpg) Links tested from various devices to test connectivity.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official 
    - ![W3C validator Main](/documentation/html-main.jpg)
    - ![W3C validator Outside](/documentation/html-outside.jpg)
    - ![W3C validator Inside](/documentation/html-inside.jpg)
    - ![W3C validator Learn more](/documentation/html-learnmore.jpg)
    - ![W3C validator Contest](/documentation/html-contest.jpg)
    - ![W3C validator Contact](/documentation/html-contact.jpg)
- CSS
  - No errors were found when passing through the official ![(Jigsaw) validator](/documentation/css-main.jpg)
- Lighthouse
  - All pages pass Lighthouse tests > 90%
    - ![Lighthouse Main](/documentation/lighthouse-main.jpg)
    - ![Lighthouse Outside](/documentation/lighthouse-outside.jpg)
    - ![Lighthouse Inside](/documentation/lighthouse-inside.jpg)
    - ![Lighthouse Learn more](/documentation/lighthouse-learnmore.jpg)
    - ![Lighthouse Contest](/documentation/lighthouse-contest.jpg)
    - ![Lighthouse Contact](/documentation/lighthouse-contact.jpg)

### Unfixed Bugs
  - There are no unfixed bugs that I am aware of at this time.

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the [GitHub repository](https://github.com/Corentin-Vidick/Project-one-The-House-v2), navigate to the Settings tab 
  - From the source section drop-down menu, select the **Main** Branch, then click "Save".
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://corentin-vidick.github.io/Project-one-The-House-v2)

### Local Deployment

In order to make a local copy of this project, you can clone it. In your IDE Terminal, type the following command to clone my repository:

- `git clone https://github.com/Corentin-Vidick/Project-one-The-House-v2.git`

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Corentin-Vidick/Project-one-The-House-v2)


## Credits 

- The icons in the navigation bar were taken from [Font Awesome](https://fontawesome.com/)
- The font on the website was taken from [Google Fonts](https://fonts.google.com/)
- Clearfix solution taken from [W3 Schools](https://www.w3schools.com/css/css_float_clear.asp)
- Colors chosen from [Adobe Color](https://color.adobe.com/create/color-wheel)
- All images and text are property of the developer, Corentin Vidick
