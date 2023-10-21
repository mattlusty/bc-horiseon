# Horiseon

## Description

Horiseon company website show casing its expertise in online marketing, including SEO optimisation, brand reputation, and social media marketing.

## Usage

N/A

## License

N/A

## Features

- Self anchor Jump Links in navigation - allow users to rapidly move to selected content sections in current page

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
