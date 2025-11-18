# Bugs Found in 1st Session

## Word Counting & Validation Logic

- Does not catch all E-Prime violations (e.g., "you're")
- Word count incorrect when pressing enter after a word
- Comma separation counts as one word
- Enter does not separate two words
- Full stop not considered when detecting "being" as verb vs. noun
- Apostrophes block violation detection inconsistently: be' be ' be ' be'
- Counting "I'm" as number of words issue

## Input/Output Validation

- Empty input should be blocked
- Enter key gives different result than empty input
- Enter key does not trigger the action as shortcut
- No clear text button

## Text Display & Formatting

- Output of multiline texts with spaces at end of line misaligned
- Output field (grey) not aligned with the box
- Output too left aligned
- Long horizontal text goes outside output box with no scrolling
- Text area sizing has no limitations
- Mixed fonts make it hard to read and understand
- Font selection doesn't help differentiate between 'l' and 'I'

## Mobile & Responsive Design

- Mobile horizontal view: no field or button visible

## Performance & Stability

- Page crashes or gets slow after large input
- Image slows down loading of page

## Internationalization

- Non-English characters printing issues
- Lithuanian letters show up as italic
- Inputting different languages (e.g., Japanese) for counting

## UI/UX Issues

- User experience of colors - meaning unclear
- Layout uses a lot of empty space
- Spelling expectations with repetitive words and missing comma

## Links & Navigation

- Links inconsistent in how they open
- URL allows you to see the code

## Assets & Resources

- Favicon does not load
- License should be footer not an image - image is unnecessary

## Summary

**32 bugs total** found across testing pairs (individual pairs found 5-16 bugs each)

**Note:** "long text prevents scrolling" was marked as FIXED during the session
