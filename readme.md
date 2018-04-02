## CSS Guidelines

### Structure:

We are using a combination of BEM and SMACSS

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

```css
.main__header {
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
