# Accessibility Implementation Reflection

By: Violet Monserate

## Website Information

### What website/app and task were you testing?
 
I was testing a project website I made in 2022 for Changemakers in Computing. Here is an image of the unedited website:

![Screenshot of the webpage Protbot created by Violet Monserate. Broadly space-themed, with header using a purple to blue gradient, and the background image is a dark purple starfield with white speckles and white text over it. The header says "ProtBot" in light steel blue. There is a scrolling subheader that says Created by Violet Monserate, Alex Vicuna Perez, and Sophia Lam." The navbar before has the tabs "Home", "Our Prototype", "About Us", and "Our Presentation." The main message below says "Never hesitate to make a difference ever again." The next header says "What is Protbot?" in white with the "What" using light steel blue](<Images/Website Overview.png>)

Here is a [link to the ORIGINAL UNEDITED website](https://prot-bot.glitch.me/).

The main task I focused on was to "learn more about protbot," thus going through the homepage, looking at the "about us" page, and ending with nagivating through the prototype.

## Accessibility Technology

### Magnifier

#### What is it?

The magnifier is an access technology that has found its way into many piece of technology, including Windows 11 and 10 (according to this [Webpage on Microsoft's Support Page](https://support.microsoft.com/en-us/windows/use-magnifier-to-make-things-on-the-screen-easier-to-see-414948ba-8b1c-d3bd-8615-0e5e32204198)), and in the specific application I used for magnification-Firefox-as described in [Mozilla's support page about font size and zoom](https://support.mozilla.org/en-US/kb/font-size-and-zoom-increase-size-of-web-pages).

#### What disabilities does it support?

The manifier supports those with Visual Impairment, such as John Klatt [in this Youtube video from the University of Wisconsin](https://www.youtube.com/watch?v=4ZRVDgeMpXc). John Klatt has a form of muscular degeneration, and shows how different types of magnification work better/are less disorienting than others. 

#### What are its strengths and/or weaknesses?

There is a wide variety of magnification softwares, including the ones demonstrated in the aforementioned Youtube video. This means that it is highly customizable to the situtation as well as the wants and needs of the disabled people utilizing magnifiers. I also like how the firefox zoom is built into the webpage, allowing VI folk to use the zoom on any computer, without additional software. One weakness is how context can get lost when very zoomed in.

#### What happened when you tried it?

Just like last time, screen magnification is disorienting. It is hard to not know the broader context of the webpage, and I kept getting lost while navigating. I was more used to it, as well as how to scroll more efficiently for content that was zoom in far enough. 

### Screen Reader

#### What is it?

According to [this website by the American Foundation for the Blind about Screen Readers](https://www.afb.org/blindness-and-low-vision/using-technology/assistive-technology-products/screen-readers), screen readers are (broadly) a form of Access Technology that converts on-screen content (including text, image, video) into speech or a braille display. Users send different keys combinations (commands) in order to instruct the Screen Reader to read out different sections or do different actions. They range in price and are avaiable on all forms of computers and phones.

#### What disabilities does it support?

The website also demonstrates how blind people are the ones who benefit from screen readers. Note that this also shows how Blind/VI AND deaf people can access computers (through the use of braille screens). However, since there is no reading, it can be useful for those with ADHD and Dyslexia, as described in this [article by Accessibility Checker](https://www.accessibilitychecker.org/blog/assistive-technology-for-dyslexia/).

#### What are its strengths and/or weaknesses?

According to [Joey G. on his personal blog](https://www.blindstreet.com/advantages-disadvantages-using-screen-reader-instead-braille/#google_vignette), screen readers allow folks to access computers and functionality that they otherwise would not be able to (reading/writing emails, browsing the internet, communicate with instant messagers). Joey notes, however, that it can be hard to know the "correct spelling of a certain word especially when it’s not that common like medical terms," and the artifical voices can be jarring and hard to use.

#### What happened when you tried it?

Compared to the previous project, I felt far more comfortable using the screen reader, and the different controls that it had. I wasn't accidentally going in and out as often, and instead felt like all my keystrokes led me in the right direction. 
         
## Summary of Problems

The problems were found in the percievability of text, the opperability of headers, and the understandability of how to navigate around to different tabs. The text was on an image background, which lead to issues of contrast at points, especially at the bottom of the webpage where the background image had more bright colors. There was also a weird error for the headers and the screen reader where the screen reader would view a single header as two objects because of some bolding. Most importantly and prominently, there was moving text on the screen in the form of a marquee and a custom slide in from left. Overall, the website was distracting and these all detracted from the content presented in the website.

## Summary of Solutions

The largest fix was in the website header. I made sure that the links inside of the header had letter-wrapping and were inside a flexbox, and thus no matter how zoomed in nor how wide the screen was, the text in its entirety would be readable and on screen. Similarly, I made sure the heading skip was removed, and instead I utilized an `<hgroup>` to pair the text with the header. I also switched the background to a flat color that is dark enough to contrast the foreground. To solve the issue of the split headers, I just used 1 color (which coincidentally helped improve the percievability of the header and removed the use of color for meaning).
  
## Conclusion (What Did I Learn?)

Above all, I practiced using accessibility technology to a further extent, now able to use a screen reader to comfortably navigate around a computer (even without a screen). I also learned how to brainstorm fixes to these issues. I have very minimal experience with user-facing systems (most of my prior programming experience is with systems programming and back-end broadly). It was nice to return to some HTML and CSS. I also noticed how there were gaps in the learning we had in CIC and I'm glad to pick up new skills to actually apply the principles I'm learning in this Accessibility class! Now, I feel like I can sense where a website has issues, and then really pinpoint the problem to a certain solution. 

## Appendix: UARS

The [UARs that I wrote are in this webpage](https://github.com/ctrl-vi/cse480e-accessibility/blob/67486d483e506eeb9bb54f91495243fbfbb955a4/Accessibility%20Implementation/Protbot%20UARs.md).
