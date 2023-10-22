# Horiseon

## Description

As Horiseon...

- Our company needs to make visible our services and attract clients who need our services.
- We built this website to make visible and advertise our services and the benefits they provide.
- It solves the problem of clients from around the world not being aware of our services.
- We learnt that to optimise our website's visibility to search engines we must ensure that the HTML structure is semantic and provides meaning and purpose to search engines.
- Lessons such as the webpage needs a meaningful, descriptive \<title\>. images require src and alt attributes. Headings \<h?\> should be used in sequential order.

## Usage

Jump Links

- To find relevant articles on the page quickly, users can click the navigation items in the header nav, and these links will jump the user to desired location on the page!

## License

N/A

## Features

Jump Links (self anchors)

- In nav the items are linked to ids of elements within the page, allowing users to rapidly move to selected content sections.

## Notes

- I added alt attr text to the three main section images.
- I did not believe it was neccessary however to add alt text descriptions to the large CSS image at the top of the page, nor the icon graphics on the right side of th page because they are more decorative than functional.

## Unsure (Questions)

1. I put .content into a \<main\> and .benefits into an \<aside\>

- Is this correct or should they be equal sections and thus the same semantic element?

2. Within the \<main\> ... for sub-sections I used \<section\>s and within the \<aside\> I used \<article\>s

- Is this okay and ...
- When should I use \<section\> and when should I use \<article\>?

3. The next level headings within the \<section\> are \<h2\> and for \<aside\> they are \<h3\>

- As these headings are on the same nested level, should they both be \<h2\>?
- (... because the \<h3\> headings in \<aside\> have skipped the \<h2\> - ie this \<h3\> has no \<h2\> in its ancestor hierarchy)
- Or is it acceptable to skip to \<h3\> because \<aside\> is less important than \<main\>?

4. Does it go against semantic philosophy to use bootstrap-like classes to add styles to HTML elements...

- ie the CSS .float-left class

## Git commit history

Please could you provide any feedback on how I have handled my git flow, commit patterns, commit messages, pulling and pushing to and from main etc? Thanks :)

![My git commit history](assets/images/git-log.png)
