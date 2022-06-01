<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/beccauwu/my-site">
    <img src="assets/images/logo.png" alt="Logo" width="308" height="80">
  </a>

<h3 align="center">Portfolio Project 1 - HTML & CSS</h3>

  <p align="center">
    project_description
    <br />
    <a href="https://github.com/beccauwu/my-site"><strong>Visit the site »</strong></a>
    <br />
    <br />
    <a href="https://github.com/beccauwu/my-site">View Demo</a>
    ·
    <a href="https://github.com/beccauwu/my-site/issues">Report Bug</a>
    ·
    <a href="https://github.com/beccauwu/my-site/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#introduction">1. Introduction</a></li>
    <li>
      <a href="#site-styling">2. Site Styling</a>
      <ul>
        <li>
          <a href="#site-wide">2.1. Common Elements</a>
          <ul>
            <li><a href="#header">2.1.1. Header</a></li>
            <li><a href="#footer">2.1.2. Footer</a></li>
            <li><a href="#colours">2.1.3. Colours</a></li>
            <li><a href="#other">2.1.4. Other</a></li>
          </ul>
        </li>
        <li>
        <a href="#pages">2.2 Pages</a>
          <ul>
            <li><a href="#index">2.2.1. Index</a></li>
            <li><a href="#pricing">2.2.2. Pricing</a></li>
            <li><a href="#gallery">2.2.3. Gallery</a></li>
            <li><a href="#about">2.2.4. About</a></li>
          </ul>
        </li>
        <li><a href="#worth-mentioning">2.3. Worth Mentioning</a></li>
      </ul>
    </li>
    <li><a href="#testing">3. Testing</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## 1. Introduction
<h2 id="introduction">1. Introduction</h2>

[![Product Name Screen Shot][product-screenshot]](https://beccauwu.github.io/my-site)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## 2. Site Styling

Here I will go through all the different design choices and talk about what implications they are designed to have on user experience. As a general note here in the beginning, it would be important to stress that usability has been the top priority in creating the site and thorough testing has been done to see potential flaws and fix them.

### 2.1. Common Elements

In this category of design choices are the header and footer as well as all the recurring stylings throughout all the pages. They all stay the same across all pages for consistency purposes.

#### 2.1.1. Header

![Header Image][header]

With the header layout I have generally tried to opt in for relatively simple solutions, but also ones that regardless work as intended. The header has a logo text on the left side, linking to the index page, and links to all the pages on the right. The links for translations are in a smaller font on the left of the page links and link to the translated version of the page the user is currently viewing. All these links get underlined on hover to make them stand out as links. The current page viewed is underlined to make it easier to understand which page one is on. The whole header is sticky up to a viewport width of 804px, when instead a working solution was added in the form of a button linking to the top of the page, visible in the bottom right corner. 

#### 2.1.2. Footer

![Footer Image][footer] 
![Footer Image on Mobile][footer-425]

The footer layout is very simple, with only a copyright notice in the middle and a sigil showing my certification within the Swedish Accounting Association (SRF). The height of the footer is the same as of the header when on laptops for consistency - unlike the header it does not resize depending on the screen width due to there not being enough content to necesitate this.

#### 2.1.3. Colours

![Site colour palette][colours]

For the colour scheme on my site I chose to go with colours already in use by the business - there is one inconsistency from the colour scheme which is the background colour of the WhatsApp QR code which did not work with any of the colours in the colour scheme, only looking fine with a white background. All colours used were added to the :root of the stylesheet as variables to make navigating between them easier, the white was also added to this to provide consistency in the code despite it not being part of the "chosen" colour scheme for the site.

#### 2.1.4. Other

##### Borders

The border thickness is consistent depending on the element it is applied on. For links where a border is used it is 2px in thickness, for tables and other text content 5px, and the border radius used is 15px.

##### Responsiveness

###### Navigation
![Image of the element linking to the top of a page][topbtn]

At a viewport width of 804px the header started taking out a substantial amount of the screen height and would have only ended up being in the way for the user. At this width there is instead a button in the bottom right corner that links to the top of the page in order for the user to still be able to easily access the navigataion bar when needed. The button is round and has an arrow pointing upwards in green on a black background, with green borders around.

### 2.2. Pages

#### 2.2.1. Index

The index page does not contain much content and is designed to be a landing page from where the user themselves can choose the information they wish to receive and in what order through browsing the other pages. Its only features are a background image which is different depending on the screen size due to the image in 16:9 aspect ratio losing its foreground elements after a certain screen width. Instead at smaller widths there is an image with a more compatible aspect ratio for viewing on displays where the height is greater than the width. Horizontally in the centre of the image is an opaque dark background oval with the text "Hi! I'm Rebecca, I'll be your accountant or photographer" and a link underneath the text with the caption "Hire me", linking to the page containing pricing information for the business. 

The text is phrased in a particular way to convey a sense of "semi-professionalism" for a lack of a better wording, meaning that I want the user to know I will be professional but at the same time friendly. In contrast to "Welcome!", "Hi!" does convey a more casual meaning which I see as preferable for my target audience. "Welcome" is also very broadly used in this context, where the use of "Hi" could capture the user's focus better.

#### 2.2.2. Pricing

The first elements on this page are quite naturally tables showing examples of the business' price list, where the data is separated into two columns - "product" and "price". There are two tables due to the business operating under two different categories, accounting and photography. Underneath the tables is a section of text - giving a disclaimer of the tables' content not reflecting the full amount of services offered, containing a link to the contact information section of the about page. Information on the business' donation policy and external shop is also provided here.

#### 2.2.3. Gallery

The gallery page is in its entirety only an assortment of photos to act as a photography portfolio, in order for the customers to feel confident in hiring the business for photography. The gallery is a 4-column flexbox which adapts its stacking for the screen width - the maximum amount of columns is 4 but depending on the screen it will be 2 or 1 columns. I ran into issues with the flexbox from the start in the 4 column variation; even though it should have aligned, well one column kept stacking down. I figured out that the issue has to do with padding, which it was, however, it doesn't explain the numerous examples of similar solutions found online seemingly working without issue. My fix to this was to subtract the amount of side padding in total divided by the amount of columns and use this as the flex and max-width values, which fixed the issue.

##### Mobile / Tablet

#### 2.2.4. About

##### Mobile / Tablet

## 3. Testing

All of the pages have been thoroughly tested by individuals as well as using software such as ARC and Lighthouse. The user feedback has been positive, without any major suggestions for improvement. Both softwares showed some issues, which have been solved as well as they possibly could have been using the already existing site framework.

### 3.2. Issues During Testing

<ul>
  <li>
    Both ARC and Lighthouse flagged the contrast ratio of the logo text compared to the background as being too low, which I believe to be a false positive. After multiple-user testing, the conclusion has consistently been that it is fully readable. The pages have been put through multiple different colour blindness filters where the text has also been fully readable on each of them. Further evidence of a false positive is that neither of these extensions flag the text on the index page hero photo, where logically the contrast ratio should be registered as lower due to the opaque background. I believe the testing fully disregards the header background colour and instead tests the logo text against the background photo on the index page, which is behind the header and therefore doesn't affect the readability of the text whatsoever.
  </li>
  <li>
    The contrast ratios of some of the smaller sized texts, particularly the ones using the red variable colour, were flagged which was quite understandable as the text was quite thin and in some cases probably would be difficult to read. This was solved by either increasing the font size or the font weight, stopping them from being flagged.
  </li>
  <li>
    In the early stages of development, the pages containing images were flagged for using uncompressed image files, this was solved by compressing the files and converting them to webp which substantially imroved the performance scores of the site - going from around 80 to 100. Most of the jpeg and png-files were converted excluding the png files which had a transparent background as webp as a format does not support it and instead creates files which don't look great. A perfect example of this would be the WhatsApp QR-code, for which if converted to webp it would become a much momre difficult and time consuming task to add a border radius to the white background, which now is done by instead of the image file having the backgrund, placing it behind the image through the stylesheet.
  </li>
</ul>

All of the UI was tested with both Lighthouse and ARC, with both flagging the contrast ratio of the logo text compared to the background as being too low, which I believe to be a false positive. After multiple-user testing, the conclusion has consistently been that it is fully readable. The pages have been put through multiple different colour blindness filters where the text has also been fully readable on each of them. Further evidence of a false positive is that neither of these extensions flag the text on the index page hero photo, where logically the contrast ratio should be registered as lower due to the opaque background. I believe the testing fully disregards the header background colour and instead tests the logo text against the background photo on the index page, which is behind the header and therefore doesn't affect the readability of the text whatsoever.

## 4. Bugs

There is a minor issue of one column in the gallery page having an amount of top padding I cannot explain at this point. It isn't an issue in terms of usability, but aesthetically it creates an inconsistent amount of gap between two of the pictures, which for me is a moderate nuisance. I will continue researching what the fault could be and aim to correct this as soon as I am able to.

## 5. Future Enhancements

There are a few details I would definitely like to improve with the site in the future:

<ol>
  <li>**Create a "sandwitch" navigation panel for mobile users**</li>
    <p>
    I tried to accomplish this with CSS and HTML alone but the search for a solution turned out to be too time consuming for it to be a viable option at this time. Once I am able to use JavaScript to a higher degree it is my plan to make this happen as from my understanding the process is much easier with JavaScript. At this point however my skills aren't good enough in JS to accomplish this but it would eliminate the need for the button to top which could have negative implications on user experience through their scroll position not being saved.
    </p>
  <li>**Fix the gap between two of the columns in gallery**</li>
    <p>
    As mentioned before this issue does not impact usability to a significant degree but in the future I would like to fix this as it is somewhat visible and deviates from the consistent padding between the photos generally.
    </p>
  <li>**Improve and add translations**</li>
    <p>
    At this point I am fully aware that the translations of all the pages aren't perfect - they are in a few points transliterated instead of finding a phrasing in the target language that would be equivalent to the English one. They are fully readable in each language however so the only difference would be a slightly improved user experience. I would also like to translate the site into other languages once I am proficient enough to be able to confidently do this, at this point however, the languages offered will be more than enough for the vast majority of the business' target demographies.
    </p>
</ol>

<!-- CONTACT -->
## Contact

Rebecca Perttula - [@uwuphoto](https://twitter.com/uwuphoto) - rebecca@perttula.co

Project Link: [https://github.com/beccauwu/my-site](https://github.com/beccauwu/my-site)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- Credits -->
## Credits

* []()
* []()
* []()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/beccauwu/my-site.svg?style=for-the-badge
[contributors-url]: https://github.com/beccauwu/my-site/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/beccauwu/my-site.svg?style=for-the-badge
[forks-url]: https://github.com/beccauwu/my-site/network/members
[stars-shield]: https://img.shields.io/github/stars/beccauwu/my-site.svg?style=for-the-badge
[stars-url]: https://github.com/beccauwu/my-site/stargazers
[issues-shield]: https://img.shields.io/github/issues/beccauwu/my-site.svg?style=for-the-badge
[issues-url]: https://github.com/beccauwu/my-site/issues
[license-shield]: https://img.shields.io/github/license/beccauwu/my-site.svg?style=for-the-badge
[license-url]: https://github.com/beccauwu/my-site/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/rebeccaperttula
[product-screenshot]: assets/images/amiresponsive.png
<!-- Site Captures -->
[header]: assets/images/site-captures/header.png
[header-425]: assets/images/site-captures/vw-425/header.png
[footer]: assets/images/site-captures/footer.png
[footer-425]: assets/images/site-captures/vw-425/footer.png
[index]: assets/images/site-captures/index.png
[index-425]: assets/images/site-captures/vw-425/index.png
[pricing]: assets/images/site-captures/pricing.png
[pricing-425]: assets/images/site-captures/vw-425/pricing.png
[gallery]: assets/images/site-captures/gallery.png
[gallery-425]: assets/images/site-captures/vw-425/gallery.png
[gallery-800]: assets/images/site-captures/vw-800/gallery.png
[about]: assets/images/site-captures/about.png
[about-425]: assets/images/site-captures/vw-425/about.png
[topbtn]: assets/images/site-captures/vw-425/topbtn.png
[colours]: assets/images/site-captures/colours.png