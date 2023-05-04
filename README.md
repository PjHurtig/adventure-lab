# AdventureLAB's website

AdventureLAB is a multi-sport adventure club where people can join a mailing-list to be informed of upcoming events and book their spot.

You can find the live site [here](https://pjhurtig.github.io/adventure-lab/)

![amiresponsive view of different sizes](https://i.imgur.com/YgkHj16.png)

# User Experience

## User Stories

- As a user, i want to be able to understand the business and its brand at first look
- As a user, i want to be able to know *why* i should want to join
- As a user, i want to know the step by step of joining an event
- As a user, i want to be able to easily subscribe
- As a user, i want to be able to get in contact with the business and follow them on social media

## Target audience

- The intended user is anyone who wants to enjoy outdoor experiences in a group setting

## Key project goals

- Create a website that makes it clear why they would want to subscribe to the newsletter
- Make it easy to subscribe consistently over the whole site

## Design

### Colour Palette

![Colours used](https://i.imgur.com/TiEA4OC.png)

"White" is also used to make the different sections stand out and "Coral" as a point-of-interest colour.

To reflect the outdoors and nature aspect of the websites mission i choose a natural, light and muted colour scheme. The palette is picked from the hero-bg image.

### Typography

- **Cantarell** is the font used for the body (with sans serif as fallback) because it is easy to read and the name reminds me of nature
- **Fjalla One** is the font used for the headings and logo (with sans serif as fallback) because it is bold and adventurous, matching the theme of the site.

### Imagery

Few but impactful images helps the user experience by being clear on the subject matter of the site.

- The hero image speakt loudly to the adventure and nature aspects
- The member portraits show the feeling of happiness being a part of the club can result in
- The media gallery shows beautiful scenery and companionship

### Overall Feel

I wanted to elicit a feeling of excitement for getting outdoors and make a simple and clear experience that feels light and airy.

### Wireframes

First draft was just super quick pen on striped notebook showing desktop and phone view:

- paper wireframe phone [here](https://i.imgur.com/mZlLsR1.png)
- paper wireframe desktop [here](https://i.imgur.com/5XhzIYm.png)

Then i used vscode to mock up the sections in both desktop and responsive view at different sizes.

- vs code mock up responsive [here](https://i.imgur.com/Gwkc0Y6.png)
- vs code mock up desktop [here](<https://i.imgur.com/05s8Ssg.png>)

# Features

## Current Features

- The website is made to be fully responsive at all tested device sizes
- The website is made to be accessible.
- Navigation menu changes size and position for best tablet, phone and desktop use
- Timeline changes direction depending on width of device
- Email link will open device email app (if installed)
- "JOIN" button on top of all pages links to subscription form.

## Future Features

- Subscribe form is only connected to code institute formdump at the moment, but will be a fully functional email-list with automatic welcome email in the future
- A user forum for diskussion between members

# Technologies Used

## Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)

## Other Aides and Programs Used

- [Font Awesome](https://fontawesome.com/) icons for social media links
- [Google Fonts](https://fonts.google.com/) to import 'Fjalla One' and 'Cantarell' fonts.
- [GitHub](https://github.com/) as repository host
- [Visual Studio Code](https://code.visualstudio.com/) to mock up functioning wireframe
- [Codeanywhere](https://app.codeanywhere.com/) to develop and commit to github
- [GitHub Pages](https://pages.github.com/) to deploy the site
- [Imgur](https://imgur.com/) for hosting external image links
- [Fontpair](https://www.fontpair.co/all) to help choose font pairing
- [Coolors](https://coolors.co/image-picker) to generate palettes from hero image
- [Lighthouse](https://developers.google.com/web/tools/lighthouse) to test performance and accessability

# Testing

## Validating

Throughout the project i have tested the code with:

- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [CSS Validator](https://jigsaw.w3.org/css-validator/)
- [HTML Validator](https://validator.w3.org/)

## Testing User Stories from (UX) Section

- "As a user, i want to be able to understand the business and its brand at first look"

#### The hero image and text looks good in any responsive size and both shows through the image and tells through text to the user who we are,and what we do
  
- "As a user, i want to be able to know *why* i should want to join"

#### The "reasons to join" tells the user about the advantages of joining and the "testimonials" lets thoose who are already "members" speak to the user and share their own positive experiences

- "As a user, i want to know the step by step of joining an event"

#### The responsive timeline is simple and clear on the basic steps a member goes through to join the events

- "As a user, i want to be able to easily subscribe"
  
#### the subscribtion form allows the user to enter their required information and also optional information about their gear**

- "As a user, i want to be able to get in contact with the business and follow them on social media"

#### The footer has links to social media platforms that open in a new window when klicked, the contact section in the footer has email address that opens in email-app if avaiable

## Testing Key project goals

- "Create a website that makes it clear why they would want to subscribe to the newsletter"
  
#### The whole site is catered to the goal of showing the user (in the target audience) why they would want to be a part of the club

- "Make it easy to subscribe consistently over the whole site"
  
### Every page has the signup form in a consistent place above the footer, and every page has a join button in the header that takes the user there with no new page load

## Further Testing

### Personal Testing

In addition to extensive responsive testing with Google chromes inspect tool throughout the project i have tested it on devices available to me with good results

#### Phones

Huawei mate 20 pro

- Chrome
- Firefox

Samsung s8

- Chrome
- Firefox

#### Tablet

Ipad

- Safari
- Chrome
  
#### Computer

lenovo ideapad

- Chrome
- Firefox
- Edge
- Opera

Lenovo thinkbook

- Firefox
- Edge

#### Responsinator

- Tested in responsinator

#### Third party testing

- I have gotten positive feedback on both usability and aesthetics from friends, family and professionals testing the site on their devices.

### Lighthouse

Throughout the project i have tested the code with Lighthouse with good results.

**Index**
![lighthousetest](https://i.imgur.com/eR7T7fo.png)

**Media**
![lighthousetest](https://i.imgur.com/WIgDR1g.png)

**About**
![lighthousetest](https://i.imgur.com/XDAdM9C.png)

#### Performance

I have used [TinyPNG](https://tinypng.com/) to optimize image sizes as well as change pixel size in an image aditor

#### Accessibility

The text in the hero section was very low contrast to background, i changed it to improve accessibility. that and other small changes increased the score from 92 to 97 on the index page.

## Bugs & Fixes

### Testimonials section

When putting margin-left to 0 in t-image class for the responsive 500px section to center all pictures above text, ”Leons” picture "runs away".

**Temporary fix**: Keep a margin of 1vw and its not too distracting.

**Bug found:**
Found the bug through chrome dev tools. The reason was a float: right, from earlier on ”Johan” (the reversed part of testimonials)

**Actual fix**:
Float can be removed because in responsive section they all use flex as is the new convention.

**Result:** Works as intended

# Deployment

## Deployment through GitHub Pages

This site was deployed through GitHub Pages using the following steps:

1. Log into [GitHub](https://github.com/).
2. Locate the [repository](https://github.com/PjHurtig/adventure-lab).
3. Locate the settings option along the options bar.
4. Locate GitHub Pages options in the sidebar.
5. In 'Source' dropdown, select 'Master' from the branch options.
6. Click the save button.
7. After a while the link is available.

## Cloning Project

1. Log into [GitHub](https://github.com/).
2. Locate the [repository](https://github.com/PjHurtig/adventure-lab).
3. Click the 'Code' dropdown above the file list.
4. Choose "Local" tab
5. Copy the "HTTPS" URL for the repository.
6. Open Git Bash on your device.
7. Change the current working directory to the location where you want the cloned directory.
8. Type git clone and the URL you copied earlier. This is what it should look like:

- $ git clone <https://github.com/PjHurtig/adventure-lab.git>
  
9. Press Enter to create your local clone.

# Credits

## Code

### README

- I used [AmyOShea's Angies-Beauty](https://github.com/AmyOShea/Angies-Beauty-MS1) README as template for this README.

### Responsive Navbar

- the 600px responsive navbar was inspired by [w3schools responsive navigation bar](https://www.w3schools.com/howto/howto_js_topnav_responsive.asp) though mine does not use any javascript.

### Mailto Link

- mailto link info from [email.uplers.com](https://email.uplers.com/blog/best-practices-for-creating-html-email-links/)

### Checkbox Styling

- styling of checkbox from [stackoverflow](https://stackoverflow.com/questions/4148499/how-to-style-a-checkbox-using-css/69164710#69164710)

### Grid Row "Reasons" section

- Grid row info from [developer.mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/repeat)

### Video box

- video box in media.html info from [w3schools](https://www.w3schools.com/html/html5_video.asp)

### Social Media Links

- social media links from [love running](https://github.com/PjHurtig/love-running) walkthrough project

## Content

### Text

- Text content was written by me

### Media

- Hero image from [unsplash](https://unsplash.com/photos/DijA5f0voGQ)

- Member profile pictures from [pexels(1)](https://www.pexels.com/sv-se/foto/man-person-solglasogon-gata-1182238/), [pexels(2)](https://www.pexels.com/sv-se/foto/man-person-sot-ung-720366/), [pexels(3)](https://www.pexels.com/sv-se/foto/kvinna-jeans-sport-lycklig-7991921/)

- About us picture from [unsplash](https://unsplash.com/photos/m1AsLR8g51g)

- Media video from [pexels](https://www.pexels.com/video/people-trekking-on-a-mountain-trail-2894895/)

- Media images from [unsplash(1)](https://unsplash.com/photos/NEqEC7qa9FM), [unsplash(2)](https://unsplash.com/photos/S_VbdMTsdiA)
