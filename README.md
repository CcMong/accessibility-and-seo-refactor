# Refactoring the Horiseon Codebase For Web Accessibility and SEO

## Description

I was approached by a marketing agency, Horiseon, to refactor their existing site to conform with accessibility standards and rank better on search engines.  

Web accessibility enables people with disabilities to access a website using assistive technologies such as video captions, screen readers, and braille keyboards. 

In line with agile development, the User Story and Acceptance Criteria were formulated prior to undertaking the project to identify the target user, any associated challenges faced, and the criteria that the solution will be defined by.

### User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

### Acceptance Criteria

Without altering the look and operation of the site, the website was made more accessible and optimised to rank highly in the search engines by satisfying the following criteria:  

```
GIVEN a webpage meets accessibility standards:
WHEN I view the source code,
THEN I find semantic HTML elements.
WHEN I view the structure of the HTML elements,
THEN I find that the elements follow a logical structure independent of styling and positioning.
WHEN I view the image elements,
THEN I find accessible alt attributes.
WHEN I view the heading attributes,
THEN they fall in sequential order.
WHEN I view the title element,
THEN I find a concise, descriptive title.
```

### Pertinent Alterations Made

- Added a concise and descriptive title that includes the company's name and services
- Added semantic HTML elements (header, abbr, nav, section, aside and footer)
- Within h1, replaced the span element wrapping the 'seo' with an abbr element, then ensured the heading could be read properly by a screen reader
- Added a hover functionality to the nav bar links to make them more interactive
- Fixed the broken link on the navigation bar by adding the right id to the intended link destination
- Made the hero image more accessible using an ARIA label, as alt attributes could not be added for background images
- Added alt attributes to all img elements
- Placed the side bar into an aside element
- Used a footer element, and changed the h2 header to h4 to promote the sequential ordering of heading attributes. Also wrapped the legal/copyright information within a small element
- Reworked the CSS by consolidating classes and using different selectors, and organising them in accordance with the semantic structure of the HTML elements
- Used comments within the HTML and CSS to highlight changes, and for sectioning the code to make it clearer and more readable  

The work was done in conjunction with Firefox's Accessibility Tool to ensure that a screen reader would be able to read the code clearly. The webpage will also now be more optimised to rank more highly in search engines. Finally, the entire site was checked to ensure that it was fully functional and broken links were fixed.

While the site is much more accessible and will now rank higher in the search engines, the codebase has been refactored to facilitate future accessibility practices. Making a site accessible should not be a one-off activity, but a matter of ongoing consideration.
  

### Lessons Learned

Accessibility should be given a lot more focus by businesses with a web presence because, actually, everyone benefits from it. Impairment is not always permanent, but can also be temporary or situational. Measures taken to improve the experience of disabled users online end up impacting all users.

According to the [European Blind Union](https://www.euroblind.org/about-blindness-and-partial-sight/facts-and-figures), there are many potential customers (an estimated 30 million visually-impaired in the EU alone) that are either unserved or underserved because product and service providers do not have accessible web pages and applications.

Therefore, businesses themselves also stand to profit from adhering to accessibility standards, as they can rank better in the search engines, influence the impression of their brand by improving collective user experience, and reach a currently overlooked customer base. 


## Installation

The site was deployed using GitHub Pages.  


## Usage

The site layout is designed for desktop viewing, and is yet to be optimised for use on other screen sizes or at a resolution smaller than 768px.

[Link to the deployed Horiseon website]()

[Link to the GitHub code repository]()

![Mock-up of Horiseon Webpage](assets/images/screenshot.png "Horiseon Webpage")


## Credits

[W3 schools](https://www.w3schools.com/)  
[Ally-101.com Development Page](https://a11y-101.com/development)  
[MDN Web Docs Page](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)  
[European Blind Union](https://www.euroblind.org/)  


## License

MIT License.

Please refer to the LICENSE in the repo.


## Badges





