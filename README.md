# HTML5-CSS-Playground

Repository and sample code to illustrate how to work with HTML5 and CSS.

# Notes on Web Development

- Javascript adds functionality, CSS provides the style, and HTML are the building blocks (defines the structure of the pages).

## How does the Web Work?

The address in the browser is the uniform resource locator (URL). It's how we locate internet resources. When we hit enter, there are two pieces: (1) Browser/client and (2) Server (computers that host the target website). This is a client-server model.

When you visit a website, the web server hosting that site could be anywhere in the world! The location of the web server is found when your browser connects to a domain name system (DNS).

Any information is based on the protocol HTTP: hypertext transfer protocol. The communication starts with a request and ends with a response. As a browser reads HTML, it constructs a DOM (document object model). Represents the objects/elements in the HTML document. Resources have an address or URL and for each resource, a seperate request is generated.

## Looking for Validation?

There are ways to validate your website for both CSS and HTML.

- For HTML, one way is to go to the following [link](https://validator.w3.org/). You can validate via file upload as well as by putting in a URL.
- For CSS, you can validate by going to the following [link](https://jigsaw.w3.org/css-validator).

## Notes on HTML

- The body element shows everything in the main browser window.
- The head element contains information about the page (rather than shown info).
- The title is what's shown in the top of the browser/tab of the page.
- There's structural (elements to describe headings/paragraphs) and semantic markup (extra info like emphasis or identifying quotes).

### HTML Code Snippets

- <sup> is for superscript.
- <sub> is for subscript.
- <br /> automatically adds a break.
- <hr /> creates a break between themes, such as a line between two paragraphs.

Things like strong and em are examples of semantic markup, which are useful for screen readers or SEO.

- <strong> will indicate strong importance.
- <em> shows emphasis.
- <blockquote> involves longer quotes that take up an entire paragraph.
- <q> is used for shorter quotes within a paragraph.
- <abbr> is used for an abbreviation or acronym.
- <cite> is used for references to a piece of work.
- <dfn> is the definition of some new terminology.
- <address> refers to the contact info of the author of the page.
- <ins> is used to show content inserted in a document whereas <del> is usually strikedthrough. <s> is a strikethrough but indicates elements that are no longer accurate or relevant.

#### HTML Lists

- Ordered lists involve each item being numbered.
  - Uses the <ol> element.
  - Each item in the list is placed between <li> </li>.
- Unordered lists are lists that begin with a bullet point.
  - Uses the <ul> tag.
- Definition lists are made up of a set of terms along with definitions for those terms.
  - Uses the <dl> tag and has <dt> </dt> to define a term being defined. The <dd> </dd> tags.
  - For example <dt> Sashimi </dt> could have <dd> Sliced raw fish </dd> underneath it.

#### Images

- <img> is the tag where you use src to identify where to find the image file.
- <alt> is a text description of the image file.
- <figure> lets you encapsulate images/their caption.
- <figcaption> allows you to caption images.
- You can specify height/width in the img tag itself, but use CSS.
- Images for the web should be saved a resolution of 72 ppi.

#### Tables

- <table> is used to create a table. Written row by row.
- <tr> indicates the start of each row. Table row.
- <td> indicates each cell of a table. Ex. a number.

## Notes on CSS

- Stands for Cascading Style Sheets and changes appearance of HTML elements.
- CSS Selector informs us of how to change the elements and what properties to change.
- In HTML, you control this with <style> tags.
- Space in CSS is called "margin."
- Spacing inside the element is "padding."
- In HTML-version-3.0, there's many examples of how to implement CSS.
- A text element is an element that runs inside a line of text.
- You can use the <span> element, assign it a class, and give it styling.
- Void elements don't need a closing tag. <link> enables you to load CSS from an external file.
