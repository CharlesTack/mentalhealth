![Mental Health Logo](assets/images/favicon/android-chrome-192x192.png)

# Mental Health | Charles Tack

## Code Institute - Individual Formative Assignment

### HTML/CSS Essentials - User Centric, Static Front-End Website

![Site example on multiple devices.](assets/images/readme/amiresponsive.jpg)

[Click Here to view the Live Project.](https://charlestack.github.io/mentalhealth/)

[Click here to view the Repository.](https://github.com/CharlesTack/mentalhealth)

## Table of Contents:

- [The Why](https://github.com/CharlesTack/mentalhealth#the-why)
- [(UX) User Experience](https://github.com/CharlesTack/mentalhealth#ux-user-experiance)

- [Design](https://github.com/CharlesTack/mentalhealth#design)

  - [Design Brief](https://github.com/CharlesTack/mentalhealth#design-brief)
  - [Typography](https://github.com/CharlesTack/mentalhealth#typography)
  - [Colours](https://github.com/CharlesTack/mentalhealth#colours)
  - [Images](https://github.com/CharlesTack/mentalhealth#images)
  - [Wireframes](https://github.com/CharlesTack/mentalhealth#wireframes)
    - [Desktop](https://github.com/CharlesTack/mentalhealth#desktop)
    - [Tablet](https://github.com/CharlesTack/mentalhealth#tablet)
    - [Mobile](https://github.com/CharlesTack/mentalhealth#mobile)

- [Technologies](https://github.com/CharlesTack/mentalhealth#technologies)
- [Testing](https://github.com/CharlesTack/mentalhealth#testing)
- [Deployment](https://github.com/CharlesTack/mentalhealth#deployment)
- [Credits](https://github.com/CharlesTack/mentalhealth#credits)

## The Why:

Provide accessible, beginner-friendly information on mental health including how to recognize common issues and manage stress, presented in a supportive and organised layout.

## (UX) User Experience:

Users are likely to have an interest in mental health conditions, but as they may be experiencing mental health difficulties the design of the site should be logical and flowing, free from frustration, and use a colour scheme which promotes calmness.  Anything which may be triggering should be subtle in imagery, and the language used should be positive and supportive.

- ### The User

  - #### A visitor struggling with their mental health:
    - To receive information on how to identify symptoms.
    - To receive tips and advice on how to manage and improve mental health.
    - To be calmed and reassured.
  - #### The parent/friend/carer of someone struggling with mental health difficulties:
    - To help recognise the symptoms of a selection of mental health conditions.
    - To find a curated selection of local mental health organisations for further support.
  - #### Anyone experiencing or caring for someone experiencing a mental health crisis:
    - To find information on where to receive emergency assistance.
    - To not be further triggered by any content.
    - To be calmed by the colour scheme.


### Future ideas:

- Implement a section of positive affirmation messages for regular visitors to refer to.
- Add ability to email positive messages to self

## Design:

### Design Brief:

The purpose of the Mental Health website is to provide information which is easy to read, logically ordered, and presented in a calming manner.  Bootstrap cards have been selected and used for their familiarity to the average user, and the colour scheme should be calming whilst also maintaining good contrast for ease of visibility.  As the most popular device for web browsing, the site was designed to be mobile-first, and responsive to look as good on a variety of device types and sizes.


### Typography:

The typography should be easy to read, and calming to the eye.  With this in mind a script style (Paprika) has been selected for headings to appear less formal, and a sans-serif font (Noto) has been selected for its legibility on a range of device sizes.  Both fonts were taken from the Google Fonts library.


### Colours:

The colour scheme for the site was decided upon using assistance from AI (Leonardo AI Image Generator).  AI was used to create the hero image using a prompt which requested a calming image featuring a person feeling relaxed and peaceful with their eyes closed, with a background which reflected nature with lush greens.  From the AI image, a pipette tool was used via imagecolorpicker.com to select colours which complemented each other, whilst maintaining good contrast and having a calming feel.  These colours were then applied via CSS variables to allow for ease of selection for different elements.

Background colour: #fbf5d8 - cornsilk
Primary colour: #668755 - reseda green
Secondary colour: #97b76a - olivine
Tertiary colour: #4a3b3a - van dyke
Highlight colour: #aabfda - powder blue
Highlight colour (light): #537c74 - hooker's green

### Images:

Images in the hero section and in the "symptoms" and "tips" cards were AI generated.

Leonardo.ai was used for the hero image.

"Symptoms" card images:
Copilot was used for the "low-mood" image.
Photoshop AI was used for the "anxiety-square" image.
ChatGPT was used for the "isolation" and "stress" images.

Tips card images:
For inspiration for the AI image prompts, the NHS "Every Mind Matters" site was used.  A selection of the images on https://www.nhs.uk/every-mind-matters/mental-wellbeing-tips/top-tips-to-improve-your-mental-wellbeing/ were described to Copilot for images to be generated from.

Favicon.io was used for the logo and browser tab images.

The external site images were logos obtained via a Google image search and adjusted in Photoshop to use the same image size.

The emergency section images (with the exception of the Samaritans logo) were created in Photoshop with the aim of using calming background colours from the colour scheme and non-triggering images. 


### Content:

Page content was written by Charles Tack with some assistance from Copilot and elements curated from other sources referenced in the credits section.

### Wireframes:

The basic structure of the site was sketched out on the Noteshelf app and then with the use of the software [BALSAMIQ](https://balsamiq.com/) the sketches were converted into a more professional and realistic looking guide.
During development, there were tweaks to the wireframes which were recorded via version progression (v1.0 through to v1.2).  Images of the v1.3 version are below and original Balsamiq files are included in the directory.

#### Mobile:

- [index.html](assets/images/wireframes/mobile-index.jpg)
- [help.html](assets/images/wireframes/mobile-help.jpg)
- [message-modal](assets/images/wireframes/mobile-modal.jpg)

#### Tablet:

- [index.html](assets/images/wireframes/tablet-index.jpg)
- [help.html](assets/images/wireframes/tablet-help.jpg)
- [message-modal](assets/images/wireframes/tablet-modal.jpg)

#### Desktop:

- [index.html](assets/images/wireframes/desktop-index.jpg)
- [help.html](assets/images/wireframes/desktop-help.jpg)
- [message-modal](assets/images/wireframes/desktop-modal.jpg)


## Technologies:

### Languages used:

- [HTML](https://en.wikipedia.org/wiki/HTML5)
- [CSS](https://en.wikipedia.org/wiki/CSS)
- [MARKDOWN](https://en.wikipedia.org/wiki/Markdown)

## Testing:

For testing multiple resources were used:

1. [Chrome Dev Tools - Lighthouse](https://developers.google.com/web/tools/lighthouse/)
2. [W3 Markup Validation Service](https://validator.w3.org/)
3. [W3 CSS Validation Service](https://jigsaw.w3.org/css-validator/)


Using the above resources I have tested all individual pages and noted all bugs found in [Bugs & Fixes] (https://github.com/charlestack/mentalhealth#bugs--fixes).
I have also used peer review for a "fresh set of eyes" to help pick out any issues I may have missed.

### Testing Results:

W3 validation testing was carried out and a number of errors were highlighted which have been fixed, see [Bugs & Fixes] (https://github.com/charlestack/mentalhealth#bugs--fixes).
W3 validation completed as clear of any errors or warnings, except for the warning regarding the h1 element on line 77 of index.html which was maintained as the appearance of the h1 element marks the true stylistic start of the page (with the preceding h2 element being in the hero section).

### Lighthouse Results:

- index.html
  - [Desktop](assets/images/lighthouse/lh-desktop-index.jpg)
  - [Mobile](assets/images/lighthouse/lh-mobile-index.jpg)
- help.html
  - [Desktop](assets/images/lighthouse/lh-desktop-help.jpg)
  - [Mobile](assets/images/lighthouse/lh-mobile-help.jpg)

### Bugs & Fixes:

- Send message doesn't deliver user to success page as success page hasn't been created.
- Auto-scrolling to sections on index.html from the navbar links didn't result in the right area being scrolled to.  Identified that the height of the un-collapsed menu was causing the issue and need to JavaScript to use a time-out instruction needed. _fixed_
- Navbar wouldn't auto collapse in mobile view. _fixed_


Initial W3 validation yielded the following errors:

index.html:
- The element button must not appear as a descendant of the a element.  From line 42, column 29; to line 42, column 62. _fixed_
- No p element in scope but a p end tag seen.  From line 83, column 17; to line 83, column 20. _fixed_
- The element button must not appear as a descendant of the a element.  From line 113, column 17; to line 113, column 50. _fixed_
- End tag div seen, but there were open elements.  From line 187, column 25; to line 187, column 30. _fixed_
- Unclosed element ul.  From line 182, column 29; to line 182, column 32. _fixed_
- Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections, or else use a div element instead for any cases where no heading is needed.  From line 272, column 9; to line 272, column 63. _fixed_
- The element button must not appear as a descendant of the a element.  From line 311, column 29; to line 311, column 62. _fixed_
- The element button must not appear as a descendant of the a element.  From line 320, column 29; to line 320, column 62. _fixed_
- The element button must not appear as a descendant of the a element.  From line 329, column 29; to line 329, column 62. _fixed_
- The element button must not appear as a descendant of the a element.  From line 338, column 29; to line 338, column 62. _fixed_
- The aria-labelledby attribute must point to an element in the same document.  From line 372, column 5; to line 372, column 118. _fixed_
- (Warning) Consider using the h1 element as a top-level heading only (all h1 elements are treated as top-level headings by many screen readers and other tools).  From line 77, column 17; to line 77, column 20.

help.html:
- No p element in scope but a p end tag seen.  From line 80, column 17; to line 80, column 20. _fixed_

CSS:
3 Errors
- .footer : Value Error : color var is not a color value : var. _fixed_
- .footer : Parse Error (--tertiary-color). _fixed_
- .footer : Parse Error }. _fixed_


## Deployment:

### Deployment to GitHub Pages

1. Visit [Github](www.github.com).
2. Navigate to the [charlestack/mentalhealth](https://github.com/CharlesTack/mentalhealth) repository.
3. Click settings along the top options bar.
4. Click pages found at the bottom of the left hand navigation bar.
5. In the 'Source' section, click the dropdown menu that is labelled 'none' and select "Main".
6. Click Save.
7. Page will auto refresh and provide you with a link to the Live GitHub Page for this repository.

The Page can sometimes take a little time to load and go live and this is expected.


### Forking Mental Health Repository

If you wish to experiment with the code freely, you can achieve this by forking the repository. Forking a repository allows you to experiment without the original project being effected. To achieve this you need to:

1. Navigate to the repository [charlestack/mentalhealth](https://github.com/CharlesTack/mentalhealth).
2. In the top right of the page, below your profile you should see a "Fork" button. Simply click on this.
3. A copy of the repository will then be added to your own Repositories Page.

## Credits:

1. [NHS Every Mind Matters](https://www.nhs.uk/every-mind-matters/mental-wellbeing-tips/top-tips-to-improve-your-mental-wellbeing/) - Text content for "tips" card, and inspiration for images.
2. [NHS Mental Health Website](https://www.nhs.uk/mental-health/feelings-symptoms-behaviours/feelings-and-symptoms/) - Source for information on symptoms.
