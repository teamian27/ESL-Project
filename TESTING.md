## Testing

How I tested the page:

* During creation I kept a preview of the page open and tested every element as I went along, modifying and changing where appropriate.
* Once I created a live link using GitHub Pages, I shared it initially among a few coding friends and had my wife (also an ESL Teacher) and a few other ex-colleagues to review and navigate the site, as they would be the intended audience. The only issues I has back were that of cosmetic, all the functions of the page ran fine.
* Once I was in a position I felt the site was in a good place, I shared it for peer review on Slack.
* Once I had finalised a page I used devtools to show how it would look on different device screens to test the compatability.

I tested the site on the following:
* Safari - via iPhone
* Chrome - via mobile and desktop
* Edge - via desktop


## Issues and Bugs

This was the first page I have ever created on my own, so I did have the problem of missing out a closing bracket and finding the page didn't want to work, or not closing a 'div' properly. This did leading to some frustrating moments early on, but I did become wiser to these mistakes quite quickly.

### Problem  

1. Centering the Social Media links in the footer.  

* **Issue** - The social media links seemed to be stay in the left hand corner, and wouldn't stay in a row on a mobile screen.
* **Solution** - I found that I had made the section sm-4, by expanding it to sm-12 and taking up the whole footer it centered easily. This was a simple fix that frustrated me.
  
2. Creating the upload file button in similar style to the submit button

* **Issue** - the upload button would only create in a grey box, and looked ugly on the page
* **Solution** - finding a code on W3Schools, I was able to find a template to use, I was able to use the template to create a replica of the submit button, it is still not perfect, but I am happy with the result.
  
3. Putting two menu bars on the Halloween and Music page
* **Issue** - I couldn't get the menu on the right hand side of the page on desktop mode to stick to the right hand side of the screen.
* **Solution** -

4. The Footer would rise up the page

* **Issue** - The footer wouldn't stick to the bottom of the page
* **Solution** - Using flex in CSS to keep the footer to the bottom of the page

5. Getting the links main text to split into 2 columns

* **Issue** - The text would either line up under one another, or bunch up to the side
* **Solution** - I found that splitting the columns evenly, and then using the same class for both sides, set it up evenly.

6. Centering all the side menus and menu headings, when moving between desktop and mobile

* **Issue** - They would center in desktop mode, but not downsized for mobile
* **Solution** - Changing the column sizing to be full screen in mobile mode changed this.  

7. The dropdown menu would show the arrow, but wouldn't expand

* **Issue** - I wanted to created a menu on the Halloween link, so it could be expanded for future development, there would be a down arrow to show that there is a dropdown menu available, but the menu wouldn't expand.
* **Solution** - The design of the page changed before finding a solution for this issue, but it is something I plan to review in the future.

8. Padding issues

* **Issue** - When padding text and images I found it would look uneven or off centre when minimising for mobile.
* **Solution** - I was using 'px' and this wasn't converting well, when I changed the padding to % it centered better.


## Validators  

### HTML

#### Issue found

* The issue I had was that I had an open div without a close, it was because I re-edited the page and removed the close div by accident, closing the div solved the issue.
* I had used section tags without having a heading tag following them, so I changed it to a div tag.
* I used a figcaption on a link on the homepage, so I removed the figcaption and replaced it with an "<a>" caption.

### CSS

* Tested, no issues found

![css-validator](docs/screenshots/css-validator.jpg)



### Accessability

I used the [WAVE-Web Accessability Evalution Tool](https://wave.webaim.org/) to check the accessability of my page, it came back with 2 errors, containing to the font colors agains the chalkboard background, I tried other colours which it said had better contrast, but I disagree. After reviewing my results and testing different font colours, I believe the yellow against the chalkboard stands out better than most. 