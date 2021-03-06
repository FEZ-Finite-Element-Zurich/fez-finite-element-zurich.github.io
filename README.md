# Landing Page for [FEZurich](https://fez-finite-element-zurich.github.io/)

For those maintaining the FEZ landing page. You can use the original repository ([advlanding](https://github.com/joyceykao/advlanding)) in the creators's GH account (@joyceykao) as a staging environment (i.e. an imitation of the real thing in the FEZ organization) to test if your changes to the website are what you envisioned before 'deploying' it to the actual landing page (i.e. forked repository in FEZ organization).

[Link to 'live' staging environment](https://joyceykao.github.io/advlanding/)

## Website basics

This website was built with HTML, CSS, & a little bit of JavaScript (JS) using the Bootstrap toolkit. Web browsers like Chrome, Firefox, Safari, etc. interpret the HTML, CSS, and JS file sent by the server hosting your website. Beware that not all websites will be compatible/interpreted the same on every browser, which is why sometimes websites show up *weird* in different browsers.

In a nutshell, here is what each file or part of a website does:
- **HTML** provides the content of a website,
- **CSS** styles the content (e.g. fonts, colors, spacing, etc.), and
- **JS** adds interactivity (e.g. animations, or in this case, interacting with external websites via APIs).
- **Bootstrap** is a library of website components made of pre-written HTML, CSS, JS.

There are many tutorials online that will go into much more depth than what is described here. JS will not be explained...you shoud not have to touch anything in the JS file to update the FEZ website (nor the CSS files).

### HTML basic syntax

`<element attr="some_attribute"> [...content...]</element>`

To update the FEZ website, you'll be copy and pasting code chunks or HTML elements into the .html files of the repository.

An element is defined by an opening and closing tag name which is in our example above `<element></element>`

Within the opening tag, you can define attributes for the element that will help format how it looks and functions when a user looks at the website online. Common tags for styling the look of html are `class` and `id`. The parameters for the attribute are always contained in double quotation marks. An HTML elmement can have multiple classes and id's applied to it.

### CSS basic syntax

```
elementname {
  property: value;
}

.classname {
  property: value;
}

#id {
  property: value;
}
```
Basic CSS is of the same format with the *target* name indicated outside of the curly braces with all properties/values that should be applied to the *target* within the braces.

The *target* can be a whole group of general elements like paragraphs (`<p></p>`), headers (`<h1></h1>`), etc.

You can also add styling using a `class` or `id` attribute (see above about html attributes). To indcate a `class` a period must precede the classname. In the same manner, `id`'s are preceded by `#` in CSS code.

*Classes* are used on repeating elements/components in a webpage where as *id*'s are normally used for specific elements when further styling is needed.

### [Bootstrap](https://getbootstrap.com/)

Bootstrap is a front-end toolkit created by Twitter. It's a library of HTML, CSS, and JS scripts so one can mix and match website components (e.g. navbars, cards, containers, etc.) to quickly put together websites by simply indicating different classes in the `class` attribute here. Not covered here, nor should you have to mess with it, but you can find all you need to know about it on the Bootstrap website: [https://getbootstrap.com/](https://getbootstrap.com/).


