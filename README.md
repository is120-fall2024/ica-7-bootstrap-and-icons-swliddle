[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Zoz2R0Ow)
# ICA 7: Bootstrap and some Icons
## Introduction
This ICA is designed to introduce you to the world of CDNS, how they work, and to help you get familiar with Bootstrap native elements, the Bootstrap grid system, and Font/Icon CDNs. You will be using Bootstrap to create a simple web page with an array of native elements and use your choice of icons from either Font Awesome or Google Fonts. You will also use a font family from Google Fonts to style the typography of your website.

> [!IMPORTANT]
> You will be adding a lot of "static" default elements to your webpage for the purpose of learning how the Bootstrap framework works. You will need to edit the content of these elements to a reasonable degree to make your webpage "your own". This means you may choose to add your own text, images, and other content to the elements you add to your webpage. How much you change the content is up to you, but you should aim to make your webpage look like a unique and cohesive design.

## Instructions
### Q1. Link Bootstrap to the ica7.html file
Adequate instructions for this question can be found in the Bootstrap documentation [here](https://getbootstrap.com/docs/5.3/getting-started/introduction/). You will need to link the Bootstrap CSS and JavaScript files to your HTML file. You can use the Bootstrap CDN to link the files to your `ica7.html` file.

> [!IMPORTANT]
> The Bootstrap documentation says to put the javascript link at the end of the body tag. While this is a good practice, it's preferable to put it in the head tag. You can do so by adding the `defer` attribute to the script tag. This will make the browser load the script after the page has been parsed (equivalent to putting it at the bottom of the `<body>` element).

### Q2. Add a Bootstrap Navbar
Bessides a `hero` section, the navigation bar is one of the most important elements of a website. It is the first thing a user sees when they visit your website. It is important to make sure the Navbar is visually appealing and easy to use.

Navigate to the Bootstrap documentation to find a a Bootstrap Navbar to add to your `ica7.html` file. You can use any of the Navbar examples provided in the documentation. You can also customize the Navbar to your liking. Make sure to add the Navbar to the top of your `ica7.html` file and configure the links in the Navbar to have navigable functionality on your page.

### Q3 - Q6. Add your choice of four Bootstrap elements, and STYLE THEM!
Now that you've learned how to import a Bootstrap element, choose any four other Bootstrap elements to add to your `ica7.html` file. In my opinion, the Bootstrap elements `Collapse`, `Card`, `Carousel`, `Scrollspy`, and `Accordion` are likely some of the most effective elements to learn the Bootstrap framework; however, pick any combination of elements you like. Customize the elements to however you feel best fit the webpage.

For each of the four elements you choose, you will need to add Bootstrap classes to style the elements. You aren't limited to any specific styles for each element, free feel use background colors (`.bg-{color}`), text styling (`.text-{alignment}`, `.fs-{size}`, etc.), borders (`.border-{color}`, `.border-{width}`, etc.), or other styles to make your elements visually appealing. Make sure to practice all the styling shortcuts discussed in this ICA.

> [!TIP]
> It's often a good idea to use a combination of elements that work well together. For example, you could use a `Carousel` element to display pictures about a product, and then use a `Accordion` element to display information snippets of each product. This would create a cohesive and visually appealing section of your webpage.

### Q7. Create an HTML user `<form>` using the Bootstrap grid system
You will need to create a form using the Bootstrap grid system. The form should be at least 4 rows tall and use a combination of column widths. You can decide what the form will be used for. This set is just for the form structure and layout. 

> [!TIP]
> Try sketching out your form on a piece of paper before you start coding. This will help you visualize the form structure and layout before you start coding. It's also a good idea to think about the use-cases for your form.
> - What will the form be used for? 
> - What kind of information will the user need to input?
> 
> This will help you structure your form in a way that makes sense for the user.

### Q8. Add Bootstrap Form elements to populate the form
Now, populate your form structure with Bootstrap form elements. You can use any form elements you like, such as input fields, radio buttons, checkboxes, etc. You can also use Bootstrap form validation classes to style your form elements.

> [!WARNING]
> How you organize your form is often the most important aspect of form building; Make sure you employ visual hierarchy techniques when building your forms, for example, Long text inputs should typically be one full row, while numbers, emails, and other short inputs can be placed side-by-side in separate columns. Make sure to group related inputs together so there is thematic cohesion in your form.

### Q9. Add three Font Awesome icons or Google Fonts icons
The purpose of icons are to help guide the users eyes to navigable elements on the webpage. They are also used to help break up large sections of text and to add visual interest to the webpage. Add three icons from a CDN to your `ica7.html` file. You can use either [Font Awesome](https://fontawesome.com/) or [Google Fonts](https://fonts.google.com/icons) icons.

### Q10. Add a Google Fonts font family
The last step is to add a Google Fonts font family to your `ica7.html` file. Be strategic with the font that you choose. You can add the font family to your `ica7.html` file using the `<link>` tag inside the `<head>` of the document, and address the font-family in your `ica7.css` file to apply to fonts to your webpage.

---
# CDNs
CDNs (Content Delivery Networks) are a way to deliver content to the user. They are a network of servers that deliver content to the user based on their geographic location. This allows for faster load times and better performance. CDNs are used to deliver content such as files, images, videos, and other media files. They are also used to deliver web pages and other web content. CDNs are used by many websites and are an important part of the modern web.

# Bootstrap
## Introduction
Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS- and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components. The main catch of Bootstrap is the flexibility and ease of use of adding CSS styles to your HTML elements in a short-hand notation. This allows for rapid development of web pages and web applications. Bootstrap is also a great tool for learning how to build responsive web pages, as it has a built-in grid system that allows for easy layout of web pages.

## Background
Backgrounds are a fundamental part of any web page. Backgrounds can be set using the class names `bg-{color}` where `{color}` is the name of the color you want to use. For example, you can set the background of an element to be blue by using the class name
 - `bg-primary` - Blue background
 - `bg-secondary` - Grey background
 - `bg-success` - Green background
 - `bg-dark` - Dark background
... and many more

Other background coloring options:
 - A light background of each color is also available by using the class `.bg-{color}-subtle`.
 - The backgound color can be set to a gradient by adding the class `.bg-gradient` to any HTML element.
 - The background color opacity can be set by adding the class `.bg-opacity-{value}` where `{value}` is a number between 0 and 100.
   - The only accepted values of the opacity `{value}`'s are 75, 50, 25, 10.
 - The background color can be set to a transparent color by adding the class `.bg-transparent` to any HTML element.

## Borders
Bootstrap has a variety of border classes that can be used to style the borders of HTML elements. The border classes can be used to add borders to the top, bottom, left, and right sides of an element. The border classes can also be used to add rounded corners to an element. The border classes can be used to add a border to an element, and the border classes can be used to remove a border from an element.

 - You can add a simple border with `.border`. You can also opt to add a border of a specific direction with `border-{direction}`, where `{direction}` is one of `top`, `end`, `bottom`, or `start`.
 - You can subtract a border from an element by adding the class `.border-0` to the element, and directionally subtract a border by adding the class `.border-{direction}-0` to the element.
 - Colored borders can be added with the additional class of `.border-{color}`. The same coloring options are available as the background color options (`border-secondary-subtle`, etc.).
 - Border opacity can be changed with the class `.border-opacity-{value}` where `{value}` is a number between 0 and 100.
   - The only accepted values of the opacity `{value}`'s are 75, 50, 25, 10.
 - Border widths can be changed with the class `.border-{width}` where `{width}` is one of `1`, `2`, `3`, `4`, `5`.
 - The border can be rounded with the class `.rounded`. The following additional classes:
  - `.rounded-top`, `.rounded-end`, `.rounded-bottom`, `.rounded-start`, `.rounded-circle`, `.rounded-pill` are all available to round the corners of an element in a specific direction.
 - The degree of the rounded corners can be changed with the class `.rounded-{size}` where `{size}` is one of `0`, `1`, `2`, `3`, `4`, `5`.

Combining these classes can create a variety of different border styles for your HTML elements. Skills in border styling are important for creating visually appealing web pages.

## Colors
 - Text color can be changed with the class `.text-{color}` where `{color}` is the name of the color you want to use. For example, you can set the font color of an element to be blue by using the class name `.text-primary`. The same color options are available as the background color options.
 - Text coloring also has the `.text-{color}-emphasis` options, where the emphasis is a duller version of the color.
 - Text opacity can be changed with the class `.text-opacity-{value}` where `{value}` is a number between 0 and 100.
  - The only accepted values of the opacity `{value}`'s are 75, 50, 25, 10.

## Position
HTML elements can be positioned using the Bootstrap positioning classes. The positioning classes can be used to set the position of an element relative to the viewport or the parent element. The positioning of this element can be set using the class `.position-{type}`:
 - Just like the `position` property in CSS, `{type}` is one of `static`, `relative`, `absolute`, `fixed`, `sticky`.

Using position Bootstrap shortcuts, you can arrange elements easily with the edge positioning utilities. The format is `{property}-{position}`.
Where property is one of:
 - `top` - for the vertical top position
 - `start` - for the horizontal left position (in LTR)
 - `bottom` - for the vertical bottom position
 - `end` - for the horizontal right position (in LTR)

Where position is one of:
 - 0 - for 0 edge position
 - 50 - for 50% edge position
 - 100 - for 100% edge position

examples:
 - `.position-absolute top-0 end-0`
 - `.position-absolute top-50 start-50`
 - `.position-absolute bottom-0 start-0`

> [!TIP]
> There are few direct use cases for using absolute positioning while using the Bootstrap framework. It's often a good idea to use the grid system to position elements on the page. Some use cases for absolute positioning are for elements that need statically positioned elements to be relative to them, like an alert for notifications, pop-ups/modals, and toggleable menus.

- You can also use `.translate-middle` to center an element horizontally and vertically when it is absolutely positioned.
- Lastly, by adding `.translate-middle-x` or `.translate-middle-y` classes, elements can be positioned only in horizontal or vertical direction.

## Sizing
 - The width and height of an element can be set by using the class `.w-{size}` or `.h-{size}` where `{size}` is one of `25`, `50`, `75`, `100`, `auto`. These values are percentages of the parent element's width or height.
 - The `max-width` and `max-height` CSS properties can be added to an element by setting the classes of `.mw-{size}` or `.mh-{size}`.
 - You can also set sizing of an element relative to the viewport:
  - `.min-vw-{size}` => minimum viewport width
  - `.min-vh-{size}` => minimum viewport height
  - `.vw-{size}` => viewport width
  - `.vh-{size}` => viewport height

## Spacing
HTML elements can be spaced using the Bootstrap spacing classes. The spacing classes can be used to add margin and padding to an element. The margin classes can be used to add space around an element, and the padding classes can be used to add space inside an element. The margin and padding classes can be used to add space to the top, bottom, left, and right sides of an element. The margin and padding classes can also be used to add space to all sides of an element.

The classes are named using the format `{property}{sides}-{size}`.

Where property is one of:
 - `m` => for classes that set margin
 - `p` => for classes that set padding

Where sides is one of:
 - `t` => for classes that set margin-top or padding-top
 - `b` => for classes that set margin-bottom or padding-bottom
 - `s` => (start) for classes that set margin-left or padding-left in LTR, margin-right or padding-right in RTL
 - `e` => (end) for classes that set margin-right or padding-right in LTR, margin-left or padding-left in RTL
 - `x` => for classes that set both *-left and *-right
 - `y` => for classes that set both *-top and *-bottom
 - `blank` => for classes that set a margin or padding on all 4 sides of the element

Where size is one of:
 - `0` => for classes that eliminate the margin or padding by setting it to 0
 - `1` => (by default) for classes that set the margin or padding to $spacer * .25
 - `2` => (by default) for classes that set the margin or padding to $spacer * .5
 - `3` => (by default) for classes that set the margin or padding to $spacer
 - `4` => (by default) for classes that set the margin or padding to $spacer * 1.5
 - `5` => (by default) for classes that set the margin or padding to $spacer * 3
 - `auto` => for classes that set the margin to auto

> [!IMPORTANT]
> The default value of `$spacer` is 1rem (16px).

You can center a block element by adding the class `.mx-auto` to the element. This will center the element horizontally.

> [!IMPORTANT]
> Using `.mx-auto` will only center elements with a `display` property of `block` and a static width. If you want to center an element with a `display` property of `inline` or `inline-block`, you will need to use the class `.text-center`.

## Text
### Text Alignment
Text can be aligned using the class `.text-{alignment}`.
 - `{alignment}` is one of `start`, `end`, `center`.

### Text Wrap
Text can be wrapped using the class `.text-{wrap}`.
 - `{wrap}` is one of `nowrap`, `wrap`.

### Text Transformation
Text can be transformed using the class `.text-{transformation}`.
 - `{transformation}` is one of `lowercase`, `uppercase`, `capitalize`, `none`.

### Font Size
Font sizes can be set by using the class `.fs-{size}`.
 - Possible `{size}` values are `1`, `2`, `3`, `4`, `5`, `6`.
 - `1` is equivalent to the size of an `h1` tag, and `6` is equivalent to the size of an `h6` tag.

### Font Weight
Font weights can be set by using the class `.fw-{weight}`.
 - Possible values for `{weight}` are `.bold`, `.bolder`, `.semibold`, `.medium`, `.normal`, `.light`, `.lighter`
`.fst-italic`
`.fst-normal`

## Grid system
The grid system is used to create a layout for a web page. The grid system is made up of rows and columns. The rows are used to group columns together, and the columns are used to layout the content of the web page. The grid system is used to create a responsive layout that works on all devices.

You can define up to 12 columns in a row. The columns are defined using the class `.col` or `.col-{size}`, where size can be `1`, `3`, `4`, `6`, `8`, or `12`. The columns can be used to layout the content of the web page. Any column that's given a static width will be given `{size} / 12` of the width of the parent element. The columns can be used to create a responsive layout that works on all devices.

Example:
```html
<div class="container text-center">
  <div class="row">
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
    <div class="col">
      Column
    </div>
  </div>
</div>
```

# Font Awesome
Font Awesome is a font and icon toolkit based on CSS and LESS. It was made by Dave Gandy for use with Bootstrap, and later was incorporated into the BootstrapCDN. Font Awesome has a 5.3.1 version, and it has 1,588 free icons and 7,842 pro icons. Font Awesome is a web font containing all the icons from the Twitter Bootstrap framework, and now many more.

Similar to the Bootstrap installation, you can use the Font Awesome CDN to link the files to your `ica7.html` file. You will be able to retrieve the appropriate link from the Font Awesome website as soon as you sign up for a free account and register for a Developer Kit. Navigate here to get started: [Font Awesome](https://fontawesome.com/)

# Google Fonts & Icons
Google Fonts is a library of free licensed font families, an interactive web directory for browsing the library, and APIs for conveniently using the fonts via CSS and Android. The library is maintained by Google and is very popular among web developers. The library contains over 1,000 free licensed font families and is used on over 20 million websites.

Implementing Google Font Icons is by the same logic as using Google Fonts, you will retrieve the appropriate link from the Google Fonts website for EACH Icon and add it to the the head of your `ica7.html` file. You can navigate to the Google Fonts website here: [Google Fonts](https://fonts.google.com/icons)