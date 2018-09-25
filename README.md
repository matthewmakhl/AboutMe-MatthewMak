
# My about me website

## __AboutMe-MatthewMak__

Hi, I am Matthew. This is my first HTML/CSS project, making an about me website.

It is not too well polished in terms of programming. I think there should be simplier way to write the HTML/CSS. Nonetheless, it does what I want it to be, and here is my brief explanation of what I did.


### __index.html__

In the __head__ tag, I set up the standard staff, including meta, title, css path and font type. For font type, I used __Raleway__ which I found in google font. I just think it is easy to read in website format.

In the __body__ tag, as I learned HTML/CSS from [Shay Howe's website]("https://learn.shayhowe.com/html-css/building-your-first-web-page/"), I referenced quite a few of the structure of its sample website.

I first set up the __header__. It contains a big __About me__, a navigation bar, one of my photo and a short introduction of myself. I set up a lot of class for them, which basically set the size of their margin, padding, and some font settings. I also wrapped the whole header in a div with class __card__ and __primary__. The __card__ class added a box shadow in the css file, which makes the header hover like a card put on a grey table. My whole webite was deigned with this box shadow effect to seperate different content. I think it is a subtle but good-looking design for an About me page.

For the navigation bar - __nav__, I used an unordered list with no marker to arrange them. In the css, I gave the __li__ tag a inline-block property in order to make the list horizontal. I also used some __img__ tag for the facebook and email icon as a contact me in the navigation bar.

It is similar in the next section, "About" and "My Experience". I also used similar class as the __header__ to adjust the margin, padding and font. However, as I want to put both parts side-by-side instead of one below another, I add one more class - __col-1-2__. What this class mainly does is to set the width to be 50% of its parent element. Therefore, the 2 section box can be displayed side-by-side. The "My Experience" part is actually an image that I drew with Adobe Illustrator. I think it would be more visually pleasent to read this instead of a table.

The next part "My Skill" is also similar except I divided it in 3 parts, using the class __col-1-3__. The width of __col-1-3__ was set to 33.33%. I also used __img__ in front of the skill set as a marker of the list. I didn't use Shay Howe's approach by setting the background of __li__ tag, as the icon I found has large size (E.g. 600 x 600px) and I found it quite hard to fit the icon in front of the skill set. Using __img__ seems to be more flexible for me, such as I can set the size of the icon.

Originally, I also found a deep blue color (#52658F) that I would like to use thought out my website to make it less dull. Here you may see that I used it in most heading and also in some of the icon.

Last but not least, it is the __footer__. I only put a somewhat copyright logo for myself and copy the navigation bar from the __header__.


### __album.html__

The __header__ and __footer__ element is same as that of __index.html__, except I remove the profile picture and short introduction in the header. 

For the rest of the album, I divided each large blocks into 3 hoziontal blocks, using the same technique as the "My Skill" part. I just divided a div elements in to 3 sections with the class __col-1-3__. In this 3 sections, I used 2 to put my pictures and the leftmost or rightmost sections to write descriptions.


### __main.css__

In the css file, the first thing I did was a __Eric Meyer's reset__. Then I set the property of __body__ element, e.g. the grey background, font color and type. Other css are mostly those that I have talked about in my index.html part.