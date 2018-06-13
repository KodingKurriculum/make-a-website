# Make a Website
A small introduction on how to create a website!  Simply download the repository
and follow along.

## Structure, Styles, and Scripts
Websites can be broken into three core components
- HTML - The structure of the page
- Styles - Colors, borders, fonts, spacing, and pictures
- Scripts - Actions, and events

## HTML (HyperText Markup Language) - Structure
HTML files are the actual webpages. They are composed of nested and indented XML tags
that define structure of the webpage. Each tag is made of a pair of tags that look like:
```HTML
<!-- divs are used for blocks of content -->
<div>
  <h2>Headers are used for titles</h2>
  <p>Paragraph tags are used for text</p>
</div>
```

## CSS (Cascading Style Sheets) - Styles
CSS are files that contain all of the styles we can use on the page. These include
colors, heights and widths, padding, fonts and text size - think about the Microsoft Word menu.

The term cascading is important because multiple stylesheets are loaded on to the page, and their
styles may override or add on to one another - like the way we override navbar styles in our example.

Styles can be applied in three ways.
1. As a set called a class '.class_name'. Classes are good to apply a standard set of styles
over the HTML page.
```HTML
<div class="mystyle">
</div>
```
```css
.mystyle {
  color: #fff;
}
```

2. To an ID. IDs are denoted by a '#' sign in the stylesheet, and only reference one element.
```HTML
<div id="about-us">
</div>
```
```css
#about-us {
  color: #fff;
}
```

3. Or directly to an HTML element.  Anywhere the HTML element is referenced, the set of styles will be applied.
```HTML
<p>Here is some text</p>
```
```css
p {
  font-size: 1.2rem;
}
```

## JavaScript - Scripts
Scripts provide actual programming to the page.  JavaScript is used to perform actions like save to a database,
perform logic, respond to actions, and display/manipulate page content.

It is beyond the scope of this tutorial to do anything with scripting.
