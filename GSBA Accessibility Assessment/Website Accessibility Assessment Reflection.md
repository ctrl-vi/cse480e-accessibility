# GSBA Accessibility Assessment Reflection

By Violet Monserate

## Reflection prompts

### Tasks you were testing in your submission

1. Donate money to the GSBA (including becoming a member, providing a scholarship)
2. RSVP/get details for events advertised on the GSBA website
3. Learn about how to get my buisness LGBTBE certified/how to do accessibility training

### Problems you could only identify with manual testing using an accessibility technology?

One of the issues I only caught while doing manual testing were when images had null/empty alt text. These are flagged as "positive" by the automatic technology, and only when I went through it and had it read the image aloud to me did I realize that I could not understand where it was taking me.

## Accessibility Technology Familiarity Competency

### Magnifier

#### What is it?

The magnifier is an access technology that has found its way into many piece of technology, including Windows 11 and 10 (according to this [Webpage on Microsoft's Support Page](https://support.microsoft.com/en-us/windows/use-magnifier-to-make-things-on-the-screen-easier-to-see-414948ba-8b1c-d3bd-8615-0e5e32204198)), and in the specific application I used for magnification-Firefox-as described in [Mozilla's support page about font size and zoom](https://support.mozilla.org/en-US/kb/font-size-and-zoom-increase-size-of-web-pages).

#### What disabilities does it support?

The manifier supports those with Visual Impairment, such as John Klatt [in this Youtube video from the University of Wisconsin](https://www.youtube.com/watch?v=4ZRVDgeMpXc). John Klatt has a form of muscular degeneration, and shows how different types of magnification work better/are less disorienting than others. 

#### What are its strengths and/or weaknesses?

There is a wide variety of magnification softwares, including the ones demonstrated in the aforementioned Youtube video. This means that it is highly customizable to the situtation as well as the wants and needs of the disabled people utilizing magnifiers. I also like how the firefox zoom is built into the webpage, allowing VI folk to use the zoom on any computer, without additional software. One weakness is how context can get lost when very zoomed in.

#### What happened when you tried it?

I was very disoriented while using the screen magnification. It is hard to not know the broader context of the webpage, and I kept getting lost while navigating. It is extremely useful to have the entire webpage in my peripheral, and I missed having that while doing my own testing. I also tried the MacOS magnifier, which was really nice and let me keep that peripheral vision.

### Screen Reader

#### What is it?

According to [this website by the American Foundation for the Blind about Screen Readers](https://www.afb.org/blindness-and-low-vision/using-technology/assistive-technology-products/screen-readers), screen readers are (broadly) a form of Access Technology that converts on-screen content (including text, image, video) into speech or a braille display. Users send different keys combinations (commands) in order to instruct the Screen Reader to read out different sections or do different actions. They range in price and are avaiable on all forms of computers and phones.

#### What disabilities does it support?

The website also demonstrates how blind people are the ones who benefit from screen readers. Note that this also shows how Blind/VI AND deaf people can access computers (through the use of braille screens). However, since there is no reading, it can be useful for those with ADHD and Dyslexia, as described in this [article by Accessibility Checker](https://www.accessibilitychecker.org/blog/assistive-technology-for-dyslexia/).

#### What are its strengths and/or weaknesses?

According to [Joey G. on his personal blog](https://www.blindstreet.com/advantages-disadvantages-using-screen-reader-instead-braille/#google_vignette), screen readers allow folks to access computers and functionality that they otherwise would not be able to (reading/writing emails, browsing the internet, communicate with instant messagers). Joey notes, however, that it can be hard to know the "correct spelling of a certain word especially when it’s not that common like medical terms," and the artifical voices can be jarring and hard to use.

#### What happened when you tried it?

The learning curve for a screen reader is STEEP, and I still input the wrong thing while using it. I also struggle with remembering the inputs. At the same, time, it is far slower for me to use than a pointer since that it what I've grown up using. With more practice, I think I'll be able to proficiently use this AT when testing my futher apps/websites.
         
## Automated Accessibility Checking Competency

### What automated tool did you use?

The automated tool I used was [WAVE by WebAIM](https://wave.webaim.org/). This is a "suite of evaluation tools that helps authors make their web content more accessible to individuals with disabilities," allowing developers to address potential WCAG violations in their page, which also learning about accessible design. 

### What did you like most and dislike most about it?

My favorite part of this tool was how neat and easy-to-read the summary was. The UI added to the experience, letting me know *exactly* where the errors were (as well as categories to see what areas of accessibility needed more attention). When clicking on an error, it would direct you to the location in the website, as well as. Contrast being its own section was a good choice, as it also allows for easy analysis of what could potentially be a better color choice. 

I dislike how the sidebar cannot hide. Sometimes I wanted to have more real-estate to view the code. It would have been nice to have a tab to the left where I could pull up the HTML. I also wish that there was a way to go to certain things. For example, there was an empty link but every time I clicked on it, it did not navigate to where the empty link was. 

### How did you use it to check POUR?

Thankfully, WAVE checks for WCAG compliance, and WCAG is based on the principles of POUR. The different errors cite which standards and guidelines of WCAG may be violated. While this is automatic, I also made sure that the citations were correct, and interpretted the output for myself, ensuring the given error matches the actual output in the browser. Overall, it was a good tool to find some initial violations, but failed at picking up on more nuanced issues.
    
## Accessibility Rules Competency

### Which website and tasks within that website were you assessing?

I accessed the GSBA (Greater Seattle Business Association). The tasks to be analyzed were:

1. Donate money to the GSBA (including becoming a member, providing a scholarship)
2. RSVP/get details for events advertised on the GSBA website
3. Learn about how to get my buisness LGBTBE certified/how to do accessibility training

The [UARs that I wrote are in this webpage](https://github.com/ctrl-vi/cse480e-accessibility/blob/471a0f58a21d478d9e9d9025eb8680265dc80284/GSBA%20Accessibility%20Assessment/Website%20Accessibility%20Assessment%20Reflection.md).

## Conclusion

### When writing the report, did you read and follow class guidelines on GAI use?
    
I have read the class guidelines regarding GAI use. I did not use GAI in order to write this. 

### Would you like to be assessed or re-assessed on any competencies? 

I would like to be assessed on:

* Accessibility Technology Familiarity
* Automated Accessibility Checking
* Accessibility Rules
* Accessible Document Creation