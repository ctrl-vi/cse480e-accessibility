# GSBA UARs

By: Violet Monserate

## ID: AT-00

### Brief Description

Images missing alt text.

### Evidence

This is one example of images missing alt text:

![Screenshot of the GSBA website's "Sponsors" section. There are 18 total images, 13 are missing alt text, as indicated with a red icon picturing an image, indicating that these link to another website.](https://github.com/ctrl-vi/cse480e-accessibility/blob/main/GSBA%20Accessibility%20Assessment/Images/AT-00-Sponsors.png?raw=true)

### Explanation

Guideline violated: 1.1.1: Non-text Content and 2.4.1: Link purpose in context. This is a massive issue since images are vital to understanding the website and its layout and content, and all of that meaning is lost due to the lack of alt-text. In addition, some of the images also act as links, which causes the user to have an unknown link that they don't know where leads.

### Severity
#### Severity Rating: 5/5

#### Frequency

No alt text is somewhat frequent throughout the website (and there are many images on this site), and it is hit or miss whether the alt text is a sufficiently useful alternative. 

#### Impact

It is nigh impossible to fix for an end-user, as they cannot describe the image themselves. This makes it impossible to know which parts of the website are which.

#### Persistence

Once the issue is fixed (or maybe they have the image described for them) then they will know what the images and the corresponding links go to. However, there is no way for the user to know which of the unlabeled images they're on since they're unlabeled. 

### Relationships to other problems reported (if relevant)

This is related to the null alt text that was seen through the screen reader. They both involve images being unusable for blind/VI folk using the GSBA website.

## ID: AT-01 

### Brief Description

Low color contrast between text and background, or within images.

### Evidence

The general color scheme on the website of medium-dark green and white text (or vice versa) flags the contrast issues. The following are only a *couple* examples: 

![Screenshot of a header on the GSBA website. White text with green highlighting on a white background. The text says "WELCOME TO GSBA." There are two icons next to the header. One indicates that the header is an "h2" and the other indicates the low contrast issue with a red icon. ](https://github.com/ctrl-vi/cse480e-accessibility/blob/main/GSBA%20Accessibility%20Assessment/Images/AT-01-Header.png?raw=true)

![Screenshot of a link on the GSBA website. Medium-dark green text on a white background. The text says "Scholarship & Education Fund." There are two icons next to the link. One indicates the low contrast issue with a red icon, and the icon on the right indicates the use of the ARIA "aria-setsize" attribute.](https://github.com/ctrl-vi/cse480e-accessibility/blob/main/GSBA%20Accessibility%20Assessment/Images/AT-01-Link.png?raw=true)

The WAVE tool says that the color contrast is 4.03:1, which is below the AA requirement of 4.5:1, and the AAA requirement of 7:1.
### Explanation

Guideline violated: 1.4.3 Contrast (Minimum) and 1.4.6 Contrast (Enhanced).

This is an issue because it prevents folks (even those who are not visually impaired) from seeing links or headers and hinders their access and comprehension of the website. This is especially true with the link as it was unclear that this was a link and something to click on. This is a more widespread issue for this company, as their choice of green and white are seen everywhere, including in their logo.

### Severity

#### Severity Rating: 4/5

#### Frequency

This is a very frequent issue as it is found at every header, every image involving their logo, and just the general color scheme of the website. 

#### Impact

This is somewhat mitigatable for users (using a black and white filter, increasing contrast broadly on a website), but this still poses an issue of percievability of images and text, and sometimes they will get lost in the background, thus losing content. 

#### Persistence

This can't just be ignored after being fixed once, as it crops up in many sections (and even in images!). Thus, there has to be much effort on the end of the developers to solve this issue for users.

### Relationships to other problems reported (if relevant)

Since some images that contain text are hard to see, some users may want to use the alt text, which is then non-existent :(  

## ID: AT-02

### Brief Description

Skipped heading level (typically skipping h3).

### Evidence

![Screenshot of WAVE's structure for the website. The h2 states "Land Acknolwedgement" and then the h4 is instead a paragraph stating "GSBA acknowledges that our organizational identity is rooted in this place we call home, which stands upon the ancestral lands of the Coast Salish peoples, many of whom continue to thrive here. We commit to recognizing and celebrating the diversity and intersectionality of two-spirit and other gender-diverse identities expressed by Native & Indigenous businesses, scholars, and leaders within our community and beyond. We honor these voices as essential to our mission of achieving equity for all"]()

![Screenshot of WAVE's structure for the website. The h2 states "Are you ready for buisness?" and then an h4 stating "Washington is home to some of the biggest names in the business world."]()

![Screenshot of WAVE's structure for the footer. After the footer, there are 4 h3's that state "GSBA MEMBERSHIP," "SIGN UP TO STATE IN TOUCH!" and "FOLLOW US"]()

### Explanation

This makes the website more unpredictable and less easy to navigate. Especially since some of the text is actually a header, this makes it harder for the screen reader to tab into it (which I found out while navigating this webpage myself). Overall, more confusion for the user.

### Severity
#### Severity Rating 3/5

#### Frequency

This is relatively infrequent, with me only finding it in a couple select areas. But the footer is present everywhere, thus that is found everywhere.

#### Impact

This is pretty annoying and since it doesn't impact every part of the website equally, is unpredictable. But many screen will simply announce the skipped header level and keep going inwards into the structure.

#### Persistence

This is a persistent issue, as the skipped header level will still be there for the user, and the screen reader will thus keep announcing the skipped header level. 

### Relationships to other problems reported (if relevant)

N/A

## ID: AT-03: MISSING LANGUAGE

### Brief Description

Language attribute missing from HTML file

### Evidence

There is no 

    <html lang = "en">

at the very beginning of the code. Instead, there is a

    <html>

which excludes the "lang" attribute. 

### Explanation

Guidelines violated: WCAG 2.1; 3.1.1 (Language of Page), 3.1.2 (Language of Parts). This is a major issue as it can disrupt the use of screen readers. 

### Severity
#### Severity Rating: 3

#### Frequency

This is an extremely common issue that will be faced by anyone using the webpage, as annotating the language ensures ANYONE using AT is getting information in the correct language. However, this webpage is the member login, thus whenever the user wants to log-in to edit or access their membership, they'll have to face this issue.

#### Impact

This means that some screen readers will straight up not work! If the reader defaults to english when not semantifically included, that will work. But, say that someone is using a spanish screen reader and implicitly thinks things are in english. This means that there will be the incorrect narration of this english webpage, and thus reducing the understandability of the page.

#### Persistence

If the screen reader implicitly labels the webpage as english, this issue goes away. Same as if the user annotates it themselves, thus it goes away. 

### Relationships to other problems reported (if relevant)

N/A

## ID: MAG-00

### Brief Description

Overlapping text and navbar whenever resizing (at specific sizes)

### Evidence

![Screenshot of the navbar and header of the GSBA website. There is the GSBA logo in the top left. The navbar is offset from being at the top, and covers part of the header banner. The navbar contains "Search Directory," "Donate," "About GSBA," "Membership," "Directory," "Scholarship," "Ready for Buisness," "Advocacy," and "Events." The header banner states "Active Member Directory"]()

![Screenshot of the GSBA website titled "Transgender and Non-Binary Affirming Employer Toolkit."]()

### Explanation

Guideline violated: 1.4.12: Text Spacing, and 1.4.4: Resize Text. Because resizing causes the text to clash and overlap, this leads to an issue of percievability and operability of clicking on the header. This makes it hard for the user to interpret the information on the screen, and makes it so that important links/texts are more likely to be covered up (as seen with the navbar).

### Severity
#### Severity Rating 3/5

#### Frequency

This only happens a couple times, but the navbar is always present on the screen. It also only happens at certain zoom levels (as the navbar will disapear or the line spacing will fix itself).

#### Impact

The navbar being offset does take up a lot of screen real estate. This makes it hard to target specific buttons or click on links in the body of the website. 

#### Persistence

This isn't something that goes away with a magnifier, and thus is pretty annoying to deal with and thus the impact is further exasterbated.

### Relationships to other problems reported (if relevant)

N/A

## ID: SR-00: NULL ALT TEXT

### Brief Description

Null alt-text. For example,

    alt = " "

### Evidence

The following are all examples of null alt-text that were NOT caught by the Automatic Tool:

![Screenshot of a header image on the GSBA website featuring the text "Equalux: Nov 9. Presented by KIA: Car Pros." The "Equalux" text is in a silver glitter, and the other text is in a combination of white and yellow/gold.]()

![Screenshot of a header image on the GSBA website featuring the text "GSBA's Open Letter to the City of Seattle regarding total..." in white text on a green background]()

![Screenshot of a portrait on the GSBA website. The portrait features an individual smiling with short grey hair, gold earrings, a blue button, up, a green coat, silver rings on their fingers, and holding glasses.]()

### Explanation

Guideline violated: 1.1.1: Non-text Content and 2.4.4: Link Purpose (In Context) and 1.4.8: Images of Text. While the 1.1.1 is primarily violated as these are important images that all have non-existent alt text, some of the headers are also links, which causes the links to lose any meaning. Most eggregiously is that some of the images are of text, which conveys meaning.

### Severity
#### Severity Rating: 5

#### Frequency: High

Anyone using a screen reader will find problems here. The screen reader often parses out images with null text (as it indicates that a field is irrelevant). 

#### Impact

The impact is great for this, as it causes the user to not know where they are, or to lose out on important content/context within the image (which could also be a navigation issue).

#### Persistence

There is no real fix from the end-user's perspective. This will keep happening (without their knowledge, perhaps) while there is only null text.

### Relationships to other problems reported (if relevant)

This is related to the issue of skipped headers (as perhaps some of the skipped headers are contained within the images) as well as the examples of MISSING alt text.