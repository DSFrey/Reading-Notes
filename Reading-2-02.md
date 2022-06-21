# Basics of HTML, CSS & JS

## Introduction to HTML

1. Using semantic tags makes it much easier for developers, search engines, and accessibility tools to read what the html is actually doing. It also helps make clear associations with other files, e.g. your CSS stylesheet.

2. There are 6 levels of heading tags. There should be just one `<h1>` per page and sub-headings should increment in order one level at a time.

3. The `<sub>` and `<sup>` elements are frequently used in math and science to write things such as H<sub>2</sub>O or x<sup>2</sup>.

4. The `title` attribute is added to a `<abbr>` tag to provide the expansion for the term.

## Learn CSS

1. CSS can be applied to a document in 3 ways.

    1. **Inline styles:** Adding an attribute to a tag that affects only the contents of that element. This is inefficient, messy, and generally frowned upon.

    2. **Internal Stylesheet:** Added in a `<style>` element in the `<head>`. This is cleaner than inline styles, but still inefficient if your site has more than one page.

    3. **External Stylesheet:** Contained in a separate file and referenced in a `<link>` element in the `<head>`.

2. It is much harder to read both the HTML and CSS if they are mixed together. Also editing CSS is much easier if it is all in one place instead of scattered over multiple lines in multiple pages.

3. |Component|Example|
    |---|---|
    |Selector|`h2`|
    |Declaration|`color: black;`|
    ||`padding: 5px;`|
    |Property|`color`|
    ||`padding`|
    |Value|`black`|
    ||`5px`|

## Learn JS
