## CSS Guidelines

### Structure:

This is the structure we are going to use for the folders.

```
stylesheets/
  site.css.scss/
    _base.scss/
    layouts/
      _header.scss
      _footer.scss
    components/
      _buttons.scss
      _cards.scss
```

### Rules:

* We are using a combination between BEM and SMACSS.
* Use 2 spaces for identation.
* Give its own line to each selector.
* Leave a blank space between opening braces ```{```

For example:
```css
.nav__link {
  font-size: 18px;
  line-height: 1.2;
}
```

### Properties:

Properties should be arranged by alphabetical order

```css
/* some selector */ {
  background: #f1f1f1;
  color: #333;
}
```
