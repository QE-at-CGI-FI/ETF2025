# 1st session

## How many bugs you got in your pair?

5-16-12-8-10-9-7-14/39

## What we did

- Read the requirements and then figure if they work
- Technical foundations: mobile, load times
- Look through the page from top to bottom, identifying features
- Assumptions
- Functionality, counting words, varying data
- Zooming and accessibility
- OWASP top-10, looking for admin site
- Repo to tell what a violation is 
- Look at the code

## What we found

- It does not catch all violations: e.g. you're 
- Wordcount when you press enter after word it counts incorrectly
- comma separation counts as one word
- enter does not separate the two words
- two words and enter gives the words on two differents in lines 
- output of multiline texts with spaces in end of line misaligned
- long text prevents scrolling (FIXED) 
- Enter does not shortcut to the action
- No clearing the text button
- Validations: empty could be blocked
- Validations: enter needs to be giving same result as empty and does not
- Page crashes or gets slow after large input
- Mobile horizontal view, no field or button visible
- Non-english characters printing
- Lithuanian letters show up as italic
- links inconsistent in how they open
- output field, the grey, is not aligned with the box
- output too left aligned
- Font selection does not help make a difference between l and I
- Long horizontal text goes outside the output box and cannot be scrolling
- The text area sizing has no limitations
- Spelling expectations with repetitive words and missing comma
- User experience of colors, meaning unclear
- layout uses a lot of empty space, more ads needed :D
- License should be footer not an image, image is unnecessary
- image slows down loading of page
- favicon does not load
- full stop not taken into considered being => verb being. => noun
- mixed fonts makes it hard to read and understand
- inputting different languages for counting, e.g japanese
- Url allows you to see the code
- one of the four apostrophes blocks detection of violation be’ be ’	be '  be'
- counting number of words for I'm


## Observations on how we worked

- sharing the work creates ideas and learning
- two people, two perspectives, two approaches -> growth in own perspective
- imposing your ideas comes easier than letting others decide off keyboard
- 